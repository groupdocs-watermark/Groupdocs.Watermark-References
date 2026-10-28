---
title: "WordProcessingShape"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili bentuk gambar dalam dokumen Word."
type: docs
weight: 141
url: /id/java/com.groupdocs.watermark.contents/wordprocessingshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject), [com.groupdocs.watermark.search.IHyperlinkContainer](../../com.groupdocs.watermark.search/ihyperlinkcontainer)
```
public class WordProcessingShape extends ShapeSearchAdapter implements IRotatableTwoDObject, IHyperlinkContainer
```

Mewakili bentuk gambar dalam dokumen Word.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getSection()](#getSection--) | Mendapatkan bagian induk dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini. |
|
|  | [getHeaderFooter()](#getHeaderFooter--) | Mendapatkan header/footer induk dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini (jika ada). |
|
|  | [getShapeType()](#getShapeType--) | Mendapatkan tipe bentuk. |
|
|  | [isWordArt()](#isWordArt--) | Mendapatkan nilai yang menunjukkan apakah `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini adalah objek WordArt. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Mendapatkan teks deskriptif (alternatif) yang terkait dengan `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Mengatur teks deskriptif (alternatif) yang terkait dengan `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini. |
|
|  | [getName()](#getName--) | Mendapatkan nama dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini. |
|
|  | [getBehindText()](#getBehindText--) | Mendapatkan nilai yang menunjukkan apakah bentuk berada di atas atau di belakang teks. |
|
|  | [setBehindText(boolean value)](#setBehindText-boolean-) | Mengatur nilai yang menunjukkan apakah bentuk berada di atas atau di belakang teks. |
|
|  | [getText()](#getText--) | Mendapatkan teks dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Mengatur teks dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Mendapatkan koleksi fragmen teks terformat dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini. |
|
|  | [getImage()](#getImage--) | Mendapatkan gambar dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini. |
|
|  | [setImage(WordProcessingWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.WordProcessingWatermarkableImage-) | Mengatur gambar dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini. |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | Mendapatkan nilai yang menentukan bagaimana bentuk diposisikan secara horizontal. |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | Mendapatkan nilai yang menentukan bagaimana bentuk diposisikan secara vertikal. |
|
|  | [getRelativeHorizontalPosition()](#getRelativeHorizontalPosition--) | Mendapatkan nilai yang menentukan ke mana bentuk diposisikan secara horizontal. |
|
|  | [getRelativeVerticalPosition()](#getRelativeVerticalPosition--) | Mendapatkan nilai yang menentukan ke mana bentuk diposisikan secara vertikal. |
|
| [getImageFillFormat()](#getImageFillFormat--) |  |
| [getAsposeWordsShape()](#getAsposeWordsShape--) |  |
|  | [getHyperlink()](#getHyperlink--) | Mendapatkan hyperlink yang terkait dengan `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini. |
|
|  | [setHyperlink(String value)](#setHyperlink-java.lang.String-) | Mengatur hyperlink yang terkait dengan `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini. |
|
|  | [getWidth()](#getWidth--) | Mendapatkan lebar `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini dalam poin. |
|
|  | [setWidth(double value)](#setWidth-double-) | Mengatur lebar `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini dalam poin. |
|
|  | [getHeight()](#getHeight--) | Mendapatkan tinggi dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` dalam poin. |
|
|  | [setHeight(double value)](#setHeight-double-) | Mengatur tinggi dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` dalam poin. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Mendapatkan sudut rotasi dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` dalam derajat. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Mengatur sudut rotasi dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` dalam derajat. |
|
|  | [getX()](#getX--) | Mendapatkan atau mengatur offset horizontal dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` dari batas kiri halaman dalam poin. |
|
|  | [setX(double value)](#setX-double-) | Mendapatkan atau mengatur offset horizontal dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` dari batas kiri halaman dalam poin. |
|
|  | [getY()](#getY--) | Mendapatkan offset vertikal dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` dari batas atas halaman dalam poin. |
|
|  | [setY(double value)](#setY-double-) | Mengatur offset vertikal dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` dari batas atas halaman dalam poin. |
|
| [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) |  |
| [getTextForSearch()](#getTextForSearch--) |  |
| [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) |  |
| [getImageForSearch()](#getImageForSearch--) |  |
| [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) |  |
### getSection() {#getSection--}
```
public final WordProcessingSection getSection()
```


Mendapatkan bagian induk dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini.


**Returns:**
[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection) - The parent section of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getHeaderFooter() {#getHeaderFooter--}
```
public final WordProcessingHeaderFooter getHeaderFooter()
```


Mendapatkan header/footer induk dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini (jika ada).


**Returns:**
[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter) - The parent header/footer of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


Mendapatkan tipe bentuk.


**Returns:**
int - Tipe bentuk.

### isWordArt() {#isWordArt--}
```
public final boolean isWordArt()
```


Mendapatkan nilai yang menunjukkan apakah `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini adalah objek WordArt.


**Returns:**
boolean - True jika bentuk merupakan objek WordArt; jika tidak, false.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Mendapatkan teks deskriptif (alternatif) yang terkait dengan `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini.


**Returns:**
java.lang.String - Teks deskriptif (alternatif) yang terkait dengan `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Mengatur teks deskriptif (alternatif) yang terkait dengan `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | java.lang.String | Teks deskriptif (alternatif) yang terkait dengan `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getName() {#getName--}
```
public final String getName()
```


Mendapatkan nama dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini.


**Returns:**
java.lang.String - Nama dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getBehindText() {#getBehindText--}
```
public final boolean getBehindText()
```


Mendapatkan nilai yang menunjukkan apakah bentuk berada di atas atau di belakang teks.


**Returns:**
boolean - Nilai yang menunjukkan apakah bentuk berada di atas atau di belakang teks. True jika bentuk berada di belakang teks; jika tidak, false.

### setBehindText(boolean value) {#setBehindText-boolean-}
```
public final void setBehindText(boolean value)
```


Mengatur nilai yang menunjukkan apakah bentuk berada di atas atau di belakang teks.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | boolean | Nilai yang menunjukkan apakah bentuk berada di atas atau di belakang teks. True jika bentuk berada di belakang teks; jika tidak, false. |
|

### getText() {#getText--}
```
public final String getText()
```


Mendapatkan teks dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini.


**Returns:**
java.lang.String - Teks dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Mengatur teks dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | java.lang.String | Teks dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Mendapatkan koleksi fragmen teks terformat dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getImage() {#getImage--}
```
public final WordProcessingWatermarkableImage getImage()
```


Mendapatkan gambar dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini.


**Returns:**
[WordProcessingWatermarkableImage](../../com.groupdocs.watermark.contents/wordprocessingwatermarkableimage) - The image of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` or `null` if the shape has no image.

### setImage(WordProcessingWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.WordProcessingWatermarkableImage-}
```
public final void setImage(WordProcessingWatermarkableImage value)
```


Mengatur gambar dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [WordProcessingWatermarkableImage](../../com.groupdocs.watermark.contents/wordprocessingwatermarkableimage) | Gambar dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` atau `null` jika gambar harus dihapus. |
|

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


Mendapatkan nilai yang menentukan bagaimana bentuk diposisikan secara horizontal.


**Returns:**
int - Nilai perataan horizontal.

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Mendapatkan nilai yang menentukan bagaimana bentuk diposisikan secara vertikal.


**Returns:**
int - Nilai perataan vertikal.

### getRelativeHorizontalPosition() {#getRelativeHorizontalPosition--}
```
public final int getRelativeHorizontalPosition()
```


Mendapatkan nilai yang menentukan ke mana bentuk diposisikan secara horizontal.


**Returns:**
int - Nilai posisi horizontal relatif.

### getRelativeVerticalPosition() {#getRelativeVerticalPosition--}
```
public final int getRelativeVerticalPosition()
```


Mendapatkan nilai yang menentukan ke mana bentuk diposisikan secara vertikal.


**Returns:**
int - Nilai posisi vertikal relatif.

### getImageFillFormat() {#getImageFillFormat--}
```
public final WordProcessingImageFillFormat getImageFillFormat()
```




**Returns:**
[WordProcessingImageFillFormat](../../com.groupdocs.watermark.internal/wordprocessingimagefillformat)
### getAsposeWordsShape() {#getAsposeWordsShape--}
```
public final Shape getAsposeWordsShape()
```




**Returns:**
com.aspose.words.Shape
### getHyperlink() {#getHyperlink--}
```
public final String getHyperlink()
```


Mendapatkan hyperlink yang terkait dengan `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini.


**Returns:**
java.lang.String - Tautan yang terkait dengan `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setHyperlink(String value) {#setHyperlink-java.lang.String-}
```
public final void setHyperlink(String value)
```


Mengatur hyperlink yang terkait dengan `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | java.lang.String | Tautan yang terkait dengan `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Mendapatkan lebar `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini dalam poin.


**Returns:**
double - Lebar dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` dalam poin.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Mengatur lebar `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini dalam poin.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Lebar dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` dalam poin. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Mendapatkan tinggi dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` dalam poin.


**Returns:**
double - Tinggi dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini dalam poin.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Mengatur tinggi dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` dalam poin.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Tinggi dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini dalam poin. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Mendapatkan sudut rotasi dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` dalam derajat.


**Returns:**
double - Sudut rotasi dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini dalam derajat.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Mengatur sudut rotasi dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` dalam derajat.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Sudut rotasi dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini dalam derajat. |
|

### getX() {#getX--}
```
public final double getX()
```


Mendapatkan atau mengatur offset horizontal dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` dari batas kiri halaman dalam poin.


**Returns:**
double - Koordinat x dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Mendapatkan atau mengatur offset horizontal dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` dari batas kiri halaman dalam poin.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Koordinat x dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini. |
|

### getY() {#getY--}
```
public final double getY()
```


Mendapatkan offset vertikal dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` dari batas atas halaman dalam poin.


**Returns:**
double - Koordinat y dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Mengatur offset vertikal dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` dari batas atas halaman dalam poin.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Koordinat y dari `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ini. |
|

### getFormattedTextFragmentsForSearch() {#getFormattedTextFragmentsForSearch--}
```
public FormattedTextFragmentCollection getFormattedTextFragmentsForSearch()
```




**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
### getTextForSearch() {#getTextForSearch--}
```
public String getTextForSearch()
```




**Returns:**
java.lang.String
### setFoundWatermarkText(String value) {#setFoundWatermarkText-java.lang.String-}
```
public void setFoundWatermarkText(String value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageForSearch() {#getImageForSearch--}
```
public WatermarkableImage getImageForSearch()
```




**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### setFoundWatermarkImage(byte[] imageData) {#setFoundWatermarkImage-byte---}
```
public void setFoundWatermarkImage(byte[] imageData)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageData | byte[] |  |

