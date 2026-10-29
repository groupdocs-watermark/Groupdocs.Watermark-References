---
title: "PdfXObject"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa un XObject en un documento pdf."
type: docs
weight: 75
url: /es/java/com.groupdocs.watermark.contents/pdfxobject/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public abstract class PdfXObject extends PdfShape
```

Representa un XObject en un documento pdf.

**Learn more:**

* [Working with XObjects](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-WorkingwithXObjects)

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getPage()](#getPage--) | Obtiene la página principal de este `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`. |
|
|  | [getX()](#getX--) | Obtiene el desplazamiento horizontal de este `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` desde el borde izquierdo de la página en puntos. |
|
|  | [getY()](#getY--) | Obtiene el desplazamiento vertical de este `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` desde el borde inferior de la página en puntos. |
|
|  | [getWidth()](#getWidth--) | Obtiene el ancho de este `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` en puntos. |
|
|  | [getHeight()](#getHeight--) | Obtiene la altura de este `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` en puntos. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Obtiene el ángulo de rotación de este `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` en grados. |
|
|  | [getMatrix()](#getMatrix--) | <br /> |

|
### getPage() {#getPage--}
```
public final PdfPage getPage()
```


Obtiene la página principal de este `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.

### getX() {#getX--}
```
public double getX()
```


Obtiene el desplazamiento horizontal de este `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` desde el borde izquierdo de la página en puntos.


**Returns:**
double - La coordenada x de este `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.

### getY() {#getY--}
```
public double getY()
```


Obtiene el desplazamiento vertical de este `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` desde el borde inferior de la página en puntos.


**Returns:**
double - La coordenada y de este `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Obtiene el ancho de este `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` en puntos.


**Returns:**
double - El ancho de este `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` en puntos.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Obtiene la altura de este `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` en puntos.


**Returns:**
double - La altura de este `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` en puntos.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Obtiene el ángulo de rotación de este `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` en grados.


**Returns:**
double - El ángulo de rotación de este `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` en grados.

### getMatrix() {#getMatrix--}
```
public final Matrix getMatrix()
```


<br />



**Returns:**
com.aspose.pdf.Matrix
