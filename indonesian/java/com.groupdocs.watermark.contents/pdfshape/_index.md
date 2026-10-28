---
title: "PdfShape"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Menyediakan kelas dasar untuk XObjects Artifacts dan Annotations."
type: docs
weight: 69
url: /id/java/com.groupdocs.watermark.contents/pdfshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public abstract class PdfShape extends ShapeSearchAdapter implements IRotatableTwoDObject
```

Menyediakan kelas dasar untuk XObjects, Artifacts, dan Annotations.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getText()](#getText--) | Mendapatkan teks dari `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` ini. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Mendapatkan atau mengatur teks dari `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` ini. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Mendapatkan koleksi fragmen teks terformat dari `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` ini. |
|
|  | [getImage()](#getImage--) | Mendapatkan gambar dari `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` ini. |
|
|  | [setImage(PdfWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.PdfWatermarkableImage-) | Mengatur gambar dari `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` ini. |
|
|  | [getX()](#getX--) | Mendapatkan koordinat x dari objek. |
|
|  | [getY()](#getY--) | Mendapatkan koordinat y dari objek. |
|
|  | [getWidth()](#getWidth--) | Mendapatkan lebar objek. |
|
|  | [getHeight()](#getHeight--) | Mendapatkan tinggi objek. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Mendapatkan sudut rotasi objek dalam derajat. |
|
|  | [getOuterForm()](#getOuterForm--) | <br /> |

|
|  | [extractImageAppearance()](#extractImageAppearance--) | <br /> |

|
|  | [getTextForSearch()](#getTextForSearch--) | <br /> |

|
|  | [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) | <br /> |

|
|  | [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) | <br /> |

|
|  | [getImageForSearch()](#getImageForSearch--) | <br /> |

|
|  | [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) | <br /> |

|
### getText() {#getText--}
```
public String getText()
```


Mendapatkan teks dari `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` ini.


**Returns:**
java.lang.String - Teks dari `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` ini.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Mendapatkan atau mengatur teks dari `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` ini.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | java.lang.String | Teks dari `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` ini. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Mendapatkan koleksi fragmen teks terformat dari `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` ini.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.

### getImage() {#getImage--}
```
public final PdfWatermarkableImage getImage()
```


Mendapatkan gambar dari `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` ini.


**Returns:**
[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage) - The image of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.

### setImage(PdfWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.PdfWatermarkableImage-}
```
public final void setImage(PdfWatermarkableImage value)
```


Mengatur gambar dari `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` ini.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage) | Gambar dari `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` ini. |
|

### getX() {#getX--}
```
public abstract double getX()
```


Mendapatkan koordinat x dari objek.


**Returns:**
double - Koordinat x dari objek.

### getY() {#getY--}
```
public abstract double getY()
```


Mendapatkan koordinat y dari objek.


**Returns:**
double - Koordinat y dari objek.

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Mendapatkan lebar objek.


**Returns:**
double - Lebar objek.

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Mendapatkan tinggi objek.


**Returns:**
double - Tinggi objek.

### getRotateAngle() {#getRotateAngle--}
```
public abstract double getRotateAngle()
```


Mendapatkan sudut rotasi objek dalam derajat.


**Returns:**
double - Sudut rotasi objek dalam derajat.

### getOuterForm() {#getOuterForm--}
```
public abstract XForm getOuterForm()
```


<br />



**Returns:**
com.aspose.pdf.XForm
### extractImageAppearance() {#extractImageAppearance--}
```
public PdfXImageAppearance extractImageAppearance()
```


<br />



**Returns:**
[PdfXImageAppearance](../../com.groupdocs.watermark.internal/pdfximageappearance)
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

