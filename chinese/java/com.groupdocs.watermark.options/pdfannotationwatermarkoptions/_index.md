---
title: "PdfAnnotationWatermarkOptions"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示在向 PDF 文档添加注释水印时的水印添加选项。"
type: docs
weight: 28
url: /zh/java/com.groupdocs.watermark.options/pdfannotationwatermarkoptions/
---
**Inheritance:**
java.lang.Object, `[com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions)`, `[com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)`
```
public final class PdfAnnotationWatermarkOptions extends PdfWatermarkOptions
```

表示在向 PDF 文档添加注释水印时的水印添加选项。

**Learn more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

以下示例演示如何向 PDF 文档添加图像注释水印。
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.pdf", loadOptions);
>
>    ImageWatermark watermark = new ImageWatermark("D:\\icon.png");
>
>    PdfAnnotationWatermarkOptions options = new PdfAnnotationWatermarkOptions();
>    options.setPageIndex(-1); // default - all pages
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.pdf");
>    watermark.close();
>    watermarker.close();
>  
> ```
> ````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PdfAnnotationWatermarkOptions()](#PdfAnnotationWatermarkOptions--) | 初始化 `[PdfAnnotationWatermarkOptions](../../com.groupdocs.watermark.options/pdfannotationwatermarkoptions)` 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | 获取要添加水印的页面索引。 |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | 设置要添加水印的页面索引。 |
|
|  | [getPrintOnly()](#getPrintOnly--) | 获取指示注释是否将在 PDF 查看应用程序中打印但不显示的值。 |
|
|  | [setPrintOnly(boolean value)](#setPrintOnly-boolean-) | 设置指示注释是否将在 PDF 查看应用程序中打印但不显示的值。 |
|
### PdfAnnotationWatermarkOptions() {#PdfAnnotationWatermarkOptions--}
```
public PdfAnnotationWatermarkOptions()
```


初始化 `[PdfAnnotationWatermarkOptions](../../com.groupdocs.watermark.options/pdfannotationwatermarkoptions)` 类的新实例。


### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


获取要添加水印的页面索引。


**Returns:**
int - 要添加水印的页面索引。

<br />

*** ** * ** ***

-1 means all pages.

<br />


### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


设置要添加水印的页面索引。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 要添加水印的页面索引。 |

<br />

*** ** * ** ***

-1 means all pages.

<br />

|

### getPrintOnly() {#getPrintOnly--}
```
public final boolean getPrintOnly()
```


获取指示注释是否将在 PDF 查看应用程序中打印但不显示的值。


**Returns:**
boolean - 指示注释是否将在 PDF 查看应用程序中打印但不显示的值。

### setPrintOnly(boolean value) {#setPrintOnly-boolean-}
```
public final void setPrintOnly(boolean value)
```


设置指示注释是否将在 PDF 查看应用程序中打印但不显示的值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 指示注释是否将在 PDF 查看应用程序中打印但不显示的值。 |
|

