---
title: "PdfAnnotation"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt een annotatie in een pdf-document voor."
type: docs
weight: 51
url: /nl/java/com.groupdocs.watermark.contents/pdfannotation/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public class PdfAnnotation extends PdfShape
```

Stelt een annotatie in een pdf-document voor.

**Learn more:**

* [Working with annotations](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-Workingwithannotations)

## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [NormalAppearanceKey](#NormalAppearanceKey) | <br /> |

|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPage()](#getPage--) | Haalt de bovenliggende pagina van deze `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` op. |
|
|  | [getAnnotationType()](#getAnnotationType--) | Haalt het type van deze `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` op. |
|
|  | [getX()](#getX--) | Haalt de horizontale offset van deze `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` op vanaf de linkerrand van de pagina in punten. |
|
|  | [getY()](#getY--) | Haalt de verticale offset van deze `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` op vanaf de onderrand van het werkblad in punten. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Haalt de rotatiehoek van deze `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` op in graden. |
|
|  | [getWidth()](#getWidth--) | Haalt de breedte van deze `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` op in punten. |
|
|  | [getHeight()](#getHeight--) | Haalt de hoogte van deze `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` op in punten. |
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


Haalt de bovenliggende pagina van deze `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` op.


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.

### getAnnotationType() {#getAnnotationType--}
```
public final int getAnnotationType()
```


Haalt het type van deze `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` op.


**Returns:**
int - Het type van deze `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.

### getX() {#getX--}
```
public double getX()
```


Haalt de horizontale offset van deze `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` op vanaf de linkerrand van de pagina in punten.


**Returns:**
double - De horizontale offset van deze `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` vanaf de linkerrand van de pagina in punten.

### getY() {#getY--}
```
public double getY()
```


Haalt de verticale offset van deze `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` op vanaf de onderrand van het werkblad in punten.


**Returns:**
double - De verticale offset van deze `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` vanaf de onderrand van het werkblad in punten.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Haalt de rotatiehoek van deze `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` op in graden.


**Returns:**
double - De rotatiehoek van deze `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` in graden.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Haalt de breedte van deze `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` op in punten.


**Returns:**
double - De breedte van deze `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` in punten.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Haalt de hoogte van deze `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` op in punten.


**Returns:**
double - De hoogte van deze `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` in punten.

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
