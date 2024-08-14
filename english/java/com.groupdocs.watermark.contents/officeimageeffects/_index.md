---
title: OfficeImageEffects
second_title: GroupDocs.Watermark for Java API Reference
description: Represents effects that can be applied to an image watermark for an office content.
type: docs
weight: 45
url: /java/com.groupdocs.watermark.contents/officeimageeffects/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IDocumentSpecificSettings](../../com.groupdocs.watermark.internal/idocumentspecificsettings)
```
public abstract class OfficeImageEffects implements IDocumentSpecificSettings
```

Represents effects that can be applied to an image watermark for an office content.
## Methods

| Method | Description |
| --- | --- |
| [getBorderLineFormat()](#getBorderLineFormat--) | Gets a line format settings for the image border. |
| [setBorderLineFormat(OfficeLineFormat value)](#setBorderLineFormat-com.groupdocs.watermark.contents.OfficeLineFormat-) | Sets a line format settings for the image border. |
| [getGrayScale()](#getGrayScale--) | Gets a value indicating whether a picture will be displayed in grayscale mode. |
| [setGrayScale(boolean value)](#setGrayScale-boolean-) | Sets a value indicating whether a picture will be displayed in grayscale mode. |
| [getChromaKey()](#getChromaKey--) | Gets the color value of the image that will be treated as transparent. |
| [setChromaKey(Color value)](#setChromaKey-com.groupdocs.watermark.watermarks.Color-) | Sets the color value of the image that will be treated as transparent. |
| [getBrightness()](#getBrightness--) | Gets the brightness of the picture. |
| [setBrightness(double value)](#setBrightness-double-) | Sets the brightness of the picture. |
| [getContrast()](#getContrast--) | Gets the contrast for the specified picture. |
| [setContrast(double value)](#setContrast-double-) | Sets the contrast for the specified picture. |
### getBorderLineFormat() {#getBorderLineFormat--}
```
public final OfficeLineFormat getBorderLineFormat()
```


Gets a line format settings for the image border.

**Returns:**
[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat) - Instance of  OfficeLineFormat  class, representing shape line format.
### setBorderLineFormat(OfficeLineFormat value) {#setBorderLineFormat-com.groupdocs.watermark.contents.OfficeLineFormat-}
```
public final void setBorderLineFormat(OfficeLineFormat value)
```


Sets a line format settings for the image border.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat) | Instance of  OfficeLineFormat  class, representing shape line format. |

### getGrayScale() {#getGrayScale--}
```
public final boolean getGrayScale()
```


Gets a value indicating whether a picture will be displayed in grayscale mode.

**Returns:**
boolean - The default value is false.
### setGrayScale(boolean value) {#setGrayScale-boolean-}
```
public final void setGrayScale(boolean value)
```


Sets a value indicating whether a picture will be displayed in grayscale mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | The default value is false. |

### getChromaKey() {#getChromaKey--}
```
public final Color getChromaKey()
```


Gets the color value of the image that will be treated as transparent.

**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The default value is fully transparent color.
### setChromaKey(Color value) {#setChromaKey-com.groupdocs.watermark.watermarks.Color-}
```
public final void setChromaKey(Color value)
```


Sets the color value of the image that will be treated as transparent.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.groupdocs.watermark.watermarks/color) | The default value is fully transparent color. |

### getBrightness() {#getBrightness--}
```
public final double getBrightness()
```


Gets the brightness of the picture. The value for this property must be a number from 0.0 (dimmest) to 1.0 (brightest).

**Returns:**
double - The default value is 0.5.
### setBrightness(double value) {#setBrightness-double-}
```
public final void setBrightness(double value)
```


Sets the brightness of the picture. The value for this property must be a number from 0.0 (dimmest) to 1.0 (brightest).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The default value is 0.5. |

### getContrast() {#getContrast--}
```
public final double getContrast()
```


Gets the contrast for the specified picture. The value for this property must be a number from 0.0 (the least contrast) to 1.0 (the greatest contrast).

**Returns:**
double - The default value is 0.5.
### setContrast(double value) {#setContrast-double-}
```
public final void setContrast(double value)
```


Sets the contrast for the specified picture. The value for this property must be a number from 0.0 (the least contrast) to 1.0 (the greatest contrast).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The default value is 0.5. |

