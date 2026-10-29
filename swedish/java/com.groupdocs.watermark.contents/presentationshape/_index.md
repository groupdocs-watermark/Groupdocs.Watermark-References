---
title: "PresentationShape"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar en ritningsform i ett PowerPoint-dokument."
type: docs
weight: 93
url: /sv/java/com.groupdocs.watermark.contents/presentationshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public class PresentationShape extends PresentationBaseShape implements IRotatableTwoDObject
```

Representerar en ritningsform i ett PowerPoint-dokument.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getRotateAngle()](#getRotateAngle--) | Hämtar rotationsvinkeln för detta `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` i grader. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Ställer in rotationsvinkeln för detta `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` i grader. |
|
|  | [getText()](#getText--) | Hämtar texten för detta `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Ställer in texten för detta `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Hämtar samlingen av formaterade textfragment för detta `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|
|  | [getShapeType()](#getShapeType--) | Hämtar förinställd typ för formens geometri. |
|
|  | [getImage()](#getImage--) | Hämtar bilden för detta `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|
|  | [setImage(PresentationWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-) | Ställer in bilden för detta `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
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


Hämtar rotationsvinkeln för detta `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` i grader.


**Returns:**
double - Rotationsvinkeln för detta `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` i grader.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Ställer in rotationsvinkeln för detta `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` i grader.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | double | Rotationsvinkeln för detta `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` i grader. |
|

### getText() {#getText--}
```
public final String getText()
```


Hämtar texten för detta `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.


**Returns:**
java.lang.String - Texten för detta `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Ställer in texten för detta `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.String | Texten för detta `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Hämtar samlingen av formaterade textfragment för detta `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


Hämtar förinställd typ för formens geometri.


**Returns:**
int - Den förinställda geometritypen.

### getImage() {#getImage--}
```
public final PresentationWatermarkableImage getImage()
```


Hämtar bilden för detta `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.


**Returns:**
[PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) - The image of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` or null if the shape has no image.

### setImage(PresentationWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-}
```
public final void setImage(PresentationWatermarkableImage value)
```


Ställer in bilden för detta `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) | Bilden för detta `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` eller null om bilden ska tas bort. |
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
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

