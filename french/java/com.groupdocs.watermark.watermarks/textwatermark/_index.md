---
title: "TextWatermark"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente un filigrane texte."
type: docs
weight: 18
url: /fr/java/com.groupdocs.watermark.watermarks/textwatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.Watermark](../../com.groupdocs.watermark/watermark)
```
public class TextWatermark extends Watermark
```

Représente un filigrane texte.

**Learn more:**

* [Adding text watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+text+watermarks)

L'exemple suivant montre comment mettre à l'échelle le filigrane texte en fonction de la taille du parent.
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


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [TextWatermark(String text, Font font)](#TextWatermark-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | Initialise une nouvelle instance de la classe `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` avec un texte et une police spécifiés. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getText()](#getText--) | Obtient le texte à utiliser comme filigrane. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Définit le texte à utiliser comme filigrane. |
|
|  | [getFont()](#getFont--) | Obtient la police du texte. |
|
|  | [setFont(Font value)](#setFont-com.groupdocs.watermark.watermarks.Font-) | Définit la police du texte. |
|
|  | [getForegroundColor()](#getForegroundColor--) | Obtient la couleur de premier plan du texte. |
|
|  | [setForegroundColor(Color value)](#setForegroundColor-com.groupdocs.watermark.watermarks.Color-) | Définit la couleur de premier plan du texte. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Obtient la couleur d'arrière-plan du texte. |
|
|  | [setBackgroundColor(Color value)](#setBackgroundColor-com.groupdocs.watermark.watermarks.Color-) | Définit la couleur d'arrière-plan du texte. |
|
|  | [getTextAlignment()](#getTextAlignment--) | Obtient le filigrane `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`. |
|
|  | [setTextAlignment(int value)](#setTextAlignment-int-) | Définit le filigrane `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`. |
|
| [isImageWatermark()](#isImageWatermark--) |  |
| [isTextWatermark()](#isTextWatermark--) |  |
| [getForegroundColorConsideringOpacity()](#getForegroundColorConsideringOpacity--) |  |
| [getBackgroundColorConsideringOpacity()](#getBackgroundColorConsideringOpacity--) |  |
| [getSize()](#getSize--) |  |
|  | [getPadding()](#getPadding--) | Obtient les paramètres de remplissage de ce `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`. |
|
|  | [setPadding(Thickness value)](#setPadding-com.groupdocs.watermark.Thickness-) | Définit les paramètres de remplissage de ce `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`. |
|
| [deepClone()](#deepClone--) |  |
| [hasSameValues(Watermark watermark)](#hasSameValues-com.groupdocs.watermark.Watermark-) |  |
| [createGeometry(ContentPartGeometry parent)](#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-) |  |
### TextWatermark(String text, Font font) {#TextWatermark-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public TextWatermark(String text, Font font)
```


Initialise une nouvelle instance de la classe `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` avec un texte et une police spécifiés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | texte | java.lang.String | Le texte à utiliser comme filigrane. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | La police du texte. |
|

### getText() {#getText--}
```
public final String getText()
```


Obtient le texte à utiliser comme filigrane.


**Returns:**
java.lang.String - La chaîne représentant le texte du filigrane.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Définit le texte à utiliser comme filigrane.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | La chaîne représentant le texte du filigrane. |
|

### getFont() {#getFont--}
```
public final Font getFont()
```


Obtient la police du texte.


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### setFont(Font value) {#setFont-com.groupdocs.watermark.watermarks.Font-}
```
public final void setFont(Font value)
```


Définit la police du texte.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [Font](../../com.groupdocs.watermark.watermarks/font) | La police du texte. |
|

### getForegroundColor() {#getForegroundColor--}
```
public final Color getForegroundColor()
```


Obtient la couleur de premier plan du texte.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### setForegroundColor(Color value) {#setForegroundColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setForegroundColor(Color value)
```


Définit la couleur de premier plan du texte.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | La couleur de premier plan du texte. |
|

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Obtient la couleur d'arrière-plan du texte.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

### setBackgroundColor(Color value) {#setBackgroundColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setBackgroundColor(Color value)
```


Définit la couleur d'arrière-plan du texte.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | La couleur d'arrière-plan du texte. |
|

### getTextAlignment() {#getTextAlignment--}
```
public final int getTextAlignment()
```


Obtient le filigrane `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`.

La valeur par défaut est `[TextAlignment.Left](../../com.groupdocs.watermark.watermarks/textalignment#Left)`.


**Returns:**
int - Le filigrane `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`.

### setTextAlignment(int value) {#setTextAlignment-int-}
```
public final void setTextAlignment(int value)
```


Définit le filigrane `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`.

La valeur par défaut est `[TextAlignment.Left](../../com.groupdocs.watermark.watermarks/textalignment#Left)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | int | Le filigrane `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`. |
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


Obtient les paramètres de remplissage de ce `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`. Cette propriété ne s'applique qu'aux fichiers image.


**Returns:**
[Thickness](../../com.groupdocs.watermark/thickness) - The padding settings of this `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`.

### setPadding(Thickness value) {#setPadding-com.groupdocs.watermark.Thickness-}
```
public final void setPadding(Thickness value)
```


Définit les paramètres de remplissage de ce `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`. Cette propriété ne s'applique qu'aux fichiers image.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [Thickness](../../com.groupdocs.watermark/thickness) | Les paramètres de remplissage de ce `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`. |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

**Returns:**
boolean
### createGeometry(ContentPartGeometry parent) {#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-}
```
public WatermarkGeometry createGeometry(ContentPartGeometry parent)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| parent | [ContentPartGeometry](../../com.groupdocs.watermark.internal/contentpartgeometry) |  |

**Returns:**
[WatermarkGeometry](../../com.groupdocs.watermark.internal/watermarkgeometry)
