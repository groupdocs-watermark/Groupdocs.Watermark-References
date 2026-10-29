---
title: "PdfAnnotation"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Bir PDF belgesindeki bir açıklamayı temsil eder."
type: docs
weight: 51
url: /tr/java/com.groupdocs.watermark.contents/pdfannotation/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public class PdfAnnotation extends PdfShape
```

Bir PDF belgesindeki bir açıklamayı temsil eder.

**Learn more:**

* [Working with annotations](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-Workingwithannotations)

## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [NormalAppearanceKey](#NormalAppearanceKey) | <br /> |

|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPage()](#getPage--) | Bu `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` öğesinin üst sayfasını alır. |
|
|  | [getAnnotationType()](#getAnnotationType--) | Bu `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` öğesinin tipini alır. |
|
|  | [getX()](#getX--) | Bu `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` öğesinin sayfa sol kenarından yatay ofsetini puan cinsinden alır. |
|
|  | [getY()](#getY--) | Bu `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` öğesinin çalışma sayfası alt kenarından dikey ofsetini puan cinsinden alır. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Bu `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` öğesinin döndürme açısını derece cinsinden alır. |
|
|  | [getWidth()](#getWidth--) | Bu `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` öğesinin genişliğini puan cinsinden alır. |
|
|  | [getHeight()](#getHeight--) | Bu `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` öğesinin yüksekliğini puan cinsinden alır. |
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


Bu `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` öğesinin üst sayfasını alır.


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.

### getAnnotationType() {#getAnnotationType--}
```
public final int getAnnotationType()
```


Bu `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` öğesinin tipini alır.


**Returns:**
int - Bu `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` öğesinin tipi.

### getX() {#getX--}
```
public double getX()
```


Bu `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` öğesinin sayfa sol kenarından yatay ofsetini puan cinsinden alır.


**Returns:**
double - Bu `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` öğesinin sayfa sol kenarından yatay ofseti puan cinsinden.

### getY() {#getY--}
```
public double getY()
```


Bu `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` öğesinin çalışma sayfası alt kenarından dikey ofsetini puan cinsinden alır.


**Returns:**
double - Bu `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` öğesinin çalışma sayfası alt kenarından dikey ofseti nokta cinsinden.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Bu `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` öğesinin döndürme açısını derece cinsinden alır.


**Returns:**
double - Bu `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` öğesinin döndürme açısı derece cinsinden.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Bu `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` öğesinin genişliğini puan cinsinden alır.


**Returns:**
double - Bu `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` öğesinin genişliği nokta cinsinden.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Bu `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` öğesinin yüksekliğini puan cinsinden alır.


**Returns:**
double - Bu `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` öğesinin yüksekliği nokta cinsinden.

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
