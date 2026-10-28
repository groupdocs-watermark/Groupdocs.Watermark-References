---
title: "PresentationWatermarkNoteSlideOptions"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示在向演示文稿文档备注幻灯片添加水印时的选项。"
type: docs
weight: 44
url: /zh/java/com.groupdocs.watermark.options/presentationwatermarknoteslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)
```
public final class PresentationWatermarkNoteSlideOptions extends PresentationWatermarkBaseSlideOptions
```

表示在向演示文稿文档备注幻灯片添加水印时的选项。

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

请参阅 `[PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)` 中的使用示例。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PresentationWatermarkNoteSlideOptions()](#PresentationWatermarkNoteSlideOptions--) | 初始化 `[PresentationWatermarkNoteSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarknoteslideoptions)` 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getSlideIndex()](#getSlideIndex--) | 获取要在其备注幻灯片上添加水印的幻灯片索引。 |
|
|  | [setSlideIndex(int value)](#setSlideIndex-int-) | 设置要在其备注幻灯片上添加水印的幻灯片索引。 |
|
### PresentationWatermarkNoteSlideOptions() {#PresentationWatermarkNoteSlideOptions--}
```
public PresentationWatermarkNoteSlideOptions()
```


初始化 `[PresentationWatermarkNoteSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarknoteslideoptions)` 类的新实例。


### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```


获取要在其备注幻灯片上添加水印的幻灯片索引。


**Returns:**
int - 要在其备注幻灯片上添加水印的幻灯片索引。

<br />

*** ** * ** ***

-1 means all slides.

<br />


### setSlideIndex(int value) {#setSlideIndex-int-}
```
public final void setSlideIndex(int value)
```


设置要在其备注幻灯片上添加水印的幻灯片索引。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 要在其备注幻灯片上添加水印的幻灯片索引。 |

<br />

*** ** * ** ***

-1 means all slides.

<br />

|

