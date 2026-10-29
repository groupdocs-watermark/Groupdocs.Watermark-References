---
title: "TextWatermark"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Bir metin filigranını temsil eder."
type: docs
weight: 18
url: /tr/java/com.groupdocs.watermark.watermarks/textwatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.Watermark](../../com.groupdocs.watermark/watermark)
```
public class TextWatermark extends Watermark
```

Bir metin filigranını temsil eder.

**Learn more:**

* [Adding text watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+text+watermarks)

Aşağıdaki örnek, metin filigranını ebeveyn boyutuna bağlı olarak nasıl ölçeklendireceğini gösterir.
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


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [TextWatermark(String text, Font font)](#TextWatermark-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | Belirtilen bir metin ve yazı tipi ile `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` sınıfının yeni bir örneğini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getText()](#getText--) | Filigran olarak kullanılacak metni alır. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Filigran olarak kullanılacak metni ayarlar. |
|
|  | [getFont()](#getFont--) | Metnin yazı tipini alır. |
|
|  | [setFont(Font value)](#setFont-com.groupdocs.watermark.watermarks.Font-) | Metnin yazı tipini ayarlar. |
|
|  | [getForegroundColor()](#getForegroundColor--) | Metnin ön plan rengini alır. |
|
|  | [setForegroundColor(Color value)](#setForegroundColor-com.groupdocs.watermark.watermarks.Color-) | Metnin ön plan rengini ayarlar. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Metnin arka plan rengini alır. |
|
|  | [setBackgroundColor(Color value)](#setBackgroundColor-com.groupdocs.watermark.watermarks.Color-) | Metnin arka plan rengini ayarlar. |
|
|  | [getTextAlignment()](#getTextAlignment--) | Filigranın `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)` değerini alır. |
|
|  | [setTextAlignment(int value)](#setTextAlignment-int-) | Filigranın `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)` değerini ayarlar. |
|
| [isImageWatermark()](#isImageWatermark--) |  |
| [isTextWatermark()](#isTextWatermark--) |  |
| [getForegroundColorConsideringOpacity()](#getForegroundColorConsideringOpacity--) |  |
| [getBackgroundColorConsideringOpacity()](#getBackgroundColorConsideringOpacity--) |  |
| [getSize()](#getSize--) |  |
|  | [getPadding()](#getPadding--) | Bu `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` nesnesinin dolgu ayarlarını alır. |
|
|  | [setPadding(Thickness value)](#setPadding-com.groupdocs.watermark.Thickness-) | Bu `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` nesnesinin dolgu ayarlarını ayarlar. |
|
| [deepClone()](#deepClone--) |  |
| [hasSameValues(Watermark watermark)](#hasSameValues-com.groupdocs.watermark.Watermark-) |  |
| [createGeometry(ContentPartGeometry parent)](#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-) |  |
### TextWatermark(String text, Font font) {#TextWatermark-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public TextWatermark(String text, Font font)
```


Belirtilen bir metin ve yazı tipi ile `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | metin | java.lang.String | Filigran olarak kullanılacak metin. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Metnin yazı tipi. |
|

### getText() {#getText--}
```
public final String getText()
```


Filigran olarak kullanılacak metni alır.


**Returns:**
java.lang.String - Filigran metnini temsil eden dize.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Filigran olarak kullanılacak metni ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Filigran metnini temsil eden dize. |
|

### getFont() {#getFont--}
```
public final Font getFont()
```


Metnin yazı tipini alır.


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### setFont(Font value) {#setFont-com.groupdocs.watermark.watermarks.Font-}
```
public final void setFont(Font value)
```


Metnin yazı tipini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [Font](../../com.groupdocs.watermark.watermarks/font) | Metnin yazı tipi. |
|

### getForegroundColor() {#getForegroundColor--}
```
public final Color getForegroundColor()
```


Metnin ön plan rengini alır.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### setForegroundColor(Color value) {#setForegroundColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setForegroundColor(Color value)
```


Metnin ön plan rengini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | Metnin ön plan rengi. |
|

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Metnin arka plan rengini alır.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

### setBackgroundColor(Color value) {#setBackgroundColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setBackgroundColor(Color value)
```


Metnin arka plan rengini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | Metnin arka plan rengi. |
|

### getTextAlignment() {#getTextAlignment--}
```
public final int getTextAlignment()
```


Filigranın `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)` değerini alır.

Varsayılan değer `[TextAlignment.Left](../../com.groupdocs.watermark.watermarks/textalignment#Left)`'dir.


**Returns:**
int - Filigranın `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)` değeri.

### setTextAlignment(int value) {#setTextAlignment-int-}
```
public final void setTextAlignment(int value)
```


Filigranın `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)` değerini ayarlar.

Varsayılan değer `[TextAlignment.Left](../../com.groupdocs.watermark.watermarks/textalignment#Left)`'dir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | int | Filigranın `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)` değeri. |
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


Bu `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` nesnesinin dolgu ayarlarını alır. Bu özellik yalnızca görüntü dosyalarına uygulanabilir.


**Returns:**
[Thickness](../../com.groupdocs.watermark/thickness) - The padding settings of this `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`.

### setPadding(Thickness value) {#setPadding-com.groupdocs.watermark.Thickness-}
```
public final void setPadding(Thickness value)
```


Bu `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` nesnesinin dolgu ayarlarını ayarlar. Bu özellik yalnızca görüntü dosyalarına uygulanabilir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [Thickness](../../com.groupdocs.watermark/thickness) | Bu `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` öğesinin dolgu ayarları. |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

**Returns:**
boolean
### createGeometry(ContentPartGeometry parent) {#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-}
```
public WatermarkGeometry createGeometry(ContentPartGeometry parent)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parent | [ContentPartGeometry](../../com.groupdocs.watermark.internal/contentpartgeometry) |  |

**Returns:**
[WatermarkGeometry](../../com.groupdocs.watermark.internal/watermarkgeometry)
