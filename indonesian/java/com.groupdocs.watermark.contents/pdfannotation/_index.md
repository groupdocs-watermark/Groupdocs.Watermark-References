---
title: "PdfAnnotation"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili anotasi dalam dokumen pdf."
type: docs
weight: 51
url: /id/java/com.groupdocs.watermark.contents/pdfannotation/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public class PdfAnnotation extends PdfShape
```

Mewakili anotasi dalam dokumen pdf.

**Learn more:**

* [Working with annotations](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-Workingwithannotations)

## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [NormalAppearanceKey](#NormalAppearanceKey) | <br /> |

|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getPage()](#getPage--) | Mendapatkan halaman induk dari `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` ini. |
|
|  | [getAnnotationType()](#getAnnotationType--) | Mendapatkan tipe dari `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` ini. |
|
|  | [getX()](#getX--) | Mendapatkan offset horizontal dari `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` ini dari batas kiri halaman dalam poin. |
|
|  | [getY()](#getY--) | Mendapatkan offset vertikal dari `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` ini dari batas bawah lembar kerja dalam poin. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Mendapatkan sudut rotasi dari `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` ini dalam derajat. |
|
|  | [getWidth()](#getWidth--) | Mendapatkan lebar dari `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` ini dalam poin. |
|
|  | [getHeight()](#getHeight--) | Mendapatkan tinggi dari `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` ini dalam poin. |
|
|  | [getAsposePdfAnnotation()](#getAsposePdfAnnotation--) | <br /> |

|
|  | [getOuterForm()](#getOuterForm--) | <br /> |

|
### NormalAppearanceKey {#NormalAppearanceKey}
```
public static final String NormalAppearanceKey
```


<br />



### getPage() {#getPage--}
```
public final PdfPage getPage()
```


Mendapatkan halaman induk dari `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` ini.


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.

### getAnnotationType() {#getAnnotationType--}
```
public final int getAnnotationType()
```


Mendapatkan tipe dari `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` ini.


**Returns:**
int - Tipe dari `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` ini.

### getX() {#getX--}
```
public double getX()
```


Mendapatkan offset horizontal dari `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` ini dari batas kiri halaman dalam poin.


**Returns:**
double - Offset horizontal dari `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` ini dari batas kiri halaman dalam poin.

### getY() {#getY--}
```
public double getY()
```


Mendapatkan offset vertikal dari `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` ini dari batas bawah lembar kerja dalam poin.


**Returns:**
double - Offset vertikal dari `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` ini dari batas bawah lembar kerja dalam poin.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Mendapatkan sudut rotasi dari `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` ini dalam derajat.


**Returns:**
double - Sudut rotasi dari `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` ini dalam derajat.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Mendapatkan lebar dari `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` ini dalam poin.


**Returns:**
double - Lebar dari `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` ini dalam poin.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Mendapatkan tinggi dari `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` ini dalam poin.


**Returns:**
double - Tinggi dari `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` ini dalam poin.

### getAsposePdfAnnotation() {#getAsposePdfAnnotation--}
```
public final Annotation getAsposePdfAnnotation()
```


<br />



**Returns:**
com.aspose.pdf.Annotation
### getOuterForm() {#getOuterForm--}
```
public XForm getOuterForm()
```


<br />



**Returns:**
com.aspose.pdf.XForm
