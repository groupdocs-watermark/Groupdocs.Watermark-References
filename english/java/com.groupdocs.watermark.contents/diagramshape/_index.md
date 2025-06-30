---
title: DiagramShape
second_title: GroupDocs.Watermark for Java API Reference
description: Represents a drawing shape in a Visio document.
type: docs
weight: 24
url: /java/com.groupdocs.watermark.contents/diagramshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public class DiagramShape extends ShapeSearchAdapter implements IRotatableTwoDObject
```

Represents a drawing shape in a Visio document.
## Methods

| Method | Description |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
| [getPage()](#getPage--) | Gets the parent page of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
| [getWidth()](#getWidth--) | Gets the width of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in points. |
| [setWidth(double value)](#setWidth-double-) | Sets the width of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in points. |
| [getHeight()](#getHeight--) | Gets the height of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in points. |
| [setHeight(double value)](#setHeight-double-) | Sets the height of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in points. |
| [getX()](#getX--) | Gets the horizontal offset of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` from page left border in points. |
| [setX(double value)](#setX-double-) | Sets the horizontal offset of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` from page left border in points. |
| [getY()](#getY--) | Gets the vertical offset of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` from page bottom border in points. |
| [setY(double value)](#setY-double-) | Sets the vertical offset of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` from page bottom border in points. |
| [getRotateAngle()](#getRotateAngle--) | Gets or sets the rotate angle of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in degrees. |
| [setRotateAngle(double value)](#setRotateAngle-double-) | Gets or sets the rotate angle of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in degrees. |
| [getText()](#getText--) | Gets or sets the text of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
| [setText(String value)](#setText-java.lang.String-) | Gets or sets the text of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
| [getFormattedTextFragments()](#getFormattedTextFragments--) | Gets the collection of formatted text fragments of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
| [getImage()](#getImage--) | Gets the image of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
| [setImage(DiagramWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.DiagramWatermarkableImage-) | Sets the image of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
| [getId()](#getId--) | Gets the identifier of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
| [getName()](#getName--) | Gets the name of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
| [getHyperlinks()](#getHyperlinks--) | Gets the collection of hyperlinks attached to this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
| [getAsposeShape()](#getAsposeShape--) |  |
| [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) |  |
| [getImageForSearch()](#getImageForSearch--) |  |
| [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) |  |
| [getTextForSearch()](#getTextForSearch--) |  |
| [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) |  |
### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```




**Returns:**
java.lang.Integer
### getPage() {#getPage--}
```
public final DiagramPage getPage()
```


Gets the parent page of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

**Returns:**
[DiagramPage](../../com.groupdocs.watermark.contents/diagrampage) - The parent page of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.
### getWidth() {#getWidth--}
```
public final double getWidth()
```


Gets the width of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in points.

**Returns:**
double - The width of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in points.
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Sets the width of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The width of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in points. |

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Gets the height of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in points.

**Returns:**
double - The height of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in points.
### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Sets the height of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The height of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in points. |

### getX() {#getX--}
```
public final double getX()
```


Gets the horizontal offset of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` from page left border in points.

**Returns:**
double - The horizontal offset of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` from page left border in points.
### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Sets the horizontal offset of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` from page left border in points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The horizontal offset of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` from page left border in points. |

### getY() {#getY--}
```
public final double getY()
```


Gets the vertical offset of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` from page bottom border in points.

**Returns:**
double - The vertical offset of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` from page bottom border in points.
### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Sets the vertical offset of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` from page bottom border in points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The vertical offset of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` from page bottom border in points. |

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Gets or sets the rotate angle of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in degrees.

**Returns:**
double - The rotate angle of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in degrees.
### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Gets or sets the rotate angle of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in degrees.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The rotate angle of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` in degrees. |

### getText() {#getText--}
```
public final String getText()
```


Gets or sets the text of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

**Returns:**
java.lang.String - The text of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Gets or sets the text of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The text of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Gets the collection of formatted text fragments of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.
### getImage() {#getImage--}
```
public final DiagramWatermarkableImage getImage()
```


Gets the image of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

**Returns:**
[DiagramWatermarkableImage](../../com.groupdocs.watermark.contents/diagramwatermarkableimage) - The image of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.
### setImage(DiagramWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.DiagramWatermarkableImage-}
```
public final void setImage(DiagramWatermarkableImage value)
```


Sets the image of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DiagramWatermarkableImage](../../com.groupdocs.watermark.contents/diagramwatermarkableimage) | The image of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |

### getId() {#getId--}
```
public final long getId()
```


Gets the identifier of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

**Returns:**
long - The identifier of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.
### getName() {#getName--}
```
public final String getName()
```


Gets the name of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

**Returns:**
java.lang.String - The name of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.
### getHyperlinks() {#getHyperlinks--}
```
public final DiagramHyperlinkCollection getHyperlinks()
```


Gets the collection of hyperlinks attached to this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

**Returns:**
[DiagramHyperlinkCollection](../../com.groupdocs.watermark.contents/diagramhyperlinkcollection) - The collection of hyperlinks attached to this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.
### getAsposeShape() {#getAsposeShape--}
```
public final Shape getAsposeShape()
```




**Returns:**
com.aspose.diagram.Shape
### getFormattedTextFragmentsForSearch() {#getFormattedTextFragmentsForSearch--}
```
public FormattedTextFragmentCollection getFormattedTextFragmentsForSearch()
```




**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
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

