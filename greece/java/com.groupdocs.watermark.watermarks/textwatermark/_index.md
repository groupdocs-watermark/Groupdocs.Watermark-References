---
title: "TextWatermark"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αναπαριστά ένα κειμενικό υδατογράφημα."
type: docs
weight: 18
url: /el/java/com.groupdocs.watermark.watermarks/textwatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.Watermark](../../com.groupdocs.watermark/watermark)
```
public class TextWatermark extends Watermark
```

Αναπαριστά ένα κειμενικό υδατογράφημα.

**Learn more:**

* [Adding text watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+text+watermarks)

Το παρακάτω παράδειγμα δείχνει πώς να κλιμακώσετε το κείμενο υδατογραφήματος ανάλογα με το μέγεθος του γονέα.
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


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [TextWatermark(String text, Font font)](#TextWatermark-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` με συγκεκριμένο κείμενο και γραμματοσειρά. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getText()](#getText--) | Λαμβάνει το κείμενο που θα χρησιμοποιηθεί ως υδατογράφημα. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Ορίζει το κείμενο που θα χρησιμοποιηθεί ως υδατογράφημα. |
|
|  | [getFont()](#getFont--) | Λαμβάνει τη γραμματοσειρά του κειμένου. |
|
|  | [setFont(Font value)](#setFont-com.groupdocs.watermark.watermarks.Font-) | Ορίζει τη γραμματοσειρά του κειμένου. |
|
|  | [getForegroundColor()](#getForegroundColor--) | Λαμβάνει το χρώμα προσκλήρου του κειμένου. |
|
|  | [setForegroundColor(Color value)](#setForegroundColor-com.groupdocs.watermark.watermarks.Color-) | Ορίζει το χρώμα προσκλήρου του κειμένου. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Λαμβάνει το χρώμα φόντου του κειμένου. |
|
|  | [setBackgroundColor(Color value)](#setBackgroundColor-com.groupdocs.watermark.watermarks.Color-) | Ορίζει το χρώμα φόντου του κειμένου. |
|
|  | [getTextAlignment()](#getTextAlignment--) | Λαμβάνει το υδατογράφημα `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`. |
|
|  | [setTextAlignment(int value)](#setTextAlignment-int-) | Ορίζει το υδατογράφημα `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`. |
|
| [isImageWatermark()](#isImageWatermark--) |  |
| [isTextWatermark()](#isTextWatermark--) |  |
| [getForegroundColorConsideringOpacity()](#getForegroundColorConsideringOpacity--) |  |
| [getBackgroundColorConsideringOpacity()](#getBackgroundColorConsideringOpacity--) |  |
| [getSize()](#getSize--) |  |
|  | [getPadding()](#getPadding--) | Λαμβάνει τις ρυθμίσεις γεμίσματος αυτού του `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`. |
|
|  | [setPadding(Thickness value)](#setPadding-com.groupdocs.watermark.Thickness-) | Ορίζει τις ρυθμίσεις γεμίσματος αυτού του `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`. |
|
| [deepClone()](#deepClone--) |  |
| [hasSameValues(Watermark watermark)](#hasSameValues-com.groupdocs.watermark.Watermark-) |  |
| [createGeometry(ContentPartGeometry parent)](#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-) |  |
### TextWatermark(String text, Font font) {#TextWatermark-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public TextWatermark(String text, Font font)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` με συγκεκριμένο κείμενο και γραμματοσειρά.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | κείμενο | java.lang.String | Το κείμενο που θα χρησιμοποιηθεί ως υδατογράφημα. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Η γραμματοσειρά του κειμένου. |
|

### getText() {#getText--}
```
public final String getText()
```


Λαμβάνει το κείμενο που θα χρησιμοποιηθεί ως υδατογράφημα.


**Returns:**
java.lang.String - Η συμβολοσειρά που αντιπροσωπεύει το κείμενο υδατογραφήματος.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Ορίζει το κείμενο που θα χρησιμοποιηθεί ως υδατογράφημα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.String | Η συμβολοσειρά που αντιπροσωπεύει το κείμενο υδατογραφήματος. |
|

### getFont() {#getFont--}
```
public final Font getFont()
```


Λαμβάνει τη γραμματοσειρά του κειμένου.


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### setFont(Font value) {#setFont-com.groupdocs.watermark.watermarks.Font-}
```
public final void setFont(Font value)
```


Ορίζει τη γραμματοσειρά του κειμένου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [Font](../../com.groupdocs.watermark.watermarks/font) | Η γραμματοσειρά του κειμένου. |
|

### getForegroundColor() {#getForegroundColor--}
```
public final Color getForegroundColor()
```


Λαμβάνει το χρώμα προσκλήρου του κειμένου.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### setForegroundColor(Color value) {#setForegroundColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setForegroundColor(Color value)
```


Ορίζει το χρώμα προσκλήρου του κειμένου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | Το χρώμα προσκλήρου του κειμένου. |
|

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Λαμβάνει το χρώμα φόντου του κειμένου.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

### setBackgroundColor(Color value) {#setBackgroundColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setBackgroundColor(Color value)
```


Ορίζει το χρώμα φόντου του κειμένου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | Το χρώμα φόντου του κειμένου. |
|

### getTextAlignment() {#getTextAlignment--}
```
public final int getTextAlignment()
```


Λαμβάνει το υδατογράφημα `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`.

Η προεπιλεγμένη τιμή είναι `[TextAlignment.Left](../../com.groupdocs.watermark.watermarks/textalignment#Left)`.


**Returns:**
int - Το υδατογράφημα `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`.

### setTextAlignment(int value) {#setTextAlignment-int-}
```
public final void setTextAlignment(int value)
```


Ορίζει το υδατογράφημα `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`.

Η προεπιλεγμένη τιμή είναι `[TextAlignment.Left](../../com.groupdocs.watermark.watermarks/textalignment#Left)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | int | Το υδατογράφημα `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`. |
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


Λαμβάνει τις ρυθμίσεις γεμίσματος αυτού του `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`. Αυτή η ιδιότητα ισχύει μόνο για αρχεία εικόνας.


**Returns:**
[Thickness](../../com.groupdocs.watermark/thickness) - The padding settings of this `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`.

### setPadding(Thickness value) {#setPadding-com.groupdocs.watermark.Thickness-}
```
public final void setPadding(Thickness value)
```


Ορίζει τις ρυθμίσεις γεμίσματος αυτού του `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`. Αυτή η ιδιότητα ισχύει μόνο για αρχεία εικόνας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [Thickness](../../com.groupdocs.watermark/thickness) | Οι ρυθμίσεις γεμίσματος αυτού του `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`. |
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

**Returns:**
boolean
### createGeometry(ContentPartGeometry parent) {#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-}
```
public WatermarkGeometry createGeometry(ContentPartGeometry parent)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| parent | [ContentPartGeometry](../../com.groupdocs.watermark.internal/contentpartgeometry) |  |

**Returns:**
[WatermarkGeometry](../../com.groupdocs.watermark.internal/watermarkgeometry)
