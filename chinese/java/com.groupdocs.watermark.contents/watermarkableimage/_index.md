---
title: "WatermarkableImage"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示文档中的图像。"
type: docs
weight: 127
url: /zh/java/com.groupdocs.watermark.contents/watermarkableimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public abstract class WatermarkableImage extends ContentPart
```

表示文档中的图像。

**Learn more:**

* [Adding watermark to images inside a document](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermark+to+images+inside+a+document)

以下示例演示了如何向任何受支持类型的文档中的所有图像添加水印。
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\input.doc");
>  
>    // Initialize text or image watermark.
>    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));
>  
>    // Find all images in the content.
>    WatermarkableImageCollection images = watermarker.getImages();
>  
>    // Add watermark.
>    for (WatermarkableImage watermarkableImage : images)
>    {
>        watermarkableImage.add(watermark);
>    }
>  
>    // Save changes.
>    watermarker.save("D:\\output.doc");
>    watermarker.close();
>  
> ```
> ````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WatermarkableImage(Content content)](#WatermarkableImage-com.groupdocs.watermark.contents.Content-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getHeight()](#getHeight--) | 获取此 `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` 的高度（像素）。 |
|
|  | [getWidth()](#getWidth--) | 获取此 `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` 的宽度（像素）。 |
|
|  | [add(Watermark watermark)](#add-com.groupdocs.watermark.Watermark-) | 向此 `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` 添加水印。 |
|
|  | [getBytes()](#getBytes--) | 获取图像的字节数组。 |
|
| [updateDocumentReference(Content parentContent)](#updateDocumentReference-com.groupdocs.watermark.contents.Content-) |  |
### WatermarkableImage(Content content) {#WatermarkableImage-com.groupdocs.watermark.contents.Content-}
```
public WatermarkableImage(Content content)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| content | [Content](../../com.groupdocs.watermark.contents/content) |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


获取此 `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` 的高度（像素）。


**Returns:**
int - 此 `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` 的高度（像素）。

### getWidth() {#getWidth--}
```
public final int getWidth()
```


获取此 `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` 的宽度（像素）。


**Returns:**
int - 此 `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` 的宽度（像素）。

### add(Watermark watermark) {#add-com.groupdocs.watermark.Watermark-}
```
public final void add(Watermark watermark)
```


向此 `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` 添加水印。

此方法假设水印的偏移量和大小以像素为单位（如果已分配）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | 要添加到图像的水印。 |
|

### getBytes() {#getBytes--}
```
public final byte[] getBytes()
```


获取图像的字节数组。


**Returns:**
byte[] - 图像数据。

### updateDocumentReference(Content parentContent) {#updateDocumentReference-com.groupdocs.watermark.contents.Content-}
```
public final void updateDocumentReference(Content parentContent)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| parentContent | [Content](../../com.groupdocs.watermark.contents/content) |  |

