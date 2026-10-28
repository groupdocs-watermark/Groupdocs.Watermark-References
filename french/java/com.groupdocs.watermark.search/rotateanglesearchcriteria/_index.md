---
title: "RotateAngleSearchCriteria"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente les critères permettant de filtrer par angle de rotation du filigrane."
type: docs
weight: 52
url: /fr/java/com.groupdocs.watermark.search/rotateanglesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class RotateAngleSearchCriteria extends SearchCriteria
```

Représente les critères permettant de filtrer par angle de rotation du filigrane.

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
|  | [RotateAngleSearchCriteria(double minAngle, double maxAngle)](#RotateAngleSearchCriteria-double-double-) | Initialise une nouvelle instance de la classe `[RotateAngleSearchCriteria](../../com.groupdocs.watermark.search/rotateanglesearchcriteria)` avec un angle de départ et un angle de fin. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getMinimumAngle()](#getMinimumAngle--) | Obtient l'angle de départ en degrés. |
|
|  | [getMaximumAngle()](#getMaximumAngle--) | Obtient l'angle de fin en degrés. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### RotateAngleSearchCriteria(double minAngle, double maxAngle) {#RotateAngleSearchCriteria-double-double-}
```
public RotateAngleSearchCriteria(double minAngle, double maxAngle)
```


Initialise une nouvelle instance de la classe `[RotateAngleSearchCriteria](../../com.groupdocs.watermark.search/rotateanglesearchcriteria)` avec un angle de départ et un angle de fin.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | minAngle | double | L'angle de départ en degrés. |
|
|  | maxAngle | double | L'angle de fin en degrés. |
|

### getMinimumAngle() {#getMinimumAngle--}
```
public final double getMinimumAngle()
```


Obtient l'angle de départ en degrés.


**Returns:**
double - L'angle de départ.

### getMaximumAngle() {#getMaximumAngle--}
```
public final double getMaximumAngle()
```


Obtient l'angle de fin en degrés.


**Returns:**
double - L'angle de fin.

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

