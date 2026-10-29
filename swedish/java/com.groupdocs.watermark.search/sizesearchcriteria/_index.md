---
title: "SizeSearchCriteria"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar kriterier som möjliggör filtrering efter vattenstämpelns storlek."
type: docs
weight: 57
url: /sv/java/com.groupdocs.watermark.search/sizesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class SizeSearchCriteria extends SearchCriteria
```

Representerar kriterier som möjliggör filtrering efter vattenstämpelns storlek.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

Följande exempel visar hur man hittar och tar bort vattenmärken med hjälp av sökkriterier.
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


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [SizeSearchCriteria(int dimension, double min, double max)](#SizeSearchCriteria-int-double-double-) | Initierar en ny instans av klassen `[SizeSearchCriteria](../../com.groupdocs.watermark.search/sizesearchcriteria)` med en angiven dimension, ett startvärde och ett slutvärde. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getMinimum()](#getMinimum--) | Hämtar startvärdet. |
|
|  | [getMaximum()](#getMaximum--) | Hämtar slutvärdet. |
|
|  | [getDimension()](#getDimension--) | Hämtar dimensionen för vattenmärket att söka efter. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### SizeSearchCriteria(int dimension, double min, double max) {#SizeSearchCriteria-int-double-double-}
```
public SizeSearchCriteria(int dimension, double min, double max)
```


Initierar en ny instans av klassen `[SizeSearchCriteria](../../com.groupdocs.watermark.search/sizesearchcriteria)` med en angiven dimension, ett startvärde och ett slutvärde.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | dimension | int | Dimensionen `[Dimension](../../com.groupdocs.watermark.common/dimension)` för ett vattenmärke att söka efter. |
|
|  | min | double | Startvärdet. |
|
|  | max | double | Slutvärdet. |
|

### getMinimum() {#getMinimum--}
```
public final double getMinimum()
```


Hämtar startvärdet.


**Returns:**
double - Startvärdet.

### getMaximum() {#getMaximum--}
```
public final double getMaximum()
```


Hämtar slutvärdet.


**Returns:**
double - Slutvärdet.

### getDimension() {#getDimension--}
```
public final int getDimension()
```


Hämtar dimensionen för vattenmärket att söka efter.


**Returns:**
int - Dimensionen för vattenstämpeln att söka efter.

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

