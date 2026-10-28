---
title: "PdfShape"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Fournit la classe de base pour les artefacts XObjects et les annotations."
type: docs
weight: 69
url: /fr/java/com.groupdocs.watermark.contents/pdfshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public abstract class PdfShape extends ShapeSearchAdapter implements IRotatableTwoDObject
```

Fournit une classe de base pour les XObjects, les Artefacts et les Annotations.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getText()](#getText--) | Obtient le texte de ce `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Obtient ou définit le texte de ce `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Obtient la collection de fragments de texte formatés de ce `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|
|  | [getImage()](#getImage--) | Obtient l'image de ce `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|
|  | [setImage(PdfWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.PdfWatermarkableImage-) | Définit l'image de ce `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|
|  | [getX()](#getX--) | Obtient la coordonnée x de l'objet. |
|
|  | [getY()](#getY--) | Obtient la coordonnée y de l'objet. |
|
|  | [getWidth()](#getWidth--) | Obtient la largeur de l'objet. |
|
|  | [getHeight()](#getHeight--) | Obtient la hauteur de l'objet. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Obtient l'angle de rotation de l'objet en degrés. |
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


Obtient le texte de ce `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.


**Returns:**
java.lang.String - Le texte de ce `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Obtient ou définit le texte de ce `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | java.lang.String | Le texte de ce `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Obtient la collection de fragments de texte formatés de ce `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.

### getImage() {#getImage--}
```
public final PdfWatermarkableImage getImage()
```


Obtient l'image de ce `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.


**Returns:**
[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage) - The image of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.

### setImage(PdfWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.PdfWatermarkableImage-}
```
public final void setImage(PdfWatermarkableImage value)
```


Définit l'image de ce `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage) | L'image de ce `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|

### getX() {#getX--}
```
public abstract double getX()
```


Obtient la coordonnée x de l'objet.


**Returns:**
double - La coordonnée x de l'objet.

### getY() {#getY--}
```
public abstract double getY()
```


Obtient la coordonnée y de l'objet.


**Returns:**
double - La coordonnée y de l'objet.

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Obtient la largeur de l'objet.


**Returns:**
double - La largeur de l'objet.

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Obtient la hauteur de l'objet.


**Returns:**
double - La hauteur de l'objet.

### getRotateAngle() {#getRotateAngle--}
```
public abstract double getRotateAngle()
```


Obtient l'angle de rotation de l'objet en degrés.


**Returns:**
double - L'angle de rotation de l'objet en degrés.

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
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| imageData | byte[] |  |

