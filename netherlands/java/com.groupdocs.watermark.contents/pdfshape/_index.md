---
title: "PdfShape"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Biedt een basisklasse voor XObjects Artefacten en Annotaties."
type: docs
weight: 69
url: /nl/java/com.groupdocs.watermark.contents/pdfshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public abstract class PdfShape extends ShapeSearchAdapter implements IRotatableTwoDObject
```

Biedt een basisklasse voor XObjects, Artefacten en Annotaties.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getText()](#getText--) | Haalt de tekst van dit `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` op. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Haalt de tekst van dit `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` op of stelt deze in. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Haalt de collectie van geformatteerde tekstfragmenten van dit `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` op. |
|
|  | [getImage()](#getImage--) | Haalt de afbeelding van dit `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` op. |
|
|  | [setImage(PdfWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.PdfWatermarkableImage-) | Stelt de afbeelding van deze `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` in. |
|
|  | [getX()](#getX--) | Haalt de x-coördinaat van het object op. |
|
|  | [getY()](#getY--) | Haalt de y-coördinaat van het object op. |
|
|  | [getWidth()](#getWidth--) | Haalt de breedte van het object op. |
|
|  | [getHeight()](#getHeight--) | Haalt de hoogte van het object op. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Haalt de rotatiehoek van het object op in graden. |
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


Haalt de tekst van dit `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` op.


**Returns:**
java.lang.String - De tekst van deze `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Haalt de tekst van dit `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` op of stelt deze in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | java.lang.String | De tekst van deze `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Haalt de collectie van geformatteerde tekstfragmenten van dit `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` op.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.

### getImage() {#getImage--}
```
public final PdfWatermarkableImage getImage()
```


Haalt de afbeelding van dit `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` op.


**Returns:**
[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage) - The image of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.

### setImage(PdfWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.PdfWatermarkableImage-}
```
public final void setImage(PdfWatermarkableImage value)
```


Stelt de afbeelding van deze `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage) | De afbeelding van deze `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|

### getX() {#getX--}
```
public abstract double getX()
```


Haalt de x-coördinaat van het object op.


**Returns:**
double - De x-coördinaat van het object.

### getY() {#getY--}
```
public abstract double getY()
```


Haalt de y-coördinaat van het object op.


**Returns:**
double - De y-coördinaat van het object.

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Haalt de breedte van het object op.


**Returns:**
double - De breedte van het object.

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Haalt de hoogte van het object op.


**Returns:**
double - De hoogte van het object.

### getRotateAngle() {#getRotateAngle--}
```
public abstract double getRotateAngle()
```


Haalt de rotatiehoek van het object op in graden.


**Returns:**
double - De rotatiehoek van het object in graden.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| imageData | byte[] |  |

