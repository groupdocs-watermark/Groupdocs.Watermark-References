---
title: "PdfAnnotation"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar en annotation i ett pdf-dokument."
type: docs
weight: 51
url: /sv/java/com.groupdocs.watermark.contents/pdfannotation/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public class PdfAnnotation extends PdfShape
```

Representerar en annotation i ett pdf-dokument.

**Learn more:**

* [Working with annotations](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-Workingwithannotations)

## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [NormalAppearanceKey](#NormalAppearanceKey) | <br /> |

|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPage()](#getPage--) | Hämtar föräldrasidan för detta `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`. |
|
|  | [getAnnotationType()](#getAnnotationType--) | Hämtar typen av detta `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`. |
|
|  | [getX()](#getX--) | Hämtar den horisontella förskjutningen för detta `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` från sidans vänstra kant i punkter. |
|
|  | [getY()](#getY--) | Hämtar det vertikala offsetet för detta `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` från kalkylbladets nedre kant i punkter. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Hämtar rotationsvinkeln för detta `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` i grader. |
|
|  | [getWidth()](#getWidth--) | Hämtar bredden på detta `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` i punkter. |
|
|  | [getHeight()](#getHeight--) | Hämtar höjden på detta `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` i punkter. |
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


Hämtar föräldrasidan för detta `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.

### getAnnotationType() {#getAnnotationType--}
```
public final int getAnnotationType()
```


Hämtar typen av detta `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.


**Returns:**
int - Typen av detta `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.

### getX() {#getX--}
```
public double getX()
```


Hämtar den horisontella förskjutningen för detta `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` från sidans vänstra kant i punkter.


**Returns:**
double - Det horisontella offsetet för detta `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` från sidans vänstra kant i punkter.

### getY() {#getY--}
```
public double getY()
```


Hämtar det vertikala offsetet för detta `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` från kalkylbladets nedre kant i punkter.


**Returns:**
double - Det vertikala offsetet för detta `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` från kalkylbladets nedre kant i punkter.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Hämtar rotationsvinkeln för detta `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` i grader.


**Returns:**
double - Rotationsvinkeln för detta `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` i grader.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Hämtar bredden på detta `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` i punkter.


**Returns:**
double - Bredden på detta `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` i punkter.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Hämtar höjden på detta `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` i punkter.


**Returns:**
double - Höjden på detta `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` i punkter.

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
