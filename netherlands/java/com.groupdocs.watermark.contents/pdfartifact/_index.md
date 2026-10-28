---
title: "PdfArtifact"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt een artefact in pdf-inhoud voor."
type: docs
weight: 54
url: /nl/java/com.groupdocs.watermark.contents/pdfartifact/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public class PdfArtifact extends PdfShape
```

Stelt een artefact in pdf-inhoud voor.

**Lean more**

* [Working with artifacts](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-Workingwithartifacts)

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPage()](#getPage--) | Haalt de bovenliggende pagina van dit `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` op. |
|
|  | [getText()](#getText--) | Haalt de tekst van dit `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` op. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Stelt de tekst van dit `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` in. |
|
|  | [getArtifactType()](#getArtifactType--) | Haalt het type van dit `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` op. |
|
|  | [getArtifactSubtype()](#getArtifactSubtype--) | Haalt de subtype van dit `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` op. |
|
|  | [getOpacity()](#getOpacity--) | Haalt de doorzichtigheid van dit `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` op. |
|
|  | [getX()](#getX--) | Haalt de horizontale offset van dit `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ten opzichte van de linkerrand van de pagina op in punten. |
|
|  | [getY()](#getY--) | Haalt de verticale offset van dit `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ten opzichte van de onderrand van de pagina op in punten. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Haalt de rotatiehoek van dit `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` op in graden. |
|
|  | [getWidth()](#getWidth--) | Haalt de breedte van dit `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` op in punten. |
|
|  | [getHeight()](#getHeight--) | Haalt de hoogte van dit `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` op in punten. |
|
|  | [getAsposePdfArtifact()](#getAsposePdfArtifact--) | <br /> |

|
|  | [getOuterForm()](#getOuterForm--) | <br /> |

|
### getPage() {#getPage--}
```
public final PdfPage getPage()
```


Haalt de bovenliggende pagina van dit `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` op.


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getText() {#getText--}
```
public String getText()
```


Haalt de tekst van dit `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` op.


**Returns:**
java.lang.String - De tekst van dit `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Stelt de tekst van dit `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | java.lang.String | De tekst van dit `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|

### getArtifactType() {#getArtifactType--}
```
public final int getArtifactType()
```


Haalt het type van dit `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` op.


**Returns:**
int - Het type van dit `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getArtifactSubtype() {#getArtifactSubtype--}
```
public final int getArtifactSubtype()
```


Haalt de subtype van dit `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` op.


**Returns:**
int - De subtype van dit `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Haalt de doorzichtigheid van dit `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` op.

Mogelijke waarden liggen in het bereik [0, 1].


**Returns:**
double - De doorzichtigheid van dit `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getX() {#getX--}
```
public double getX()
```


Haalt de horizontale offset van dit `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ten opzichte van de linkerrand van de pagina op in punten.


**Returns:**
double - De x-coördinaat van dit `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getY() {#getY--}
```
public double getY()
```


Haalt de verticale offset van dit `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` ten opzichte van de onderrand van de pagina op in punten.


**Returns:**
double - De y-coördinaat van dit `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Haalt de rotatiehoek van dit `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` op in graden.


**Returns:**
double - De rotatiehoek van dit `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` in graden.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Haalt de breedte van dit `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` op in punten.


**Returns:**
double - De breedte van dit `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` in punten.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Haalt de hoogte van dit `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` op in punten.


**Returns:**
double - De hoogte van dit `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` in punten.

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
