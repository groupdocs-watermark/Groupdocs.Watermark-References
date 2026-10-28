---
title: "PdfArtifactWatermarkOptions"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示在向 PDF 文档添加制品水印时的水印添加选项。"
type: docs
weight: 29
url: /zh/java/com.groupdocs.watermark.options/pdfartifactwatermarkoptions/
---
**Inheritance:**
java.lang.Object, `[com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions)`, `[com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)`
```
public final class PdfArtifactWatermarkOptions extends PdfWatermarkOptions
```

表示在向 PDF 文档添加制品水印时的水印添加选项。

**Leran more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

以下示例演示如何向 PDF 文档添加图像工件水印。
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.pdf", loadOptions);
>
>    ImageWatermark watermark = new ImageWatermark("D:\\icon.png");
>
>    PdfArtifactWatermarkOptions options = new PdfArtifactWatermarkOptions();
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
|  | [PdfArtifactWatermarkOptions()](#PdfArtifactWatermarkOptions--) | 初始化 `[PdfArtifactWatermarkOptions](../../com.groupdocs.watermark.options/pdfartifactwatermarkoptions)` 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | 获取要添加水印的页面索引。 |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | 设置要添加水印的页面索引。 |
|
### PdfArtifactWatermarkOptions() {#PdfArtifactWatermarkOptions--}
```
public PdfArtifactWatermarkOptions()
```


初始化 `[PdfArtifactWatermarkOptions](../../com.groupdocs.watermark.options/pdfartifactwatermarkoptions)` 类的新实例。


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

