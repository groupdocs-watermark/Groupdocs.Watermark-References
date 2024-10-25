---
title: TextWatermark
second_title: GroupDocs.Watermark for Java API Reference
description: Represents a text watermark.
type: docs
weight: 18
url: /java/com.groupdocs.watermark.watermarks/textwatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.Watermark](../../com.groupdocs.watermark/watermark)
```
public class TextWatermark extends Watermark
```

Represents a text watermark.

**Learn more:**

 *  [Adding text watermarks][]

The following example demonstrates how to scale the text watermark depending on the parent size.

> ```
> ```
> 
>    Watermarker watermarker = new Watermarker("C:\\test.some_ext");
>    TextWatermark watermark = new TextWatermark("test watermark", new Font("Arial", 36));
> 
>    watermark.setHorizontalAlignment(HorizontalAlignment.Center);
>    watermark.setVerticalAlignment(VerticalAlignment.Center);
>    watermark.setSizingType(SizingType.ScaleToParentDimensions);
>    watermark.setRotateAngle(45);
>    watermark.setScaleFactor(0.4);
> 
>    watermarker.add(watermark);
> 
>    watermarker.save("C:\\modified_test.some_ext");
>    watermarker.close();
>  
> ```
> ```


[Adding text watermarks]: https://docs.groupdocs.com/display/watermarkjava/Adding+text+watermarks
## Constructors

| Constructor | Description |
| --- | --- |
| [TextWatermark(String text, Font font)](#TextWatermark-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | Initializes a new instance of the `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` class with a specified text and a font. |
## Methods

| Method | Description |
| --- | --- |
| [getText()](#getText--) | Gets the text to be used as watermark. |
| [setText(String value)](#setText-java.lang.String-) | Sets the text to be used as watermark. |
| [getFont()](#getFont--) | Gets the font of the text. |
| [setFont(Font value)](#setFont-com.groupdocs.watermark.watermarks.Font-) | Sets the font of the text. |
| [getForegroundColor()](#getForegroundColor--) | Gets the foreground color of the text. |
| [setForegroundColor(Color value)](#setForegroundColor-com.groupdocs.watermark.watermarks.Color-) | Sets the foreground color of the text. |
| [getBackgroundColor()](#getBackgroundColor--) | Gets the background color of the text. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.groupdocs.watermark.watermarks.Color-) | Sets the background color of the text. |
| [getTextAlignment()](#getTextAlignment--) | Gets the watermark `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`. |
| [setTextAlignment(int value)](#setTextAlignment-int-) | Sets the watermark `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`. |
| [isImageWatermark()](#isImageWatermark--) |  |
| [isTextWatermark()](#isTextWatermark--) |  |
| [getForegroundColorConsideringOpacity()](#getForegroundColorConsideringOpacity--) |  |
| [getBackgroundColorConsideringOpacity()](#getBackgroundColorConsideringOpacity--) |  |
| [getSize()](#getSize--) |  |
| [getPadding()](#getPadding--) | Gets the padding settings of this `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`. |
| [setPadding(Thickness value)](#setPadding-com.groupdocs.watermark.Thickness-) | Sets the padding settings of this `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`. |
| [deepClone()](#deepClone--) |  |
| [hasSameValues(Watermark watermark)](#hasSameValues-com.groupdocs.watermark.Watermark-) |  |
| [createGeometry(ContentPartGeometry parent)](#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-) |  |
### TextWatermark(String text, Font font) {#TextWatermark-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public TextWatermark(String text, Font font)
```


Initializes a new instance of the `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` class with a specified text and a font.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | The text to be used as watermark. |
| font | [Font](../../com.groupdocs.watermark.watermarks/font) | The font of the text. |

### getText() {#getText--}
```
public final String getText()
```


Gets the text to be used as watermark.

**Returns:**
java.lang.String - The string representing watermark text.
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Sets the text to be used as watermark.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The string representing watermark text. |

### getFont() {#getFont--}
```
public final Font getFont()
```


Gets the font of the text.

**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.
### setFont(Font value) {#setFont-com.groupdocs.watermark.watermarks.Font-}
```
public final void setFont(Font value)
```


Sets the font of the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Font](../../com.groupdocs.watermark.watermarks/font) | The font of the text. |

### getForegroundColor() {#getForegroundColor--}
```
public final Color getForegroundColor()
```


Gets the foreground color of the text.

**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.
### setForegroundColor(Color value) {#setForegroundColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setForegroundColor(Color value)
```


Sets the foreground color of the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.groupdocs.watermark.watermarks/color) | The foreground color of the text. |

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Gets the background color of the text.

**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.
### setBackgroundColor(Color value) {#setBackgroundColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setBackgroundColor(Color value)
```


Sets the background color of the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.groupdocs.watermark.watermarks/color) | The background color of the text. |

### getTextAlignment() {#getTextAlignment--}
```
public final int getTextAlignment()
```


Gets the watermark `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`.

Default value is `[TextAlignment.Left](../../com.groupdocs.watermark.watermarks/textalignment#Left)`.

**Returns:**
int - The watermark `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`.
### setTextAlignment(int value) {#setTextAlignment-int-}
```
public final void setTextAlignment(int value)
```


Sets the watermark `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`.

Default value is `[TextAlignment.Left](../../com.groupdocs.watermark.watermarks/textalignment#Left)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The watermark `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`. |

### isImageWatermark() {#isImageWatermark--}
```
public boolean isImageWatermark()
```




**Returns:**
boolean
### isTextWatermark() {#isTextWatermark--}
```
public boolean isTextWatermark()
```




**Returns:**
boolean
### getForegroundColorConsideringOpacity() {#getForegroundColorConsideringOpacity--}
```
public final Color getForegroundColorConsideringOpacity()
```




**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color)
### getBackgroundColorConsideringOpacity() {#getBackgroundColorConsideringOpacity--}
```
public final Color getBackgroundColorConsideringOpacity()
```




**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color)
### getSize() {#getSize--}
```
public SizeD getSize()
```




**Returns:**
[SizeD](../../com.groupdocs.watermark.internal/sized)
### getPadding() {#getPadding--}
```
public final Thickness getPadding()
```


Gets the padding settings of this `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`. This property is applicable only to image files.

**Returns:**
[Thickness](../../com.groupdocs.watermark/thickness) - The padding settings of this `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`.
### setPadding(Thickness value) {#setPadding-com.groupdocs.watermark.Thickness-}
```
public final void setPadding(Thickness value)
```


Sets the padding settings of this `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`. This property is applicable only to image files.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Thickness](../../com.groupdocs.watermark/thickness) | The padding settings of this `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`. |

### deepClone() {#deepClone--}
```
public Watermark deepClone()
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
public WatermarkGeometry createGeometry(ContentPartGeometry parent)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parent | [ContentPartGeometry](../../com.groupdocs.watermark.internal/contentpartgeometry) |  |

**Returns:**
[WatermarkGeometry](../../com.groupdocs.watermark.internal/watermarkgeometry)
