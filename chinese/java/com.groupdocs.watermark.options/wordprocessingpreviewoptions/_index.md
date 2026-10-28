---
title: "WordProcessingPreviewOptions"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "提供设置需求和流委托以生成 WordProcessing 文档预览的选项。"
type: docs
weight: 69
url: /zh/java/com.groupdocs.watermark.options/wordprocessingpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class WordProcessingPreviewOptions extends PreviewOptions
```

提供设置需求和流委托以生成 WordProcessing 文档预览的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [WordProcessingPreviewOptions(ICreatePageStream createPageStream)](#WordProcessingPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | 初始化 `[WordProcessingPreviewOptions](../../com.groupdocs.watermark.options/wordprocessingpreviewoptions)` 类的实例，并关闭输出流。 |
|
|  | [WordProcessingPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#WordProcessingPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | 初始化 `[WordProcessingPreviewOptions](../../com.groupdocs.watermark.options/wordprocessingpreviewoptions)` 类的实例，并将输出流返回给客户端以供进一步使用。 |
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
|  | [setResolution(float value)](#setResolution-float-) | 设置生成图像的分辨率（每英寸点数）。 |
|
### WordProcessingPreviewOptions(ICreatePageStream createPageStream) {#WordProcessingPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public WordProcessingPreviewOptions(ICreatePageStream createPageStream)
```


初始化 `[WordProcessingPreviewOptions](../../com.groupdocs.watermark.options/wordprocessingpreviewoptions)` 类的实例，并关闭输出流。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | 为特定页面预览创建流。 |
|

### WordProcessingPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#WordProcessingPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public WordProcessingPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


初始化 `[WordProcessingPreviewOptions](../../com.groupdocs.watermark.options/wordprocessingpreviewoptions)` 类的实例，并将输出流返回给客户端以供进一步使用。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | 为特定页面预览创建流。 |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | 通知页面预览生成完成并获取输出流。 |
|

### DefaultResolution {#DefaultResolution}
```
public static final float DefaultResolution
```


默认分辨率（每英寸点数）。


### getResolution() {#getResolution--}
```
public final float getResolution()
```


获取生成图像的分辨率（每英寸点数）。


**Returns:**
float - 生成图像的分辨率，单位为每英寸点数（dpi）。

<br />

*** ** * ** ***

默认值为 96。

<br />


### setResolution(float value) {#setResolution-float-}
```
public final void setResolution(float value)
```


设置生成图像的分辨率（每英寸点数）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | float | 生成图像的分辨率（每英寸点数）。 |

<br />

*** ** * ** ***

默认值为 96。

<br />

|

