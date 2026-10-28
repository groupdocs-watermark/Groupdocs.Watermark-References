---
title: "SizeSearchCriteria"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示允许按水印大小进行过滤的条件。"
type: docs
weight: 57
url: /zh/java/com.groupdocs.watermark.search/sizesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class SizeSearchCriteria extends SearchCriteria
```

表示允许按水印大小进行过滤的条件。

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

以下示例演示如何使用搜索条件查找并删除水印。
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


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [SizeSearchCriteria(int dimension, double min, double max)](#SizeSearchCriteria-int-double-double-) | 使用指定的维度、起始值和结束值初始化 `[SizeSearchCriteria](../../com.groupdocs.watermark.search/sizesearchcriteria)` 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getMinimum()](#getMinimum--) | 获取起始值。 |
|
|  | [getMaximum()](#getMaximum--) | 获取结束值。 |
|
|  | [getDimension()](#getDimension--) | 获取用于搜索的水印维度。 |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### SizeSearchCriteria(int dimension, double min, double max) {#SizeSearchCriteria-int-double-double-}
```
public SizeSearchCriteria(int dimension, double min, double max)
```


使用指定的维度、起始值和结束值初始化 `[SizeSearchCriteria](../../com.groupdocs.watermark.search/sizesearchcriteria)` 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | dimension | int | 用于搜索的水印维度 `[Dimension](../../com.groupdocs.watermark.common/dimension)`。 |
|
|  | min | double | 起始值。 |
|
|  | 最大 | double | 结束值。 |
|

### getMinimum() {#getMinimum--}
```
public final double getMinimum()
```


获取起始值。


**Returns:**
double - 起始值。

### getMaximum() {#getMaximum--}
```
public final double getMaximum()
```


获取结束值。


**Returns:**
double - 结束值。

### getDimension() {#getDimension--}
```
public final int getDimension()
```


获取用于搜索的水印维度。


**Returns:**
int - 用于搜索水印的维度。

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

