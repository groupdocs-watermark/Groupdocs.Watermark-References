---
title: "PdfArtifact"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل عنصرًا في محتوى PDF."
type: docs
weight: 54
url: /ar/java/com.groupdocs.watermark.contents/pdfartifact/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public class PdfArtifact extends PdfShape
```

يمثل عنصرًا في محتوى PDF.

**Lean more**

* [Working with artifacts](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-Workingwithartifacts)

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPage()](#getPage--) | يحصل على الصفحة الأصلية لهذا `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getText()](#getText--) | يحصل على النص لهذا `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | يضبط النص لهذا `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getArtifactType()](#getArtifactType--) | يحصل على النوع لهذا `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getArtifactSubtype()](#getArtifactSubtype--) | يحصل على النوع الفرعي لهذا `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getOpacity()](#getOpacity--) | يحصل على شفافية هذا `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|
|  | [getX()](#getX--) | يحصل على الإزاحة الأفقية لهذا `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` من الحد الأيسر للصفحة بالنقاط. |
|
|  | [getY()](#getY--) | يحصل على الإزاحة العمودية لهذا `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` من الحد السفلي للصفحة بالنقاط. |
|
|  | [getRotateAngle()](#getRotateAngle--) | يحصل على زاوية الدوران لهذا `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` بالدرجات. |
|
|  | [getWidth()](#getWidth--) | يحصل على العرض لهذا `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` بالنقاط. |
|
|  | [getHeight()](#getHeight--) | يحصل على الارتفاع لهذا `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` بالنقاط. |
|
|  | [getAsposePdfArtifact()](#getAsposePdfArtifact--) | <br /> |

|
|  | [getOuterForm()](#getOuterForm--) | <br /> |

|
### getPage() {#getPage--}
```
public final PdfPage getPage()
```


يحصل على الصفحة الأصلية لهذا `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getText() {#getText--}
```
public String getText()
```


يحصل على النص لهذا `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Returns:**
java.lang.String - النص لهذا `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


يضبط النص لهذا `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | java.lang.String | النص لهذا `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
|

### getArtifactType() {#getArtifactType--}
```
public final int getArtifactType()
```


يحصل على النوع لهذا `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Returns:**
int - النوع لهذا `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getArtifactSubtype() {#getArtifactSubtype--}
```
public final int getArtifactSubtype()
```


يحصل على النوع الفرعي لهذا `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.


**Returns:**
int - النوع الفرعي لهذا `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


يحصل على شفافية هذا `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

القيم الممكنة في النطاق [0, 1].


**Returns:**
double - شفافية هذا `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getX() {#getX--}
```
public double getX()
```


يحصل على الإزاحة الأفقية لهذا `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` من الحد الأيسر للصفحة بالنقاط.


**Returns:**
double - الإحداثي السيني لهذا `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getY() {#getY--}
```
public double getY()
```


يحصل على الإزاحة العمودية لهذا `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` من الحد السفلي للصفحة بالنقاط.


**Returns:**
double - الإحداثي الصادي لهذا `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


يحصل على زاوية الدوران لهذا `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` بالدرجات.


**Returns:**
double - زاوية الدوران لهذا `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` بالدرجات.

### getWidth() {#getWidth--}
```
public double getWidth()
```


يحصل على العرض لهذا `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` بالنقاط.


**Returns:**
double - عرض هذا `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` بالنقاط.

### getHeight() {#getHeight--}
```
public double getHeight()
```


يحصل على الارتفاع لهذا `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` بالنقاط.


**Returns:**
double - ارتفاع هذا `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` بالنقاط.

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
