---
title: "PdfXObject"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili sebuah XObject dalam dokumen pdf."
type: docs
weight: 75
url: /id/java/com.groupdocs.watermark.contents/pdfxobject/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public abstract class PdfXObject extends PdfShape
```

Mewakili sebuah XObject dalam dokumen pdf.

**Learn more:**

* [Working with XObjects](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-WorkingwithXObjects)

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getPage()](#getPage--) | Mendapatkan halaman induk dari `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` ini. |
|
|  | [getX()](#getX--) | Mendapatkan offset horizontal dari `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` ini dari batas kiri halaman dalam poin. |
|
|  | [getY()](#getY--) | Mendapatkan offset vertikal dari `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` ini dari batas bawah halaman dalam poin. |
|
|  | [getWidth()](#getWidth--) | Mendapatkan lebar `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` ini dalam poin. |
|
|  | [getHeight()](#getHeight--) | Mendapatkan tinggi `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` ini dalam poin. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Mendapatkan sudut rotasi `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` ini dalam derajat. |
|
|  | [getMatrix()](#getMatrix--) | <br /> |

|
### getPage() {#getPage--}
```
public final PdfPage getPage()
```


Mendapatkan halaman induk dari `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` ini.


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.

### getX() {#getX--}
```
public double getX()
```


Mendapatkan offset horizontal dari `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` ini dari batas kiri halaman dalam poin.


**Returns:**
double - Koordinat x dari `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` ini.

### getY() {#getY--}
```
public double getY()
```


Mendapatkan offset vertikal dari `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` ini dari batas bawah halaman dalam poin.


**Returns:**
double - Koordinat y dari `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` ini.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Mendapatkan lebar `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` ini dalam poin.


**Returns:**
double - Lebar `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` ini dalam poin.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Mendapatkan tinggi `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` ini dalam poin.


**Returns:**
double - Tinggi `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` ini dalam poin.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Mendapatkan sudut rotasi `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` ini dalam derajat.


**Returns:**
double - Sudut rotasi `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` ini dalam derajat.

### getMatrix() {#getMatrix--}
```
public final Matrix getMatrix()
```


<br />



**Returns:**
com.aspose.pdf.Matrix
