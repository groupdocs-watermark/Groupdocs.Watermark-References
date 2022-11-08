---
title: SpreadsheetImageFillFormat
second_title: GroupDocs.Watermark for Java API Reference
description: Represents the image fill format settings in an Excel document.
type: docs
weight: 114
url: /java/com.groupdocs.watermark.contents/spreadsheetimagefillformat/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.contents.OfficeImageFillFormat
```
public class SpreadsheetImageFillFormat extends OfficeImageFillFormat<SpreadsheetWatermarkableImage>
```

Represents the image fill format settings in an Excel document.
## Methods

| Method | Description |
| --- | --- |
| [getTileAsTexture()](#getTileAsTexture--) | Gets a value indicating whether the image is tiled across the background. |
| [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | Sets a value indicating whether the image is tiled across the background. |
| [getTransparency()](#getTransparency--) | Gets the transparency of the background image as a value from 0.0 (opaque) through 1.0 (fully transparent). |
| [setTransparency(double value)](#setTransparency-double-) | Sets the transparency of the background image as a value from 0.0 (opaque) through 1.0 (fully transparent). |
| [getBackgroundImage()](#getBackgroundImage--) | Gets the background image. |
| [setBackgroundImage(SpreadsheetWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | Sets the background image. |
### getTileAsTexture() {#getTileAsTexture--}
```
public boolean getTileAsTexture()
```


Gets a value indicating whether the image is tiled across the background.

**Returns:**
boolean - True if the image is tiled across the background; otherwise, false (the image is stretched).
### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public void setTileAsTexture(boolean value)
```


Sets a value indicating whether the image is tiled across the background.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | True if the image is tiled across the background; otherwise, false (the image is stretched). |

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
public SpreadsheetWatermarkableImage getBackgroundImage()
```


Gets the background image.

**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The background image. Returns null if the image is not set.
### setBackgroundImage(SpreadsheetWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public void setBackgroundImage(SpreadsheetWatermarkableImage value)
```


Sets the background image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | The background image. Returns null if the image is not set. |

