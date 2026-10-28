---
title: "PdfAnnotation"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta un'annotazione in un documento PDF."
type: docs
weight: 51
url: /it/java/com.groupdocs.watermark.contents/pdfannotation/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public class PdfAnnotation extends PdfShape
```

Rappresenta un'annotazione in un documento PDF.

**Learn more:**

* [Working with annotations](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-Workingwithannotations)

## Campi

| Campo | Descrizione |
| --- | --- |
|  | [NormalAppearanceKey](#NormalAppearanceKey) | <br /> |

|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPage()](#getPage--) | Restituisce la pagina genitore di questo `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`. |
|
|  | [getAnnotationType()](#getAnnotationType--) | Restituisce il tipo di questo `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`. |
|
|  | [getX()](#getX--) | Restituisce lo spostamento orizzontale di questo `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` dal bordo sinistro della pagina in punti. |
|
|  | [getY()](#getY--) | Restituisce lo spostamento verticale di questo `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` dal bordo inferiore del foglio di lavoro in punti. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Restituisce l'angolo di rotazione di questo `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` in gradi. |
|
|  | [getWidth()](#getWidth--) | Restituisce la larghezza di questo `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` in punti. |
|
|  | [getHeight()](#getHeight--) | Restituisce l'altezza di questo `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` in punti. |
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


Restituisce la pagina genitore di questo `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.

### getAnnotationType() {#getAnnotationType--}
```
public final int getAnnotationType()
```


Restituisce il tipo di questo `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.


**Returns:**
int - Il tipo di questo `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.

### getX() {#getX--}
```
public double getX()
```


Restituisce lo spostamento orizzontale di questo `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` dal bordo sinistro della pagina in punti.


**Returns:**
double - Lo spostamento orizzontale di questo `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` dal bordo sinistro della pagina in punti.

### getY() {#getY--}
```
public double getY()
```


Restituisce lo spostamento verticale di questo `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` dal bordo inferiore del foglio di lavoro in punti.


**Returns:**
double - Lo spostamento verticale di questo `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` dal bordo inferiore del foglio di lavoro in punti.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Restituisce l'angolo di rotazione di questo `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` in gradi.


**Returns:**
double - L'angolo di rotazione di questo `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` in gradi.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Restituisce la larghezza di questo `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` in punti.


**Returns:**
double - La larghezza di questo `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` in punti.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Restituisce l'altezza di questo `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` in punti.


**Returns:**
double - L'altezza di questo `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` in punti.

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
