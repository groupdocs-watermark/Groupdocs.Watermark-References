---
title: PdfShape
second_title: GroupDocs.Watermark for Java API Reference
description: Provides base class for XObjects Artifacts and Annotations.
type: docs
weight: 69
url: /java/com.groupdocs.watermark.contents/pdfshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public abstract class PdfShape extends ShapeSearchAdapter implements IRotatableTwoDObject
```

Provides base class for XObjects, Artifacts and Annotations.
## Methods

| Method | Description |
| --- | --- |
| [getText()](#getText--) | Gets the text of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
| [setText(String value)](#setText-java.lang.String-) | Gets or sets the text of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
| [getFormattedTextFragments()](#getFormattedTextFragments--) | Gets the collection of formatted text fragments of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
| [getImage()](#getImage--) | Gets the image of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
| [setImage(PdfWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.PdfWatermarkableImage-) | Sets the image of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
| [getX()](#getX--) | Gets the x-coordinate of the object. |
| [getY()](#getY--) | Gets the y-coordinate of the object. |
| [getWidth()](#getWidth--) | Gets the width of the object. |
| [getHeight()](#getHeight--) | Gets the height of the object. |
| [getRotateAngle()](#getRotateAngle--) | Gets the rotate angle of the object in degrees. |
| [getOuterForm()](#getOuterForm--) |  |
| [extractImageAppearance()](#extractImageAppearance--) |  |
| [getTextForSearch()](#getTextForSearch--) |  |
| [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) |  |
| [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) |  |
| [getImageForSearch()](#getImageForSearch--) |  |
| [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) |  |
### getText() {#getText--}
```
public String getText()
```


Gets the text of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.

**Returns:**
java.lang.String - The text of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Gets or sets the text of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The text of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Gets the collection of formatted text fragments of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.

**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.
### getImage() {#getImage--}
```
public final PdfWatermarkableImage getImage()
```


Gets the image of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.

**Returns:**
[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage) - The image of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.
### setImage(PdfWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.PdfWatermarkableImage-}
```
public final void setImage(PdfWatermarkableImage value)
```


Sets the image of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage) | The image of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |

### getX() {#getX--}
```
public abstract double getX()
```


Gets the x-coordinate of the object.

**Returns:**
double - The x-coordinate of the object.
### getY() {#getY--}
```
public abstract double getY()
```


Gets the y-coordinate of the object.

**Returns:**
double - The y-coordinate of the object.
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Gets the width of the object.

**Returns:**
double - The width of the object.
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Gets the height of the object.

**Returns:**
double - The height of the object.
### getRotateAngle() {#getRotateAngle--}
```
public abstract double getRotateAngle()
```


Gets the rotate angle of the object in degrees.

**Returns:**
double - The rotate angle of the object in degrees.
### getOuterForm() {#getOuterForm--}
```
public abstract XForm getOuterForm()
```




**Returns:**
com.aspose.pdf.XForm
### extractImageAppearance() {#extractImageAppearance--}
```
public PdfXImageAppearance extractImageAppearance()
```




**Returns:**
[PdfXImageAppearance](../../com.groupdocs.watermark.internal/pdfximageappearance)
### getTextForSearch() {#getTextForSearch--}
```
public String getTextForSearch()
```




**Returns:**
java.lang.String
### setFoundWatermarkText(String value) {#setFoundWatermarkText-java.lang.String-}
```
public void setFoundWatermarkText(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormattedTextFragmentsForSearch() {#getFormattedTextFragmentsForSearch--}
```
public FormattedTextFragmentCollection getFormattedTextFragmentsForSearch()
```




**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
### getImageForSearch() {#getImageForSearch--}
```
public WatermarkableImage getImageForSearch()
```




**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### setFoundWatermarkImage(byte[] imageData) {#setFoundWatermarkImage-byte---}
```
public void setFoundWatermarkImage(byte[] imageData)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageData | byte[] |  |

