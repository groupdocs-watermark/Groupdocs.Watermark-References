---
title: "PresentationShape"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt eine Zeichenform in einem PowerPoint-Dokument dar."
type: docs
weight: 93
url: /de/java/com.groupdocs.watermark.contents/presentationshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public class PresentationShape extends PresentationBaseShape implements IRotatableTwoDObject
```

Stellt eine Zeichenform in einem PowerPoint-Dokument dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getRotateAngle()](#getRotateAngle--) | Ermittelt den Rotationswinkel dieses `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` in Grad. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Setzt den Rotationswinkel dieses `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` in Grad. |
|
|  | [getText()](#getText--) | Ermittelt den Text dieses `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Setzt den Text dieses `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Ermittelt die Sammlung formatierter Textfragmente dieses `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|
|  | [getShapeType()](#getShapeType--) | Ermittelt den voreingestellten Typ der Formgeometrie. |
|
|  | [getImage()](#getImage--) | Ermittelt das Bild dieses `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|
|  | [setImage(PresentationWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-) | Setzt das Bild dieses `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|
|  | [getImageForSearch()](#getImageForSearch--) | <br /> |

|
|  | [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) | <br /> |

|
|  | [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) | <br /> |

|
|  | [getTextForSearch()](#getTextForSearch--) | <br /> |

|
|  | [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) | <br /> |

|
### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Ermittelt den Rotationswinkel dieses `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` in Grad.


**Returns:**
double - Der Rotationswinkel dieses `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` in Grad.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Setzt den Rotationswinkel dieses `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` in Grad.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | double | Der Rotationswinkel dieses `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` in Grad. |
|

### getText() {#getText--}
```
public final String getText()
```


Ermittelt den Text dieses `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.


**Returns:**
java.lang.String - Der Text dieses `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Setzt den Text dieses `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | java.lang.String | Der Text dieses `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Ermittelt die Sammlung formatierter Textfragmente dieses `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


Ermittelt den voreingestellten Typ der Formgeometrie.


**Returns:**
int - Der vordefinierte Geometrietyp.

### getImage() {#getImage--}
```
public final PresentationWatermarkableImage getImage()
```


Ermittelt das Bild dieses `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.


**Returns:**
[PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) - The image of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` or null if the shape has no image.

### setImage(PresentationWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-}
```
public final void setImage(PresentationWatermarkableImage value)
```


Setzt das Bild dieses `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) | Das Bild dieses `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` oder null, wenn das Bild entfernt werden soll. |
|

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

### getFormattedTextFragmentsForSearch() {#getFormattedTextFragmentsForSearch--}
```
public FormattedTextFragmentCollection getFormattedTextFragmentsForSearch()
```


<br />



**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
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

