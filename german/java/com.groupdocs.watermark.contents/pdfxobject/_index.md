---
title: "PdfXObject"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt ein XObject in einem PDF-Dokument dar."
type: docs
weight: 75
url: /de/java/com.groupdocs.watermark.contents/pdfxobject/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public abstract class PdfXObject extends PdfShape
```

Stellt ein XObject in einem PDF-Dokument dar.

**Learn more:**

* [Working with XObjects](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-WorkingwithXObjects)

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPage()](#getPage--) | Ruft die übergeordnete Seite dieses `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` ab. |
|
|  | [getX()](#getX--) | Ruft den horizontalen Abstand dieses `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` vom linken Seitenrand in Punkten ab. |
|
|  | [getY()](#getY--) | Ruft den vertikalen Abstand dieses `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` vom unteren Seitenrand in Punkten ab. |
|
|  | [getWidth()](#getWidth--) | Ruft die Breite dieses `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` in Punkten ab. |
|
|  | [getHeight()](#getHeight--) | Ruft die Höhe dieses `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` in Punkten ab. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Ruft den Rotationswinkel dieses `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` in Grad ab. |
|
|  | [getMatrix()](#getMatrix--) | <br /> |

|
### getPage() {#getPage--}
```
public final PdfPage getPage()
```


Ruft die übergeordnete Seite dieses `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` ab.


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.

### getX() {#getX--}
```
public double getX()
```


Ruft den horizontalen Abstand dieses `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` vom linken Seitenrand in Punkten ab.


**Returns:**
double - Die x-Koordinate dieses `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.

### getY() {#getY--}
```
public double getY()
```


Ruft den vertikalen Abstand dieses `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` vom unteren Seitenrand in Punkten ab.


**Returns:**
double - Die y-Koordinate dieses `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Ruft die Breite dieses `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` in Punkten ab.


**Returns:**
double - Die Breite dieses `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` in Punkten.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Ruft die Höhe dieses `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` in Punkten ab.


**Returns:**
double - Die Höhe dieses `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` in Punkten.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Ruft den Rotationswinkel dieses `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` in Grad ab.


**Returns:**
double - Der Rotationswinkel dieses `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` in Grad.

### getMatrix() {#getMatrix--}
```
public final Matrix getMatrix()
```


<br />



**Returns:**
com.aspose.pdf.Matrix
