---
title: "Font"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Klass som representerar ett typsnitt."
type: docs
weight: 11
url: /sv/java/com.groupdocs.watermark.watermarks/font/
---
**Inheritance:**
java.lang.Object
```
public final class Font
```

Klass som representerar ett typsnitt.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | Initierar en ny instans av klassen `[Font](../../com.groupdocs.watermark.watermarks/font)` med ett angivet typsnittsfamiljenamn och en storlek. |
|
|  | [Font(String fontFamilyName, float size, int style)](#Font-java.lang.String-float-int-) | Initierar en ny instans av klassen `[Font](../../com.groupdocs.watermark.watermarks/font)` med ett angivet typsnittsfamiljenamn, en storlek och en stil. |
|
| [Font(String fontFamilyName, String folderPath, float size)](#Font-java.lang.String-java.lang.String-float-) |  |
| [Font(String fontFamilyName, String folderPath, float size, FontStyle style)](#Font-java.lang.String-java.lang.String-float-com.groupdocs.watermark.watermarks.FontStyle-) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFolderPath()](#getFolderPath--) |  |
| [setFolderPath(String folderPath)](#setFolderPath-java.lang.String-) |  |
|  | [getFamilyName()](#getFamilyName--) | Hämtar familjenamnet för detta `[Font](../../com.groupdocs.watermark.watermarks/font)`. |
|
|  | [getSize()](#getSize--) | Hämtar storleken för detta `[Font](../../com.groupdocs.watermark.watermarks/font)`. |
|
|  | [getStyle()](#getStyle--) | Hämtar `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` för detta `[Font](../../com.groupdocs.watermark.watermarks/font)`. |
|
|  | [getBold()](#getBold--) | Hämtar ett värde som indikerar om typsnittet är fetstil. |
|
|  | [getItalic()](#getItalic--) | Hämtar ett värde som indikerar om teckensnittet är kursivt. |
|
|  | [getStrikeout()](#getStrikeout--) | Hämtar ett värde som indikerar om teckensnittet har en horisontell linje genom teckensnittet. |
|
|  | [getUnderline()](#getUnderline--) | Hämtar ett värde som indikerar om teckensnittet är understruket. |
|
### Font(String fontFamilyName, float size) {#Font-java.lang.String-float-}
```
public Font(String fontFamilyName, float size)
```


Initierar en ny instans av klassen `[Font](../../com.groupdocs.watermark.watermarks/font)` med ett angivet typsnittsfamiljenamn och en storlek.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | Teckensnittsfamiljens namn. |
|
|  | size | float | Storleken på det nya teckensnittet. |
|

### Font(String fontFamilyName, float size, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontFamilyName, float size, int style)
```


Initierar en ny instans av klassen `[Font](../../com.groupdocs.watermark.watermarks/font)` med ett angivet typsnittsfamiljenamn, en storlek och en stil.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | Teckensnittsfamiljens namn. |
|
|  | size | float | Storleken på det nya teckensnittet. |
|
|  | style | int | Den `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` för det nya teckensnittet. |
|

### Font(String fontFamilyName, String folderPath, float size) {#Font-java.lang.String-java.lang.String-float-}
```
public Font(String fontFamilyName, String folderPath, float size)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontFamilyName | java.lang.String |  |
| folderPath | java.lang.String |  |
| size | float |  |

### Font(String fontFamilyName, String folderPath, float size, FontStyle style) {#Font-java.lang.String-java.lang.String-float-com.groupdocs.watermark.watermarks.FontStyle-}
```
public Font(String fontFamilyName, String folderPath, float size, FontStyle style)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folderPath | java.lang.String |  |

### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


Hämtar familjenamnet för detta `[Font](../../com.groupdocs.watermark.watermarks/font)`.


**Returns:**
java.lang.String - Familjenamnet för detta `[Font](../../com.groupdocs.watermark.watermarks/font)`.

### getSize() {#getSize--}
```
public final float getSize()
```


Hämtar storleken för detta `[Font](../../com.groupdocs.watermark.watermarks/font)`.


**Returns:**
float - Storleken på detta `[Font](../../com.groupdocs.watermark.watermarks/font)`.

### getStyle() {#getStyle--}
```
public final int getStyle()
```


Hämtar `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` för detta `[Font](../../com.groupdocs.watermark.watermarks/font)`.

Standardvärdet är `[FontStyle.Regular](../../com.groupdocs.watermark.watermarks/fontstyle#Regular)` (normal text).


**Returns:**
int - `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` för detta `[Font](../../com.groupdocs.watermark.watermarks/font)`.

### getBold() {#getBold--}
```
public final boolean getBold()
```


Hämtar ett värde som indikerar om typsnittet är fetstil.


**Returns:**
boolean - Sant om detta teckensnitt är fetstil; annars falskt.

### getItalic() {#getItalic--}
```
public final boolean getItalic()
```


Hämtar ett värde som indikerar om teckensnittet är kursivt.


**Returns:**
boolean - Sant om detta teckensnitt är kursivt; annars falskt.

### getStrikeout() {#getStrikeout--}
```
public final boolean getStrikeout()
```


Hämtar ett värde som indikerar om teckensnittet har en horisontell linje genom teckensnittet.


**Returns:**
boolean - Sant om detta teckensnitt har en horisontell linje genom teckensnittet; annars falskt.

### getUnderline() {#getUnderline--}
```
public final boolean getUnderline()
```


Hämtar ett värde som indikerar om teckensnittet är understruket.


**Returns:**
boolean - Sant om detta teckensnitt är understruket; annars falskt.

