---
title: "PresentationPreviewOptions"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "提供选项以设置需求和流委托，用于生成 Presentation 文档的预览。"
type: docs
weight: 12
url: /zh/java/com.groupdocs.watermark/presentationpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class PresentationPreviewOptions extends PreviewOptions
```

提供选项以设置需求和流委托，用于生成 Presentation 文档的预览。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PresentationPreviewOptions(ICreatePageStream createPageStream)](#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | 初始化 `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` 类的新实例，使输出流被关闭。 |
|
|  | [PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | 初始化 `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` 类的新实例，使输出流返回给客户端以供进一步使用。 |
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
|  | [setResolution(long value)](#setResolution-long-) | 设置生成图像的分辨率（每英寸点数）。 |
|
### PresentationPreviewOptions(ICreatePageStream createPageStream) {#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PresentationPreviewOptions(ICreatePageStream createPageStream)
```


初始化 `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` 类的新实例，使输出流被关闭。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | 为特定页面预览创建流。 |
|

### PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


初始化 `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` 类的新实例，使输出流返回给客户端以供进一步使用。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | 为特定页面预览创建流。 |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | 通知页面预览生成完成并获取输出流。 |
|

### DefaultResolution {#DefaultResolution}
```
public static final long DefaultResolution
```


默认分辨率（每英寸点数）。


### getResolution() {#getResolution--}
```
public final long getResolution()
```


获取生成图像的分辨率（每英寸点数）。


**Returns:**
long - 生成图像的分辨率（每英寸点数）。

### setResolution(long value) {#setResolution-long-}
```
public final void setResolution(long value)
```


设置生成图像的分辨率（每英寸点数）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | long | 生成图像的分辨率（每英寸点数）。 |
|

