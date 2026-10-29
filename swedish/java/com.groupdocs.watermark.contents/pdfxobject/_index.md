---
title: "PdfXObject"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar ett XObject i ett pdf-dokument."
type: docs
weight: 75
url: /sv/java/com.groupdocs.watermark.contents/pdfxobject/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public abstract class PdfXObject extends PdfShape
```

Representerar ett XObject i ett pdf-dokument.

**Learn more:**

* [Working with XObjects](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-WorkingwithXObjects)

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPage()](#getPage--) | Hämtar föräldrasidan för detta `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`. |
|
|  | [getX()](#getX--) | Hämtar den horisontella förskjutningen för detta `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` från sidans vänstra kant i punkter. |
|
|  | [getY()](#getY--) | Hämtar den vertikala förskjutningen för detta `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` från sidans nedre kant i punkter. |
|
|  | [getWidth()](#getWidth--) | Hämtar bredden på detta `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` i punkter. |
|
|  | [getHeight()](#getHeight--) | Hämtar höjden på detta `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` i punkter. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Hämtar rotationsvinkeln för detta `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` i grader. |
|
|  | [getMatrix()](#getMatrix--) | <br /> |

|
### getPage() {#getPage--}
```
public final PdfPage getPage()
```


Hämtar föräldrasidan för detta `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.

### getX() {#getX--}
```
public double getX()
```


Hämtar den horisontella förskjutningen för detta `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` från sidans vänstra kant i punkter.


**Returns:**
double - X-koordinaten för detta `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.

### getY() {#getY--}
```
public double getY()
```


Hämtar den vertikala förskjutningen för detta `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` från sidans nedre kant i punkter.


**Returns:**
double - Y-koordinaten för detta `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Hämtar bredden på detta `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` i punkter.


**Returns:**
double - Bredden för detta `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` i punkter.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Hämtar höjden på detta `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` i punkter.


**Returns:**
double - Höjden för detta `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` i punkter.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Hämtar rotationsvinkeln för detta `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` i grader.


**Returns:**
double - Rotationsvinkeln för detta `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` i grader.

### getMatrix() {#getMatrix--}
```
public final Matrix getMatrix()
```


<br />



**Returns:**
com.aspose.pdf.Matrix
