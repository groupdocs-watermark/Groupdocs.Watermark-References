---
title: "SizeSearchCriteria"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente les critères permettant de filtrer par taille du filigrane."
type: docs
weight: 57
url: /fr/java/com.groupdocs.watermark.search/sizesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class SizeSearchCriteria extends SearchCriteria
```

Représente les critères permettant de filtrer par taille du filigrane.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

L'exemple suivant montre comment trouver et supprimer les filigranes à l'aide de critères de recherche.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("C:\\test.some_ext");
>    SizeSearchCriteria widthRange = new SizeSearchCriteria(Dimension.Width, 50, 100);
>    RotateAngleSearchCriteria rotateAngle = new RotateAngleSearchCriteria(0, 45);
>    TextSearchCriteria textCriteria = new TextSearchCriteria(Pattern.compile("^Test watermark$"));
>
>    PossibleWatermarkCollection watermarks = watermarker.search(textCriteria.and(widthRange.or(rotateAngle)));
>    watermarks.clear();
>
>    watermarker.save("C:\\modified_test.some_ext");
>    watermarker.close();
>  
> ```
> ````


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [SizeSearchCriteria(int dimension, double min, double max)](#SizeSearchCriteria-int-double-double-) | Initialise une nouvelle instance de la classe `[SizeSearchCriteria](../../com.groupdocs.watermark.search/sizesearchcriteria)` avec une dimension spécifiée, une valeur de départ et une valeur de fin. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getMinimum()](#getMinimum--) | Obtient la valeur de départ. |
|
|  | [getMaximum()](#getMaximum--) | Obtient la valeur de fin. |
|
|  | [getDimension()](#getDimension--) | Obtient la dimension du filigrane à rechercher. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### SizeSearchCriteria(int dimension, double min, double max) {#SizeSearchCriteria-int-double-double-}
```
public SizeSearchCriteria(int dimension, double min, double max)
```


Initialise une nouvelle instance de la classe `[SizeSearchCriteria](../../com.groupdocs.watermark.search/sizesearchcriteria)` avec une dimension spécifiée, une valeur de départ et une valeur de fin.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | dimension | int | La dimension `[Dimension](../../com.groupdocs.watermark.common/dimension)` d'un filigrane à rechercher. |
|
|  | min | double | La valeur de départ. |
|
|  | max | double | La valeur de fin. |
|

### getMinimum() {#getMinimum--}
```
public final double getMinimum()
```


Obtient la valeur de départ.


**Returns:**
double - La valeur de départ.

### getMaximum() {#getMaximum--}
```
public final double getMaximum()
```


Obtient la valeur de fin.


**Returns:**
double - La valeur de fin.

### getDimension() {#getDimension--}
```
public final int getDimension()
```


Obtient la dimension du filigrane à rechercher.


**Returns:**
int - La dimension du filigrane à rechercher.

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

