---
title: TiffImageWatermarkOptions
second_title: GroupDocs.Watermark for Java API Reference
description: Represents watermark adding options when adding watermark to a TIFF image.
type: docs
weight: 63
url: /java/com.groupdocs.watermark.options/tiffimagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)
```
public final class TiffImageWatermarkOptions extends MultiframeImageWatermarkOptions
```

Represents watermark adding options when adding watermark to a TIFF image.

**Learn more:**

 *  [Add watermarks to images][]

The following example demonstrates how to add a watermark to a particular frame of TIFF image.

> ```
> ```
> 
>    TiffImageImageLoadOptions loadOptions = new TiffImageImageLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\test.tiff", loadOptions);
> 
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));
> 
>    TiffImageWatermarkOptions options = new TiffImageWatermarkOptions();
>    options.setFrameIndex(0);
> 
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.tiff");
>    watermarker.close();
>  
> ```
> ```


[Add watermarks to images]: https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images
## Constructors

| Constructor | Description |
| --- | --- |
| [TiffImageWatermarkOptions()](#TiffImageWatermarkOptions--) | Initializes a new instance of the `[TiffImageWatermarkOptions](../../com.groupdocs.watermark.options/tiffimagewatermarkoptions)` class. |
| [TiffImageWatermarkOptions(int frameIndex)](#TiffImageWatermarkOptions-int-) | Initializes a new instance of the `[TiffImageWatermarkOptions](../../com.groupdocs.watermark.options/tiffimagewatermarkoptions)` class with a specified index of the frame. |
### TiffImageWatermarkOptions() {#TiffImageWatermarkOptions--}
```
public TiffImageWatermarkOptions()
```


Initializes a new instance of the `[TiffImageWatermarkOptions](../../com.groupdocs.watermark.options/tiffimagewatermarkoptions)` class.

### TiffImageWatermarkOptions(int frameIndex) {#TiffImageWatermarkOptions-int-}
```
public TiffImageWatermarkOptions(int frameIndex)
```


Initializes a new instance of the `[TiffImageWatermarkOptions](../../com.groupdocs.watermark.options/tiffimagewatermarkoptions)` class with a specified index of the frame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| frameIndex | int | The index of frame to add watermark. |

