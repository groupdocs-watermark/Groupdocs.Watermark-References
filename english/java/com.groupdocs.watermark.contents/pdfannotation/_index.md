---
title: PdfAnnotation
second_title: GroupDocs.Watermark for Java API Reference
description: Represents an annotation in a pdf document.
type: docs
weight: 51
url: /java/com.groupdocs.watermark.contents/pdfannotation/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public class PdfAnnotation extends PdfShape
```

Represents an annotation in a pdf document.

**Learn more:**

 *  [Working with annotations][]


[Working with annotations]: https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-Workingwithannotations
## Fields

| Field | Description |
| --- | --- |
| [NormalAppearanceKey](#NormalAppearanceKey) |  |
## Methods

| Method | Description |
| --- | --- |
| [getPage()](#getPage--) | Gets the parent page of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`. |
| [getAnnotationType()](#getAnnotationType--) | Gets the type of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`. |
| [getX()](#getX--) | Gets the horizontal offset of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` from page left border in points. |
| [getY()](#getY--) | Gets the vertical offset of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` from worksheet bottom border in points. |
| [getRotateAngle()](#getRotateAngle--) | Gets the rotate angle of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` in degrees. |
| [getWidth()](#getWidth--) | Gets the width of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` in points. |
| [getHeight()](#getHeight--) | Gets the height of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` in points. |
| [getAsposePdfAnnotation()](#getAsposePdfAnnotation--) |  |
| [getOuterForm()](#getOuterForm--) |  |
### NormalAppearanceKey {#NormalAppearanceKey}
```
public static final String NormalAppearanceKey
```




### getPage() {#getPage--}
```
public final PdfPage getPage()
```


Gets the parent page of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.

**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.
### getAnnotationType() {#getAnnotationType--}
```
public final int getAnnotationType()
```


Gets the type of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.

**Returns:**
int - The type of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.
### getX() {#getX--}
```
public double getX()
```


Gets the horizontal offset of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` from page left border in points.

**Returns:**
double - The horizontal offset of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` from page left border in points.
### getY() {#getY--}
```
public double getY()
```


Gets the vertical offset of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` from worksheet bottom border in points.

**Returns:**
double - The vertical offset of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` from worksheet bottom border in points.
### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Gets the rotate angle of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` in degrees.

**Returns:**
double - The rotate angle of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` in degrees.
### getWidth() {#getWidth--}
```
public double getWidth()
```


Gets the width of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` in points.

**Returns:**
double - The width of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` in points.
### getHeight() {#getHeight--}
```
public double getHeight()
```


Gets the height of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` in points.

**Returns:**
double - The height of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` in points.
### getAsposePdfAnnotation() {#getAsposePdfAnnotation--}
```
public final Annotation getAsposePdfAnnotation()
```




**Returns:**
com.aspose.pdf.Annotation
### getOuterForm() {#getOuterForm--}
```
public XForm getOuterForm()
```




**Returns:**
com.aspose.pdf.XForm
