---
title: ColorRange
second_title: GroupDocs.Watermark for Java API Reference
description: Represents a range of colors.
type: docs
weight: 12
url: /java/com.groupdocs.watermark.search/colorrange/
---
**Inheritance:**
java.lang.Object
```
public class ColorRange
```

Represents a range of colors. Specifies ranges using HSB representation of RGB color.
## Constructors

| Constructor | Description |
| --- | --- |
| [ColorRange()](#ColorRange--) | Initializes a new instance of the `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` class. |
| [ColorRange(Color exactColor)](#ColorRange-com.groupdocs.watermark.watermarks.Color-) | Initializes a new instance of the `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` class with a specified exact color. |
## Methods

| Method | Description |
| --- | --- |
| [getMinHue()](#getMinHue--) | Gets the starting hue value, in degrees. |
| [setMinHue(float value)](#setMinHue-float-) | Sets the starting hue value, in degrees. |
| [getMaxHue()](#getMaxHue--) | Gets the ending hue value, in degrees. |
| [setMaxHue(float value)](#setMaxHue-float-) | Sets the ending hue value, in degrees. |
| [getMinSaturation()](#getMinSaturation--) | Gets the starting saturation value. |
| [setMinSaturation(float value)](#setMinSaturation-float-) | Sets the starting saturation value. |
| [getMaxSaturation()](#getMaxSaturation--) | Gets the ending saturation value. |
| [setMaxSaturation(float value)](#setMaxSaturation-float-) | Sets the ending saturation value. |
| [getMinBrightness()](#getMinBrightness--) | Gets the starting brightness value. |
| [setMinBrightness(float value)](#setMinBrightness-float-) | Sets the starting brightness value. |
| [getMaxBrightness()](#getMaxBrightness--) | Gets the ending brightness value. |
| [setMaxBrightness(float value)](#setMaxBrightness-float-) | Sets the ending brightness value. |
| [isEmpty()](#isEmpty--) | Gets a value indicating whether only the empty color is in range. |
| [setEmpty(boolean value)](#setEmpty-boolean-) | Sets a value indicating whether only the empty color is in range. |
### ColorRange() {#ColorRange--}
```
public ColorRange()
```


Initializes a new instance of the `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` class.

### ColorRange(Color exactColor) {#ColorRange-com.groupdocs.watermark.watermarks.Color-}
```
public ColorRange(Color exactColor)
```


Initializes a new instance of the `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` class with a specified exact color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| exactColor | [Color](../../com.groupdocs.watermark.watermarks/color) | The exact color from which the range is created. |

### getMinHue() {#getMinHue--}
```
public final float getMinHue()
```


Gets the starting hue value, in degrees.

**Returns:**
float - The starting hue value, in degrees.
### setMinHue(float value) {#setMinHue-float-}
```
public final void setMinHue(float value)
```


Sets the starting hue value, in degrees.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The starting hue value, in degrees. |

### getMaxHue() {#getMaxHue--}
```
public final float getMaxHue()
```


Gets the ending hue value, in degrees.

**Returns:**
float - The ending hue value, in degrees.
### setMaxHue(float value) {#setMaxHue-float-}
```
public final void setMaxHue(float value)
```


Sets the ending hue value, in degrees.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The ending hue value, in degrees. |

### getMinSaturation() {#getMinSaturation--}
```
public final float getMinSaturation()
```


Gets the starting saturation value.

**Returns:**
float - The saturation ranges from 0.0 through 1.0, where 0.0 is grayscale and 1.0 is the most saturated.
### setMinSaturation(float value) {#setMinSaturation-float-}
```
public final void setMinSaturation(float value)
```


Sets the starting saturation value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The saturation ranges from 0.0 through 1.0, where 0.0 is grayscale and 1.0 is the most saturated. |

### getMaxSaturation() {#getMaxSaturation--}
```
public final float getMaxSaturation()
```


Gets the ending saturation value.

**Returns:**
float - The saturation ranges from 0.0 through 1.0, where 0.0 is grayscale and 1.0 is the most saturated.
### setMaxSaturation(float value) {#setMaxSaturation-float-}
```
public final void setMaxSaturation(float value)
```


Sets the ending saturation value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The saturation ranges from 0.0 through 1.0, where 0.0 is grayscale and 1.0 is the most saturated. |

### getMinBrightness() {#getMinBrightness--}
```
public final float getMinBrightness()
```


Gets the starting brightness value.

**Returns:**
float - The brightness ranges from 0.0 through 1.0, where 0.0 represents black and 1.0 represents white.
### setMinBrightness(float value) {#setMinBrightness-float-}
```
public final void setMinBrightness(float value)
```


Sets the starting brightness value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The brightness ranges from 0.0 through 1.0, where 0.0 represents black and 1.0 represents white. |

### getMaxBrightness() {#getMaxBrightness--}
```
public final float getMaxBrightness()
```


Gets the ending brightness value.

**Returns:**
float - The brightness ranges from 0.0 through 1.0, where 0.0 represents black and 1.0 represents white.
### setMaxBrightness(float value) {#setMaxBrightness-float-}
```
public final void setMaxBrightness(float value)
```


Sets the ending brightness value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The brightness ranges from 0.0 through 1.0, where 0.0 represents black and 1.0 represents white. |

### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Gets a value indicating whether only the empty color is in range.

**Returns:**
boolean - True if only the empty color is in range (HSB ranges are ignored); otherwise, false.
### setEmpty(boolean value) {#setEmpty-boolean-}
```
public final void setEmpty(boolean value)
```


Sets a value indicating whether only the empty color is in range.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | True if only the empty color is in range (HSB ranges are ignored); otherwise, false. |

