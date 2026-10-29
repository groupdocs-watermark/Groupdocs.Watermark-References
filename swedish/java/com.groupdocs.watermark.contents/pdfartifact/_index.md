---
title: "PdfArtifact"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar ett artefakt i ett pdf-innehåll."
type: docs
weight: 54
url: /sv/java/com.groupdocs.watermark.contents/pdfartifact/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public class PdfArtifact extends PdfShape
```

Representerar ett artefakt i ett pdf-innehåll.

**Lean more**

* [Working with artifacts](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-Workingwithartifacts)

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPage()](#getPage--) | Hämtar föräldrasidan för detta `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getText()](#getText--) | Hämtar texten för detta `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Sätter texten för detta `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getArtifactType()](#getArtifactType--) | Hämtar typen för detta `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getArtifactSubtype()](#getArtifactSubtype--) | Hämtar undertypen för detta `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getOpacity()](#getOpacity--) | Hämtar opaciteten för detta `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getX()](#getX--) | Hämtar den horisontella förskjutningen för detta `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` från sidans vänstra kant i punkter. |
|
|  | [getY()](#getY--) | Hämtar den vertikala förskjutningen för detta `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` från sidans nedre kant i punkter. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Hämtar rotationsvinkeln för detta `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` i grader. |
|
|  | [getWidth()](#getWidth--) | Hämtar bredden för detta `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` i punkter. |
|
|  | [getHeight()](#getHeight--) | Hämtar höjden för detta `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` i punkter. |
|
|  | [getAsposePdfArtifact()](#getAsposePdfArtifact--) | <br /> |

|
|  | [getOuterForm()](#getOuterForm--) | <br /> |

|
### getPage() {#getPage--}
```
public final PdfPage getPage()
```


Hämtar föräldrasidan för detta `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getText() {#getText--}
```
public String getText()
```


Hämtar texten för detta `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Returns:**
java.lang.String - Texten för detta `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Sätter texten för detta `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.String | Texten för detta `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|

### getArtifactType() {#getArtifactType--}
```
public final int getArtifactType()
```


Hämtar typen för detta `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Returns:**
int - Typen för detta `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getArtifactSubtype() {#getArtifactSubtype--}
```
public final int getArtifactSubtype()
```


Hämtar undertypen för detta `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Returns:**
int - Undertypen för detta `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Hämtar opaciteten för detta `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

Möjliga värden är i intervallet [0, 1].


**Returns:**
double - Opaciteten för detta `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getX() {#getX--}
```
public double getX()
```


Hämtar den horisontella förskjutningen för detta `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` från sidans vänstra kant i punkter.


**Returns:**
double - X-koordinaten för detta `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getY() {#getY--}
```
public double getY()
```


Hämtar den vertikala förskjutningen för detta `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` från sidans nedre kant i punkter.


**Returns:**
double - Y-koordinaten för detta `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Hämtar rotationsvinkeln för detta `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` i grader.


**Returns:**
double - Rotationsvinkeln för detta `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` i grader.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Hämtar bredden för detta `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` i punkter.


**Returns:**
double - Bredden på detta `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` i punkter.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Hämtar höjden för detta `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` i punkter.


**Returns:**
double - Höjden på detta `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` i punkter.

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
