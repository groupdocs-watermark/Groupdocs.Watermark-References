---
title: WordProcessingShape
second_title: GroupDocs.Watermark for Java API Reference
description: Represents a drawing shape in a Word document.
type: docs
weight: 141
url: /java/com.groupdocs.watermark.contents/wordprocessingshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject), [com.groupdocs.watermark.search.IHyperlinkContainer](../../com.groupdocs.watermark.search/ihyperlinkcontainer)
```
public class WordProcessingShape extends ShapeSearchAdapter implements IRotatableTwoDObject, IHyperlinkContainer
```

Represents a drawing shape in a Word document.
## Methods

| Method | Description |
| --- | --- |
| [getSection()](#getSection--) | Gets the parent section of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
| [getHeaderFooter()](#getHeaderFooter--) | Gets the parent header/footer of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` (if presents). |
| [getShapeType()](#getShapeType--) | Gets the shape type. |
| [isWordArt()](#isWordArt--) | Gets a value indicating whether this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` is a WordArt object. |
| [getAlternativeText()](#getAlternativeText--) | Gets the descriptive (alternative) text associated with this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Sets the descriptive (alternative) text associated with this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
| [getName()](#getName--) | Gets the name of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
| [getBehindText()](#getBehindText--) | Gets a value indicating whether the shape is over or behind the text. |
| [setBehindText(boolean value)](#setBehindText-boolean-) | Sets a value indicating whether the shape is over or behind the text. |
| [getText()](#getText--) | Gets the text of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
| [setText(String value)](#setText-java.lang.String-) | Sets the text of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
| [getFormattedTextFragments()](#getFormattedTextFragments--) | Gets the collection of formatted text fragments of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
| [getImage()](#getImage--) | Gets the image of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
| [setImage(WordProcessingWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.WordProcessingWatermarkableImage-) | Sets the image of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Gets a value specifying how the shape is positioned horizontally. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Gets a value specifying how the shape is positioned vertically. |
| [getRelativeHorizontalPosition()](#getRelativeHorizontalPosition--) | Gets a value specifying to what the shape is positioned horizontally. |
| [getRelativeVerticalPosition()](#getRelativeVerticalPosition--) | Gets a value specifying to what the shape is positioned vertically. |
| [getImageFillFormat()](#getImageFillFormat--) |  |
| [getAsposeWordsShape()](#getAsposeWordsShape--) |  |
| [getHyperlink()](#getHyperlink--) | Gets the hyperlink associated with this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
| [setHyperlink(String value)](#setHyperlink-java.lang.String-) | Sets the hyperlink associated with this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
| [getWidth()](#getWidth--) | Gets the width of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in points. |
| [setWidth(double value)](#setWidth-double-) | Sets the width of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in points. |
| [getHeight()](#getHeight--) | Gets the height of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in points. |
| [setHeight(double value)](#setHeight-double-) | Sets the height of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in points. |
| [getRotateAngle()](#getRotateAngle--) | Gets the rotate angle of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in degrees. |
| [setRotateAngle(double value)](#setRotateAngle-double-) | Sets the rotate angle of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in degrees. |
| [getX()](#getX--) | Gets or sets the horizontal offset of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` from page left border in points. |
| [setX(double value)](#setX-double-) | Gets or sets the horizontal offset of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` from page left border in points. |
| [getY()](#getY--) | Gets the vertical offset of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` from page top border in points. |
| [setY(double value)](#setY-double-) | Sets the vertical offset of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` from page top border in points. |
| [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) |  |
| [getTextForSearch()](#getTextForSearch--) |  |
| [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) |  |
| [getImageForSearch()](#getImageForSearch--) |  |
| [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) |  |
### getSection() {#getSection--}
```
public final WordProcessingSection getSection()
```


Gets the parent section of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

**Returns:**
[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection) - The parent section of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.
### getHeaderFooter() {#getHeaderFooter--}
```
public final WordProcessingHeaderFooter getHeaderFooter()
```


Gets the parent header/footer of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` (if presents).

**Returns:**
[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter) - The parent header/footer of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.
### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


Gets the shape type.

**Returns:**
int - The shape type.
### isWordArt() {#isWordArt--}
```
public final boolean isWordArt()
```


Gets a value indicating whether this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` is a WordArt object.

**Returns:**
boolean - True if the shape is a WordArt object; otherwise, false.
### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Gets the descriptive (alternative) text associated with this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

**Returns:**
java.lang.String - The descriptive (alternative) text associated with this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Sets the descriptive (alternative) text associated with this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The descriptive (alternative) text associated with this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |

### getName() {#getName--}
```
public final String getName()
```


Gets the name of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

**Returns:**
java.lang.String - The name of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.
### getBehindText() {#getBehindText--}
```
public final boolean getBehindText()
```


Gets a value indicating whether the shape is over or behind the text.

**Returns:**
boolean - The value indicating whether the shape is over or behind the text. True if the shape is behind the text; otherwise, false.
### setBehindText(boolean value) {#setBehindText-boolean-}
```
public final void setBehindText(boolean value)
```


Sets a value indicating whether the shape is over or behind the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | The value indicating whether the shape is over or behind the text. True if the shape is behind the text; otherwise, false. |

### getText() {#getText--}
```
public final String getText()
```


Gets the text of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

**Returns:**
java.lang.String - The text of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Sets the text of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The text of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Gets the collection of formatted text fragments of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.
### getImage() {#getImage--}
```
public final WordProcessingWatermarkableImage getImage()
```


Gets the image of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

**Returns:**
[WordProcessingWatermarkableImage](../../com.groupdocs.watermark.contents/wordprocessingwatermarkableimage) - The image of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` or `null` if the shape has no image.
### setImage(WordProcessingWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.WordProcessingWatermarkableImage-}
```
public final void setImage(WordProcessingWatermarkableImage value)
```


Sets the image of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WordProcessingWatermarkableImage](../../com.groupdocs.watermark.contents/wordprocessingwatermarkableimage) | The image of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` or `null` if the image should be removed. |

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


Gets a value specifying how the shape is positioned horizontally.

**Returns:**
int - The horizontal alignment value.
### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Gets a value specifying how the shape is positioned vertically.

**Returns:**
int - The vertical alignment value.
### getRelativeHorizontalPosition() {#getRelativeHorizontalPosition--}
```
public final int getRelativeHorizontalPosition()
```


Gets a value specifying to what the shape is positioned horizontally.

**Returns:**
int - The relative horizontal position value.
### getRelativeVerticalPosition() {#getRelativeVerticalPosition--}
```
public final int getRelativeVerticalPosition()
```


Gets a value specifying to what the shape is positioned vertically.

**Returns:**
int - The relative vertical position value.
### getImageFillFormat() {#getImageFillFormat--}
```
public final WordProcessingImageFillFormat getImageFillFormat()
```




**Returns:**
[WordProcessingImageFillFormat](../../com.groupdocs.watermark.internal/wordprocessingimagefillformat)
### getAsposeWordsShape() {#getAsposeWordsShape--}
```
public final Shape getAsposeWordsShape()
```




**Returns:**
com.aspose.words.Shape
### getHyperlink() {#getHyperlink--}
```
public final String getHyperlink()
```


Gets the hyperlink associated with this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

**Returns:**
java.lang.String - The hyperlink associated with this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.
### setHyperlink(String value) {#setHyperlink-java.lang.String-}
```
public final void setHyperlink(String value)
```


Sets the hyperlink associated with this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The hyperlink associated with this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Gets the width of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in points.

**Returns:**
double - The width of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in points.
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Sets the width of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The width of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in points. |

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Gets the height of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in points.

**Returns:**
double - The height of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in points.
### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Sets the height of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The height of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in points. |

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Gets the rotate angle of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in degrees.

**Returns:**
double - The rotate angle of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in degrees.
### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Sets the rotate angle of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in degrees.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The rotate angle of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in degrees. |

### getX() {#getX--}
```
public final double getX()
```


Gets or sets the horizontal offset of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` from page left border in points.

**Returns:**
double - The x-coordinate of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.
### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Gets or sets the horizontal offset of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` from page left border in points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The x-coordinate of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |

### getY() {#getY--}
```
public final double getY()
```


Gets the vertical offset of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` from page top border in points.

**Returns:**
double - The y-coordinate of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.
### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Sets the vertical offset of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` from page top border in points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The y-coordinate of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |

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

