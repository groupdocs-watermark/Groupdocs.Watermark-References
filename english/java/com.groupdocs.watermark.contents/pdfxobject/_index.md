---
title: PdfXObject
second_title: GroupDocs.Watermark for Java API Reference
description: Represents an XObject in a pdf document.
type: docs
weight: 75
url: /java/com.groupdocs.watermark.contents/pdfxobject/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public abstract class PdfXObject extends PdfShape
```

Represents an XObject in a pdf document.

**Learn more:**

 *  [Working with XObjects][]


[Working with XObjects]: https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-WorkingwithXObjects
## Methods

| Method | Description |
| --- | --- |
| [getPage()](#getPage--) | Gets the parent page of this `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`. |
| [getX()](#getX--) | Gets the horizontal offset of this `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` from page left border in points. |
| [getY()](#getY--) | Gets the vertical offset of this `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` from page bottom border in points. |
| [getWidth()](#getWidth--) | Gets the width of this `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` in points. |
| [getHeight()](#getHeight--) | Gets the height of this `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` in points. |
| [getRotateAngle()](#getRotateAngle--) | Gets the rotate angle of this `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` in degrees. |
| [getMatrix()](#getMatrix--) |  |
### getPage() {#getPage--}
```
public final PdfPage getPage()
```


Gets the parent page of this `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.

**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.
### getX() {#getX--}
```
public double getX()
```


Gets the horizontal offset of this `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` from page left border in points.

**Returns:**
double - The x-coordinate of this `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.
### getY() {#getY--}
```
public double getY()
```


Gets the vertical offset of this `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` from page bottom border in points.

**Returns:**
double - The y-coordinate of this `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.
### getWidth() {#getWidth--}
```
public double getWidth()
```


Gets the width of this `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` in points.

**Returns:**
double - The width of this `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` in points.
### getHeight() {#getHeight--}
```
public double getHeight()
```


Gets the height of this `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` in points.

**Returns:**
double - The height of this `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` in points.
### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Gets the rotate angle of this `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` in degrees.

**Returns:**
double - The rotate angle of this `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` in degrees.
### getMatrix() {#getMatrix--}
```
public final Matrix getMatrix()
```




**Returns:**
com.aspose.pdf.Matrix
