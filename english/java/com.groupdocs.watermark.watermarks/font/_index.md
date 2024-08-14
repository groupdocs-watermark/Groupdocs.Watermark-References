---
title: Font
second_title: GroupDocs.Watermark for Java API Reference
description: Class representing a font.
type: docs
weight: 11
url: /java/com.groupdocs.watermark.watermarks/font/
---
**Inheritance:**
java.lang.Object
```
public final class Font
```

Class representing a font.
## Constructors

| Constructor | Description |
| --- | --- |
| [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | Initializes a new instance of the `[Font](../../com.groupdocs.watermark.watermarks/font)` class with a specified font family name and a size. |
| [Font(String fontFamilyName, float size, int style)](#Font-java.lang.String-float-int-) | Initializes a new instance of the `[Font](../../com.groupdocs.watermark.watermarks/font)` class with a specified font family name, a size and a style. |
| [Font(String fontFamilyName, String folderPath, float size)](#Font-java.lang.String-java.lang.String-float-) |  |
| [Font(String fontFamilyName, String folderPath, float size, FontStyle style)](#Font-java.lang.String-java.lang.String-float-com.groupdocs.watermark.watermarks.FontStyle-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getFolderPath()](#getFolderPath--) |  |
| [setFolderPath(String folderPath)](#setFolderPath-java.lang.String-) |  |
| [getFamilyName()](#getFamilyName--) | Gets the family name of this `[Font](../../com.groupdocs.watermark.watermarks/font)`. |
| [getSize()](#getSize--) | Gets the size of this `[Font](../../com.groupdocs.watermark.watermarks/font)`. |
| [getStyle()](#getStyle--) | Gets the `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` for this `[Font](../../com.groupdocs.watermark.watermarks/font)`. |
| [getBold()](#getBold--) | Gets a value indicating whether the font is bold. |
| [getItalic()](#getItalic--) | Gets a value indicating whether the font is italic. |
| [getStrikeout()](#getStrikeout--) | Gets a value indicating whether the font specifies a horizontal line through the font. |
| [getUnderline()](#getUnderline--) | Gets a value indicating whether the font is underlined. |
### Font(String fontFamilyName, float size) {#Font-java.lang.String-float-}
```
public Font(String fontFamilyName, float size)
```


Initializes a new instance of the `[Font](../../com.groupdocs.watermark.watermarks/font)` class with a specified font family name and a size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontFamilyName | java.lang.String | The font family name. |
| size | float | The size of the new font. |

### Font(String fontFamilyName, float size, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontFamilyName, float size, int style)
```


Initializes a new instance of the `[Font](../../com.groupdocs.watermark.watermarks/font)` class with a specified font family name, a size and a style.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontFamilyName | java.lang.String | The font family name. |
| size | float | The size of the new font. |
| style | int | The `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` of the new font. |

### Font(String fontFamilyName, String folderPath, float size) {#Font-java.lang.String-java.lang.String-float-}
```
public Font(String fontFamilyName, String folderPath, float size)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontFamilyName | java.lang.String |  |
| folderPath | java.lang.String |  |
| size | float |  |

### Font(String fontFamilyName, String folderPath, float size, FontStyle style) {#Font-java.lang.String-java.lang.String-float-com.groupdocs.watermark.watermarks.FontStyle-}
```
public Font(String fontFamilyName, String folderPath, float size, FontStyle style)
```


**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| folderPath | java.lang.String |  |

### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


Gets the family name of this `[Font](../../com.groupdocs.watermark.watermarks/font)`.

**Returns:**
java.lang.String - The family name of this `[Font](../../com.groupdocs.watermark.watermarks/font)`.
### getSize() {#getSize--}
```
public final float getSize()
```


Gets the size of this `[Font](../../com.groupdocs.watermark.watermarks/font)`.

**Returns:**
float - The size of this `[Font](../../com.groupdocs.watermark.watermarks/font)`.
### getStyle() {#getStyle--}
```
public final int getStyle()
```


Gets the `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` for this `[Font](../../com.groupdocs.watermark.watermarks/font)`.

Default value is `[FontStyle.Regular](../../com.groupdocs.watermark.watermarks/fontstyle#Regular)` (normal text).

**Returns:**
int - The `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` of this `[Font](../../com.groupdocs.watermark.watermarks/font)`.
### getBold() {#getBold--}
```
public final boolean getBold()
```


Gets a value indicating whether the font is bold.

**Returns:**
boolean - True if this font is bold; otherwise, false.
### getItalic() {#getItalic--}
```
public final boolean getItalic()
```


Gets a value indicating whether the font is italic.

**Returns:**
boolean - True if this font is italic; otherwise, false.
### getStrikeout() {#getStrikeout--}
```
public final boolean getStrikeout()
```


Gets a value indicating whether the font specifies a horizontal line through the font.

**Returns:**
boolean - True if this font specifies a horizontal line through the font; otherwise, false.
### getUnderline() {#getUnderline--}
```
public final boolean getUnderline()
```


Gets a value indicating whether the font is underlined.

**Returns:**
boolean - True if this font is underlined; otherwise, false.
