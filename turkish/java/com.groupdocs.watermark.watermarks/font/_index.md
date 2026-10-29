---
title: "Font"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Bir yazı tipini temsil eden sınıf."
type: docs
weight: 11
url: /tr/java/com.groupdocs.watermark.watermarks/font/
---
**Inheritance:**
java.lang.Object
```
public final class Font
```

Bir yazı tipini temsil eden sınıf.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | Belirtilen bir yazı tipi ailesi adı ve boyut ile `[Font](../../com.groupdocs.watermark.watermarks/font)` sınıfının yeni bir örneğini başlatır. |
|
|  | [Font(String fontFamilyName, float size, int style)](#Font-java.lang.String-float-int-) | Belirtilen bir yazı tipi ailesi adı, bir boyut ve bir stil ile `[Font](../../com.groupdocs.watermark.watermarks/font)` sınıfının yeni bir örneğini başlatır. |
|
| [Font(String fontFamilyName, String folderPath, float size)](#Font-java.lang.String-java.lang.String-float-) |  |
| [Font(String fontFamilyName, String folderPath, float size, FontStyle style)](#Font-java.lang.String-java.lang.String-float-com.groupdocs.watermark.watermarks.FontStyle-) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFolderPath()](#getFolderPath--) |  |
| [setFolderPath(String folderPath)](#setFolderPath-java.lang.String-) |  |
|  | [getFamilyName()](#getFamilyName--) | Bu `[Font](../../com.groupdocs.watermark.watermarks/font)` sınıfının aile adını alır. |
|
|  | [getSize()](#getSize--) | Bu `[Font](../../com.groupdocs.watermark.watermarks/font)` sınıfının boyutunu alır. |
|
|  | [getStyle()](#getStyle--) | Bu `[Font](../../com.groupdocs.watermark.watermarks/font)` için `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` değerini alır. |
|
|  | [getBold()](#getBold--) | Yazı tipinin kalın olup olmadığını gösteren bir değer alır. |
|
|  | [getItalic()](#getItalic--) | Yazı tipinin italik olup olmadığını gösteren bir değer alır. |
|
|  | [getStrikeout()](#getStrikeout--) | Yazı tipinin üzerinden yatay bir çizgi geçip geçmediğini gösteren bir değer alır. |
|
|  | [getUnderline()](#getUnderline--) | Yazı tipinin altı çizili olup olmadığını gösteren bir değer alır. |
|
### Font(String fontFamilyName, float size) {#Font-java.lang.String-float-}
```
public Font(String fontFamilyName, float size)
```


Belirtilen bir yazı tipi ailesi adı ve boyut ile `[Font](../../com.groupdocs.watermark.watermarks/font)` sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | Yazı tipi ailesi adı. |
|
|  | size | float | Yeni yazı tipinin boyutu. |
|

### Font(String fontFamilyName, float size, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontFamilyName, float size, int style)
```


Belirtilen bir yazı tipi ailesi adı, bir boyut ve bir stil ile `[Font](../../com.groupdocs.watermark.watermarks/font)` sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | Yazı tipi ailesi adı. |
|
|  | size | float | Yeni yazı tipinin boyutu. |
|
|  | style | int | Yeni yazı tipinin `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` değeri. |
|

### Font(String fontFamilyName, String folderPath, float size) {#Font-java.lang.String-java.lang.String-float-}
```
public Font(String fontFamilyName, String folderPath, float size)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontFamilyName | java.lang.String |  |
| folderPath | java.lang.String |  |
| size | float |  |

### Font(String fontFamilyName, String folderPath, float size, FontStyle style) {#Font-java.lang.String-java.lang.String-float-com.groupdocs.watermark.watermarks.FontStyle-}
```
public Font(String fontFamilyName, String folderPath, float size, FontStyle style)
```


**Parameters:**
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| folderPath | java.lang.String |  |

### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


Bu `[Font](../../com.groupdocs.watermark.watermarks/font)` sınıfının aile adını alır.


**Returns:**
java.lang.String - Bu `[Font](../../com.groupdocs.watermark.watermarks/font)`'ın aile adı.

### getSize() {#getSize--}
```
public final float getSize()
```


Bu `[Font](../../com.groupdocs.watermark.watermarks/font)` sınıfının boyutunu alır.


**Returns:**
float - Bu `[Font](../../com.groupdocs.watermark.watermarks/font)`'ın boyutu.

### getStyle() {#getStyle--}
```
public final int getStyle()
```


Bu `[Font](../../com.groupdocs.watermark.watermarks/font)` için `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` değerini alır.

Varsayılan değer `[FontStyle.Regular](../../com.groupdocs.watermark.watermarks/fontstyle#Regular)` (normal metin) olarak ayarlanmıştır.


**Returns:**
int - Bu `[Font](../../com.groupdocs.watermark.watermarks/font)`'ın `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` değeri.

### getBold() {#getBold--}
```
public final boolean getBold()
```


Yazı tipinin kalın olup olmadığını gösteren bir değer alır.


**Returns:**
boolean - Bu yazı tipi kalın ise true; aksi takdirde false.

### getItalic() {#getItalic--}
```
public final boolean getItalic()
```


Yazı tipinin italik olup olmadığını gösteren bir değer alır.


**Returns:**
boolean - Bu yazı tipi italik ise true; aksi takdirde false.

### getStrikeout() {#getStrikeout--}
```
public final boolean getStrikeout()
```


Yazı tipinin üzerinden yatay bir çizgi geçip geçmediğini gösteren bir değer alır.


**Returns:**
boolean - Bu yazı tipi üzerinden yatay bir çizgi geçiyorsa true; aksi takdirde false.

### getUnderline() {#getUnderline--}
```
public final boolean getUnderline()
```


Yazı tipinin altı çizili olup olmadığını gösteren bir değer alır.


**Returns:**
boolean - Bu yazı tipi altı çizili ise true; aksi takdirde false.

