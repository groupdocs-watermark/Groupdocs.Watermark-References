---
title: "SpreadsheetPreviewOptions"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "提供设置需求和流委托以生成电子表格文档预览的选项。"
type: docs
weight: 52
url: /zh/java/com.groupdocs.watermark.options/spreadsheetpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class SpreadsheetPreviewOptions extends PreviewOptions
```

提供设置需求和流委托以生成电子表格文档预览的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [SpreadsheetPreviewOptions(ICreatePageStream createPageStream)](#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | 初始化一个 `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` 类的新实例，使输出流被关闭。 |
|
|  | [SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | 初始化一个 `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` 类的新实例，使输出流返回给客户端以供进一步使用。 |
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
|  | [getOnlyDataArea()](#getOnlyDataArea--) | 获取仅渲染数据区域而不包括页眉、页脚、边距的标志。 |
|
|  | [setOnlyDataArea(boolean value)](#setOnlyDataArea-boolean-) | 设置仅渲染数据区域而不包括页眉、页脚、边距的标志。 |
|
### SpreadsheetPreviewOptions(ICreatePageStream createPageStream) {#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public SpreadsheetPreviewOptions(ICreatePageStream createPageStream)
```


初始化一个 `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` 类的新实例，使输出流被关闭。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | 为特定页面预览创建流。 |
|

### SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


初始化一个 `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` 类的新实例，使输出流返回给客户端以供进一步使用。


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

默认值为 96。

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

默认值为 96。

<br />

|

### getOnlyDataArea() {#getOnlyDataArea--}
```
public final boolean getOnlyDataArea()
```


获取仅渲染数据区域而不包括页眉、页脚、边距的标志。


**Returns:**
boolean - 仅渲染数据区域而不包括页眉、页脚、边距的标志。

<br />

*** ** * ** ***

此标志导致在单页上渲染整个工作表。默认值为 false。

<br />


### setOnlyDataArea(boolean value) {#setOnlyDataArea-boolean-}
```
public final void setOnlyDataArea(boolean value)
```


设置仅渲染数据区域而不包括页眉、页脚、边距的标志。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 仅渲染数据区域而不包括页眉、页脚、边距的标志。 |

<br />

*** ** * ** ***

此标志导致在单页上渲染整个工作表。默认值为 false。

<br />

|

