---
title: "PdfXObject"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente un XObject dans un document pdf."
type: docs
weight: 75
url: /fr/java/com.groupdocs.watermark.contents/pdfxobject/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public abstract class PdfXObject extends PdfShape
```

Représente un XObject dans un document pdf.

**Learn more:**

* [Working with XObjects](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-WorkingwithXObjects)

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getPage()](#getPage--) | Obtient la page parente de cet `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`. |
|
|  | [getX()](#getX--) | Obtient le décalage horizontal de cet `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` par rapport à la bordure gauche de la page en points. |
|
|  | [getY()](#getY--) | Obtient le décalage vertical de cet `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` par rapport à la bordure inférieure de la page en points. |
|
|  | [getWidth()](#getWidth--) | Obtient la largeur de cet `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` en points. |
|
|  | [getHeight()](#getHeight--) | Obtient la hauteur de cet `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` en points. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Obtient l'angle de rotation de cet `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` en degrés. |
|
|  | [getMatrix()](#getMatrix--) | <br /> |

|
### getPage() {#getPage--}
```
public final PdfPage getPage()
```


Obtient la page parente de cet `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.

### getX() {#getX--}
```
public double getX()
```


Obtient le décalage horizontal de cet `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` par rapport à la bordure gauche de la page en points.


**Returns:**
double - La coordonnée x de cet `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.

### getY() {#getY--}
```
public double getY()
```


Obtient le décalage vertical de cet `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` par rapport à la bordure inférieure de la page en points.


**Returns:**
double - La coordonnée y de cet `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Obtient la largeur de cet `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` en points.


**Returns:**
double - La largeur de cet `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` en points.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Obtient la hauteur de cet `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` en points.


**Returns:**
double - La hauteur de cet `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` en points.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Obtient l'angle de rotation de cet `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` en degrés.


**Returns:**
double - L'angle de rotation de cet `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` en degrés.

### getMatrix() {#getMatrix--}
```
public final Matrix getMatrix()
```


<br />



**Returns:**
com.aspose.pdf.Matrix
