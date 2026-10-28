---
title: "PdfAnnotation"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل تعليقا في مستند PDF."
type: docs
weight: 51
url: /ar/java/com.groupdocs.watermark.contents/pdfannotation/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public class PdfAnnotation extends PdfShape
```

يمثل تعليقا في مستند PDF.

**Learn more:**

* [Working with annotations](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-Workingwithannotations)

## الحقول

| حقل | الوصف |
| --- | --- |
|  | [NormalAppearanceKey](#NormalAppearanceKey) | <br /> |

|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPage()](#getPage--) | يحصل على الصفحة الأصلية لهذا `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`. |
|
|  | [getAnnotationType()](#getAnnotationType--) | يحصل على نوع هذا `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`. |
|
|  | [getX()](#getX--) | يحصل على الإزاحة الأفقية لهذا `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` من الحد الأيسر للصفحة بالنقاط. |
|
|  | [getY()](#getY--) | يحصل على الإزاحة العمودية لهذا `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` من الحد السفلي لورقة العمل بالنقاط. |
|
|  | [getRotateAngle()](#getRotateAngle--) | يحصل على زاوية الدوران لهذا `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` بالدرجات. |
|
|  | [getWidth()](#getWidth--) | يحصل على عرض هذا `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` بالنقاط. |
|
|  | [getHeight()](#getHeight--) | يحصل على ارتفاع هذا `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` بالنقاط. |
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


يحصل على الصفحة الأصلية لهذا `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.

### getAnnotationType() {#getAnnotationType--}
```
public final int getAnnotationType()
```


يحصل على نوع هذا `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.


**Returns:**
int - نوع هذا `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.

### getX() {#getX--}
```
public double getX()
```


يحصل على الإزاحة الأفقية لهذا `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` من الحد الأيسر للصفحة بالنقاط.


**Returns:**
double - الإزاحة الأفقية لهذا `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` من الحد الأيسر للصفحة بالنقاط.

### getY() {#getY--}
```
public double getY()
```


يحصل على الإزاحة العمودية لهذا `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` من الحد السفلي لورقة العمل بالنقاط.


**Returns:**
double - الإزاحة العمودية لهذا `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` من الحد السفلي للورقة في النقاط.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


يحصل على زاوية الدوران لهذا `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` بالدرجات.


**Returns:**
double - زاوية الدوران لهذا `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` بالدرجات.

### getWidth() {#getWidth--}
```
public double getWidth()
```


يحصل على عرض هذا `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` بالنقاط.


**Returns:**
double - عرض هذا `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` بالنقاط.

### getHeight() {#getHeight--}
```
public double getHeight()
```


يحصل على ارتفاع هذا `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` بالنقاط.


**Returns:**
double - ارتفاع هذا `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` بالنقاط.

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
