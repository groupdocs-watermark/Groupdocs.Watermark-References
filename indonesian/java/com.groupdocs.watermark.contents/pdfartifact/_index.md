---
title: "PdfArtifact"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili artefak dalam konten pdf."
type: docs
weight: 54
url: /id/java/com.groupdocs.watermark.contents/pdfartifact/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public class PdfArtifact extends PdfShape
```

Mewakili artefak dalam konten pdf.

**Lean more**

* [Working with artifacts](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-Workingwithartifacts)

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getPage()](#getPage--) | Mendapatkan halaman induk dari `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ini. |
|
|  | [getText()](#getText--) | Mendapatkan teks dari `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ini. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Mengatur teks dari `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ini. |
|
|  | [getArtifactType()](#getArtifactType--) | Mendapatkan tipe dari `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ini. |
|
|  | [getArtifactSubtype()](#getArtifactSubtype--) | Mendapatkan subtipe dari `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ini. |
|
|  | [getOpacity()](#getOpacity--) | Mendapatkan opasitas dari `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ini. |
|
|  | [getX()](#getX--) | Mendapatkan offset horizontal dari `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ini dari batas kiri halaman dalam poin. |
|
|  | [getY()](#getY--) | Mendapatkan offset vertikal dari `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ini dari batas bawah halaman dalam poin. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Mendapatkan sudut rotasi dari `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ini dalam derajat. |
|
|  | [getWidth()](#getWidth--) | Mendapatkan lebar dari `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ini dalam poin. |
|
|  | [getHeight()](#getHeight--) | Mendapatkan tinggi dari `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ini dalam poin. |
|
|  | [getAsposePdfArtifact()](#getAsposePdfArtifact--) | <br /> |

|
|  | [getOuterForm()](#getOuterForm--) | <br /> |

|
### getPage() {#getPage--}
```
public final PdfPage getPage()
```


Mendapatkan halaman induk dari `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ini.


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getText() {#getText--}
```
public String getText()
```


Mendapatkan teks dari `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ini.


**Returns:**
java.lang.String - Teks dari `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ini.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Mengatur teks dari `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ini.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | java.lang.String | Teks dari `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ini. |
|

### getArtifactType() {#getArtifactType--}
```
public final int getArtifactType()
```


Mendapatkan tipe dari `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ini.


**Returns:**
int - Tipe dari `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ini.

### getArtifactSubtype() {#getArtifactSubtype--}
```
public final int getArtifactSubtype()
```


Mendapatkan subtipe dari `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ini.


**Returns:**
int - Subtipe dari `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ini.

### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Mendapatkan opasitas dari `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ini.

Nilai yang mungkin berada dalam rentang [0, 1].


**Returns:**
double - Opasitas dari `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ini.

### getX() {#getX--}
```
public double getX()
```


Mendapatkan offset horizontal dari `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ini dari batas kiri halaman dalam poin.


**Returns:**
double - Koordinat x dari `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ini.

### getY() {#getY--}
```
public double getY()
```


Mendapatkan offset vertikal dari `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ini dari batas bawah halaman dalam poin.


**Returns:**
double - Koordinat y dari `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ini.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Mendapatkan sudut rotasi dari `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ini dalam derajat.


**Returns:**
double - Sudut rotasi dari `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ini dalam derajat.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Mendapatkan lebar dari `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ini dalam poin.


**Returns:**
double - Lebar dari `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ini dalam poin.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Mendapatkan tinggi dari `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ini dalam poin.


**Returns:**
double - Tinggi dari `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ini dalam poin.

### getAsposePdfArtifact() {#getAsposePdfArtifact--}
```
public final Artifact getAsposePdfArtifact()
```


<br />



**Returns:**
com.aspose.pdf.Artifact
### getOuterForm() {#getOuterForm--}
```
public XForm getOuterForm()
```


<br />



**Returns:**
com.aspose.pdf.XForm
