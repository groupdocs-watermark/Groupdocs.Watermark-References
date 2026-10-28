---
title: "PdfAnnotation"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt eine Anmerkung in einem PDF-Dokument dar."
type: docs
weight: 51
url: /de/java/com.groupdocs.watermark.contents/pdfannotation/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public class PdfAnnotation extends PdfShape
```

Stellt eine Anmerkung in einem PDF-Dokument dar.

**Learn more:**

* [Working with annotations](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-Workingwithannotations)

## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [NormalAppearanceKey](#NormalAppearanceKey) | <br /> |

|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPage()](#getPage--) | Ruft die übergeordnete Seite dieses `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` ab. |
|
|  | [getAnnotationType()](#getAnnotationType--) | Ruft den Typ dieses `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` ab. |
|
|  | [getX()](#getX--) | Ruft den horizontalen Versatz dieses `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` vom linken Seitenrand in Punkten ab. |
|
|  | [getY()](#getY--) | Ruft den vertikalen Versatz dieses `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` vom unteren Arbeitsblattrand in Punkten ab. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Ruft den Rotationswinkel dieses `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` in Grad ab. |
|
|  | [getWidth()](#getWidth--) | Ruft die Breite dieses `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` in Punkten ab. |
|
|  | [getHeight()](#getHeight--) | Ruft die Höhe dieses `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` in Punkten ab. |
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


Ruft die übergeordnete Seite dieses `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` ab.


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.

### getAnnotationType() {#getAnnotationType--}
```
public final int getAnnotationType()
```


Ruft den Typ dieses `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` ab.


**Returns:**
int - Der Typ dieses `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.

### getX() {#getX--}
```
public double getX()
```


Ruft den horizontalen Versatz dieses `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` vom linken Seitenrand in Punkten ab.


**Returns:**
double - Der horizontale Versatz dieses `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` vom linken Seitenrand in Punkten.

### getY() {#getY--}
```
public double getY()
```


Ruft den vertikalen Versatz dieses `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` vom unteren Arbeitsblattrand in Punkten ab.


**Returns:**
double - Der vertikale Versatz dieses `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` vom unteren Rand des Arbeitsblatts in Punkten.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Ruft den Rotationswinkel dieses `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` in Grad ab.


**Returns:**
double - Der Rotationswinkel dieses `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` in Grad.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Ruft die Breite dieses `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` in Punkten ab.


**Returns:**
double - Die Breite dieses `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` in Punkten.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Ruft die Höhe dieses `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` in Punkten ab.


**Returns:**
double - Die Höhe dieses `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` in Punkten.

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
