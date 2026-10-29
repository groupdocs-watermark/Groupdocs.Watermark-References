---
title: "Font"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Clase que representa una fuente."
type: docs
weight: 11
url: /es/java/com.groupdocs.watermark.watermarks/font/
---
**Inheritance:**
java.lang.Object
```
public final class Font
```

Clase que representa una fuente.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | Inicializa una nueva instancia de la clase `[Font](../../com.groupdocs.watermark.watermarks/font)` con un nombre de familia de fuente especificado y un tamaño. |
|
|  | [Font(String fontFamilyName, float size, int style)](#Font-java.lang.String-float-int-) | Inicializa una nueva instancia de la clase `[Font](../../com.groupdocs.watermark.watermarks/font)` con un nombre de familia de fuente especificado, un tamaño y un estilo. |
|
| [Font(String fontFamilyName, String folderPath, float size)](#Font-java.lang.String-java.lang.String-float-) |  |
| [Font(String fontFamilyName, String folderPath, float size, FontStyle style)](#Font-java.lang.String-java.lang.String-float-com.groupdocs.watermark.watermarks.FontStyle-) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFolderPath()](#getFolderPath--) |  |
| [setFolderPath(String folderPath)](#setFolderPath-java.lang.String-) |  |
|  | [getFamilyName()](#getFamilyName--) | Obtiene el nombre de familia de este `[Font](../../com.groupdocs.watermark.watermarks/font)`. |
|
|  | [getSize()](#getSize--) | Obtiene el tamaño de este `[Font](../../com.groupdocs.watermark.watermarks/font)`. |
|
|  | [getStyle()](#getStyle--) | Obtiene el `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` de este `[Font](../../com.groupdocs.watermark.watermarks/font)`. |
|
|  | [getBold()](#getBold--) | Obtiene un valor que indica si la fuente es negrita. |
|
|  | [getItalic()](#getItalic--) | Obtiene un valor que indica si la fuente es cursiva. |
|
|  | [getStrikeout()](#getStrikeout--) | Obtiene un valor que indica si la fuente especifica una línea horizontal a través de la fuente. |
|
|  | [getUnderline()](#getUnderline--) | Obtiene un valor que indica si la fuente está subrayada. |
|
### Font(String fontFamilyName, float size) {#Font-java.lang.String-float-}
```
public Font(String fontFamilyName, float size)
```


Inicializa una nueva instancia de la clase `[Font](../../com.groupdocs.watermark.watermarks/font)` con un nombre de familia de fuente especificado y un tamaño.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | El nombre de la familia de fuentes. |
|
|  | size | float | El tamaño de la nueva fuente. |
|

### Font(String fontFamilyName, float size, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontFamilyName, float size, int style)
```


Inicializa una nueva instancia de la clase `[Font](../../com.groupdocs.watermark.watermarks/font)` con un nombre de familia de fuente especificado, un tamaño y un estilo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | El nombre de la familia de fuentes. |
|
|  | size | float | El tamaño de la nueva fuente. |
|
|  | style | int | El `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` de la nueva fuente. |
|

### Font(String fontFamilyName, String folderPath, float size) {#Font-java.lang.String-java.lang.String-float-}
```
public Font(String fontFamilyName, String folderPath, float size)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontFamilyName | java.lang.String |  |
| folderPath | java.lang.String |  |
| size | float |  |

### Font(String fontFamilyName, String folderPath, float size, FontStyle style) {#Font-java.lang.String-java.lang.String-float-com.groupdocs.watermark.watermarks.FontStyle-}
```
public Font(String fontFamilyName, String folderPath, float size, FontStyle style)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontFamilyName | java.lang.String |  |
| folderPath | java.lang.String |  |
| size | float |  |
| style | [FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle) |  |

### getFolderPath() {#getFolderPath--}
```
public String getFolderPath()
```




**Returns:**
java.lang.String
### setFolderPath(String folderPath) {#setFolderPath-java.lang.String-}
```
public void setFolderPath(String folderPath)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| folderPath | java.lang.String |  |

### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


Obtiene el nombre de familia de este `[Font](../../com.groupdocs.watermark.watermarks/font)`.


**Returns:**
java.lang.String - El nombre de la familia de este `[Font](../../com.groupdocs.watermark.watermarks/font)`.

### getSize() {#getSize--}
```
public final float getSize()
```


Obtiene el tamaño de este `[Font](../../com.groupdocs.watermark.watermarks/font)`.


**Returns:**
float - El tamaño de este `[Font](../../com.groupdocs.watermark.watermarks/font)`.

### getStyle() {#getStyle--}
```
public final int getStyle()
```


Obtiene el `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` de este `[Font](../../com.groupdocs.watermark.watermarks/font)`.

El valor predeterminado es `[FontStyle.Regular](../../com.groupdocs.watermark.watermarks/fontstyle#Regular)` (texto normal).


**Returns:**
int - El `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` de este `[Font](../../com.groupdocs.watermark.watermarks/font)`.

### getBold() {#getBold--}
```
public final boolean getBold()
```


Obtiene un valor que indica si la fuente es negrita.


**Returns:**
boolean - Verdadero si esta fuente es negrita; de lo contrario, falso.

### getItalic() {#getItalic--}
```
public final boolean getItalic()
```


Obtiene un valor que indica si la fuente es cursiva.


**Returns:**
boolean - Verdadero si esta fuente es cursiva; de lo contrario, falso.

### getStrikeout() {#getStrikeout--}
```
public final boolean getStrikeout()
```


Obtiene un valor que indica si la fuente especifica una línea horizontal a través de la fuente.


**Returns:**
boolean - Verdadero si esta fuente especifica una línea horizontal a través de la fuente; de lo contrario, falso.

### getUnderline() {#getUnderline--}
```
public final boolean getUnderline()
```


Obtiene un valor que indica si la fuente está subrayada.


**Returns:**
boolean - Verdadero si esta fuente está subrayada; de lo contrario, falso.

