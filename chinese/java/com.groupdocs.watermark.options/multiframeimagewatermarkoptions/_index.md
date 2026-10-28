---
title: "MultiframeImageWatermarkOptions"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示在向多帧图像添加水印时的水印添加选项。"
type: docs
weight: 26
url: /zh/java/com.groupdocs.watermark.options/multiframeimagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions)
```
public class MultiframeImageWatermarkOptions extends WatermarkOptions
```

表示在向多帧图像添加水印时的水印添加选项。

**Learn more:**

* [Add watermarks to images](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images)

以下示例演示了如何向多帧图像的特定帧添加水印。
>
> ````
> ```
>
>    ImageLoadOptions loadOptions = new ImageLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\test.gif", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));
>
>    MultiframeImageWatermarkOptions options = new MultiframeImageWatermarkOptions();
>    options.setFrameIndex(0);
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.gif");
>    watermarker.close();
>  
> ```
> ````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [MultiframeImageWatermarkOptions()](#MultiframeImageWatermarkOptions--) | 初始化一个新的 `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` 类实例。 |
|
|  | [MultiframeImageWatermarkOptions(int frameIndex)](#MultiframeImageWatermarkOptions-int-) | 初始化一个新的 `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` 类实例，并指定帧的索引。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getFrameIndex()](#getFrameIndex--) | 获取要添加水印的帧索引。 |
|
|  | [setFrameIndex(int value)](#setFrameIndex-int-) | 设置要添加水印的帧索引。 |
|
### MultiframeImageWatermarkOptions() {#MultiframeImageWatermarkOptions--}
```
public MultiframeImageWatermarkOptions()
```


初始化一个新的 `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` 类实例。


### MultiframeImageWatermarkOptions(int frameIndex) {#MultiframeImageWatermarkOptions-int-}
```
public MultiframeImageWatermarkOptions(int frameIndex)
```


初始化一个新的 `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` 类实例，并指定帧的索引。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | frameIndex | int | 要添加水印的帧索引。 |
|

### getFrameIndex() {#getFrameIndex--}
```
public final int getFrameIndex()
```


获取要添加水印的帧索引。


**Returns:**
int - 要添加水印的帧索引。

<br />

*** ** * ** ***

-1 means all frames.

<br />


### setFrameIndex(int value) {#setFrameIndex-int-}
```
public final void setFrameIndex(int value)
```


设置要添加水印的帧索引。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 要添加水印的帧索引。 |

<br />

*** ** * ** ***

-1 means all frames.

<br />

|

