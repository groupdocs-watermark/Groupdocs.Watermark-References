---
title: "PdfShape"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Tillhandahåller basklass för XObjects artefakter och anmärkningar."
type: docs
weight: 69
url: /sv/java/com.groupdocs.watermark.contents/pdfshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public abstract class PdfShape extends ShapeSearchAdapter implements IRotatableTwoDObject
```

Tillhandahåller basklass för XObjects, Artifacts och Annotations.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getText()](#getText--) | Hämtar texten för detta `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Hämtar eller anger texten för detta `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Hämtar samlingen av formaterade textfragment för detta `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|
|  | [getImage()](#getImage--) | Hämtar bilden för detta `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|
|  | [setImage(PdfWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.PdfWatermarkableImage-) | Anger bilden för detta `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|
|  | [getX()](#getX--) | Hämtar x-koordinaten för objektet. |
|
|  | [getY()](#getY--) | Hämtar y-koordinaten för objektet. |
|
|  | [getWidth()](#getWidth--) | Hämtar bredden på objektet. |
|
|  | [getHeight()](#getHeight--) | Hämtar höjden på objektet. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Hämtar rotationsvinkeln för objektet i grader. |
|
|  | [getOuterForm()](#getOuterForm--) | <br /> |

|
|  | [extractImageAppearance()](#extractImageAppearance--) | <br /> |

|
|  | [getTextForSearch()](#getTextForSearch--) | <br /> |

|
|  | [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) | <br /> |

|
|  | [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) | <br /> |

|
|  | [getImageForSearch()](#getImageForSearch--) | <br /> |

|
|  | [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) | <br /> |

|
### getText() {#getText--}
```
public String getText()
```


Hämtar texten för detta `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.


**Returns:**
java.lang.String - Texten för detta `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Hämtar eller anger texten för detta `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.String | Texten för detta `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Hämtar samlingen av formaterade textfragment för detta `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.

### getImage() {#getImage--}
```
public final PdfWatermarkableImage getImage()
```


Hämtar bilden för detta `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.


**Returns:**
[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage) - The image of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.

### setImage(PdfWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.PdfWatermarkableImage-}
```
public final void setImage(PdfWatermarkableImage value)
```


Anger bilden för detta `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage) | Bilden för detta `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|

### getX() {#getX--}
```
public abstract double getX()
```


Hämtar x-koordinaten för objektet.


**Returns:**
double - X-koordinaten för objektet.

### getY() {#getY--}
```
public abstract double getY()
```


Hämtar y-koordinaten för objektet.


**Returns:**
double - Y-koordinaten för objektet.

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Hämtar bredden på objektet.


**Returns:**
double - Bredden på objektet.

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Hämtar höjden på objektet.


**Returns:**
double - Höjden på objektet.

### getRotateAngle() {#getRotateAngle--}
```
public abstract double getRotateAngle()
```


Hämtar rotationsvinkeln för objektet i grader.


**Returns:**
double - rotationsvinkeln för objektet i grader.

### getOuterForm() {#getOuterForm--}
```
public abstract XForm getOuterForm()
```


<br />



**Returns:**
com.aspose.pdf.XForm
### extractImageAppearance() {#extractImageAppearance--}
```
public PdfXImageAppearance extractImageAppearance()
```


<br />



**Returns:**
[PdfXImageAppearance](../../com.groupdocs.watermark.internal/pdfximageappearance)
### getTextForSearch() {#getTextForSearch--}
```
public String getTextForSearch()
```


<br />



**Returns:**
java.lang.String
### setFoundWatermarkText(String value) {#setFoundWatermarkText-java.lang.String-}
```
public void setFoundWatermarkText(String value)
```


<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getFormattedTextFragmentsForSearch() {#getFormattedTextFragmentsForSearch--}
```
public FormattedTextFragmentCollection getFormattedTextFragmentsForSearch()
```


<br />



**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
### getImageForSearch() {#getImageForSearch--}
```
public WatermarkableImage getImageForSearch()
```


<br />



**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### setFoundWatermarkImage(byte[] imageData) {#setFoundWatermarkImage-byte---}
```
public void setFoundWatermarkImage(byte[] imageData)
```


<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageData | byte[] |  |

