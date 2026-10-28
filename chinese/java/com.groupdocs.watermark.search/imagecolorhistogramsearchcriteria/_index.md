---
title: "ImageColorHistogramSearchCriteria"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示在内容中查找图像的搜索条件。"
type: docs
weight: 30
url: /zh/java/com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria), [com.groupdocs.watermark.search.ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria)
```
public class ImageColorHistogramSearchCriteria extends ImageSearchCriteria
```

表示在内容中查找图像的搜索条件。

<br />

*** ** * ** ***

此搜索条件使用图像颜色直方图来计算图像相似度。

<br />


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [ImageColorHistogramSearchCriteria(String filePath)](#ImageColorHistogramSearchCriteria-java.lang.String-) | 使用指定的文件路径初始化 `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` 类的新实例。 |
|
|  | [ImageColorHistogramSearchCriteria(InputStream stream)](#ImageColorHistogramSearchCriteria-java.io.InputStream-) | 使用指定的流初始化 `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getBinsCount()](#getBinsCount--) | 获取用于构建颜色直方图的箱子数量。 |
|
|  | [setBinsCount(byte value)](#setBinsCount-byte-) | 设置用于构建颜色直方图的箱子数量。 |
|
### ImageColorHistogramSearchCriteria(String filePath) {#ImageColorHistogramSearchCriteria-java.lang.String-}
```
public ImageColorHistogramSearchCriteria(String filePath)
```


使用指定的文件路径初始化 `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 加载图像的文件路径。 |
|

### ImageColorHistogramSearchCriteria(InputStream stream) {#ImageColorHistogramSearchCriteria-java.io.InputStream-}
```
public ImageColorHistogramSearchCriteria(InputStream stream)
```


使用指定的流初始化 `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | stream | java.io.InputStream | 加载图像的流。 |
|

### getBinsCount() {#getBinsCount--}
```
public final byte getBinsCount()
```


获取用于构建颜色直方图的箱子数量。


**Returns:**
byte - 默认值为 10。

### setBinsCount(byte value) {#setBinsCount-byte-}
```
public final void setBinsCount(byte value)
```


设置用于构建颜色直方图的箱子数量。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | byte | 默认值为 10。 |
|

