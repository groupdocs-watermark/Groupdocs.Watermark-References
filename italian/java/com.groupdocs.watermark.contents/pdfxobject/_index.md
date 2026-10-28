---
title: "PdfXObject"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta un XObject in un documento pdf."
type: docs
weight: 75
url: /it/java/com.groupdocs.watermark.contents/pdfxobject/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public abstract class PdfXObject extends PdfShape
```

Rappresenta un XObject in un documento pdf.

**Learn more:**

* [Working with XObjects](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-WorkingwithXObjects)

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPage()](#getPage--) | Ottiene la pagina padre di questo `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`. |
|
|  | [getX()](#getX--) | Ottiene lo spostamento orizzontale di questo `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` dal bordo sinistro della pagina in punti. |
|
|  | [getY()](#getY--) | Ottiene lo spostamento verticale di questo `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` dal bordo inferiore della pagina in punti. |
|
|  | [getWidth()](#getWidth--) | Ottiene la larghezza di questo `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` in punti. |
|
|  | [getHeight()](#getHeight--) | Ottiene l'altezza di questo `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` in punti. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Ottiene l'angolo di rotazione di questo `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` in gradi. |
|
|  | [getMatrix()](#getMatrix--) | <br /> |

|
### getPage() {#getPage--}
```
public final PdfPage getPage()
```


Ottiene la pagina padre di questo `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.

### getX() {#getX--}
```
public double getX()
```


Ottiene lo spostamento orizzontale di questo `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` dal bordo sinistro della pagina in punti.


**Returns:**
double - La coordinata x di questo `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.

### getY() {#getY--}
```
public double getY()
```


Ottiene lo spostamento verticale di questo `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` dal bordo inferiore della pagina in punti.


**Returns:**
double - La coordinata y di questo `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Ottiene la larghezza di questo `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` in punti.


**Returns:**
double - La larghezza di questo `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` in punti.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Ottiene l'altezza di questo `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` in punti.


**Returns:**
double - L'altezza di questo `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` in punti.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Ottiene l'angolo di rotazione di questo `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` in gradi.


**Returns:**
double - L'angolo di rotazione di questo `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` in gradi.

### getMatrix() {#getMatrix--}
```
public final Matrix getMatrix()
```


<br />



**Returns:**
com.aspose.pdf.Matrix
