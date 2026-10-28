---
title: "Font"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Klasse die een lettertype voorstelt."
type: docs
weight: 11
url: /nl/java/com.groupdocs.watermark.watermarks/font/
---
**Inheritance:**
java.lang.Object
```
public final class Font
```

Klasse die een lettertype voorstelt.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | Initialiseert een nieuw exemplaar van de `[Font](../../com.groupdocs.watermark.watermarks/font)`-klasse met een opgegeven lettertypefamilienaam en een grootte. |
|
|  | [Font(String fontFamilyName, float size, int style)](#Font-java.lang.String-float-int-) | Initialiseert een nieuw exemplaar van de `[Font](../../com.groupdocs.watermark.watermarks/font)`-klasse met een opgegeven lettertypefamilienaam, een grootte en een stijl. |
|
| [Font(String fontFamilyName, String folderPath, float size)](#Font-java.lang.String-java.lang.String-float-) |  |
| [Font(String fontFamilyName, String folderPath, float size, FontStyle style)](#Font-java.lang.String-java.lang.String-float-com.groupdocs.watermark.watermarks.FontStyle-) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFolderPath()](#getFolderPath--) |  |
| [setFolderPath(String folderPath)](#setFolderPath-java.lang.String-) |  |
|  | [getFamilyName()](#getFamilyName--) | Haalt de familienaam op van dit `[Font](../../com.groupdocs.watermark.watermarks/font)`. |
|
|  | [getSize()](#getSize--) | Haalt de grootte op van dit `[Font](../../com.groupdocs.watermark.watermarks/font)`. |
|
|  | [getStyle()](#getStyle--) | Haalt de `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` op voor dit `[Font](../../com.groupdocs.watermark.watermarks/font)`. |
|
|  | [getBold()](#getBold--) | Haalt een waarde op die aangeeft of het lettertype vetgedrukt is. |
|
|  | [getItalic()](#getItalic--) | Retourneert een waarde die aangeeft of het lettertype cursief is. |
|
|  | [getStrikeout()](#getStrikeout--) | Retourneert een waarde die aangeeft of het lettertype een horizontale doorstreping heeft. |
|
|  | [getUnderline()](#getUnderline--) | Retourneert een waarde die aangeeft of het lettertype onderstreept is. |
|
### Font(String fontFamilyName, float size) {#Font-java.lang.String-float-}
```
public Font(String fontFamilyName, float size)
```


Initialiseert een nieuw exemplaar van de `[Font](../../com.groupdocs.watermark.watermarks/font)`-klasse met een opgegeven lettertypefamilienaam en een grootte.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | De naam van de lettertypefamilie. |
|
|  | size | float | De grootte van het nieuwe lettertype. |
|

### Font(String fontFamilyName, float size, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontFamilyName, float size, int style)
```


Initialiseert een nieuw exemplaar van de `[Font](../../com.groupdocs.watermark.watermarks/font)`-klasse met een opgegeven lettertypefamilienaam, een grootte en een stijl.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | De naam van de lettertypefamilie. |
|
|  | size | float | De grootte van het nieuwe lettertype. |
|
|  | style | int | De `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` van het nieuwe lettertype. |
|

### Font(String fontFamilyName, String folderPath, float size) {#Font-java.lang.String-java.lang.String-float-}
```
public Font(String fontFamilyName, String folderPath, float size)
```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontFamilyName | java.lang.String |  |
| folderPath | java.lang.String |  |
| size | float |  |

### Font(String fontFamilyName, String folderPath, float size, FontStyle style) {#Font-java.lang.String-java.lang.String-float-com.groupdocs.watermark.watermarks.FontStyle-}
```
public Font(String fontFamilyName, String folderPath, float size, FontStyle style)
```


**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| folderPath | java.lang.String |  |

### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


Haalt de familienaam op van dit `[Font](../../com.groupdocs.watermark.watermarks/font)`.


**Returns:**
java.lang.String - De familienaam van dit `[Font](../../com.groupdocs.watermark.watermarks/font)`.

### getSize() {#getSize--}
```
public final float getSize()
```


Haalt de grootte op van dit `[Font](../../com.groupdocs.watermark.watermarks/font)`.


**Returns:**
float - De grootte van dit `[Font](../../com.groupdocs.watermark.watermarks/font)`.

### getStyle() {#getStyle--}
```
public final int getStyle()
```


Haalt de `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` op voor dit `[Font](../../com.groupdocs.watermark.watermarks/font)`.

Standaardwaarde is `[FontStyle.Regular](../../com.groupdocs.watermark.watermarks/fontstyle#Regular)` (normale tekst).


**Returns:**
int - De `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` van dit `[Font](../../com.groupdocs.watermark.watermarks/font)`.

### getBold() {#getBold--}
```
public final boolean getBold()
```


Haalt een waarde op die aangeeft of het lettertype vetgedrukt is.


**Returns:**
boolean - True als dit lettertype vet is; anders false.

### getItalic() {#getItalic--}
```
public final boolean getItalic()
```


Retourneert een waarde die aangeeft of het lettertype cursief is.


**Returns:**
boolean - True als dit lettertype cursief is; anders false.

### getStrikeout() {#getStrikeout--}
```
public final boolean getStrikeout()
```


Retourneert een waarde die aangeeft of het lettertype een horizontale doorstreping heeft.


**Returns:**
boolean - True als dit lettertype een horizontale doorstreping heeft; anders false.

### getUnderline() {#getUnderline--}
```
public final boolean getUnderline()
```


Retourneert een waarde die aangeeft of het lettertype onderstreept is.


**Returns:**
boolean - True als dit lettertype onderstreept is; anders false.

