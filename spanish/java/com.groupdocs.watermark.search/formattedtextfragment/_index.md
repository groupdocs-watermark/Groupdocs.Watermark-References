---
title: "FormattedTextFragment"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Proporciona una clase base abstracta para un fragmento de texto con formato en un contenido."
type: docs
weight: 26
url: /es/java/com.groupdocs.watermark.search/formattedtextfragment/
---
**Inheritance:**
java.lang.Object
```
public abstract class FormattedTextFragment
```

Proporciona una clase base abstracta para un fragmento de texto con formato en un contenido.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [FormattedTextFragment()](#FormattedTextFragment--) |  |
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
### FormattedTextFragment() {#FormattedTextFragment--}
```
public FormattedTextFragment()
```




### getText() {#getText--}
```
public abstract String getText()
```


Obtiene el texto del fragmento.


**Returns:**
java.lang.String - El texto del fragmento.

### getFont() {#getFont--}
```
public abstract Font getFont()
```


Obtiene la fuente del texto.


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### getForegroundColor() {#getForegroundColor--}
```
public abstract Color getForegroundColor()
```


Obtiene el color de primer plano del texto.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### getBackgroundColor() {#getBackgroundColor--}
```
public abstract Color getBackgroundColor()
```


Obtiene el color de fondo del texto.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

