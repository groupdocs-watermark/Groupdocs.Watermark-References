---
title: Margins
second_title: GroupDocs.Watermark for Java API Reference
description: Represents margin settings for each edge of an object.
type: docs
weight: 15
url: /java/com.groupdocs.watermark.watermarks/margins/
---
**Inheritance:**
java.lang.Object
```
public class Margins
```

Represents margin settings for each edge of an object.
## Constructors

| Constructor | Description |
| --- | --- |
| [Margins()](#Margins--) | Initializes a new instance of the `[Margins](../../com.groupdocs.watermark.watermarks/margins)` class. |
| [Margins(int marginType, double left, double right, double top, double bottom)](#Margins-int-double-double-double-double-) | Initializes a new instance of the `[Margins](../../com.groupdocs.watermark.watermarks/margins)` class with the specified type, location and size. |
## Methods

| Method | Description |
| --- | --- |
| [getMarginType()](#getMarginType--) | Gets `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. |
| [setMarginType(int value)](#setMarginType-int-) | Sets `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. |
| [getLeft()](#getLeft--) | Gets the left margin. |
| [setLeft(double value)](#setLeft-double-) | Sets the left margin. |
| [getRight()](#getRight--) | Gets the right margin. |
| [setRight(double value)](#setRight-double-) | Sets the right margin. |
| [getTop()](#getTop--) | Gets the top margin. |
| [setTop(double value)](#setTop-double-) | Sets the top margin. |
| [getBottom()](#getBottom--) | Gets the bottom margin. |
| [setBottom(double value)](#setBottom-double-) | Sets the bottom margin. |
### Margins() {#Margins--}
```
public Margins()
```


Initializes a new instance of the `[Margins](../../com.groupdocs.watermark.watermarks/margins)` class.

### Margins(int marginType, double left, double right, double top, double bottom) {#Margins-int-double-double-double-double-}
```
public Margins(int marginType, double left, double right, double top, double bottom)
```


Initializes a new instance of the `[Margins](../../com.groupdocs.watermark.watermarks/margins)` class with the specified type, location and size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| marginType | int | The `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. Specifies how margin values should be interpreted. |
| left | double | The left margin value. |
| right | double | The right margin value. |
| top | double | The top margin value. |
| bottom | double | The bottom margin value. |

### getMarginType() {#getMarginType--}
```
public final int getMarginType()
```


Gets `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. Setting a new value to this property automatically returns all margins to their default values (zero).

The default value is `[MarginType.Absolute](../../com.groupdocs.watermark.watermarks/margintype#Absolute)`

**Returns:**
int - The value specifying how margins should be interpreted.
### setMarginType(int value) {#setMarginType-int-}
```
public final void setMarginType(int value)
```


Sets `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. Setting a new value to this property automatically returns all margins to their default values (zero).

The default value is `[MarginType.Absolute](../../com.groupdocs.watermark.watermarks/margintype#Absolute)`

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The value specifying how margins should be interpreted. |

### getLeft() {#getLeft--}
```
public final double getLeft()
```


Gets the left margin.

**Returns:**
double - Horizontal offset from parent left border.
### setLeft(double value) {#setLeft-double-}
```
public final void setLeft(double value)
```


Sets the left margin.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Horizontal offset from parent left border. |

### getRight() {#getRight--}
```
public final double getRight()
```


Gets the right margin.

**Returns:**
double - Horizontal offset from parent right border.
### setRight(double value) {#setRight-double-}
```
public final void setRight(double value)
```


Sets the right margin.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Horizontal offset from parent right border. |

### getTop() {#getTop--}
```
public final double getTop()
```


Gets the top margin.

**Returns:**
double - Horizontal offset from parent top border.
### setTop(double value) {#setTop-double-}
```
public final void setTop(double value)
```


Sets the top margin.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Horizontal offset from parent top border. |

### getBottom() {#getBottom--}
```
public final double getBottom()
```


Gets the bottom margin.

**Returns:**
double - Horizontal offset from parent bottom border.
### setBottom(double value) {#setBottom-double-}
```
public final void setBottom(double value)
```


Sets the bottom margin.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Horizontal offset from parent bottom border. |

