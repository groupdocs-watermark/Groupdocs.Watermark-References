---
title: "SpreadsheetShape"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili bentuk gambar dalam dokumen Excel."
type: docs
weight: 117
url: /id/java/com.groupdocs.watermark.contents/spreadsheetshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject), [com.groupdocs.watermark.search.IHyperlinkContainer](../../com.groupdocs.watermark.search/ihyperlinkcontainer)
```
public class SpreadsheetShape extends ShapeSearchAdapter implements IRotatableTwoDObject, IHyperlinkContainer
```

Mewakili bentuk gambar dalam dokumen Excel.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getWorksheet()](#getWorksheet--) | Mendapatkan lembar kerja induk dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini. |
|
|  | [getAutoShapeType()](#getAutoShapeType--) | Mendapatkan tipe bentuk otomatis. |
|
|  | [getMsoDrawingType()](#getMsoDrawingType--) | Mendapatkan tipe gambar mso. |
|
|  | [getText()](#getText--) | Mendapatkan teks dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Mengatur teks untuk `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Mendapatkan koleksi fragmen teks terformat dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini. |
|
|  | [getImage()](#getImage--) | Mendapatkan gambar dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini. |
|
|  | [setImage(SpreadsheetWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | Mengatur gambar untuk `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini. |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | Mendapatkan pengaturan format isian gambar dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini. |
|
|  | [getId()](#getId--) | Mendapatkan pengidentifikasi dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Mendapatkan teks deskriptif (alternatif) yang terkait dengan `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Mengatur teks deskriptif (alternatif) yang terkait dengan `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini. |
|
|  | [isWordArt()](#isWordArt--) | Mendapatkan nilai yang menunjukkan apakah `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini adalah objek WordArt. |
|
|  | [getName()](#getName--) | Mendapatkan nama dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini. |
|
|  | [getAsposeCellsShape()](#getAsposeCellsShape--) | <br /> |

|
|  | [getHyperlink()](#getHyperlink--) | Mendapatkan hyperlink yang terkait dengan `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini. |
|
|  | [setHyperlink(String value)](#setHyperlink-java.lang.String-) | Mengatur hyperlink yang terkait dengan `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini. |
|
|  | [getX()](#getX--) | Mendapatkan offset horizontal dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini terhadap batas kiri lembar kerja dalam poin. |
|
|  | [setX(double value)](#setX-double-) | Mengatur offset horizontal dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini terhadap batas kiri lembar kerja dalam poin. |
|
|  | [getY()](#getY--) | Mendapatkan offset vertikal dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini terhadap batas atas lembar kerja dalam poin. |
|
|  | [setY(double value)](#setY-double-) | Mengatur offset vertikal dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini terhadap batas atas lembar kerja dalam poin. |
|
|  | [getWidth()](#getWidth--) | Mendapatkan lebar dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini dalam poin. |
|
|  | [setWidth(double value)](#setWidth-double-) | Mengatur lebar dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini dalam poin. |
|
|  | [getHeight()](#getHeight--) | Mendapatkan tinggi dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini dalam poin. |
|
|  | [setHeight(double value)](#setHeight-double-) | Mengatur tinggi dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini dalam poin. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Mendapatkan atau mengatur sudut rotasi dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini dalam derajat. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Mendapatkan atau mengatur sudut rotasi dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini dalam derajat. |
|
|  | [getImageForSearch()](#getImageForSearch--) | <br /> |

|
|  | [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) | <br /> |

|
|  | [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) | <br /> |

|
|  | [getTextForSearch()](#getTextForSearch--) | <br /> |

|
|  | [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) | <br /> |

|
### getWorksheet() {#getWorksheet--}
```
public final SpreadsheetWorksheet getWorksheet()
```


Mendapatkan lembar kerja induk dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini.


**Returns:**
[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) - The parent worksheet of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getAutoShapeType() {#getAutoShapeType--}
```
public final int getAutoShapeType()
```


Mendapatkan tipe bentuk otomatis.


**Returns:**
int - Jenis bentuk otomatis.

### getMsoDrawingType() {#getMsoDrawingType--}
```
public final int getMsoDrawingType()
```


Mendapatkan tipe gambar mso.


**Returns:**
int - Jenis gambar mso.

### getText() {#getText--}
```
public final String getText()
```


Mendapatkan teks dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini.


**Returns:**
java.lang.String - Teks dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Mengatur teks untuk `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | java.lang.String | Teks dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Mendapatkan koleksi fragmen teks terformat dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getImage() {#getImage--}
```
public final SpreadsheetWatermarkableImage getImage()
```


Mendapatkan gambar dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini.


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The image of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` or null if the shape has no image.

### setImage(SpreadsheetWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public final void setImage(SpreadsheetWatermarkableImage value)
```


Mengatur gambar untuk `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | Gambar dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini atau null jika gambar harus dihapus. |
|

### getImageFillFormat() {#getImageFillFormat--}
```
public final SpreadsheetImageFillFormat getImageFillFormat()
```


Mendapatkan pengaturan format isian gambar dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini.


**Returns:**
[SpreadsheetImageFillFormat](../../com.groupdocs.watermark.contents/spreadsheetimagefillformat) - The image fill format settings of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getId() {#getId--}
```
public final int getId()
```


Mendapatkan pengidentifikasi dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini.


**Returns:**
int - Pengidentifikasi dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Mendapatkan teks deskriptif (alternatif) yang terkait dengan `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini.


**Returns:**
java.lang.String - Teks deskriptif (alternatif) yang terkait dengan `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Mengatur teks deskriptif (alternatif) yang terkait dengan `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | java.lang.String | Teks deskriptif (alternatif) yang terkait dengan `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini. |
|

### isWordArt() {#isWordArt--}
```
public final boolean isWordArt()
```


Mendapatkan nilai yang menunjukkan apakah `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini adalah objek WordArt.


**Returns:**
boolean - True jika bentuk merupakan objek WordArt; jika tidak, false.

### getName() {#getName--}
```
public final String getName()
```


Mendapatkan nama dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini.


**Returns:**
java.lang.String - Nama dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini.

### getAsposeCellsShape() {#getAsposeCellsShape--}
```
public final Shape getAsposeCellsShape()
```


<br />



**Returns:**
com.aspose.cells.Shape
### getHyperlink() {#getHyperlink--}
```
public final String getHyperlink()
```


Mendapatkan hyperlink yang terkait dengan `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini.


**Returns:**
java.lang.String - Tautan yang terkait dengan `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini.

### setHyperlink(String value) {#setHyperlink-java.lang.String-}
```
public final void setHyperlink(String value)
```


Mengatur hyperlink yang terkait dengan `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | java.lang.String | Tautan yang terkait dengan `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini. |
|

### getX() {#getX--}
```
public final double getX()
```


Mendapatkan offset horizontal dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini terhadap batas kiri lembar kerja dalam poin.


**Returns:**
double - Koordinat x dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Mengatur offset horizontal dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini terhadap batas kiri lembar kerja dalam poin.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Koordinat x dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini. |
|

### getY() {#getY--}
```
public final double getY()
```


Mendapatkan offset vertikal dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini terhadap batas atas lembar kerja dalam poin.


**Returns:**
double - Koordinat y dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Mengatur offset vertikal dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini terhadap batas atas lembar kerja dalam poin.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Koordinat y dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Mendapatkan lebar dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini dalam poin.


**Returns:**
double - Lebar dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini dalam poin.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Mengatur lebar dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini dalam poin.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Lebar dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini dalam poin. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Mendapatkan tinggi dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini dalam poin.


**Returns:**
double - Tinggi dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini dalam poin.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Mengatur tinggi dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini dalam poin.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Tinggi dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini dalam poin. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Mendapatkan atau mengatur sudut rotasi dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini dalam derajat.


**Returns:**
double - Sudut rotasi dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini dalam derajat.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Mendapatkan atau mengatur sudut rotasi dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini dalam derajat.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Sudut rotasi dari `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ini dalam derajat. |
|

### getImageForSearch() {#getImageForSearch--}
```
public WatermarkableImage getImageForSearch()
```


<br />



**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### setFoundWatermarkImage(byte[] imageData) {#setFoundWatermarkImage-byte---}
```
public void setFoundWatermarkImage(byte[] imageData)
```


<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageData | byte[] |  |

### getFormattedTextFragmentsForSearch() {#getFormattedTextFragmentsForSearch--}
```
public FormattedTextFragmentCollection getFormattedTextFragmentsForSearch()
```


<br />



**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
### getTextForSearch() {#getTextForSearch--}
```
public String getTextForSearch()
```


<br />



**Returns:**
java.lang.String
### setFoundWatermarkText(String value) {#setFoundWatermarkText-java.lang.String-}
```
public void setFoundWatermarkText(String value)
```


<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

