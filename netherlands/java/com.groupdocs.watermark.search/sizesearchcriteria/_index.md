---
title: "SizeSearchCriteria"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Geeft criteria weer die filteren op watermerkgrootte."
type: docs
weight: 57
url: /nl/java/com.groupdocs.watermark.search/sizesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class SizeSearchCriteria extends SearchCriteria
```

Geeft criteria weer die filteren op watermerkgrootte.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

Het volgende voorbeeld toont hoe watermerken te vinden en te verwijderen met behulp van zoekcriteria.
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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [SizeSearchCriteria(int dimension, double min, double max)](#SizeSearchCriteria-int-double-double-) | Initialiseert een nieuw exemplaar van de `[SizeSearchCriteria](../../com.groupdocs.watermark.search/sizesearchcriteria)` klasse met een opgegeven dimensie, een startwaarde en een eindwaarde. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getMinimum()](#getMinimum--) | Haalt de startwaarde op. |
|
|  | [getMaximum()](#getMaximum--) | Haalt de eindwaarde op. |
|
|  | [getDimension()](#getDimension--) | Haalt de dimensie van het watermerk op waarnaar gezocht wordt. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### SizeSearchCriteria(int dimension, double min, double max) {#SizeSearchCriteria-int-double-double-}
```
public SizeSearchCriteria(int dimension, double min, double max)
```


Initialiseert een nieuw exemplaar van de `[SizeSearchCriteria](../../com.groupdocs.watermark.search/sizesearchcriteria)` klasse met een opgegeven dimensie, een startwaarde en een eindwaarde.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | dimension | int | De dimensie `[Dimension](../../com.groupdocs.watermark.common/dimension)` van een watermerk waarnaar gezocht wordt. |
|
|  | min | double | De startwaarde. |
|
|  | max | double | De eindwaarde. |
|

### getMinimum() {#getMinimum--}
```
public final double getMinimum()
```


Haalt de startwaarde op.


**Returns:**
double - De startwaarde.

### getMaximum() {#getMaximum--}
```
public final double getMaximum()
```


Haalt de eindwaarde op.


**Returns:**
double - De eindwaarde.

### getDimension() {#getDimension--}
```
public final int getDimension()
```


Haalt de dimensie van het watermerk op waarnaar gezocht wordt.


**Returns:**
int - De dimensie van het watermerk om naar te zoeken.

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

