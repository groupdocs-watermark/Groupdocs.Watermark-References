---
title: "Font"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Kelas yang mewakili font."
type: docs
weight: 11
url: /id/java/com.groupdocs.watermark.watermarks/font/
---
**Inheritance:**
java.lang.Object
```
public final class Font
```

Kelas yang mewakili font.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | Menginisialisasi instance baru dari kelas `[Font](../../com.groupdocs.watermark.watermarks/font)` dengan nama keluarga font yang ditentukan dan ukuran. |
|
|  | [Font(String fontFamilyName, float size, int style)](#Font-java.lang.String-float-int-) | Menginisialisasi instance baru dari kelas `[Font](../../com.groupdocs.watermark.watermarks/font)` dengan nama keluarga font yang ditentukan, ukuran, dan gaya. |
|
| [Font(String fontFamilyName, String folderPath, float size)](#Font-java.lang.String-java.lang.String-float-) |  |
| [Font(String fontFamilyName, String folderPath, float size, FontStyle style)](#Font-java.lang.String-java.lang.String-float-com.groupdocs.watermark.watermarks.FontStyle-) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFolderPath()](#getFolderPath--) |  |
| [setFolderPath(String folderPath)](#setFolderPath-java.lang.String-) |  |
|  | [getFamilyName()](#getFamilyName--) | Mendapatkan nama keluarga dari `[Font](../../com.groupdocs.watermark.watermarks/font)` ini. |
|
|  | [getSize()](#getSize--) | Mendapatkan ukuran dari `[Font](../../com.groupdocs.watermark.watermarks/font)` ini. |
|
|  | [getStyle()](#getStyle--) | Mendapatkan `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` untuk `[Font](../../com.groupdocs.watermark.watermarks/font)` ini. |
|
|  | [getBold()](#getBold--) | Mendapatkan nilai yang menunjukkan apakah font tersebut tebal. |
|
|  | [getItalic()](#getItalic--) | Mendapatkan nilai yang menunjukkan apakah font miring. |
|
|  | [getStrikeout()](#getStrikeout--) | Mendapatkan nilai yang menunjukkan apakah font memiliki garis horizontal yang melintang. |
|
|  | [getUnderline()](#getUnderline--) | Mendapatkan nilai yang menunjukkan apakah font bergaris bawah. |
|
### Font(String fontFamilyName, float size) {#Font-java.lang.String-float-}
```
public Font(String fontFamilyName, float size)
```


Menginisialisasi instance baru dari kelas `[Font](../../com.groupdocs.watermark.watermarks/font)` dengan nama keluarga font yang ditentukan dan ukuran.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | Nama keluarga font. |
|
|  | size | float | Ukuran font baru. |
|

### Font(String fontFamilyName, float size, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontFamilyName, float size, int style)
```


Menginisialisasi instance baru dari kelas `[Font](../../com.groupdocs.watermark.watermarks/font)` dengan nama keluarga font yang ditentukan, ukuran, dan gaya.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | Nama keluarga font. |
|
|  | size | float | Ukuran font baru. |
|
|  | style | int | `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` dari font baru. |
|

### Font(String fontFamilyName, String folderPath, float size) {#Font-java.lang.String-java.lang.String-float-}
```
public Font(String fontFamilyName, String folderPath, float size)
```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontFamilyName | java.lang.String |  |
| folderPath | java.lang.String |  |
| size | float |  |

### Font(String fontFamilyName, String folderPath, float size, FontStyle style) {#Font-java.lang.String-java.lang.String-float-com.groupdocs.watermark.watermarks.FontStyle-}
```
public Font(String fontFamilyName, String folderPath, float size, FontStyle style)
```


**Parameters:**
| Parameter | Tipe | Deskripsi |
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| folderPath | java.lang.String |  |

### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


Mendapatkan nama keluarga dari `[Font](../../com.groupdocs.watermark.watermarks/font)` ini.


**Returns:**
java.lang.String - Nama keluarga dari `[Font](../../com.groupdocs.watermark.watermarks/font)` ini.

### getSize() {#getSize--}
```
public final float getSize()
```


Mendapatkan ukuran dari `[Font](../../com.groupdocs.watermark.watermarks/font)` ini.


**Returns:**
float - Ukuran dari `[Font](../../com.groupdocs.watermark.watermarks/font)` ini.

### getStyle() {#getStyle--}
```
public final int getStyle()
```


Mendapatkan `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` untuk `[Font](../../com.groupdocs.watermark.watermarks/font)` ini.

Nilai default adalah `[FontStyle.Regular](../../com.groupdocs.watermark.watermarks/fontstyle#Regular)` (teks normal).


**Returns:**
int - `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` dari `[Font](../../com.groupdocs.watermark.watermarks/font)` ini.

### getBold() {#getBold--}
```
public final boolean getBold()
```


Mendapatkan nilai yang menunjukkan apakah font tersebut tebal.


**Returns:**
boolean - Benar jika font ini tebal; jika tidak, false.

### getItalic() {#getItalic--}
```
public final boolean getItalic()
```


Mendapatkan nilai yang menunjukkan apakah font miring.


**Returns:**
boolean - Benar jika font ini miring; jika tidak, false.

### getStrikeout() {#getStrikeout--}
```
public final boolean getStrikeout()
```


Mendapatkan nilai yang menunjukkan apakah font memiliki garis horizontal yang melintang.


**Returns:**
boolean - Benar jika font ini memiliki garis horizontal yang melintang; jika tidak, false.

### getUnderline() {#getUnderline--}
```
public final boolean getUnderline()
```


Mendapatkan nilai yang menunjukkan apakah font bergaris bawah.


**Returns:**
boolean - Benar jika font ini bergaris bawah; jika tidak, false.

