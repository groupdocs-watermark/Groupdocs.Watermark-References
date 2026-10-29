---
title: "PdfAnnotation"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa una anotación en un documento pdf."
type: docs
weight: 51
url: /es/java/com.groupdocs.watermark.contents/pdfannotation/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public class PdfAnnotation extends PdfShape
```

Representa una anotación en un documento pdf.

**Learn more:**

* [Working with annotations](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-Workingwithannotations)

## Campos

| Campo | Descripción |
| --- | --- |
|  | [NormalAppearanceKey](#NormalAppearanceKey) | <br /> |

|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getPage()](#getPage--) | Obtiene la página padre de este `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`. |
|
|  | [getAnnotationType()](#getAnnotationType--) | Obtiene el tipo de este `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`. |
|
|  | [getX()](#getX--) | Obtiene el desplazamiento horizontal de este `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` desde el borde izquierdo de la página en puntos. |
|
|  | [getY()](#getY--) | Obtiene el desplazamiento vertical de este `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` desde el borde inferior de la hoja de cálculo en puntos. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Obtiene el ángulo de rotación de este `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` en grados. |
|
|  | [getWidth()](#getWidth--) | Obtiene el ancho de este `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` en puntos. |
|
|  | [getHeight()](#getHeight--) | Obtiene la altura de este `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` en puntos. |
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


Obtiene la página padre de este `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.

### getAnnotationType() {#getAnnotationType--}
```
public final int getAnnotationType()
```


Obtiene el tipo de este `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.


**Returns:**
int - El tipo de este `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.

### getX() {#getX--}
```
public double getX()
```


Obtiene el desplazamiento horizontal de este `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` desde el borde izquierdo de la página en puntos.


**Returns:**
double - El desplazamiento horizontal de este `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` desde el borde izquierdo de la página en puntos.

### getY() {#getY--}
```
public double getY()
```


Obtiene el desplazamiento vertical de este `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` desde el borde inferior de la hoja de cálculo en puntos.


**Returns:**
double - El desplazamiento vertical de este `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` desde el borde inferior de la hoja de cálculo en puntos.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Obtiene el ángulo de rotación de este `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` en grados.


**Returns:**
double - El ángulo de rotación de este `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` en grados.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Obtiene el ancho de este `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` en puntos.


**Returns:**
double - El ancho de este `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` en puntos.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Obtiene la altura de este `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` en puntos.


**Returns:**
double - La altura de este `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` en puntos.

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
