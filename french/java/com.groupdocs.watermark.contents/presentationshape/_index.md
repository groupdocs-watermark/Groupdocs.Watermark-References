---
title: "PresentationShape"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente une forme de dessin dans un document PowerPoint."
type: docs
weight: 93
url: /fr/java/com.groupdocs.watermark.contents/presentationshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public class PresentationShape extends PresentationBaseShape implements IRotatableTwoDObject
```

Représente une forme de dessin dans un document PowerPoint.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getRotateAngle()](#getRotateAngle--) | Obtient l'angle de rotation de cet `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` en degrés. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Définit l'angle de rotation de cet `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` en degrés. |
|
|  | [getText()](#getText--) | Obtient le texte de cet `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Définit le texte de cet `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Obtient la collection des fragments de texte formatés de cet `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|
|  | [getShapeType()](#getShapeType--) | Obtient le type de préréglage de géométrie de forme. |
|
|  | [getImage()](#getImage--) | Obtient l'image de cet `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|
|  | [setImage(PresentationWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-) | Définit l'image de cet `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
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


Obtient l'angle de rotation de cet `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` en degrés.


**Returns:**
double - L'angle de rotation de cet `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` en degrés.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Définit l'angle de rotation de cet `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` en degrés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | double | L'angle de rotation de cet `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` en degrés. |
|

### getText() {#getText--}
```
public final String getText()
```


Obtient le texte de cet `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.


**Returns:**
java.lang.String - Le texte de cet `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Définit le texte de cet `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | java.lang.String | Le texte de cet `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Obtient la collection des fragments de texte formatés de cet `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


Obtient le type de préréglage de géométrie de forme.


**Returns:**
int - Le type de préréglage de géométrie.

### getImage() {#getImage--}
```
public final PresentationWatermarkableImage getImage()
```


Obtient l'image de cet `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.


**Returns:**
[PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) - The image of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` or null if the shape has no image.

### setImage(PresentationWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-}
```
public final void setImage(PresentationWatermarkableImage value)
```


Définit l'image de cet `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) | L'image de cet `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` ou null si l'image doit être supprimée. |
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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

