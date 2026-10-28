---
title: "TextWatermark"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt ein Textwasserzeichen dar."
type: docs
weight: 18
url: /de/java/com.groupdocs.watermark.watermarks/textwatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.Watermark](../../com.groupdocs.watermark/watermark)
```
public class TextWatermark extends Watermark
```

Stellt ein Textwasserzeichen dar.

**Learn more:**

* [Adding text watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+text+watermarks)

Das folgende Beispiel zeigt, wie das Textwasserzeichen abhängig von der Größe des übergeordneten Elements skaliert wird.
>
> ````
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
> ````


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [TextWatermark(String text, Font font)](#TextWatermark-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | Initialisiert eine neue Instanz der `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` Klasse mit einem angegebenen Text und einer Schriftart. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getText()](#getText--) | Ruft den Text ab, der als Wasserzeichen verwendet wird. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Legt den Text fest, der als Wasserzeichen verwendet wird. |
|
|  | [getFont()](#getFont--) | Ruft die Schriftart des Textes ab. |
|
|  | [setFont(Font value)](#setFont-com.groupdocs.watermark.watermarks.Font-) | Legt die Schriftart des Textes fest. |
|
|  | [getForegroundColor()](#getForegroundColor--) | Ruft die Vordergrundfarbe des Textes ab. |
|
|  | [setForegroundColor(Color value)](#setForegroundColor-com.groupdocs.watermark.watermarks.Color-) | Legt die Vordergrundfarbe des Textes fest. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Ruft die Hintergrundfarbe des Textes ab. |
|
|  | [setBackgroundColor(Color value)](#setBackgroundColor-com.groupdocs.watermark.watermarks.Color-) | Legt die Hintergrundfarbe des Textes fest. |
|
|  | [getTextAlignment()](#getTextAlignment--) | Ruft das Wasserzeichen `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)` ab. |
|
|  | [setTextAlignment(int value)](#setTextAlignment-int-) | Legt das Wasserzeichen `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)` fest. |
|
| [isImageWatermark()](#isImageWatermark--) |  |
| [isTextWatermark()](#isTextWatermark--) |  |
| [getForegroundColorConsideringOpacity()](#getForegroundColorConsideringOpacity--) |  |
| [getBackgroundColorConsideringOpacity()](#getBackgroundColorConsideringOpacity--) |  |
| [getSize()](#getSize--) |  |
|  | [getPadding()](#getPadding--) | Ruft die Padding‑Einstellungen dieses `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` ab. |
|
|  | [setPadding(Thickness value)](#setPadding-com.groupdocs.watermark.Thickness-) | Legt die Padding‑Einstellungen dieses `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` fest. |
|
| [deepClone()](#deepClone--) |  |
| [hasSameValues(Watermark watermark)](#hasSameValues-com.groupdocs.watermark.Watermark-) |  |
| [createGeometry(ContentPartGeometry parent)](#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-) |  |
### TextWatermark(String text, Font font) {#TextWatermark-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public TextWatermark(String text, Font font)
```


Initialisiert eine neue Instanz der `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` Klasse mit einem angegebenen Text und einer Schriftart.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Text | java.lang.String | Der Text, der als Wasserzeichen verwendet wird. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Die Schriftart des Textes. |
|

### getText() {#getText--}
```
public final String getText()
```


Ruft den Text ab, der als Wasserzeichen verwendet wird.


**Returns:**
java.lang.String – Die Zeichenkette, die den Wasserzeichen‑Text darstellt.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Legt den Text fest, der als Wasserzeichen verwendet wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Die Zeichenkette, die den Wasserzeichen‑Text darstellt. |
|

### getFont() {#getFont--}
```
public final Font getFont()
```


Ruft die Schriftart des Textes ab.


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### setFont(Font value) {#setFont-com.groupdocs.watermark.watermarks.Font-}
```
public final void setFont(Font value)
```


Legt die Schriftart des Textes fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [Font](../../com.groupdocs.watermark.watermarks/font) | Die Schriftart des Textes. |
|

### getForegroundColor() {#getForegroundColor--}
```
public final Color getForegroundColor()
```


Ruft die Vordergrundfarbe des Textes ab.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### setForegroundColor(Color value) {#setForegroundColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setForegroundColor(Color value)
```


Legt die Vordergrundfarbe des Textes fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | Die Vordergrundfarbe des Textes. |
|

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Ruft die Hintergrundfarbe des Textes ab.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

### setBackgroundColor(Color value) {#setBackgroundColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setBackgroundColor(Color value)
```


Legt die Hintergrundfarbe des Textes fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | Die Hintergrundfarbe des Textes. |
|

### getTextAlignment() {#getTextAlignment--}
```
public final int getTextAlignment()
```


Ruft das Wasserzeichen `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)` ab.

Standardwert ist `[TextAlignment.Left](../../com.groupdocs.watermark.watermarks/textalignment#Left)`.


**Returns:**
int – Das Wasserzeichen `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`.

### setTextAlignment(int value) {#setTextAlignment-int-}
```
public final void setTextAlignment(int value)
```


Legt das Wasserzeichen `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)` fest.

Standardwert ist `[TextAlignment.Left](../../com.groupdocs.watermark.watermarks/textalignment#Left)`.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | int | Das Wasserzeichen `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`. |
|

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


Ruft die Padding‑Einstellungen dieses `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` ab. Diese Eigenschaft gilt nur für Bilddateien.


**Returns:**
[Thickness](../../com.groupdocs.watermark/thickness) - The padding settings of this `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`.

### setPadding(Thickness value) {#setPadding-com.groupdocs.watermark.Thickness-}
```
public final void setPadding(Thickness value)
```


Legt die Padding‑Einstellungen dieses `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` fest. Diese Eigenschaft gilt nur für Bilddateien.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [Thickness](../../com.groupdocs.watermark/thickness) | Die Padding‑Einstellungen dieses `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`. |
|

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

**Returns:**
boolean
### createGeometry(ContentPartGeometry parent) {#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-}
```
public WatermarkGeometry createGeometry(ContentPartGeometry parent)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parent | [ContentPartGeometry](../../com.groupdocs.watermark.internal/contentpartgeometry) |  |

**Returns:**
[WatermarkGeometry](../../com.groupdocs.watermark.internal/watermarkgeometry)
