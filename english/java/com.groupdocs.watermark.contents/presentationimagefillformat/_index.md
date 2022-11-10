---
title: PresentationImageFillFormat
second_title: GroupDocs.Watermark for Java API Reference
description: Represents the image fill format settings in a PowerPoint document.
type: docs
weight: 85
url: /java/com.groupdocs.watermark.contents/presentationimagefillformat/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.contents.OfficeImageFillFormat
```
public class PresentationImageFillFormat extends OfficeImageFillFormat<PresentationWatermarkableImage>
```

Represents the image fill format settings in a PowerPoint document.
## Methods

| Method | Description |
| --- | --- |
| [getTileAsTexture()](#getTileAsTexture--) | Gets a value indicating whether the image is tiled across the background. |
| [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | Sets a value indicating whether the image is tiled across the background. |
| [getTransparency()](#getTransparency--) | Gets the transparency of the background image as a value from 0.0 (opaque) through 1.0 (fully transparent). |
| [setTransparency(double value)](#setTransparency-double-) | Sets the transparency of the background image as a value from 0.0 (opaque) through 1.0 (fully transparent). |
| [getBackgroundImage()](#getBackgroundImage--) | Gets the background image. |
| [setBackgroundImage(PresentationWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-) | Sets the background image. |
### getTileAsTexture() {#getTileAsTexture--}
```
public boolean getTileAsTexture()
```


Gets a value indicating whether the image is tiled across the background.

**Returns:**
boolean - True if the image is tiled across the background; otherwise, false (the image is stretched). The default value is false.
### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public void setTileAsTexture(boolean value)
```


Sets a value indicating whether the image is tiled across the background.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | True if the image is tiled across the background; otherwise, false (the image is stretched). The default value is false. |

### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


Gets the transparency of the background image as a value from 0.0 (opaque) through 1.0 (fully transparent).

**Returns:**
double - The transparency of the background image as a value from 0.0 (opaque) through 1.0 (fully transparent).
### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


Sets the transparency of the background image as a value from 0.0 (opaque) through 1.0 (fully transparent).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The transparency of the background image as a value from 0.0 (opaque) through 1.0 (fully transparent). |

### getBackgroundImage() {#getBackgroundImage--}
```
public PresentationWatermarkableImage getBackgroundImage()
```


Gets the background image.

**Returns:**
[PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) - The background image. Returns null if the image is not set.
### setBackgroundImage(PresentationWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-}
```
public void setBackgroundImage(PresentationWatermarkableImage value)
```


Sets the background image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) | The background image. Returns null if the image is not set. |

