---
title: OfficeLineFormat
second_title: GroupDocs.Watermark for Java API Reference
description: Represents a shape line format.
type: docs
weight: 47
url: /java/com.groupdocs.watermark.contents/officelineformat/
---
**Inheritance:**
java.lang.Object
```
public final class OfficeLineFormat
```

Represents a shape line format.
## Constructors

| Constructor | Description |
| --- | --- |
| [OfficeLineFormat()](#OfficeLineFormat--) | Initializes a new instance of the `[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat)` class. |
## Methods

| Method | Description |
| --- | --- |
| [getWeight()](#getWeight--) | Gets the brush thickness that strokes the path of a shape. |
| [setWeight(double value)](#setWeight-double-) | Sets the brush thickness that strokes the path of a shape. |
| [getColor()](#getColor--) | Gets the color of the line. |
| [setColor(Color value)](#setColor-com.groupdocs.watermark.watermarks.Color-) | Sets the color of the line. |
| [getOpacity()](#getOpacity--) | Gets the line opacity. |
| [setOpacity(double value)](#setOpacity-double-) | Sets the line opacity. |
| [getEnabled()](#getEnabled--) | Gets a value indicating whether a shape will be stroked. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Sets a value indicating whether a shape will be stroked. |
| [getDashStyle()](#getDashStyle--) | Gets the dot and dash pattern for a line. |
| [setDashStyle(int value)](#setDashStyle-int-) | Sets the dot and dash pattern for a line. |
| [getLineStyle()](#getLineStyle--) | Gets the line style. |
| [setLineStyle(int value)](#setLineStyle-int-) | Sets the line style. |
| [getTransparency()](#getTransparency--) |  |
| [getColorConsideringOpacity()](#getColorConsideringOpacity--) |  |
### OfficeLineFormat() {#OfficeLineFormat--}
```
public OfficeLineFormat()
```


Initializes a new instance of the `[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat)` class.

### getWeight() {#getWeight--}
```
public final double getWeight()
```


Gets the brush thickness that strokes the path of a shape.

**Returns:**
double - The line thickness in points. The default value is 0.75.
### setWeight(double value) {#setWeight-double-}
```
public final void setWeight(double value)
```


Sets the brush thickness that strokes the path of a shape.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The line thickness in points. The default value is 0.75. |

### getColor() {#getColor--}
```
public final Color getColor()
```


Gets the color of the line.

The default value is `[Color.getBlack()](../../com.groupdocs.watermark.watermarks/color#getBlack--)`.

**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The color of the line.
### setColor(Color value) {#setColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setColor(Color value)
```


Sets the color of the line.

The default value is `[Color.getBlack()](../../com.groupdocs.watermark.watermarks/color#getBlack--)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.groupdocs.watermark.watermarks/color) | The color of the line. |

### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Gets the line opacity.

**Returns:**
double - The value should be between 0 and 1. Default value is 1.
### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


Sets the line opacity.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The value should be between 0 and 1. Default value is 1. |

### getEnabled() {#getEnabled--}
```
public final boolean getEnabled()
```


Gets a value indicating whether a shape will be stroked.

**Returns:**
boolean - The default value is false.
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Sets a value indicating whether a shape will be stroked.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | The default value is false. |

### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


Gets the dot and dash pattern for a line.

**Returns:**
int
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


Sets the dot and dash pattern for a line.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLineStyle() {#getLineStyle--}
```
public final int getLineStyle()
```


Gets the line style.

The default value is `[OfficeLineStyle.Single](../../com.groupdocs.watermark.contents/officelinestyle#Single)`.

**Returns:**
int - The line style.
### setLineStyle(int value) {#setLineStyle-int-}
```
public final void setLineStyle(int value)
```


Sets the line style.

The default value is `[OfficeLineStyle.Single](../../com.groupdocs.watermark.contents/officelinestyle#Single)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The line style. |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```




**Returns:**
double
### getColorConsideringOpacity() {#getColorConsideringOpacity--}
```
public final Color getColorConsideringOpacity()
```




**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color)
