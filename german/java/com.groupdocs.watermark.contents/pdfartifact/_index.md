---
title: "PdfArtifact"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt ein Artefakt in einem PDF-Inhalt dar."
type: docs
weight: 54
url: /de/java/com.groupdocs.watermark.contents/pdfartifact/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public class PdfArtifact extends PdfShape
```

Stellt ein Artefakt in einem PDF-Inhalt dar.

**Lean more**

* [Working with artifacts](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-Workingwithartifacts)

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPage()](#getPage--) | Gibt die übergeordnete Seite dieses `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getText()](#getText--) | Gibt den Text dieses `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Setzt den Text dieses `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getArtifactType()](#getArtifactType--) | Gibt den Typ dieses `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getArtifactSubtype()](#getArtifactSubtype--) | Gibt den Subtyp dieses `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getOpacity()](#getOpacity--) | Gibt die Deckkraft dieses `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getX()](#getX--) | Gibt den horizontalen Versatz dieses `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` vom linken Seitenrand in Punkten. |
|
|  | [getY()](#getY--) | Gibt den vertikalen Versatz dieses `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` vom unteren Seitenrand in Punkten. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Gibt den Rotationswinkel dieses `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` in Grad. |
|
|  | [getWidth()](#getWidth--) | Gibt die Breite dieses `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` in Punkten. |
|
|  | [getHeight()](#getHeight--) | Gibt die Höhe dieses `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` in Punkten. |
|
|  | [getAsposePdfArtifact()](#getAsposePdfArtifact--) | <br /> |

|
|  | [getOuterForm()](#getOuterForm--) | <br /> |

|
### getPage() {#getPage--}
```
public final PdfPage getPage()
```


Gibt die übergeordnete Seite dieses `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getText() {#getText--}
```
public String getText()
```


Gibt den Text dieses `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Returns:**
java.lang.String - Der Text dieses `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Setzt den Text dieses `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | java.lang.String | Der Text dieses `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|

### getArtifactType() {#getArtifactType--}
```
public final int getArtifactType()
```


Gibt den Typ dieses `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Returns:**
int - Der Typ dieses `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getArtifactSubtype() {#getArtifactSubtype--}
```
public final int getArtifactSubtype()
```


Gibt den Subtyp dieses `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Returns:**
int - Der Subtyp dieses `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Gibt die Deckkraft dieses `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

Mögliche Werte liegen im Bereich [0, 1].


**Returns:**
double - Die Deckkraft dieses `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getX() {#getX--}
```
public double getX()
```


Gibt den horizontalen Versatz dieses `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` vom linken Seitenrand in Punkten.


**Returns:**
double - Die x-Koordinate dieses `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getY() {#getY--}
```
public double getY()
```


Gibt den vertikalen Versatz dieses `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` vom unteren Seitenrand in Punkten.


**Returns:**
double - Die y-Koordinate dieses `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Gibt den Rotationswinkel dieses `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` in Grad.


**Returns:**
double - Der Rotationswinkel dieses `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` in Grad.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Gibt die Breite dieses `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` in Punkten.


**Returns:**
double - Die Breite dieses `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` in Punkten.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Gibt die Höhe dieses `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` in Punkten.


**Returns:**
double - Die Höhe dieses `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` in Punkten.

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
