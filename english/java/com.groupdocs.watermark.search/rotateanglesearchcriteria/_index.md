---
title: RotateAngleSearchCriteria
second_title: GroupDocs.Watermark for Java API Reference
description: Represents criteria allowing filtering by watermark rotate angle.
type: docs
weight: 52
url: /java/com.groupdocs.watermark.search/rotateanglesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class RotateAngleSearchCriteria extends SearchCriteria
```

Represents criteria allowing filtering by watermark rotate angle.

**Learn more:**

 *  [Searching watermarks][]

The following example demonstrates how to find and remove watermarks using search criteria.

> ```
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
> ```


[Searching watermarks]: https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks
## Constructors

| Constructor | Description |
| --- | --- |
| [RotateAngleSearchCriteria(double minAngle, double maxAngle)](#RotateAngleSearchCriteria-double-double-) | Initializes a new instance of the `[RotateAngleSearchCriteria](../../com.groupdocs.watermark.search/rotateanglesearchcriteria)` class with a starting angle and a ending angle. |
## Methods

| Method | Description |
| --- | --- |
| [getMinimumAngle()](#getMinimumAngle--) | Gets the starting angle in degrees. |
| [getMaximumAngle()](#getMaximumAngle--) | Gets the ending angle in degrees. |
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### RotateAngleSearchCriteria(double minAngle, double maxAngle) {#RotateAngleSearchCriteria-double-double-}
```
public RotateAngleSearchCriteria(double minAngle, double maxAngle)
```


Initializes a new instance of the `[RotateAngleSearchCriteria](../../com.groupdocs.watermark.search/rotateanglesearchcriteria)` class with a starting angle and a ending angle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| minAngle | double | The starting angle in degrees. |
| maxAngle | double | The ending angle in degrees. |

### getMinimumAngle() {#getMinimumAngle--}
```
public final double getMinimumAngle()
```


Gets the starting angle in degrees.

**Returns:**
double - The starting angle.
### getMaximumAngle() {#getMaximumAngle--}
```
public final double getMaximumAngle()
```


Gets the ending angle in degrees.

**Returns:**
double - The ending angle.
### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | com.groupdocs.watermark.internal.ICriteriaVisitor |  |

