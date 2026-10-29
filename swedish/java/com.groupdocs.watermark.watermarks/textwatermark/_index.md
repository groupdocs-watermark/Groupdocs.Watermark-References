---
title: "TextWatermark"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar ett textvattenmärke."
type: docs
weight: 18
url: /sv/java/com.groupdocs.watermark.watermarks/textwatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.Watermark](../../com.groupdocs.watermark/watermark)
```
public class TextWatermark extends Watermark
```

Representerar ett textvattenmärke.

**Learn more:**

* [Adding text watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+text+watermarks)

Följande exempel visar hur man skalar textvattenstämpeln beroende på förälderns storlek.
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


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [TextWatermark(String text, Font font)](#TextWatermark-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | Initialiserar en ny instans av klassen `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` med en angiven text och ett teckensnitt. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getText()](#getText--) | Hämtar texten som ska användas som vattenstämpel. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Ställer in texten som ska användas som vattenstämpel. |
|
|  | [getFont()](#getFont--) | Hämtar teckensnittet för texten. |
|
|  | [setFont(Font value)](#setFont-com.groupdocs.watermark.watermarks.Font-) | Ställer in teckensnittet för texten. |
|
|  | [getForegroundColor()](#getForegroundColor--) | Hämtar förgrundsfärgen för texten. |
|
|  | [setForegroundColor(Color value)](#setForegroundColor-com.groupdocs.watermark.watermarks.Color-) | Ställer in förgrundsfärgen för texten. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Hämtar bakgrundsfärgen för texten. |
|
|  | [setBackgroundColor(Color value)](#setBackgroundColor-com.groupdocs.watermark.watermarks.Color-) | Ställer in bakgrundsfärgen för texten. |
|
|  | [getTextAlignment()](#getTextAlignment--) | Hämtar vattenstämpeln `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`. |
|
|  | [setTextAlignment(int value)](#setTextAlignment-int-) | Ställer in vattenstämpeln `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`. |
|
| [isImageWatermark()](#isImageWatermark--) |  |
| [isTextWatermark()](#isTextWatermark--) |  |
| [getForegroundColorConsideringOpacity()](#getForegroundColorConsideringOpacity--) |  |
| [getBackgroundColorConsideringOpacity()](#getBackgroundColorConsideringOpacity--) |  |
| [getSize()](#getSize--) |  |
|  | [getPadding()](#getPadding--) | Hämtar paddinginställningarna för denna `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`. |
|
|  | [setPadding(Thickness value)](#setPadding-com.groupdocs.watermark.Thickness-) | Ställer in paddinginställningarna för denna `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`. |
|
| [deepClone()](#deepClone--) |  |
| [hasSameValues(Watermark watermark)](#hasSameValues-com.groupdocs.watermark.Watermark-) |  |
| [createGeometry(ContentPartGeometry parent)](#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-) |  |
### TextWatermark(String text, Font font) {#TextWatermark-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public TextWatermark(String text, Font font)
```


Initialiserar en ny instans av klassen `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` med en angiven text och ett teckensnitt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | text | java.lang.String | Texten som ska användas som vattenstämpel. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Teckensnittet för texten. |
|

### getText() {#getText--}
```
public final String getText()
```


Hämtar texten som ska användas som vattenstämpel.


**Returns:**
java.lang.String - Strängen som representerar vattenstämpeltext.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Ställer in texten som ska användas som vattenstämpel.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.lang.String | Strängen som representerar vattenstämpeltext. |
|

### getFont() {#getFont--}
```
public final Font getFont()
```


Hämtar teckensnittet för texten.


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### setFont(Font value) {#setFont-com.groupdocs.watermark.watermarks.Font-}
```
public final void setFont(Font value)
```


Ställer in teckensnittet för texten.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [Font](../../com.groupdocs.watermark.watermarks/font) | Teckensnittet för texten. |
|

### getForegroundColor() {#getForegroundColor--}
```
public final Color getForegroundColor()
```


Hämtar förgrundsfärgen för texten.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### setForegroundColor(Color value) {#setForegroundColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setForegroundColor(Color value)
```


Ställer in förgrundsfärgen för texten.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | Förgrundsfärgen för texten. |
|

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Hämtar bakgrundsfärgen för texten.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

### setBackgroundColor(Color value) {#setBackgroundColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setBackgroundColor(Color value)
```


Ställer in bakgrundsfärgen för texten.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | Bakgrundsfärgen för texten. |
|

### getTextAlignment() {#getTextAlignment--}
```
public final int getTextAlignment()
```


Hämtar vattenstämpeln `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`.

Standardvärdet är `[TextAlignment.Left](../../com.groupdocs.watermark.watermarks/textalignment#Left)`.


**Returns:**
int - Vattenstämpeln `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`.

### setTextAlignment(int value) {#setTextAlignment-int-}
```
public final void setTextAlignment(int value)
```


Ställer in vattenstämpeln `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`.

Standardvärdet är `[TextAlignment.Left](../../com.groupdocs.watermark.watermarks/textalignment#Left)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | int | Vattenstämpeln `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`. |
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


Hämtar paddinginställningarna för denna `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`. Denna egenskap gäller endast för bildfiler.


**Returns:**
[Thickness](../../com.groupdocs.watermark/thickness) - The padding settings of this `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`.

### setPadding(Thickness value) {#setPadding-com.groupdocs.watermark.Thickness-}
```
public final void setPadding(Thickness value)
```


Ställer in paddinginställningarna för denna `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`. Denna egenskap gäller endast för bildfiler.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [Thickness](../../com.groupdocs.watermark/thickness) | Paddinginställningarna för denna `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`. |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

**Returns:**
boolean
### createGeometry(ContentPartGeometry parent) {#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-}
```
public WatermarkGeometry createGeometry(ContentPartGeometry parent)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parent | [ContentPartGeometry](../../com.groupdocs.watermark.internal/contentpartgeometry) |  |

**Returns:**
[WatermarkGeometry](../../com.groupdocs.watermark.internal/watermarkgeometry)
