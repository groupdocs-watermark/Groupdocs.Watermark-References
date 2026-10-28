---
title: "PdfArtifact"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta un artefatto in un contenuto PDF."
type: docs
weight: 54
url: /it/java/com.groupdocs.watermark.contents/pdfartifact/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public class PdfArtifact extends PdfShape
```

Rappresenta un artefatto in un contenuto PDF.

**Lean more**

* [Working with artifacts](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-Workingwithartifacts)

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPage()](#getPage--) | Restituisce la pagina padre di questo `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getText()](#getText--) | Restituisce il testo di questo `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Imposta il testo di questo `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getArtifactType()](#getArtifactType--) | Restituisce il tipo di questo `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getArtifactSubtype()](#getArtifactSubtype--) | Restituisce il sottotipo di questo `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getOpacity()](#getOpacity--) | Restituisce l'opacità di questo `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getX()](#getX--) | Restituisce lo spostamento orizzontale di questo `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` dal bordo sinistro della pagina in punti. |
|
|  | [getY()](#getY--) | Restituisce lo spostamento verticale di questo `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` dal bordo inferiore della pagina in punti. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Restituisce l'angolo di rotazione di questo `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` in gradi. |
|
|  | [getWidth()](#getWidth--) | Restituisce la larghezza di questo `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` in punti. |
|
|  | [getHeight()](#getHeight--) | Restituisce l'altezza di questo `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` in punti. |
|
|  | [getAsposePdfArtifact()](#getAsposePdfArtifact--) | <br /> |

|
|  | [getOuterForm()](#getOuterForm--) | <br /> |

|
### getPage() {#getPage--}
```
public final PdfPage getPage()
```


Restituisce la pagina padre di questo `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getText() {#getText--}
```
public String getText()
```


Restituisce il testo di questo `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Returns:**
java.lang.String - Il testo di questo `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Imposta il testo di questo `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | java.lang.String | Il testo di questo `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|

### getArtifactType() {#getArtifactType--}
```
public final int getArtifactType()
```


Restituisce il tipo di questo `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Returns:**
int - Il tipo di questo `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getArtifactSubtype() {#getArtifactSubtype--}
```
public final int getArtifactSubtype()
```


Restituisce il sottotipo di questo `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Returns:**
int - Il sottotipo di questo `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Restituisce l'opacità di questo `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

I valori possibili sono nell'intervallo [0, 1].


**Returns:**
double - L'opacità di questo `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getX() {#getX--}
```
public double getX()
```


Restituisce lo spostamento orizzontale di questo `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` dal bordo sinistro della pagina in punti.


**Returns:**
double - La coordinata x di questo `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getY() {#getY--}
```
public double getY()
```


Restituisce lo spostamento verticale di questo `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` dal bordo inferiore della pagina in punti.


**Returns:**
double - La coordinata y di questo `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Restituisce l'angolo di rotazione di questo `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` in gradi.


**Returns:**
double - L'angolo di rotazione di questo `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` in gradi.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Restituisce la larghezza di questo `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` in punti.


**Returns:**
double - La larghezza di questo `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` in punti.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Restituisce l'altezza di questo `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` in punti.


**Returns:**
double - L'altezza di questo `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` in punti.

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
