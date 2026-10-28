---
title: "PdfXObject"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt een XObject voor in een pdf-document."
type: docs
weight: 75
url: /nl/java/com.groupdocs.watermark.contents/pdfxobject/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public abstract class PdfXObject extends PdfShape
```

Stelt een XObject voor in een pdf-document.

**Learn more:**

* [Working with XObjects](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-WorkingwithXObjects)

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPage()](#getPage--) | Haalt de bovenliggende pagina van dit `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` op. |
|
|  | [getX()](#getX--) | Haalt de horizontale offset van dit `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` vanaf de linkerrand van de pagina op in punten. |
|
|  | [getY()](#getY--) | Haalt de verticale offset van dit `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` vanaf de onderrand van de pagina op in punten. |
|
|  | [getWidth()](#getWidth--) | Haalt de breedte van dit `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` op in punten. |
|
|  | [getHeight()](#getHeight--) | Haalt de hoogte van dit `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` op in punten. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Haalt de rotatiehoek van dit `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` op in graden. |
|
|  | [getMatrix()](#getMatrix--) | <br /> |

|
### getPage() {#getPage--}
```
public final PdfPage getPage()
```


Haalt de bovenliggende pagina van dit `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` op.


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.

### getX() {#getX--}
```
public double getX()
```


Haalt de horizontale offset van dit `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` vanaf de linkerrand van de pagina op in punten.


**Returns:**
double - De x-coördinaat van dit `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.

### getY() {#getY--}
```
public double getY()
```


Haalt de verticale offset van dit `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` vanaf de onderrand van de pagina op in punten.


**Returns:**
double - De y-coördinaat van dit `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Haalt de breedte van dit `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` op in punten.


**Returns:**
double - De breedte van dit `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` in punten.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Haalt de hoogte van dit `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` op in punten.


**Returns:**
double - De hoogte van dit `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` in punten.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Haalt de rotatiehoek van dit `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` op in graden.


**Returns:**
double - De rotatiehoek van dit `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` in graden.

### getMatrix() {#getMatrix--}
```
public final Matrix getMatrix()
```


<br />



**Returns:**
com.aspose.pdf.Matrix
