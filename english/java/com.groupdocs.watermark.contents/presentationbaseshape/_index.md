---
title: PresentationBaseShape
second_title: GroupDocs.Watermark for Java API Reference
description: Provides the abstract base class for shapes of all types in a PowerPoint document.
type: docs
weight: 77
url: /java/com.groupdocs.watermark.contents/presentationbaseshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.ITwoDObject](../../com.groupdocs.watermark.search/itwodobject), [com.groupdocs.watermark.contents.IPresentationHyperlinkContainer](../../com.groupdocs.watermark.contents/ipresentationhyperlinkcontainer)
```
public abstract class PresentationBaseShape extends ShapeSearchAdapter implements ITwoDObject, IPresentationHyperlinkContainer
```

Provides the abstract base class for shapes of all types in a PowerPoint document.
## Methods

| Method | Description |
| --- | --- |
| [getPresentation()](#getPresentation--) | Gets the parent presentation of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
| [getImageFillFormat()](#getImageFillFormat--) | Gets the image fill format settings of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
| [getName()](#getName--) | Gets the name of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
| [getAlternativeText()](#getAlternativeText--) | Gets the descriptive (alternative) text associated with this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Sets the descriptive (alternative) text associated with this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
| [getId()](#getId--) | Gets the identifier of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
| [getZOrderPosition()](#getZOrderPosition--) | Gets the position of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in the z-order. |
| [getHyperlink(int actionType)](#getHyperlink-int-) | Gets the hyperlink associated with this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
| [setHyperlink(int actionType, String url)](#setHyperlink-int-java.lang.String-) | Sets the hyperlink associated with this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
| [getX()](#getX--) | Gets the horizontal offset of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` from presentation left border in points. |
| [setX(double value)](#setX-double-) | Sets the horizontal offset of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` from presentation left border in points. |
| [getY()](#getY--) | Gets or sets the vertical offset of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` from presentation top border in points. |
| [setY(double value)](#setY-double-) | Gets or sets the vertical offset of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` from presentation top border in points. |
| [getWidth()](#getWidth--) | Gets the width of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in points. |
| [setWidth(double value)](#setWidth-double-) | Sets the width of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in points. |
| [getHeight()](#getHeight--) | Gets the height of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in points. |
| [setHeight(double value)](#setHeight-double-) | Sets the height of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in points. |
### getPresentation() {#getPresentation--}
```
public final PresentationBaseSlide getPresentation()
```


Gets the parent presentation of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

**Returns:**
[PresentationBaseSlide](../../com.groupdocs.watermark.contents/presentationbaseslide) - The parent presentation of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.
### getImageFillFormat() {#getImageFillFormat--}
```
public final PresentationImageFillFormat getImageFillFormat()
```


Gets the image fill format settings of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

**Returns:**
[PresentationImageFillFormat](../../com.groupdocs.watermark.contents/presentationimagefillformat) - The image fill format settings of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.
### getName() {#getName--}
```
public final String getName()
```


Gets the name of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

**Returns:**
java.lang.String - The name of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.
### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Gets the descriptive (alternative) text associated with this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

**Returns:**
java.lang.String - The descriptive (alternative) text associated with this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Sets the descriptive (alternative) text associated with this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The descriptive (alternative) text associated with this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |

### getId() {#getId--}
```
public final long getId()
```


Gets the identifier of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

**Returns:**
long - The identifier of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.
### getZOrderPosition() {#getZOrderPosition--}
```
public final int getZOrderPosition()
```


Gets the position of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in the z-order.

A shape with greater z-order is always in front of a shape with a lower z-order.

**Returns:**
int - The position of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in the z-order.
### getHyperlink(int actionType) {#getHyperlink-int-}
```
public final String getHyperlink(int actionType)
```


Gets the hyperlink associated with this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| actionType | int | The action that activates the hyperlink. |

**Returns:**
java.lang.String - The url of the hyperlink that is activated on specified action.
### setHyperlink(int actionType, String url) {#setHyperlink-int-java.lang.String-}
```
public final void setHyperlink(int actionType, String url)
```


Sets the hyperlink associated with this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| actionType | int | The action that activates the hyperlink. |
| url | java.lang.String | The hyperlink url. |

### getX() {#getX--}
```
public final double getX()
```


Gets the horizontal offset of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` from presentation left border in points.

**Returns:**
double - The x-coordinate of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.
### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Sets the horizontal offset of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` from presentation left border in points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The x-coordinate of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |

### getY() {#getY--}
```
public final double getY()
```


Gets or sets the vertical offset of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` from presentation top border in points.

**Returns:**
double - The y-coordinate of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.
### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Gets or sets the vertical offset of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` from presentation top border in points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The y-coordinate of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Gets the width of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in points.

**Returns:**
double - The width of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in points.
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Sets the width of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The width of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in points. |

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Gets the height of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in points.

**Returns:**
double - The height of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in points.
### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Sets the height of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The height of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in points. |

