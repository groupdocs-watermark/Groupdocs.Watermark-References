---
title: "TextWatermark"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili watermark teks."
type: docs
weight: 18
url: /id/java/com.groupdocs.watermark.watermarks/textwatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.Watermark](../../com.groupdocs.watermark/watermark)
```
public class TextWatermark extends Watermark
```

Mewakili watermark teks.

**Learn more:**

* [Adding text watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+text+watermarks)

Contoh berikut menunjukkan cara menskalakan watermark teks tergantung pada ukuran induk.
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


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [TextWatermark(String text, Font font)](#TextWatermark-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | Menginisialisasi instance baru dari kelas `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` dengan teks dan font yang ditentukan. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getText()](#getText--) | Mendapatkan teks yang akan digunakan sebagai watermark. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Mengatur teks yang akan digunakan sebagai watermark. |
|
|  | [getFont()](#getFont--) | Mendapatkan font teks. |
|
|  | [setFont(Font value)](#setFont-com.groupdocs.watermark.watermarks.Font-) | Mengatur font teks. |
|
|  | [getForegroundColor()](#getForegroundColor--) | Mendapatkan warna latar depan teks. |
|
|  | [setForegroundColor(Color value)](#setForegroundColor-com.groupdocs.watermark.watermarks.Color-) | Mengatur warna latar depan teks. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Mendapatkan warna latar belakang teks. |
|
|  | [setBackgroundColor(Color value)](#setBackgroundColor-com.groupdocs.watermark.watermarks.Color-) | Mengatur warna latar belakang teks. |
|
|  | [getTextAlignment()](#getTextAlignment--) | Mendapatkan watermark `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`. |
|
|  | [setTextAlignment(int value)](#setTextAlignment-int-) | Mengatur watermark `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`. |
|
| [isImageWatermark()](#isImageWatermark--) |  |
| [isTextWatermark()](#isTextWatermark--) |  |
| [getForegroundColorConsideringOpacity()](#getForegroundColorConsideringOpacity--) |  |
| [getBackgroundColorConsideringOpacity()](#getBackgroundColorConsideringOpacity--) |  |
| [getSize()](#getSize--) |  |
|  | [getPadding()](#getPadding--) | Mendapatkan pengaturan padding dari `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` ini. |
|
|  | [setPadding(Thickness value)](#setPadding-com.groupdocs.watermark.Thickness-) | Mengatur pengaturan padding dari `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` ini. |
|
| [deepClone()](#deepClone--) |  |
| [hasSameValues(Watermark watermark)](#hasSameValues-com.groupdocs.watermark.Watermark-) |  |
| [createGeometry(ContentPartGeometry parent)](#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-) |  |
### TextWatermark(String text, Font font) {#TextWatermark-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public TextWatermark(String text, Font font)
```


Menginisialisasi instance baru dari kelas `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` dengan teks dan font yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | teks | java.lang.String | Teks yang akan digunakan sebagai watermark. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Font teks. |
|

### getText() {#getText--}
```
public final String getText()
```


Mendapatkan teks yang akan digunakan sebagai watermark.


**Returns:**
java.lang.String - String yang mewakili teks watermark.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Mengatur teks yang akan digunakan sebagai watermark.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | java.lang.String | String yang mewakili teks watermark. |
|

### getFont() {#getFont--}
```
public final Font getFont()
```


Mendapatkan font teks.


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### setFont(Font value) {#setFont-com.groupdocs.watermark.watermarks.Font-}
```
public final void setFont(Font value)
```


Mengatur font teks.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [Font](../../com.groupdocs.watermark.watermarks/font) | Font teks. |
|

### getForegroundColor() {#getForegroundColor--}
```
public final Color getForegroundColor()
```


Mendapatkan warna latar depan teks.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### setForegroundColor(Color value) {#setForegroundColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setForegroundColor(Color value)
```


Mengatur warna latar depan teks.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | Warna latar depan teks. |
|

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Mendapatkan warna latar belakang teks.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

### setBackgroundColor(Color value) {#setBackgroundColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setBackgroundColor(Color value)
```


Mengatur warna latar belakang teks.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | Warna latar belakang teks. |
|

### getTextAlignment() {#getTextAlignment--}
```
public final int getTextAlignment()
```


Mendapatkan watermark `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`.

Nilai default adalah `[TextAlignment.Left](../../com.groupdocs.watermark.watermarks/textalignment#Left)`.


**Returns:**
int - Watermark `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`.

### setTextAlignment(int value) {#setTextAlignment-int-}
```
public final void setTextAlignment(int value)
```


Mengatur watermark `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`.

Nilai default adalah `[TextAlignment.Left](../../com.groupdocs.watermark.watermarks/textalignment#Left)`.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | int | Watermark `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`. |
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


Mendapatkan pengaturan padding dari `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` ini. Properti ini hanya berlaku untuk file gambar.


**Returns:**
[Thickness](../../com.groupdocs.watermark/thickness) - The padding settings of this `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`.

### setPadding(Thickness value) {#setPadding-com.groupdocs.watermark.Thickness-}
```
public final void setPadding(Thickness value)
```


Mengatur pengaturan padding dari `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` ini. Properti ini hanya berlaku untuk file gambar.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [Thickness](../../com.groupdocs.watermark/thickness) | Pengaturan padding dari `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` ini. |
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

**Returns:**
boolean
### createGeometry(ContentPartGeometry parent) {#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-}
```
public WatermarkGeometry createGeometry(ContentPartGeometry parent)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| parent | [ContentPartGeometry](../../com.groupdocs.watermark.internal/contentpartgeometry) |  |

**Returns:**
[WatermarkGeometry](../../com.groupdocs.watermark.internal/watermarkgeometry)
