---
title: "Font"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Classe représentant une police."
type: docs
weight: 11
url: /fr/java/com.groupdocs.watermark.watermarks/font/
---
**Inheritance:**
java.lang.Object
```
public final class Font
```

Classe représentant une police.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | Initialise une nouvelle instance de la classe `[Font](../../com.groupdocs.watermark.watermarks/font)` avec un nom de famille de police spécifié et une taille. |
|
|  | [Font(String fontFamilyName, float size, int style)](#Font-java.lang.String-float-int-) | Initialise une nouvelle instance de la classe `[Font](../../com.groupdocs.watermark.watermarks/font)` avec un nom de famille de police spécifié, une taille et un style. |
|
| [Font(String fontFamilyName, String folderPath, float size)](#Font-java.lang.String-java.lang.String-float-) |  |
| [Font(String fontFamilyName, String folderPath, float size, FontStyle style)](#Font-java.lang.String-java.lang.String-float-com.groupdocs.watermark.watermarks.FontStyle-) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFolderPath()](#getFolderPath--) |  |
| [setFolderPath(String folderPath)](#setFolderPath-java.lang.String-) |  |
|  | [getFamilyName()](#getFamilyName--) | Obtient le nom de famille de ce `[Font](../../com.groupdocs.watermark.watermarks/font)`. |
|
|  | [getSize()](#getSize--) | Obtient la taille de ce `[Font](../../com.groupdocs.watermark.watermarks/font)`. |
|
|  | [getStyle()](#getStyle--) | Obtient le `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` de ce `[Font](../../com.groupdocs.watermark.watermarks/font)`. |
|
|  | [getBold()](#getBold--) | Obtient une valeur indiquant si la police est en gras. |
|
|  | [getItalic()](#getItalic--) | Obtient une valeur indiquant si la police est italique. |
|
|  | [getStrikeout()](#getStrikeout--) | Obtient une valeur indiquant si la police spécifie une ligne horizontale traversant la police. |
|
|  | [getUnderline()](#getUnderline--) | Obtient une valeur indiquant si la police est soulignée. |
|
### Font(String fontFamilyName, float size) {#Font-java.lang.String-float-}
```
public Font(String fontFamilyName, float size)
```


Initialise une nouvelle instance de la classe `[Font](../../com.groupdocs.watermark.watermarks/font)` avec un nom de famille de police spécifié et une taille.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | Le nom de la famille de polices. |
|
|  | size | float | La taille de la nouvelle police. |
|

### Font(String fontFamilyName, float size, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontFamilyName, float size, int style)
```


Initialise une nouvelle instance de la classe `[Font](../../com.groupdocs.watermark.watermarks/font)` avec un nom de famille de police spécifié, une taille et un style.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | Le nom de la famille de polices. |
|
|  | size | float | La taille de la nouvelle police. |
|
|  | style | int | Le `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` de la nouvelle police. |
|

### Font(String fontFamilyName, String folderPath, float size) {#Font-java.lang.String-java.lang.String-float-}
```
public Font(String fontFamilyName, String folderPath, float size)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontFamilyName | java.lang.String |  |
| folderPath | java.lang.String |  |
| size | float |  |

### Font(String fontFamilyName, String folderPath, float size, FontStyle style) {#Font-java.lang.String-java.lang.String-float-com.groupdocs.watermark.watermarks.FontStyle-}
```
public Font(String fontFamilyName, String folderPath, float size, FontStyle style)
```


**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| folderPath | java.lang.String |  |

### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


Obtient le nom de famille de ce `[Font](../../com.groupdocs.watermark.watermarks/font)`.


**Returns:**
java.lang.String - Le nom de la famille de ce `[Font](../../com.groupdocs.watermark.watermarks/font)`.

### getSize() {#getSize--}
```
public final float getSize()
```


Obtient la taille de ce `[Font](../../com.groupdocs.watermark.watermarks/font)`.


**Returns:**
float - La taille de ce `[Font](../../com.groupdocs.watermark.watermarks/font)`.

### getStyle() {#getStyle--}
```
public final int getStyle()
```


Obtient le `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` de ce `[Font](../../com.groupdocs.watermark.watermarks/font)`.

La valeur par défaut est `[FontStyle.Regular](../../com.groupdocs.watermark.watermarks/fontstyle#Regular)` (texte normal).


**Returns:**
int - Le `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` de ce `[Font](../../com.groupdocs.watermark.watermarks/font)`.

### getBold() {#getBold--}
```
public final boolean getBold()
```


Obtient une valeur indiquant si la police est en gras.


**Returns:**
boolean - Vrai si cette police est en gras ; sinon, faux.

### getItalic() {#getItalic--}
```
public final boolean getItalic()
```


Obtient une valeur indiquant si la police est italique.


**Returns:**
boolean - Vrai si cette police est italique ; sinon, faux.

### getStrikeout() {#getStrikeout--}
```
public final boolean getStrikeout()
```


Obtient une valeur indiquant si la police spécifie une ligne horizontale traversant la police.


**Returns:**
boolean - Vrai si cette police spécifie une ligne horizontale traversant la police ; sinon, faux.

### getUnderline() {#getUnderline--}
```
public final boolean getUnderline()
```


Obtient une valeur indiquant si la police est soulignée.


**Returns:**
boolean - Vrai si cette police est soulignée ; sinon, faux.

