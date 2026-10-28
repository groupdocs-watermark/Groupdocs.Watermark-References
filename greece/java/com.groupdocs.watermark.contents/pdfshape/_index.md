---
title: "PdfShape"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Παρέχει τη βασική κλάση για τα XObjects, τα Αντικείμενα και τις Σχόλια."
type: docs
weight: 69
url: /el/java/com.groupdocs.watermark.contents/pdfshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public abstract class PdfShape extends ShapeSearchAdapter implements IRotatableTwoDObject
```

Παρέχει τη βασική κλάση για XObjects, Artifacts και Annotations.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getText()](#getText--) | Λαμβάνει το κείμενο αυτού του `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Λαμβάνει ή ορίζει το κείμενο αυτού του `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Λαμβάνει τη συλλογή των μορφοποιημένων τμημάτων κειμένου αυτού του `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|
|  | [getImage()](#getImage--) | Λαμβάνει την εικόνα αυτού του `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|
|  | [setImage(PdfWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.PdfWatermarkableImage-) | Ορίζει την εικόνα αυτού του `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|
|  | [getX()](#getX--) | Λαμβάνει τη συντεταγμένη x του αντικειμένου. |
|
|  | [getY()](#getY--) | Λαμβάνει τη συντεταγμένη y του αντικειμένου. |
|
|  | [getWidth()](#getWidth--) | Λαμβάνει το πλάτος του αντικειμένου. |
|
|  | [getHeight()](#getHeight--) | Λαμβάνει το ύψος του αντικειμένου. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Λαμβάνει τη γωνία περιστροφής του αντικειμένου σε μοίρες. |
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


Λαμβάνει το κείμενο αυτού του `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.


**Returns:**
java.lang.String - Το κείμενο αυτού του `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Λαμβάνει ή ορίζει το κείμενο αυτού του `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.lang.String | Το κείμενο αυτού του `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Λαμβάνει τη συλλογή των μορφοποιημένων τμημάτων κειμένου αυτού του `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.

### getImage() {#getImage--}
```
public final PdfWatermarkableImage getImage()
```


Λαμβάνει την εικόνα αυτού του `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.


**Returns:**
[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage) - The image of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.

### setImage(PdfWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.PdfWatermarkableImage-}
```
public final void setImage(PdfWatermarkableImage value)
```


Ορίζει την εικόνα αυτού του `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage) | Η εικόνα αυτού του `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|

### getX() {#getX--}
```
public abstract double getX()
```


Λαμβάνει τη συντεταγμένη x του αντικειμένου.


**Returns:**
double - Η συντεταγμένη x του αντικειμένου.

### getY() {#getY--}
```
public abstract double getY()
```


Λαμβάνει τη συντεταγμένη y του αντικειμένου.


**Returns:**
double - Η συντεταγμένη y του αντικειμένου.

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Λαμβάνει το πλάτος του αντικειμένου.


**Returns:**
double - Το πλάτος του αντικειμένου.

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Λαμβάνει το ύψος του αντικειμένου.


**Returns:**
double - Το ύψος του αντικειμένου.

### getRotateAngle() {#getRotateAngle--}
```
public abstract double getRotateAngle()
```


Λαμβάνει τη γωνία περιστροφής του αντικειμένου σε μοίρες.


**Returns:**
double - Η γωνία περιστροφής του αντικειμένου σε μοίρες.

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageData | byte[] |  |

