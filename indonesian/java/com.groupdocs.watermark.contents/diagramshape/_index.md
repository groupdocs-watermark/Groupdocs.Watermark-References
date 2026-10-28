---
title: "DiagramShape"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili bentuk gambar dalam dokumen Visio."
type: docs
weight: 24
url: /id/java/com.groupdocs.watermark.contents/diagramshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public class DiagramShape extends ShapeSearchAdapter implements IRotatableTwoDObject
```

Mewakili bentuk gambar dalam dokumen Visio.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
|  | [getPage()](#getPage--) | Mendapatkan halaman induk dari `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini. |
|
|  | [getWidth()](#getWidth--) | Mendapatkan lebar `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini dalam poin. |
|
|  | [setWidth(double value)](#setWidth-double-) | Mengatur lebar `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini dalam poin. |
|
|  | [getHeight()](#getHeight--) | Mendapatkan tinggi `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini dalam poin. |
|
|  | [setHeight(double value)](#setHeight-double-) | Mengatur tinggi `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini dalam poin. |
|
|  | [getX()](#getX--) | Mendapatkan offset horizontal `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini dari batas kiri halaman dalam poin. |
|
|  | [setX(double value)](#setX-double-) | Mengatur offset horizontal `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini dari batas kiri halaman dalam poin. |
|
|  | [getY()](#getY--) | Mendapatkan offset vertikal `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini dari batas bawah halaman dalam poin. |
|
|  | [setY(double value)](#setY-double-) | Mengatur offset vertikal `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini dari batas bawah halaman dalam poin. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Mendapatkan atau mengatur sudut rotasi `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini dalam derajat. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Mendapatkan atau mengatur sudut rotasi `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini dalam derajat. |
|
|  | [getText()](#getText--) | Mendapatkan atau mengatur teks `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Mendapatkan atau mengatur teks `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Mendapatkan koleksi fragmen teks terformat dari `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini. |
|
|  | [getImage()](#getImage--) | Mendapatkan gambar `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini. |
|
|  | [setImage(DiagramWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.DiagramWatermarkableImage-) | Mengatur gambar `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini. |
|
|  | [getId()](#getId--) | Mendapatkan pengidentifikasi `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini. |
|
|  | [getName()](#getName--) | Mendapatkan nama `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini. |
|
|  | [getHyperlinks()](#getHyperlinks--) | Mendapatkan koleksi hyperlink yang terlampir pada `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini. |
|
|  | [getAsposeShape()](#getAsposeShape--) | <br /> |

|
|  | [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) | <br /> |

|
|  | [getImageForSearch()](#getImageForSearch--) | <br /> |

|
|  | [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) | <br /> |

|
|  | [getTextForSearch()](#getTextForSearch--) | <br /> |

|
|  | [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) | <br /> |

|
### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```




**Returns:**
java.lang.Integer
### getPage() {#getPage--}
```
public final DiagramPage getPage()
```


Mendapatkan halaman induk dari `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini.


**Returns:**
[DiagramPage](../../com.groupdocs.watermark.contents/diagrampage) - The parent page of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Mendapatkan lebar `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini dalam poin.


**Returns:**
double - Lebar `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini dalam poin.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Mengatur lebar `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini dalam poin.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Lebar `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini dalam poin. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Mendapatkan tinggi `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini dalam poin.


**Returns:**
double - Tinggi `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini dalam poin.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Mengatur tinggi `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini dalam poin.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Tinggi `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini dalam poin. |
|

### getX() {#getX--}
```
public final double getX()
```


Mendapatkan offset horizontal `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini dari batas kiri halaman dalam poin.


**Returns:**
double - Offset horizontal `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini dari batas kiri halaman dalam poin.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Mengatur offset horizontal `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini dari batas kiri halaman dalam poin.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Offset horizontal `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini dari batas kiri halaman dalam poin. |
|

### getY() {#getY--}
```
public final double getY()
```


Mendapatkan offset vertikal `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini dari batas bawah halaman dalam poin.


**Returns:**
double - Offset vertikal `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini dari batas bawah halaman dalam poin.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Mengatur offset vertikal `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini dari batas bawah halaman dalam poin.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Offset vertikal `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini dari batas bawah halaman dalam poin. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Mendapatkan atau mengatur sudut rotasi `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini dalam derajat.


**Returns:**
double - Sudut rotasi dari `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` dalam derajat.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Mendapatkan atau mengatur sudut rotasi `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini dalam derajat.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Sudut rotasi dari `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` dalam derajat. |
|

### getText() {#getText--}
```
public final String getText()
```


Mendapatkan atau mengatur teks `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini.


**Returns:**
java.lang.String - Teks dari `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Mendapatkan atau mengatur teks `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | java.lang.String | Teks dari `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Mendapatkan koleksi fragmen teks terformat dari `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getImage() {#getImage--}
```
public final DiagramWatermarkableImage getImage()
```


Mendapatkan gambar `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini.


**Returns:**
[DiagramWatermarkableImage](../../com.groupdocs.watermark.contents/diagramwatermarkableimage) - The image of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### setImage(DiagramWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.DiagramWatermarkableImage-}
```
public final void setImage(DiagramWatermarkableImage value)
```


Mengatur gambar `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [DiagramWatermarkableImage](../../com.groupdocs.watermark.contents/diagramwatermarkableimage) | Gambar dari `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|

### getId() {#getId--}
```
public final long getId()
```


Mendapatkan pengidentifikasi `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini.


**Returns:**
long - Pengidentifikasi dari `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getName() {#getName--}
```
public final String getName()
```


Mendapatkan nama `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini.


**Returns:**
java.lang.String - Nama dari `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getHyperlinks() {#getHyperlinks--}
```
public final DiagramHyperlinkCollection getHyperlinks()
```


Mendapatkan koleksi hyperlink yang terlampir pada `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` ini.


**Returns:**
[DiagramHyperlinkCollection](../../com.groupdocs.watermark.contents/diagramhyperlinkcollection) - The collection of hyperlinks attached to this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getAsposeShape() {#getAsposeShape--}
```
public final Shape getAsposeShape()
```


<br />



**Returns:**
com.aspose.diagram.Shape
### getFormattedTextFragmentsForSearch() {#getFormattedTextFragmentsForSearch--}
```
public FormattedTextFragmentCollection getFormattedTextFragmentsForSearch()
```


<br />



**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
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

