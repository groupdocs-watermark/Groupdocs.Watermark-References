---
title: "PreviewOptions"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "提供设置需求和流委托以生成预览的选项。"
type: docs
weight: 47
url: /zh/java/com.groupdocs.watermark.options/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

提供设置需求和流委托以生成预览的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PreviewOptions(ICreatePageStream createPageStream)](#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | 初始化 `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` 类的新实例，使输出流被关闭。 |
|
|  | [PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | 初始化 `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` 类的新实例，使输出流返回给客户端以供进一步使用。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getWidth()](#getWidth--) | 获取页面预览宽度。 |
|
|  | [setWidth(int value)](#setWidth-int-) | 设置页面预览宽度。 |
|
|  | [getHeight()](#getHeight--) | 获取页面预览高度。 |
|
|  | [setHeight(int value)](#setHeight-int-) | 设置页面预览高度。 |
|
|  | [getPageNumbers()](#getPageNumbers--) | 获取用于生成预览的页码数组。 |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | 设置用于生成预览的页码数组。 |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | 获取预览图像格式。 |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | 设置预览图像格式。 |
|
|  | [getCreatePageStream()](#getCreatePageStream--) | 获取页面流创建类的实例。 |
|
|  | [setCreatePageStream(ICreatePageStream value)](#setCreatePageStream-com.groupdocs.watermark.options.ICreatePageStream-) | 设置页面流创建类的实例。 |
|
|  | [getReleasePageStream()](#getReleasePageStream--) | 获取页面预览完成类的实例。 |
|
|  | [setReleasePageStream(IReleasePageStream value)](#setReleasePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | 设置页面预览完成类的实例。 |
|
### PreviewOptions(ICreatePageStream createPageStream) {#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PreviewOptions(ICreatePageStream createPageStream)
```


初始化 `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` 类的新实例，使输出流被关闭。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | 为特定页面预览创建流。 |
|

### PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


初始化 `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` 类的新实例，使输出流返回给客户端以供进一步使用。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | 为特定页面预览创建流。 |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | 通知页面预览生成完成并获取输出流。 |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


获取页面预览宽度。


**Returns:**
int - 页面预览宽度。

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


设置页面预览宽度。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 页面预览宽度。 |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


获取页面预览高度。


**Returns:**
int - 页面预览高度。

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


设置页面预览高度。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 页面预览高度。 |
|

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


获取用于生成预览的页码数组。


**Returns:**
int[] - 用于生成预览的页码数组。

### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


设置用于生成预览的页码数组。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int[] | 用于生成预览的页码数组。 |
|

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


获取预览图像格式。


**Returns:**
int - 预览图像格式。

### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


设置预览图像格式。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 预览图像格式。 |
|

### getCreatePageStream() {#getCreatePageStream--}
```
public final ICreatePageStream getCreatePageStream()
```


获取页面流创建类的实例。


**Returns:**
[ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) - The instance of the page stream creation class.

### setCreatePageStream(ICreatePageStream value) {#setCreatePageStream-com.groupdocs.watermark.options.ICreatePageStream-}
```
public final void setCreatePageStream(ICreatePageStream value)
```


设置页面流创建类的实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | 页面流创建类的实例。 |
|

### getReleasePageStream() {#getReleasePageStream--}
```
public final IReleasePageStream getReleasePageStream()
```


获取页面预览完成类的实例。


**Returns:**
[IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) - The instance of the page preview completion delegate.

### setReleasePageStream(IReleasePageStream value) {#setReleasePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public final void setReleasePageStream(IReleasePageStream value)
```


设置页面预览完成类的实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | 页面预览完成委托的实例。 |
|

