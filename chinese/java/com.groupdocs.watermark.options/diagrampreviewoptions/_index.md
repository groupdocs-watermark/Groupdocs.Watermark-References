---
title: "DiagramPreviewOptions"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "提供选项以设置需求和流委托，用于生成 Diagram 文档的预览。"
type: docs
weight: 12
url: /zh/java/com.groupdocs.watermark.options/diagrampreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class DiagramPreviewOptions extends PreviewOptions
```

提供选项以设置需求和流委托，用于生成 Diagram 文档的预览。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [DiagramPreviewOptions(ICreatePageStream createPageStream)](#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | 初始化 `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` 类，使输出流被关闭。 |
|
|  | [DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | 初始化 `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` 类，使输出流返回给客户端以供进一步使用。 |
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
|  | [getHighQualityRendering()](#getHighQualityRendering--) | 获取高质量渲染的标志。 |
|
|  | [setHighQualityRendering(boolean value)](#setHighQualityRendering-boolean-) | 设置高质量渲染的标志。 |
|
### DiagramPreviewOptions(ICreatePageStream createPageStream) {#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public DiagramPreviewOptions(ICreatePageStream createPageStream)
```


初始化 `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` 类，使输出流被关闭。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | 为特定页面预览创建流。 |
|

### DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


初始化 `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` 类，使输出流返回给客户端以供进一步使用。


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

默认值为 300。

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

默认值为 300。

<br />

|

### getHighQualityRendering() {#getHighQualityRendering--}
```
public final boolean getHighQualityRendering()
```


获取高质量渲染的标志。


**Returns:**
boolean - 高质量渲染的标志。

<br />

*** ** * ** ***

高质量渲染会使用更多资源。默认值为 false。

<br />


### setHighQualityRendering(boolean value) {#setHighQualityRendering-boolean-}
```
public final void setHighQualityRendering(boolean value)
```


设置高质量渲染的标志。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 高质量渲染的标志。 |

<br />

*** ** * ** ***

高质量渲染会使用更多资源。默认值为 false。

<br />

|

