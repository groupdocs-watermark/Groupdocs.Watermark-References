---
title: "PdfShape"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt die Basisklasse für XObjects, Artefakte und Anmerkungen bereit."
type: docs
weight: 69
url: /de/java/com.groupdocs.watermark.contents/pdfshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public abstract class PdfShape extends ShapeSearchAdapter implements IRotatableTwoDObject
```

Stellt eine Basisklasse für XObjects, Artefakte und Anmerkungen bereit.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getText()](#getText--) | Liefert den Text dieses `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Liefert oder setzt den Text dieses `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Liefert die Sammlung formatierter Textfragmente dieses `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|
|  | [getImage()](#getImage--) | Liefert das Bild dieses `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|
|  | [setImage(PdfWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.PdfWatermarkableImage-) | Setzt das Bild dieses `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|
|  | [getX()](#getX--) | Liefert die x-Koordinate des Objekts. |
|
|  | [getY()](#getY--) | Liefert die y-Koordinate des Objekts. |
|
|  | [getWidth()](#getWidth--) | Liefert die Breite des Objekts. |
|
|  | [getHeight()](#getHeight--) | Liefert die Höhe des Objekts. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Gibt den Rotationswinkel des Objekts in Grad zurück. |
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


Liefert den Text dieses `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.


**Returns:**
java.lang.String - Der Text dieses `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Liefert oder setzt den Text dieses `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | java.lang.String | Der Text dieses `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Liefert die Sammlung formatierter Textfragmente dieses `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.

### getImage() {#getImage--}
```
public final PdfWatermarkableImage getImage()
```


Liefert das Bild dieses `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.


**Returns:**
[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage) - The image of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.

### setImage(PdfWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.PdfWatermarkableImage-}
```
public final void setImage(PdfWatermarkableImage value)
```


Setzt das Bild dieses `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage) | Das Bild dieses `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|

### getX() {#getX--}
```
public abstract double getX()
```


Liefert die x-Koordinate des Objekts.


**Returns:**
double - Die x-Koordinate des Objekts.

### getY() {#getY--}
```
public abstract double getY()
```


Liefert die y-Koordinate des Objekts.


**Returns:**
double - Die y-Koordinate des Objekts.

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Liefert die Breite des Objekts.


**Returns:**
double - Die Breite des Objekts.

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Liefert die Höhe des Objekts.


**Returns:**
double - Die Höhe des Objekts.

### getRotateAngle() {#getRotateAngle--}
```
public abstract double getRotateAngle()
```


Gibt den Rotationswinkel des Objekts in Grad zurück.


**Returns:**
double - Der Rotationswinkel des Objekts in Grad.

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageData | byte[] |  |

