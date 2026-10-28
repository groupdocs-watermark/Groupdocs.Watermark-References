---
title: "TextWatermark"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta una filigrana di testo."
type: docs
weight: 18
url: /it/java/com.groupdocs.watermark.watermarks/textwatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.Watermark](../../com.groupdocs.watermark/watermark)
```
public class TextWatermark extends Watermark
```

Rappresenta una filigrana di testo.

**Learn more:**

* [Adding text watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+text+watermarks)

Il seguente esempio dimostra come scalare la filigrana di testo in base alle dimensioni del genitore.
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


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [TextWatermark(String text, Font font)](#TextWatermark-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | Inizializza una nuova istanza della classe `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` con un testo e un font specificati. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getText()](#getText--) | Ottiene il testo da utilizzare come filigrana. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Imposta il testo da utilizzare come filigrana. |
|
|  | [getFont()](#getFont--) | Ottiene il carattere del testo. |
|
|  | [setFont(Font value)](#setFont-com.groupdocs.watermark.watermarks.Font-) | Imposta il carattere del testo. |
|
|  | [getForegroundColor()](#getForegroundColor--) | Ottiene il colore di primo piano del testo. |
|
|  | [setForegroundColor(Color value)](#setForegroundColor-com.groupdocs.watermark.watermarks.Color-) | Imposta il colore di primo piano del testo. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Ottiene il colore di sfondo del testo. |
|
|  | [setBackgroundColor(Color value)](#setBackgroundColor-com.groupdocs.watermark.watermarks.Color-) | Imposta il colore di sfondo del testo. |
|
|  | [getTextAlignment()](#getTextAlignment--) | Ottiene la filigrana `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`. |
|
|  | [setTextAlignment(int value)](#setTextAlignment-int-) | Imposta la filigrana `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`. |
|
| [isImageWatermark()](#isImageWatermark--) |  |
| [isTextWatermark()](#isTextWatermark--) |  |
| [getForegroundColorConsideringOpacity()](#getForegroundColorConsideringOpacity--) |  |
| [getBackgroundColorConsideringOpacity()](#getBackgroundColorConsideringOpacity--) |  |
| [getSize()](#getSize--) |  |
|  | [getPadding()](#getPadding--) | Ottiene le impostazioni di riempimento di questo `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`. |
|
|  | [setPadding(Thickness value)](#setPadding-com.groupdocs.watermark.Thickness-) | Imposta le impostazioni di riempimento di questo `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`. |
|
| [deepClone()](#deepClone--) |  |
| [hasSameValues(Watermark watermark)](#hasSameValues-com.groupdocs.watermark.Watermark-) |  |
| [createGeometry(ContentPartGeometry parent)](#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-) |  |
### TextWatermark(String text, Font font) {#TextWatermark-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public TextWatermark(String text, Font font)
```


Inizializza una nuova istanza della classe `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` con un testo e un font specificati.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | testo | java.lang.String | Il testo da utilizzare come filigrana. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Il carattere del testo. |
|

### getText() {#getText--}
```
public final String getText()
```


Ottiene il testo da utilizzare come filigrana.


**Returns:**
java.lang.String - La stringa che rappresenta il testo della filigrana.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Imposta il testo da utilizzare come filigrana.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | La stringa che rappresenta il testo della filigrana. |
|

### getFont() {#getFont--}
```
public final Font getFont()
```


Ottiene il carattere del testo.


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### setFont(Font value) {#setFont-com.groupdocs.watermark.watermarks.Font-}
```
public final void setFont(Font value)
```


Imposta il carattere del testo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [Font](../../com.groupdocs.watermark.watermarks/font) | Il carattere del testo. |
|

### getForegroundColor() {#getForegroundColor--}
```
public final Color getForegroundColor()
```


Ottiene il colore di primo piano del testo.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### setForegroundColor(Color value) {#setForegroundColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setForegroundColor(Color value)
```


Imposta il colore di primo piano del testo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | Il colore di primo piano del testo. |
|

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Ottiene il colore di sfondo del testo.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

### setBackgroundColor(Color value) {#setBackgroundColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setBackgroundColor(Color value)
```


Imposta il colore di sfondo del testo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | Il colore di sfondo del testo. |
|

### getTextAlignment() {#getTextAlignment--}
```
public final int getTextAlignment()
```


Ottiene la filigrana `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`.

Il valore predefinito è `[TextAlignment.Left](../../com.groupdocs.watermark.watermarks/textalignment#Left)`.


**Returns:**
int - La filigrana `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`.

### setTextAlignment(int value) {#setTextAlignment-int-}
```
public final void setTextAlignment(int value)
```


Imposta la filigrana `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`.

Il valore predefinito è `[TextAlignment.Left](../../com.groupdocs.watermark.watermarks/textalignment#Left)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | int | La filigrana `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`. |
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


Ottiene le impostazioni di riempimento di questo `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`. Questa proprietà è applicabile solo ai file immagine.


**Returns:**
[Thickness](../../com.groupdocs.watermark/thickness) - The padding settings of this `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`.

### setPadding(Thickness value) {#setPadding-com.groupdocs.watermark.Thickness-}
```
public final void setPadding(Thickness value)
```


Imposta le impostazioni di riempimento di questo `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`. Questa proprietà è applicabile solo ai file immagine.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [Thickness](../../com.groupdocs.watermark/thickness) | Le impostazioni di riempimento di questo `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`. |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

**Returns:**
boolean
### createGeometry(ContentPartGeometry parent) {#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-}
```
public WatermarkGeometry createGeometry(ContentPartGeometry parent)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| parent | [ContentPartGeometry](../../com.groupdocs.watermark.internal/contentpartgeometry) |  |

**Returns:**
[WatermarkGeometry](../../com.groupdocs.watermark.internal/watermarkgeometry)
