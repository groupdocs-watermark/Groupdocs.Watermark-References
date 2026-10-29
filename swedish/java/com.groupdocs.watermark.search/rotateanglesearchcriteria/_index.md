---
title: "RotateAngleSearchCriteria"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar kriterier som möjliggör filtrering efter vattenstämpelns roteringsvinkel."
type: docs
weight: 52
url: /sv/java/com.groupdocs.watermark.search/rotateanglesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class RotateAngleSearchCriteria extends SearchCriteria
```

Representerar kriterier som möjliggör filtrering efter vattenstämpelns roteringsvinkel.

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
|  | [RotateAngleSearchCriteria(double minAngle, double maxAngle)](#RotateAngleSearchCriteria-double-double-) | Initierar en ny instans av klassen `[RotateAngleSearchCriteria](../../com.groupdocs.watermark.search/rotateanglesearchcriteria)` med en startvinkel och en slutvinkel. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getMinimumAngle()](#getMinimumAngle--) | Hämtar startvinkeln i grader. |
|
|  | [getMaximumAngle()](#getMaximumAngle--) | Hämtar slutvinkeln i grader. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### RotateAngleSearchCriteria(double minAngle, double maxAngle) {#RotateAngleSearchCriteria-double-double-}
```
public RotateAngleSearchCriteria(double minAngle, double maxAngle)
```


Initierar en ny instans av klassen `[RotateAngleSearchCriteria](../../com.groupdocs.watermark.search/rotateanglesearchcriteria)` med en startvinkel och en slutvinkel.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | minAngle | double | Startvinkeln i grader. |
|
|  | maxAngle | double | Slutvinkeln i grader. |
|

### getMinimumAngle() {#getMinimumAngle--}
```
public final double getMinimumAngle()
```


Hämtar startvinkeln i grader.


**Returns:**
double - Startvinkeln.

### getMaximumAngle() {#getMaximumAngle--}
```
public final double getMaximumAngle()
```


Hämtar slutvinkeln i grader.


**Returns:**
double - Slutvinkeln.

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

