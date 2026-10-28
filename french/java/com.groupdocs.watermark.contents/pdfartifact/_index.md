---
title: "PdfArtifact"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente un artefact dans un contenu PDF."
type: docs
weight: 54
url: /fr/java/com.groupdocs.watermark.contents/pdfartifact/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public class PdfArtifact extends PdfShape
```

Représente un artefact dans un contenu PDF.

**Lean more**

* [Working with artifacts](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-Workingwithartifacts)

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getPage()](#getPage--) | Obtient la page parente de ce `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getText()](#getText--) | Obtient le texte de ce `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Définit le texte de ce `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getArtifactType()](#getArtifactType--) | Obtient le type de ce `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getArtifactSubtype()](#getArtifactSubtype--) | Obtient le sous-type de ce `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getOpacity()](#getOpacity--) | Obtient l'opacité de ce `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getX()](#getX--) | Obtient le décalage horizontal de ce `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` depuis la bordure gauche de la page en points. |
|
|  | [getY()](#getY--) | Obtient le décalage vertical de ce `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` depuis la bordure inférieure de la page en points. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Obtient l'angle de rotation de ce `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` en degrés. |
|
|  | [getWidth()](#getWidth--) | Obtient la largeur de ce `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` en points. |
|
|  | [getHeight()](#getHeight--) | Obtient la hauteur de ce `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` en points. |
|
|  | [getAsposePdfArtifact()](#getAsposePdfArtifact--) | <br /> |

|
|  | [getOuterForm()](#getOuterForm--) | <br /> |

|
### getPage() {#getPage--}
```
public final PdfPage getPage()
```


Obtient la page parente de ce `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getText() {#getText--}
```
public String getText()
```


Obtient le texte de ce `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Returns:**
java.lang.String - Le texte de ce `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Définit le texte de ce `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | java.lang.String | Le texte de ce `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|

### getArtifactType() {#getArtifactType--}
```
public final int getArtifactType()
```


Obtient le type de ce `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Returns:**
int - Le type de ce `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getArtifactSubtype() {#getArtifactSubtype--}
```
public final int getArtifactSubtype()
```


Obtient le sous-type de ce `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Returns:**
int - Le sous-type de ce `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Obtient l'opacité de ce `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

Les valeurs possibles sont dans la plage [0, 1].


**Returns:**
double - L'opacité de ce `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getX() {#getX--}
```
public double getX()
```


Obtient le décalage horizontal de ce `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` depuis la bordure gauche de la page en points.


**Returns:**
double - La coordonnée x de ce `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getY() {#getY--}
```
public double getY()
```


Obtient le décalage vertical de ce `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` depuis la bordure inférieure de la page en points.


**Returns:**
double - La coordonnée y de ce `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Obtient l'angle de rotation de ce `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` en degrés.


**Returns:**
double - L'angle de rotation de ce `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` en degrés.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Obtient la largeur de ce `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` en points.


**Returns:**
double - La largeur de ce `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` en points.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Obtient la hauteur de ce `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` en points.


**Returns:**
double - La hauteur de ce `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` en points.

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
