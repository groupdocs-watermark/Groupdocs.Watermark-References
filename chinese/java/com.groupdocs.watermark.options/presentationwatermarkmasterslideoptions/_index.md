---
title: "PresentationWatermarkMasterSlideOptions"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示在向演示文稿文档母版幻灯片添加水印时的选项。"
type: docs
weight: 43
url: /zh/java/com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)
```
public final class PresentationWatermarkMasterSlideOptions extends PresentationWatermarkBaseSlideOptions
```

表示在向演示文稿文档母版幻灯片添加水印时的选项。

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

请参阅 `[PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)` 中的使用示例。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PresentationWatermarkMasterSlideOptions()](#PresentationWatermarkMasterSlideOptions--) | 初始化 `[PresentationWatermarkMasterSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions)` 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getMasterSlideIndex()](#getMasterSlideIndex--) | 获取要添加水印的母版幻灯片的索引。 |
|
|  | [setMasterSlideIndex(int value)](#setMasterSlideIndex-int-) | 设置要添加水印的母版幻灯片的索引。 |
|
### PresentationWatermarkMasterSlideOptions() {#PresentationWatermarkMasterSlideOptions--}
```
public PresentationWatermarkMasterSlideOptions()
```


初始化 `[PresentationWatermarkMasterSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions)` 类的新实例。


### getMasterSlideIndex() {#getMasterSlideIndex--}
```
public final int getMasterSlideIndex()
```


获取要添加水印的母版幻灯片的索引。


**Returns:**
int - 要添加水印的母版幻灯片的索引。

<br />

*** ** * ** ***

-1 means all slides.

<br />


### setMasterSlideIndex(int value) {#setMasterSlideIndex-int-}
```
public final void setMasterSlideIndex(int value)
```


设置要添加水印的母版幻灯片的索引。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 要添加水印的母版幻灯片的索引。 |

<br />

*** ** * ** ***

-1 means all slides.

<br />

|

