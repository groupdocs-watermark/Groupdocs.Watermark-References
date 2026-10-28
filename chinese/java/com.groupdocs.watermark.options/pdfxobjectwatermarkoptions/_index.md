---
title: "PdfXObjectWatermarkOptions"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示在向 PDF 文档添加 XObject 水印时的水印添加选项。"
type: docs
weight: 34
url: /zh/java/com.groupdocs.watermark.options/pdfxobjectwatermarkoptions/
---
**Inheritance:**
java.lang.Object, `[com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions)`, `[com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)`
```
public final class PdfXObjectWatermarkOptions extends PdfWatermarkOptions
```

表示在向 PDF 文档添加 XObject 水印时的水印添加选项。

**Learn more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

以下示例演示如何向 PDF 文档的特定页面添加水印。
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\doc.pdf", loadOptions);
>
>    ImageWatermark watermark = new ImageWatermark("C:\\watermark.png");
>
>    PdfXObjectWatermarkOptions options = new PdfXObjectWatermarkOptions();
>    options.setPageIndex(0);
>
>    watermarker.add(watermark, options);
>    watermarker.save("C:\\watermarked_doc.pdf");
>    watermark.close();
>    watermarker.close();
>  
> ```
> ````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PdfXObjectWatermarkOptions()](#PdfXObjectWatermarkOptions--) | 初始化 `[PdfXObjectWatermarkOptions](../../com.groupdocs.watermark.options/pdfxobjectwatermarkoptions)` 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | 获取要添加水印的页面索引。 |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | 设置要添加水印的页面索引。 |
|
### PdfXObjectWatermarkOptions() {#PdfXObjectWatermarkOptions--}
```
public PdfXObjectWatermarkOptions()
```


初始化 `[PdfXObjectWatermarkOptions](../../com.groupdocs.watermark.options/pdfxobjectwatermarkoptions)` 类的新实例。


### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


获取要添加水印的页面索引。


**Returns:**
int - 要添加水印的页面索引。

### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


设置要添加水印的页面索引。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 要添加水印的页面索引。 |
|

