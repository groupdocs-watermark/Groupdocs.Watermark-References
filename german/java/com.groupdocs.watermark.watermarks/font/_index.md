---
title: "Font"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Klasse, die eine Schriftart darstellt."
type: docs
weight: 11
url: /de/java/com.groupdocs.watermark.watermarks/font/
---
**Inheritance:**
java.lang.Object
```
public final class Font
```

Klasse, die eine Schriftart darstellt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | Initialisiert eine neue Instanz der `[Font](../../com.groupdocs.watermark.watermarks/font)`-Klasse mit einem angegebenen Schriftfamiliennamen und einer Größe. |
|
|  | [Font(String fontFamilyName, float size, int style)](#Font-java.lang.String-float-int-) | Initialisiert eine neue Instanz der `[Font](../../com.groupdocs.watermark.watermarks/font)`-Klasse mit einem angegebenen Schriftfamiliennamen, einer Größe und einem Stil. |
|
| [Font(String fontFamilyName, String folderPath, float size)](#Font-java.lang.String-java.lang.String-float-) |  |
| [Font(String fontFamilyName, String folderPath, float size, FontStyle style)](#Font-java.lang.String-java.lang.String-float-com.groupdocs.watermark.watermarks.FontStyle-) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFolderPath()](#getFolderPath--) |  |
| [setFolderPath(String folderPath)](#setFolderPath-java.lang.String-) |  |
|  | [getFamilyName()](#getFamilyName--) | Gibt den Familiennamen dieses `[Font](../../com.groupdocs.watermark.watermarks/font)` zurück. |
|
|  | [getSize()](#getSize--) | Gibt die Größe dieses `[Font](../../com.groupdocs.watermark.watermarks/font)` zurück. |
|
|  | [getStyle()](#getStyle--) | Gibt den `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` für dieses `[Font](../../com.groupdocs.watermark.watermarks/font)` zurück. |
|
|  | [getBold()](#getBold--) | Gibt einen Wert zurück, der angibt, ob die Schrift fett ist. |
|
|  | [getItalic()](#getItalic--) | Gibt einen Wert zurück, der angibt, ob die Schrift kursiv ist. |
|
|  | [getStrikeout()](#getStrikeout--) | Gibt einen Wert zurück, der angibt, ob die Schrift eine horizontale Linie durch die Schrift definiert. |
|
|  | [getUnderline()](#getUnderline--) | Gibt einen Wert zurück, der angibt, ob die Schrift unterstrichen ist. |
|
### Font(String fontFamilyName, float size) {#Font-java.lang.String-float-}
```
public Font(String fontFamilyName, float size)
```


Initialisiert eine neue Instanz der `[Font](../../com.groupdocs.watermark.watermarks/font)`-Klasse mit einem angegebenen Schriftfamiliennamen und einer Größe.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | Der Name der Schriftfamilie. |
|
|  | Größe | float | Die Größe der neuen Schrift. |
|

### Font(String fontFamilyName, float size, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontFamilyName, float size, int style)
```


Initialisiert eine neue Instanz der `[Font](../../com.groupdocs.watermark.watermarks/font)`-Klasse mit einem angegebenen Schriftfamiliennamen, einer Größe und einem Stil.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | Der Name der Schriftfamilie. |
|
|  | Größe | float | Die Größe der neuen Schrift. |
|
|  | style | int | Der `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` der neuen Schrift. |
|

### Font(String fontFamilyName, String folderPath, float size) {#Font-java.lang.String-java.lang.String-float-}
```
public Font(String fontFamilyName, String folderPath, float size)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontFamilyName | java.lang.String |  |
| folderPath | java.lang.String |  |
| Größe | float |  |

### Font(String fontFamilyName, String folderPath, float size, FontStyle style) {#Font-java.lang.String-java.lang.String-float-com.groupdocs.watermark.watermarks.FontStyle-}
```
public Font(String fontFamilyName, String folderPath, float size, FontStyle style)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontFamilyName | java.lang.String |  |
| folderPath | java.lang.String |  |
| Größe | float |  |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folderPath | java.lang.String |  |

### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


Gibt den Familiennamen dieses `[Font](../../com.groupdocs.watermark.watermarks/font)` zurück.


**Returns:**
java.lang.String - Der Familienname dieses `[Font](../../com.groupdocs.watermark.watermarks/font)`.

### getSize() {#getSize--}
```
public final float getSize()
```


Gibt die Größe dieses `[Font](../../com.groupdocs.watermark.watermarks/font)` zurück.


**Returns:**
float - Die Größe dieses `[Font](../../com.groupdocs.watermark.watermarks/font)`.

### getStyle() {#getStyle--}
```
public final int getStyle()
```


Gibt den `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` für dieses `[Font](../../com.groupdocs.watermark.watermarks/font)` zurück.

Standardwert ist `[FontStyle.Regular](../../com.groupdocs.watermark.watermarks/fontstyle#Regular)` (normaler Text).


**Returns:**
int - Der `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` dieses `[Font](../../com.groupdocs.watermark.watermarks/font)`.

### getBold() {#getBold--}
```
public final boolean getBold()
```


Gibt einen Wert zurück, der angibt, ob die Schrift fett ist.


**Returns:**
boolean - True, wenn diese Schrift fett ist; andernfalls false.

### getItalic() {#getItalic--}
```
public final boolean getItalic()
```


Gibt einen Wert zurück, der angibt, ob die Schrift kursiv ist.


**Returns:**
boolean - True, wenn diese Schrift kursiv ist; andernfalls false.

### getStrikeout() {#getStrikeout--}
```
public final boolean getStrikeout()
```


Gibt einen Wert zurück, der angibt, ob die Schrift eine horizontale Linie durch die Schrift definiert.


**Returns:**
boolean - True, wenn diese Schrift eine horizontale Linie durch die Schrift definiert; andernfalls false.

### getUnderline() {#getUnderline--}
```
public final boolean getUnderline()
```


Gibt einen Wert zurück, der angibt, ob die Schrift unterstrichen ist.


**Returns:**
boolean - True, wenn diese Schrift unterstrichen ist; andernfalls false.

