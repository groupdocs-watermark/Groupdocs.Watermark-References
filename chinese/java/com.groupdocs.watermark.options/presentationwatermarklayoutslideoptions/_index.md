---
title: "PresentationWatermarkLayoutSlideOptions"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示在向演示文稿文档布局幻灯片添加水印时的选项。"
type: docs
weight: 40
url: /zh/java/com.groupdocs.watermark.options/presentationwatermarklayoutslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)
```
public final class PresentationWatermarkLayoutSlideOptions extends PresentationWatermarkBaseSlideOptions
```

表示在向演示文稿文档布局幻灯片添加水印时的选项。

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

请参阅 `[PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)` 中的使用示例。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PresentationWatermarkLayoutSlideOptions()](#PresentationWatermarkLayoutSlideOptions--) | 初始化 `[PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions)` 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getLayoutSlideIndex()](#getLayoutSlideIndex--) | 获取要添加水印的布局幻灯片索引。 |
|
|  | [setLayoutSlideIndex(int value)](#setLayoutSlideIndex-int-) | 设置要添加水印的布局幻灯片索引。 |
|
### PresentationWatermarkLayoutSlideOptions() {#PresentationWatermarkLayoutSlideOptions--}
```
public PresentationWatermarkLayoutSlideOptions()
```


初始化 `[PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions)` 类的新实例。


### getLayoutSlideIndex() {#getLayoutSlideIndex--}
```
public final int getLayoutSlideIndex()
```


获取要添加水印的布局幻灯片索引。


**Returns:**
int - 要添加水印的布局幻灯片索引。

<br />

*** ** * ** ***

-1 means all slides.

<br />


### setLayoutSlideIndex(int value) {#setLayoutSlideIndex-int-}
```
public final void setLayoutSlideIndex(int value)
```


设置要添加水印的布局幻灯片索引。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 要添加水印的布局幻灯片索引。 |

<br />

*** ** * ** ***

-1 means all slides.

<br />

|

