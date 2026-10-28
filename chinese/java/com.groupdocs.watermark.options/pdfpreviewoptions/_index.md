---
title: "PdfPreviewOptions"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "提供用于设置 PDF 文档预览生成的要求和流委托的选项。"
type: docs
weight: 31
url: /zh/java/com.groupdocs.watermark.options/pdfpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class PdfPreviewOptions extends PreviewOptions
```

提供用于设置 PDF 文档预览生成的要求和流委托的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PdfPreviewOptions(ICreatePageStream createPageStream)](#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | 初始化 `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` 类的新实例，使输出流被关闭。 |
|
|  | [PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | 初始化 `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` 类的新实例，使输出流返回给客户端以供进一步使用。 |
|
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [DefaultResolution](#DefaultResolution) | 默认分辨率（每英寸点数）。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getResolution()](#getResolution--) | 获取生成图像的分辨率（每英寸点数）。 |
|
|  | [setResolution(int value)](#setResolution-int-) | 设置生成图像的分辨率（每英寸点数）。 |
|
### PdfPreviewOptions(ICreatePageStream createPageStream) {#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PdfPreviewOptions(ICreatePageStream createPageStream)
```


初始化 `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` 类的新实例，使输出流被关闭。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | 为特定页面预览创建流。 |
|

### PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


初始化 `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` 类的新实例，使输出流返回给客户端以供进一步使用。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | 为特定页面预览创建流。 |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | 通知页面预览生成完成并获取输出流。 |
|

### DefaultResolution {#DefaultResolution}
```
public static final int DefaultResolution
```


默认分辨率（每英寸点数）。


### getResolution() {#getResolution--}
```
public final int getResolution()
```


获取生成图像的分辨率（每英寸点数）。


**Returns:**
int - 生成图像的分辨率，单位为每英寸点数（dpi）。

<br />

*** ** * ** ***

默认值是 150。

<br />


### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


设置生成图像的分辨率（每英寸点数）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 生成图像的分辨率（每英寸点数）。 |

<br />

*** ** * ** ***

默认值是 150。

<br />

|

