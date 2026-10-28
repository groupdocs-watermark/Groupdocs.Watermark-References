---
title: "PdfXObject"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل كائن XObject في مستند pdf."
type: docs
weight: 75
url: /ar/java/com.groupdocs.watermark.contents/pdfxobject/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public abstract class PdfXObject extends PdfShape
```

يمثل كائن XObject في مستند pdf.

**Learn more:**

* [Working with XObjects](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-WorkingwithXObjects)

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPage()](#getPage--) | يحصل على الصفحة الأصلية لهذا `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`. |
|
|  | [getX()](#getX--) | يحصل على الإزاحة الأفقية لهذا `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` من الحد الأيسر للصفحة بالنقاط. |
|
|  | [getY()](#getY--) | يحصل على الإزاحة العمودية لهذا `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` من الحد السفلي للصفحة بالنقاط. |
|
|  | [getWidth()](#getWidth--) | يحصل على عرض هذا `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` بالنقاط. |
|
|  | [getHeight()](#getHeight--) | يحصل على ارتفاع هذا `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` بالنقاط. |
|
|  | [getRotateAngle()](#getRotateAngle--) | يحصل على زاوية الدوران لهذا `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` بالدرجات. |
|
|  | [getMatrix()](#getMatrix--) | <br /> |

|
### getPage() {#getPage--}
```
public final PdfPage getPage()
```


يحصل على الصفحة الأصلية لهذا `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.

### getX() {#getX--}
```
public double getX()
```


يحصل على الإزاحة الأفقية لهذا `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` من الحد الأيسر للصفحة بالنقاط.


**Returns:**
double - إحداثي x لهذا `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.

### getY() {#getY--}
```
public double getY()
```


يحصل على الإزاحة العمودية لهذا `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` من الحد السفلي للصفحة بالنقاط.


**Returns:**
double - إحداثي y لهذا `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


يحصل على عرض هذا `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` بالنقاط.


**Returns:**
double - عرض هذا `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` بالنقاط.

### getHeight() {#getHeight--}
```
public double getHeight()
```


يحصل على ارتفاع هذا `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` بالنقاط.


**Returns:**
double - ارتفاع هذا `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` بالنقاط.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


يحصل على زاوية الدوران لهذا `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` بالدرجات.


**Returns:**
double - زاوية الدوران لهذا `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` بالدرجات.

### getMatrix() {#getMatrix--}
```
public final Matrix getMatrix()
```


<br />



**Returns:**
com.aspose.pdf.Matrix
