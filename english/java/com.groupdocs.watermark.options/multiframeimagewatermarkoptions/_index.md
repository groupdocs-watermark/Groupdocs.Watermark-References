---
title: MultiframeImageWatermarkOptions
second_title: GroupDocs.Watermark for Java API Reference
description: Represents watermark adding options when adding watermark to a multi-frame image.
type: docs
weight: 26
url: /java/com.groupdocs.watermark.options/multiframeimagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions)
```
public class MultiframeImageWatermarkOptions extends WatermarkOptions
```

Represents watermark adding options when adding watermark to a multi-frame image.

**Learn more:**

 *  [Add watermarks to images][]

The following example demonstrates how to add a watermark to a particular frame of multi-frame image.

> ```
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
> ```


[Add watermarks to images]: https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images
## Constructors

| Constructor | Description |
| --- | --- |
| [MultiframeImageWatermarkOptions()](#MultiframeImageWatermarkOptions--) | Initializes a new instance of the `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` class. |
| [MultiframeImageWatermarkOptions(int frameIndex)](#MultiframeImageWatermarkOptions-int-) | Initializes a new instance of the `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` class with a specified index of the frame. |
## Methods

| Method | Description |
| --- | --- |
| [getFrameIndex()](#getFrameIndex--) | Gets the index of frame to add watermark. |
| [setFrameIndex(int value)](#setFrameIndex-int-) | Sets the index of frame to add watermark. |
### MultiframeImageWatermarkOptions() {#MultiframeImageWatermarkOptions--}
```
public MultiframeImageWatermarkOptions()
```


Initializes a new instance of the `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` class.

### MultiframeImageWatermarkOptions(int frameIndex) {#MultiframeImageWatermarkOptions-int-}
```
public MultiframeImageWatermarkOptions(int frameIndex)
```


Initializes a new instance of the `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` class with a specified index of the frame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| frameIndex | int | The index of frame to add watermark. |

### getFrameIndex() {#getFrameIndex--}
```
public final int getFrameIndex()
```


Gets the index of frame to add watermark.

**Returns:**
int - The index of frame to add watermark.

--------------------

\-1 means all frames.
### setFrameIndex(int value) {#setFrameIndex-int-}
```
public final void setFrameIndex(int value)
```


Sets the index of frame to add watermark.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The index of frame to add watermark.

--------------------

\-1 means all frames. |

