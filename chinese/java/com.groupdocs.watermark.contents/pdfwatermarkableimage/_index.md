---
title: "PdfWatermarkableImage"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示 PDF 文档中的图像。"
type: docs
weight: 72
url: /zh/java/com.groupdocs.watermark.contents/pdfwatermarkableimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
```
public class PdfWatermarkableImage extends WatermarkableImage
```

表示 PDF 文档中的图像。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PdfWatermarkableImage(byte[] imageData)](#PdfWatermarkableImage-byte---) | 使用指定的图像数据初始化 `[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage)` 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [fetchOrCreate(XImageCollection imageCollection, String nameInCollection, PdfContent content)](#fetchOrCreate-com.aspose.pdf.XImageCollection-java.lang.String-com.groupdocs.watermark.contents.PdfContent-) | <br /> |

|
### PdfWatermarkableImage(byte[] imageData) {#PdfWatermarkableImage-byte---}
```
public PdfWatermarkableImage(byte[] imageData)
```


使用指定的图像数据初始化 `[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage)` 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | imageData | byte[] | 用于创建 `[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage)` 的无符号字节数组。 |
|

### fetchOrCreate(XImageCollection imageCollection, String nameInCollection, PdfContent content) {#fetchOrCreate-com.aspose.pdf.XImageCollection-java.lang.String-com.groupdocs.watermark.contents.PdfContent-}
```
public static PdfWatermarkableImage fetchOrCreate(XImageCollection imageCollection, String nameInCollection, PdfContent content)
```


<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageCollection | com.aspose.pdf.XImageCollection |  |
| nameInCollection | java.lang.String |  |
| content | [PdfContent](../../com.groupdocs.watermark.contents/pdfcontent) |  |

**Returns:**
[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage)
