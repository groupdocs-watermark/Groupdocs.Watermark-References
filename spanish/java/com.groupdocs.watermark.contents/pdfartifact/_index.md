---
title: "PdfArtifact"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa un artefacto en un contenido pdf."
type: docs
weight: 54
url: /es/java/com.groupdocs.watermark.contents/pdfartifact/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public class PdfArtifact extends PdfShape
```

Representa un artefacto en un contenido pdf.

**Lean more**

* [Working with artifacts](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-Workingwithartifacts)

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getPage()](#getPage--) | Obtiene la página padre de este `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getText()](#getText--) | Obtiene el texto de este `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Establece el texto de este `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getArtifactType()](#getArtifactType--) | Obtiene el tipo de este `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getArtifactSubtype()](#getArtifactSubtype--) | Obtiene el subtipo de este `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getOpacity()](#getOpacity--) | Obtiene la opacidad de este `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getX()](#getX--) | Obtiene el desplazamiento horizontal de este `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` desde el borde izquierdo de la página en puntos. |
|
|  | [getY()](#getY--) | Obtiene el desplazamiento vertical de este `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` desde el borde inferior de la página en puntos. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Obtiene el ángulo de rotación de este `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` en grados. |
|
|  | [getWidth()](#getWidth--) | Obtiene el ancho de este `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` en puntos. |
|
|  | [getHeight()](#getHeight--) | Obtiene la altura de este `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` en puntos. |
|
|  | [getAsposePdfArtifact()](#getAsposePdfArtifact--) | <br /> |

|
|  | [getOuterForm()](#getOuterForm--) | <br /> |

|
### getPage() {#getPage--}
```
public final PdfPage getPage()
```


Obtiene la página padre de este `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getText() {#getText--}
```
public String getText()
```


Obtiene el texto de este `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Returns:**
java.lang.String - El texto de este `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Establece el texto de este `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | java.lang.String | El texto de este `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|

### getArtifactType() {#getArtifactType--}
```
public final int getArtifactType()
```


Obtiene el tipo de este `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Returns:**
int - El tipo de este `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getArtifactSubtype() {#getArtifactSubtype--}
```
public final int getArtifactSubtype()
```


Obtiene el subtipo de este `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Returns:**
int - El subtipo de este `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Obtiene la opacidad de este `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

Los valores posibles están en el rango [0, 1].


**Returns:**
double - La opacidad de este `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getX() {#getX--}
```
public double getX()
```


Obtiene el desplazamiento horizontal de este `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` desde el borde izquierdo de la página en puntos.


**Returns:**
double - La coordenada x de este `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getY() {#getY--}
```
public double getY()
```


Obtiene el desplazamiento vertical de este `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` desde el borde inferior de la página en puntos.


**Returns:**
double - La coordenada y de este `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Obtiene el ángulo de rotación de este `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` en grados.


**Returns:**
double - El ángulo de rotación de este `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` en grados.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Obtiene el ancho de este `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` en puntos.


**Returns:**
double - El ancho de este `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` en puntos.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Obtiene la altura de este `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` en puntos.


**Returns:**
double - La altura de este `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` en puntos.

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
