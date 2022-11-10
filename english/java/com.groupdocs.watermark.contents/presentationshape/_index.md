---
title: PresentationShape
second_title: GroupDocs.Watermark for Java API Reference
description: Represents a drawing shape in a PowerPoint document.
type: docs
weight: 93
url: /java/com.groupdocs.watermark.contents/presentationshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public class PresentationShape extends PresentationBaseShape implements IRotatableTwoDObject
```

Represents a drawing shape in a PowerPoint document.
## Methods

| Method | Description |
| --- | --- |
| [getRotateAngle()](#getRotateAngle--) | Gets the rotate angle of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` in degrees. |
| [setRotateAngle(double value)](#setRotateAngle-double-) | Sets the rotate angle of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` in degrees. |
| [getText()](#getText--) | Gets the text of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
| [setText(String value)](#setText-java.lang.String-) | Sets the text of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
| [getFormattedTextFragments()](#getFormattedTextFragments--) | Gets the collection of formatted text fragments of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
| [getShapeType()](#getShapeType--) | Gets the shape geometry preset type. |
| [getImage()](#getImage--) | Gets the image of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
| [setImage(PresentationWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-) | Sets the image of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
| [getImageForSearch()](#getImageForSearch--) |  |
| [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) |  |
| [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) |  |
| [getTextForSearch()](#getTextForSearch--) |  |
| [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) |  |
### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Gets the rotate angle of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` in degrees.

**Returns:**
double - The rotate angle of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` in degrees.
### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Sets the rotate angle of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` in degrees.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The rotate angle of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` in degrees. |

### getText() {#getText--}
```
public final String getText()
```


Gets the text of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.

**Returns:**
java.lang.String - The text of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Sets the text of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The text of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Gets the collection of formatted text fragments of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.

**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.
### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


Gets the shape geometry preset type.

**Returns:**
int - The geometry preset type.
### getImage() {#getImage--}
```
public final PresentationWatermarkableImage getImage()
```


Gets the image of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.

**Returns:**
[PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) - The image of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` or null if the shape has no image.
### setImage(PresentationWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-}
```
public final void setImage(PresentationWatermarkableImage value)
```


Sets the image of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) | The image of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` or null if the image should be removed. |

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

### getFormattedTextFragmentsForSearch() {#getFormattedTextFragmentsForSearch--}
```
public FormattedTextFragmentCollection getFormattedTextFragmentsForSearch()
```




**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
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

