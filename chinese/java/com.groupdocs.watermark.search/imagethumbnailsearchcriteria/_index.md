---
title: "ImageThumbnailSearchCriteria"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示在内容中查找图像的搜索条件。"
type: docs
weight: 33
url: /zh/java/com.groupdocs.watermark.search/imagethumbnailsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria), [com.groupdocs.watermark.search.ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria)
```
public class ImageThumbnailSearchCriteria extends ImageSearchCriteria
```

表示在内容中查找图像的搜索条件。

<br />

*** ** * ** ***

此搜索条件使用二值化图像缩略图来计算图像相似度。

<br />


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [ImageThumbnailSearchCriteria(String filePath)](#ImageThumbnailSearchCriteria-java.lang.String-) | 使用指定的文件路径初始化 `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` 类的新实例。 |
|
|  | [ImageThumbnailSearchCriteria(InputStream stream)](#ImageThumbnailSearchCriteria-java.io.InputStream-) | 使用指定的流初始化 `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getThumbnailSize()](#getThumbnailSize--) | 获取缩略图大小。 |
|
|  | [setThumbnailSize(byte value)](#setThumbnailSize-byte-) | 设置缩略图大小。 |
|
### ImageThumbnailSearchCriteria(String filePath) {#ImageThumbnailSearchCriteria-java.lang.String-}
```
public ImageThumbnailSearchCriteria(String filePath)
```


使用指定的文件路径初始化 `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 加载图像的文件路径。 |
|

### ImageThumbnailSearchCriteria(InputStream stream) {#ImageThumbnailSearchCriteria-java.io.InputStream-}
```
public ImageThumbnailSearchCriteria(InputStream stream)
```


使用指定的流初始化 `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | stream | java.io.InputStream | 加载图像的流。 |
|

### getThumbnailSize() {#getThumbnailSize--}
```
public final byte getThumbnailSize()
```


获取缩略图大小。


**Returns:**
byte - 默认使用 32X32 缩略图。

### setThumbnailSize(byte value) {#setThumbnailSize-byte-}
```
public final void setThumbnailSize(byte value)
```


设置缩略图大小。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | byte | 默认使用 32X32 缩略图。 |
|

