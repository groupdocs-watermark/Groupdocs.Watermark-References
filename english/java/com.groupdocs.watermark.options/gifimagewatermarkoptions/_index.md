---
title: GifImageWatermarkOptions
second_title: GroupDocs.Watermark for Java API Reference
description: Represents watermark adding options when adding watermark to a GIF image.
type: docs
weight: 21
url: /java/com.groupdocs.watermark.options/gifimagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)
```
public final class GifImageWatermarkOptions extends MultiframeImageWatermarkOptions
```

Represents watermark adding options when adding watermark to a GIF image.

**Learn more:**

 *  [Add watermarks to images][]

The following example demonstrates how to add a watermark to a particular frame of GIF image.

> ```
> ```
> 
>    GifImageLoadOptions loadOptions = new GifImageLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\test.gif", loadOptions);
> 
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));
> 
>    GifImageWatermarkOptions options = new GifImageWatermarkOptions();
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
| [GifImageWatermarkOptions()](#GifImageWatermarkOptions--) | Initializes a new instance of the `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)` class. |
| [GifImageWatermarkOptions(int frameIndex)](#GifImageWatermarkOptions-int-) | Initializes a new instance of the `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)` class with a specified index of a frame. |
### GifImageWatermarkOptions() {#GifImageWatermarkOptions--}
```
public GifImageWatermarkOptions()
```


Initializes a new instance of the `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)` class.

### GifImageWatermarkOptions(int frameIndex) {#GifImageWatermarkOptions-int-}
```
public GifImageWatermarkOptions(int frameIndex)
```


Initializes a new instance of the `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)` class with a specified index of a frame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| frameIndex | int | The index of frame to add watermark. |

