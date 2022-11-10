---
title: SizeSearchCriteria
second_title: GroupDocs.Watermark for Java API Reference
description: Represents criteria allowing filtering by watermark size.
type: docs
weight: 57
url: /java/com.groupdocs.watermark.search/sizesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class SizeSearchCriteria extends SearchCriteria
```

Represents criteria allowing filtering by watermark size.

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
| [SizeSearchCriteria(int dimension, double min, double max)](#SizeSearchCriteria-int-double-double-) | Initializes a new instance of the `[SizeSearchCriteria](../../com.groupdocs.watermark.search/sizesearchcriteria)` class with a specified dimension, a starting value and an ending value. |
## Methods

| Method | Description |
| --- | --- |
| [getMinimum()](#getMinimum--) | Gets the starting value. |
| [getMaximum()](#getMaximum--) | Gets the ending value. |
| [getDimension()](#getDimension--) | Gets the dimension of watermark to search by. |
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### SizeSearchCriteria(int dimension, double min, double max) {#SizeSearchCriteria-int-double-double-}
```
public SizeSearchCriteria(int dimension, double min, double max)
```


Initializes a new instance of the `[SizeSearchCriteria](../../com.groupdocs.watermark.search/sizesearchcriteria)` class with a specified dimension, a starting value and an ending value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dimension | int | The dimension `[Dimension](../../com.groupdocs.watermark.common/dimension)` of a watermark to search by. |
| min | double | The starting value. |
| max | double | The ending value. |

### getMinimum() {#getMinimum--}
```
public final double getMinimum()
```


Gets the starting value.

**Returns:**
double - The starting value.
### getMaximum() {#getMaximum--}
```
public final double getMaximum()
```


Gets the ending value.

**Returns:**
double - The ending value.
### getDimension() {#getDimension--}
```
public final int getDimension()
```


Gets the dimension of watermark to search by.

**Returns:**
int - The dimension of watermark to search by.
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

