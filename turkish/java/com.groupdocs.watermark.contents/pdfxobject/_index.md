---
title: "PdfXObject"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Bir pdf belgesindeki XObject'i temsil eder."
type: docs
weight: 75
url: /tr/java/com.groupdocs.watermark.contents/pdfxobject/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public abstract class PdfXObject extends PdfShape
```

Bir pdf belgesindeki XObject'i temsil eder.

**Learn more:**

* [Working with XObjects](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-WorkingwithXObjects)

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPage()](#getPage--) | Bu `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` nesnesinin üst sayfasını alır. |
|
|  | [getX()](#getX--) | Bu `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` nesnesinin sayfa sol kenarından puan cinsinden yatay kaymasını alır. |
|
|  | [getY()](#getY--) | Bu `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` nesnesinin sayfa alt kenarından puan cinsinden dikey kaymasını alır. |
|
|  | [getWidth()](#getWidth--) | Bu `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` nesnesinin genişliğini puan cinsinden alır. |
|
|  | [getHeight()](#getHeight--) | Bu `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` nesnesinin yüksekliğini puan cinsinden alır. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Bu `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` nesnesinin döndürme açısını derece cinsinden alır. |
|
|  | [getMatrix()](#getMatrix--) | <br /> |

|
### getPage() {#getPage--}
```
public final PdfPage getPage()
```


Bu `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` nesnesinin üst sayfasını alır.


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.

### getX() {#getX--}
```
public double getX()
```


Bu `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` nesnesinin sayfa sol kenarından puan cinsinden yatay kaymasını alır.


**Returns:**
double - Bu `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` nesnesinin x koordinatı.

### getY() {#getY--}
```
public double getY()
```


Bu `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` nesnesinin sayfa alt kenarından puan cinsinden dikey kaymasını alır.


**Returns:**
double - Bu `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` nesnesinin y koordinatı.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Bu `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` nesnesinin genişliğini puan cinsinden alır.


**Returns:**
double - Bu `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` nesnesinin genişliği puan cinsinden.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Bu `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` nesnesinin yüksekliğini puan cinsinden alır.


**Returns:**
double - Bu `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` nesnesinin yüksekliği puan cinsinden.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Bu `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` nesnesinin döndürme açısını derece cinsinden alır.


**Returns:**
double - Bu `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` nesnesinin döndürme açısı derece cinsinden.

### getMatrix() {#getMatrix--}
```
public final Matrix getMatrix()
```


<br />



**Returns:**
com.aspose.pdf.Matrix
