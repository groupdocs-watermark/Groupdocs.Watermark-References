---
title: PdfArtifact
second_title: GroupDocs.Watermark for Java API Reference
description: Represents an artifact in a pdf content.
type: docs
weight: 54
url: /java/com.groupdocs.watermark.contents/pdfartifact/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public class PdfArtifact extends PdfShape
```

Represents an artifact in a pdf content.

**Lean more**

 *  [Working with artifacts][]


[Working with artifacts]: https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-Workingwithartifacts
## Methods

| Method | Description |
| --- | --- |
| [getPage()](#getPage--) | Gets the parent page of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
| [getText()](#getText--) | Gets the text of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
| [setText(String value)](#setText-java.lang.String-) | Sets the text of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
| [getArtifactType()](#getArtifactType--) | Gets the type of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
| [getArtifactSubtype()](#getArtifactSubtype--) | Gets the subtype of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
| [getOpacity()](#getOpacity--) | Gets the opacity of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |
| [getX()](#getX--) | Gets the horizontal offset of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` from page left border in points. |
| [getY()](#getY--) | Gets the vertical offset of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` from page bottom border in points. |
| [getRotateAngle()](#getRotateAngle--) | Gets the rotate angle of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` in degrees. |
| [getWidth()](#getWidth--) | Gets the width of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` in points. |
| [getHeight()](#getHeight--) | Gets the height of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` in points. |
| [getAsposePdfArtifact()](#getAsposePdfArtifact--) |  |
| [getOuterForm()](#getOuterForm--) |  |
### getPage() {#getPage--}
```
public final PdfPage getPage()
```


Gets the parent page of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.
### getText() {#getText--}
```
public String getText()
```


Gets the text of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

**Returns:**
java.lang.String - The text of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Sets the text of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The text of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`. |

### getArtifactType() {#getArtifactType--}
```
public final int getArtifactType()
```


Gets the type of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

**Returns:**
int - The type of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.
### getArtifactSubtype() {#getArtifactSubtype--}
```
public final int getArtifactSubtype()
```


Gets the subtype of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

**Returns:**
int - The subtype of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.
### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Gets the opacity of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

Possible values are in range [0, 1].

**Returns:**
double - The opacity of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.
### getX() {#getX--}
```
public double getX()
```


Gets the horizontal offset of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` from page left border in points.

**Returns:**
double - The x-coordinate of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.
### getY() {#getY--}
```
public double getY()
```


Gets the vertical offset of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` from page bottom border in points.

**Returns:**
double - The y-coordinate of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.
### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Gets the rotate angle of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` in degrees.

**Returns:**
double - The rotate angle of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` in degrees.
### getWidth() {#getWidth--}
```
public double getWidth()
```


Gets the width of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` in points.

**Returns:**
double - The width of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` in points.
### getHeight() {#getHeight--}
```
public double getHeight()
```


Gets the height of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` in points.

**Returns:**
double - The height of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` in points.
### getAsposePdfArtifact() {#getAsposePdfArtifact--}
```
public final Artifact getAsposePdfArtifact()
```




**Returns:**
com.aspose.pdf.Artifact
### getOuterForm() {#getOuterForm--}
```
public XForm getOuterForm()
```




**Returns:**
com.aspose.pdf.XForm
