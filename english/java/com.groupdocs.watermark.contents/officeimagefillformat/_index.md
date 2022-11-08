---
title: OfficeImageFillFormat
second_title: GroupDocs.Watermark for Java API Reference
description: Represents the image fill format settings in any supported office content.
type: docs
weight: 46
url: /java/com.groupdocs.watermark.contents/officeimagefillformat/
---
**Inheritance:**
java.lang.Object
```
public abstract class OfficeImageFillFormat<TWatermarkableImage>
```

Represents the image fill format settings in any supported office content.

 TWatermarkableImage : The exact type of the watermarkable image that is used as background.
## Constructors

| Constructor | Description |
| --- | --- |
| [OfficeImageFillFormat()](#OfficeImageFillFormat--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getTileAsTexture()](#getTileAsTexture--) | Gets a value indicating whether the image is tiled across the background. |
| [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | Sets a value indicating whether the image is tiled across the background. |
| [getTransparency()](#getTransparency--) | Gets the transparency of the background image as a value from 0.0 (opaque) through 1.0 (fully transparent). |
| [setTransparency(double value)](#setTransparency-double-) | Sets the transparency of the background image as a value from 0.0 (opaque) through 1.0 (fully transparent). |
| [getBackgroundImage()](#getBackgroundImage--) | Gets the background image. |
| [setBackgroundImage(TWatermarkableImage value)](#setBackgroundImage-TWatermarkableImage-) | Sets the background image. |
| [checkIfBackgroundImageIsSet()](#checkIfBackgroundImageIsSet--) |  |
### OfficeImageFillFormat() {#OfficeImageFillFormat--}
```
public OfficeImageFillFormat()
```




### getTileAsTexture() {#getTileAsTexture--}
```
public abstract boolean getTileAsTexture()
```


Gets a value indicating whether the image is tiled across the background.

**Returns:**
boolean - True if the image is tiled across the background; otherwise, false (the image is stretched).
### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public abstract void setTileAsTexture(boolean value)
```


Sets a value indicating whether the image is tiled across the background.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | True if the image is tiled across the background; otherwise, false (the image is stretched). |

### getTransparency() {#getTransparency--}
```
public abstract double getTransparency()
```


Gets the transparency of the background image as a value from 0.0 (opaque) through 1.0 (fully transparent).

**Returns:**
double - The transparency of the background image as a value from 0.0 (opaque) through 1.0 (fully transparent).
### setTransparency(double value) {#setTransparency-double-}
```
public abstract void setTransparency(double value)
```


Sets the transparency of the background image as a value from 0.0 (opaque) through 1.0 (fully transparent).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The transparency of the background image as a value from 0.0 (opaque) through 1.0 (fully transparent). |

### getBackgroundImage() {#getBackgroundImage--}
```
public abstract TWatermarkableImage getBackgroundImage()
```


Gets the background image.

**Returns:**
TWatermarkableImage - The background image. Returns null if the image is not set.
### setBackgroundImage(TWatermarkableImage value) {#setBackgroundImage-TWatermarkableImage-}
```
public abstract void setBackgroundImage(TWatermarkableImage value)
```


Sets the background image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | TWatermarkableImage | The background image. Returns null if the image is not set. |

### checkIfBackgroundImageIsSet() {#checkIfBackgroundImageIsSet--}
```
public final void checkIfBackgroundImageIsSet()
```




