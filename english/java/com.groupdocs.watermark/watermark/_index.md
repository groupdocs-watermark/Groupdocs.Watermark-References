---
title: Watermark
second_title: GroupDocs.Watermark for Java API Reference
description: Represents a watermark to be added to a document.
type: docs
weight: 11
url: /java/com.groupdocs.watermark/watermark/
---
**Inheritance:**
java.lang.Object
```
public abstract class Watermark
```

Represents a watermark to be added to a document.

**Learn more**

 *  More details about watermark properties: [Adding text watermarks][].
 *  More advanced watermarking topics: [Adding watermarks][]


[Adding text watermarks]: https://docs.groupdocs.com/display/watermarkjava/Adding+text+watermarks
[Adding watermarks]: https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks
## Constructors

| Constructor | Description |
| --- | --- |
| [Watermark()](#Watermark--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getOpacity()](#getOpacity--) | Gets or sets the opacity of this `[Watermark](../../com.groupdocs.watermark/watermark)`. |
| [setOpacity(double value)](#setOpacity-double-) | Gets or sets the opacity of this `[Watermark](../../com.groupdocs.watermark/watermark)`. |
| [getY()](#getY--) | Gets the y-coordinate of this `[Watermark](../../com.groupdocs.watermark/watermark)`. |
| [setY(double value)](#setY-double-) | Sets the y-coordinate of this `[Watermark](../../com.groupdocs.watermark/watermark)`. |
| [getX()](#getX--) | Gets the x-coordinate of this `[Watermark](../../com.groupdocs.watermark/watermark)`. |
| [setX(double value)](#setX-double-) | Sets the x-coordinate of this `[Watermark](../../com.groupdocs.watermark/watermark)`. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Gets the vertical alignment of this `[Watermark](../../com.groupdocs.watermark/watermark)`. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Sets the vertical alignment of this `[Watermark](../../com.groupdocs.watermark/watermark)`. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Gets the horizontal alignment of this `[Watermark](../../com.groupdocs.watermark/watermark)`. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Sets the horizontal alignment of this `[Watermark](../../com.groupdocs.watermark/watermark)`. |
| [getRotateAngle()](#getRotateAngle--) | Gets the rotate angle of this `[Watermark](../../com.groupdocs.watermark/watermark)` in degrees. |
| [setRotateAngle(double value)](#setRotateAngle-double-) | Sets the rotate angle of this `[Watermark](../../com.groupdocs.watermark/watermark)` in degrees. |
| [isBackground()](#isBackground--) | Gets a value indicating whether the watermark should be placed at background. |
| [setBackground(boolean value)](#setBackground-boolean-) | Sets a value indicating whether the watermark should be placed at background. |
| [getMargins()](#getMargins--) | Gets the margin settings of this `[Watermark](../../com.groupdocs.watermark/watermark)`. |
| [setMargins(Margins value)](#setMargins-com.groupdocs.watermark.watermarks.Margins-) | Sets the margin settings of this `[Watermark](../../com.groupdocs.watermark/watermark)`. |
| [getHeight()](#getHeight--) | Gets the desired height of this `[Watermark](../../com.groupdocs.watermark/watermark)`. |
| [setHeight(double value)](#setHeight-double-) | Sets the desired height of this `[Watermark](../../com.groupdocs.watermark/watermark)`. |
| [getWidth()](#getWidth--) | Gets the desired width of this `[Watermark](../../com.groupdocs.watermark/watermark)`. |
| [setWidth(double value)](#setWidth-double-) | Sets the desired width of this `[Watermark](../../com.groupdocs.watermark/watermark)`. |
| [getScaleFactor()](#getScaleFactor--) | Gets a value that defines how watermark size depends on parent size. |
| [setScaleFactor(double value)](#setScaleFactor-double-) | Sets a value that defines how watermark size depends on parent size. |
| [getSizingType()](#getSizingType--) | Gets a value specifying a way watermark should be sized. |
| [setSizingType(int value)](#setSizingType-int-) | Sets a value specifying a way watermark should be sized. |
| [getConsiderParentMargins()](#getConsiderParentMargins--) | Gets a value indicating whether the watermark size and coordinates are calculated considering parent margins. |
| [setConsiderParentMargins(boolean value)](#setConsiderParentMargins-boolean-) | Sets a value indicating whether the watermark size and coordinates are calculated considering parent margins. |
| [isImageWatermark()](#isImageWatermark--) |  |
| [isTextWatermark()](#isTextWatermark--) |  |
| [getTransparency()](#getTransparency--) |  |
| [getSize()](#getSize--) |  |
| [copyPropertiesValues(Watermark source, Watermark destination)](#copyPropertiesValues-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.Watermark-) |  |
| [deepClone()](#deepClone--) |  |
| [hasSameValues(Watermark watermark)](#hasSameValues-com.groupdocs.watermark.Watermark-) |  |
| [createGeometry(ContentPartGeometry parent)](#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-) |  |
### Watermark() {#Watermark--}
```
public Watermark()
```




### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Gets or sets the opacity of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

The value of opacity should be between 0 and 1. The default value is 1.

**Returns:**
double - The opacity of this `[Watermark](../../com.groupdocs.watermark/watermark)`.
### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


Gets or sets the opacity of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

The value of opacity should be between 0 and 1. The default value is 1.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The opacity of this `[Watermark](../../com.groupdocs.watermark/watermark)`. |

### getY() {#getY--}
```
public final double getY()
```


Gets the y-coordinate of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

**Returns:**
double - The y-coordinate of this `[Watermark](../../com.groupdocs.watermark/watermark)`.
### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Sets the y-coordinate of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The y-coordinate of this `[Watermark](../../com.groupdocs.watermark/watermark)`. |

### getX() {#getX--}
```
public final double getX()
```


Gets the x-coordinate of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

**Returns:**
double - The x-coordinate of this `[Watermark](../../com.groupdocs.watermark/watermark)`.
### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Sets the x-coordinate of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The x-coordinate of this `[Watermark](../../com.groupdocs.watermark/watermark)`. |

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Gets the vertical alignment of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

Default value is `[VerticalAlignment.None](../../com.groupdocs.watermark.common/verticalalignment#None)`.

**Returns:**
int - The `[VerticalAlignment](../../com.groupdocs.watermark.common/verticalalignment)` of this `[Watermark](../../com.groupdocs.watermark/watermark)`.
### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


Sets the vertical alignment of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

Default value is `[VerticalAlignment.None](../../com.groupdocs.watermark.common/verticalalignment#None)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The `[VerticalAlignment](../../com.groupdocs.watermark.common/verticalalignment)` of this `[Watermark](../../com.groupdocs.watermark/watermark)`. |

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


Gets the horizontal alignment of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

Default value is `[HorizontalAlignment.None](../../com.groupdocs.watermark.common/horizontalalignment#None)`.

**Returns:**
int - The `[HorizontalAlignment](../../com.groupdocs.watermark.common/horizontalalignment)` of this `[Watermark](../../com.groupdocs.watermark/watermark)`.
### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public final void setHorizontalAlignment(int value)
```


Sets the horizontal alignment of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

Default value is `[HorizontalAlignment.None](../../com.groupdocs.watermark.common/horizontalalignment#None)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The `[HorizontalAlignment](../../com.groupdocs.watermark.common/horizontalalignment)` of this `[Watermark](../../com.groupdocs.watermark/watermark)`. |

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Gets the rotate angle of this `[Watermark](../../com.groupdocs.watermark/watermark)` in degrees.

**Returns:**
double - The rotate angle of this `[Watermark](../../com.groupdocs.watermark/watermark)` in degrees.
### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Sets the rotate angle of this `[Watermark](../../com.groupdocs.watermark/watermark)` in degrees.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The rotate angle of this `[Watermark](../../com.groupdocs.watermark/watermark)` in degrees. |

### isBackground() {#isBackground--}
```
public final boolean isBackground()
```


Gets a value indicating whether the watermark should be placed at background.

**Returns:**
boolean - If the value is true, the watermark will be placed at the bottom. By default, the value is false, the watermark will be placed at the top.
### setBackground(boolean value) {#setBackground-boolean-}
```
public final void setBackground(boolean value)
```


Sets a value indicating whether the watermark should be placed at background.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | If the value is true, the watermark will be placed at the bottom. By default, the value is false, the watermark will be placed at the top. |

### getMargins() {#getMargins--}
```
public final Margins getMargins()
```


Gets the margin settings of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

**Returns:**
[Margins](../../com.groupdocs.watermark.watermarks/margins) - The margin settings of this `[Watermark](../../com.groupdocs.watermark/watermark)`.
### setMargins(Margins value) {#setMargins-com.groupdocs.watermark.watermarks.Margins-}
```
public final void setMargins(Margins value)
```


Sets the margin settings of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Margins](../../com.groupdocs.watermark.watermarks/margins) | The margin settings of this `[Watermark](../../com.groupdocs.watermark/watermark)`. |

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Gets the desired height of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

**Returns:**
double - The desired height of this `[Watermark](../../com.groupdocs.watermark/watermark)`.
### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Sets the desired height of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

Setting this property will also change the value of `#getSizingType().getSizingType()` property to `[SizingType.Absolute](../../com.groupdocs.watermark.watermarks/sizingtype#Absolute)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The desired height of this `[Watermark](../../com.groupdocs.watermark/watermark)`. |

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Gets the desired width of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

**Returns:**
double - The desired width of this `[Watermark](../../com.groupdocs.watermark/watermark)`.
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Sets the desired width of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

Setting this property will also change the value of `#getSizingType().getSizingType()` property to `[SizingType.Absolute](../../com.groupdocs.watermark.watermarks/sizingtype#Absolute)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The desired width of this `[Watermark](../../com.groupdocs.watermark/watermark)`. |

### getScaleFactor() {#getScaleFactor--}
```
public final double getScaleFactor()
```


Gets a value that defines how watermark size depends on parent size.

The value must be between 0 and 1.

**Returns:**
double - The scale factor of this `[Watermark](../../com.groupdocs.watermark/watermark)`.
### setScaleFactor(double value) {#setScaleFactor-double-}
```
public final void setScaleFactor(double value)
```


Sets a value that defines how watermark size depends on parent size.

The value must be between 0 and 1.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The scale factor of this `[Watermark](../../com.groupdocs.watermark/watermark)`. |

### getSizingType() {#getSizingType--}
```
public final int getSizingType()
```


Gets a value specifying a way watermark should be sized.

**Returns:**
int - The sizing type.
### setSizingType(int value) {#setSizingType-int-}
```
public final void setSizingType(int value)
```


Sets a value specifying a way watermark should be sized.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The sizing type. |

### getConsiderParentMargins() {#getConsiderParentMargins--}
```
public final boolean getConsiderParentMargins()
```


Gets a value indicating whether the watermark size and coordinates are calculated considering parent margins.

**Returns:**
boolean - If the value is true, watermark size and coordinates are calculated considering parent margins. By default, the value is false, parent margins are ignored.
### setConsiderParentMargins(boolean value) {#setConsiderParentMargins-boolean-}
```
public final void setConsiderParentMargins(boolean value)
```


Sets a value indicating whether the watermark size and coordinates are calculated considering parent margins.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | If the value is true, watermark size and coordinates are calculated considering parent margins. By default, the value is false, parent margins are ignored. |

### isImageWatermark() {#isImageWatermark--}
```
public abstract boolean isImageWatermark()
```




**Returns:**
boolean
### isTextWatermark() {#isTextWatermark--}
```
public abstract boolean isTextWatermark()
```




**Returns:**
boolean
### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```




**Returns:**
double
### getSize() {#getSize--}
```
public abstract SizeD getSize()
```




**Returns:**
com.groupdocs.watermark.internal.SizeD
### copyPropertiesValues(Watermark source, Watermark destination) {#copyPropertiesValues-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.Watermark-}
```
public static void copyPropertiesValues(Watermark source, Watermark destination)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| destination | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### deepClone() {#deepClone--}
```
public abstract Watermark deepClone()
```




**Returns:**
[Watermark](../../com.groupdocs.watermark/watermark)
### hasSameValues(Watermark watermark) {#hasSameValues-com.groupdocs.watermark.Watermark-}
```
public boolean hasSameValues(Watermark watermark)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

**Returns:**
boolean
### createGeometry(ContentPartGeometry parent) {#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-}
```
public abstract WatermarkGeometry createGeometry(ContentPartGeometry parent)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parent | com.groupdocs.watermark.internal.ContentPartGeometry |  |

**Returns:**
com.groupdocs.watermark.internal.WatermarkGeometry
