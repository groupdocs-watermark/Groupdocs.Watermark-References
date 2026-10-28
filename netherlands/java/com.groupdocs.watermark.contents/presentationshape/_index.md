---
title: "PresentationShape"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt een tekenvorm voor in een PowerPoint-document."
type: docs
weight: 93
url: /nl/java/com.groupdocs.watermark.contents/presentationshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public class PresentationShape extends PresentationBaseShape implements IRotatableTwoDObject
```

Stelt een tekenvorm voor in een PowerPoint-document.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getRotateAngle()](#getRotateAngle--) | Haalt de rotatiehoek van deze `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` op in graden. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Stelt de rotatiehoek van deze `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` in graden in. |
|
|  | [getText()](#getText--) | Haalt de tekst van deze `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` op. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Stelt de tekst van deze `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` in. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Haalt de collectie van opgemaakte tekstfragmenten van deze `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` op. |
|
|  | [getShapeType()](#getShapeType--) | Haalt het preset-type van de vormgeometrie op. |
|
|  | [getImage()](#getImage--) | Haalt de afbeelding van deze `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` op. |
|
|  | [setImage(PresentationWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-) | Stelt de afbeelding van deze `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` in. |
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


Haalt de rotatiehoek van deze `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` op in graden.


**Returns:**
double - De rotatiehoek van deze `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` in graden.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Stelt de rotatiehoek van deze `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` in graden in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | double | De rotatiehoek van deze `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` in graden. |
|

### getText() {#getText--}
```
public final String getText()
```


Haalt de tekst van deze `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` op.


**Returns:**
java.lang.String - De tekst van deze `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Stelt de tekst van deze `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | java.lang.String | De tekst van deze `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Haalt de collectie van opgemaakte tekstfragmenten van deze `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` op.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


Haalt het preset-type van de vormgeometrie op.


**Returns:**
int - Het preset-type van de geometrie.

### getImage() {#getImage--}
```
public final PresentationWatermarkableImage getImage()
```


Haalt de afbeelding van deze `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` op.


**Returns:**
[PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) - The image of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` or null if the shape has no image.

### setImage(PresentationWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-}
```
public final void setImage(PresentationWatermarkableImage value)
```


Stelt de afbeelding van deze `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) | De afbeelding van deze `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` of null als de afbeelding verwijderd moet worden. |
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
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

