---
title: "PresentationFormattedTextFragment"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa un fragmento de texto con formato en un documento PowerPoint."
type: docs
weight: 82
url: /es/java/com.groupdocs.watermark.contents/presentationformattedtextfragment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)

**All Implemented Interfaces:**
[com.groupdocs.watermark.contents.IPresentationHyperlinkContainer](../../com.groupdocs.watermark.contents/ipresentationhyperlinkcontainer)
```
public class PresentationFormattedTextFragment extends FormattedTextFragment implements IPresentationHyperlinkContainer
```

Representa un fragmento de texto con formato en un documento PowerPoint.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getText()](#getText--) | Obtiene el texto del fragmento. |
|
|  | [getFont()](#getFont--) | Obtiene la fuente del texto. |
|
|  | [getForegroundColor()](#getForegroundColor--) | Obtiene el color de primer plano del texto. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Obtiene el color de fondo del texto. |
|
|  | [getHyperlink(int actionType)](#getHyperlink-int-) | Obtiene el hipervínculo asociado al texto. |
|
|  | [setHyperlink(int actionType, String url)](#setHyperlink-int-java.lang.String-) | Establece el hipervínculo asociado al texto. |
|
### getText() {#getText--}
```
public String getText()
```


Obtiene el texto del fragmento.


**Returns:**
java.lang.String - El texto del fragmento.

### getFont() {#getFont--}
```
public Font getFont()
```


Obtiene la fuente del texto.


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Obtiene el color de primer plano del texto.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Obtiene el color de fondo del texto.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

### getHyperlink(int actionType) {#getHyperlink-int-}
```
public final String getHyperlink(int actionType)
```


Obtiene el hipervínculo asociado al texto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | actionType | int | La acción que activa el hipervínculo. |
|

**Returns:**
java.lang.String - La URL del hipervínculo que se activa con la acción especificada.

### setHyperlink(int actionType, String url) {#setHyperlink-int-java.lang.String-}
```
public final void setHyperlink(int actionType, String url)
```


Establece el hipervínculo asociado al texto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | actionType | int | La acción que activa el hipervínculo. |
|
|  | url | java.lang.String | La URL del hipervínculo. |
|

