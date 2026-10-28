---
title: "PdfAnnotation"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente une annotation dans un document PDF."
type: docs
weight: 51
url: /fr/java/com.groupdocs.watermark.contents/pdfannotation/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public class PdfAnnotation extends PdfShape
```

Représente une annotation dans un document PDF.

**Learn more:**

* [Working with annotations](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-Workingwithannotations)

## Champs

| Champ | Description |
| --- | --- |
|  | [NormalAppearanceKey](#NormalAppearanceKey) | <br /> |

|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getPage()](#getPage--) | Obtient la page parente de ce `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`. |
|
|  | [getAnnotationType()](#getAnnotationType--) | Obtient le type de ce `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`. |
|
|  | [getX()](#getX--) | Obtient le décalage horizontal de ce `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` depuis la bordure gauche de la page en points. |
|
|  | [getY()](#getY--) | Obtient le décalage vertical de ce `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` depuis la bordure inférieure de la feuille de calcul en points. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Obtient l'angle de rotation de ce `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` en degrés. |
|
|  | [getWidth()](#getWidth--) | Obtient la largeur de ce `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` en points. |
|
|  | [getHeight()](#getHeight--) | Obtient la hauteur de ce `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` en points. |
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


Obtient la page parente de ce `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.

### getAnnotationType() {#getAnnotationType--}
```
public final int getAnnotationType()
```


Obtient le type de ce `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.


**Returns:**
int - Le type de ce `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.

### getX() {#getX--}
```
public double getX()
```


Obtient le décalage horizontal de ce `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` depuis la bordure gauche de la page en points.


**Returns:**
double - Le décalage horizontal de ce `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` depuis la bordure gauche de la page en points.

### getY() {#getY--}
```
public double getY()
```


Obtient le décalage vertical de ce `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` depuis la bordure inférieure de la feuille de calcul en points.


**Returns:**
double - Le décalage vertical de ce `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` depuis la bordure inférieure de la feuille de calcul en points.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Obtient l'angle de rotation de ce `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` en degrés.


**Returns:**
double - L'angle de rotation de ce `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` en degrés.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Obtient la largeur de ce `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` en points.


**Returns:**
double - La largeur de ce `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` en points.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Obtient la hauteur de ce `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` en points.


**Returns:**
double - La hauteur de ce `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` en points.

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
