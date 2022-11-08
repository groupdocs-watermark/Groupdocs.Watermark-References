---
title: SpreadsheetShape
second_title: GroupDocs.Watermark for Java API Reference
description: Represents a drawing shape in an Excel document.
type: docs
weight: 117
url: /java/com.groupdocs.watermark.contents/spreadsheetshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject), [com.groupdocs.watermark.search.IHyperlinkContainer](../../com.groupdocs.watermark.search/ihyperlinkcontainer)
```
public class SpreadsheetShape extends ShapeSearchAdapter implements IRotatableTwoDObject, IHyperlinkContainer
```

Represents a drawing shape in an Excel document.
## Methods

| Method | Description |
| --- | --- |
| [getWorksheet()](#getWorksheet--) | Gets the parent worksheet of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
| [getAutoShapeType()](#getAutoShapeType--) | Gets the auto shape type. |
| [getMsoDrawingType()](#getMsoDrawingType--) | Gets the mso drawing type. |
| [getText()](#getText--) | Gets the text of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
| [setText(String value)](#setText-java.lang.String-) | Sets the text of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
| [getFormattedTextFragments()](#getFormattedTextFragments--) | Gets the collection of formatted text fragments of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
| [getImage()](#getImage--) | Gets the image of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
| [setImage(SpreadsheetWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | Sets the image of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
| [getImageFillFormat()](#getImageFillFormat--) | Gets the image fill format settings of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
| [getId()](#getId--) | Gets the identifier of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
| [getAlternativeText()](#getAlternativeText--) | Gets the descriptive (alternative) text associated with this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Sets the descriptive (alternative) text associated with this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
| [isWordArt()](#isWordArt--) | Gets a value indicating whether this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` is a WordArt object. |
| [getName()](#getName--) | Gets the name of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
| [getAsposeCellsShape()](#getAsposeCellsShape--) |  |
| [getHyperlink()](#getHyperlink--) | Gets the hyperlink associated with this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
| [setHyperlink(String value)](#setHyperlink-java.lang.String-) | Sets the hyperlink associated with this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
| [getX()](#getX--) | Gets the horizontal offset of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` from worksheet left border in points. |
| [setX(double value)](#setX-double-) | Sets the horizontal offset of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` from worksheet left border in points. |
| [getY()](#getY--) | Gets the vertical offset of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` from worksheet top border in points. |
| [setY(double value)](#setY-double-) | Sets the vertical offset of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` from worksheet top border in points. |
| [getWidth()](#getWidth--) | Gets the width of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in points. |
| [setWidth(double value)](#setWidth-double-) | Sets the width of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in points. |
| [getHeight()](#getHeight--) | Gets the height of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in points. |
| [setHeight(double value)](#setHeight-double-) | Sets the height of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in points. |
| [getRotateAngle()](#getRotateAngle--) | Gets or sets the rotate angle of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in degrees. |
| [setRotateAngle(double value)](#setRotateAngle-double-) | Gets or sets the rotate angle of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in degrees. |
| [getImageForSearch()](#getImageForSearch--) |  |
| [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) |  |
| [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) |  |
| [getTextForSearch()](#getTextForSearch--) |  |
| [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) |  |
### getWorksheet() {#getWorksheet--}
```
public final SpreadsheetWorksheet getWorksheet()
```


Gets the parent worksheet of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

**Returns:**
[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) - The parent worksheet of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.
### getAutoShapeType() {#getAutoShapeType--}
```
public final int getAutoShapeType()
```


Gets the auto shape type.

**Returns:**
int - The auto shape type.
### getMsoDrawingType() {#getMsoDrawingType--}
```
public final int getMsoDrawingType()
```


Gets the mso drawing type.

**Returns:**
int - The mso drawing type.
### getText() {#getText--}
```
public final String getText()
```


Gets the text of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

**Returns:**
java.lang.String - The text of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Sets the text of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The text of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Gets the collection of formatted text fragments of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.
### getImage() {#getImage--}
```
public final SpreadsheetWatermarkableImage getImage()
```


Gets the image of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The image of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` or null if the shape has no image.
### setImage(SpreadsheetWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public final void setImage(SpreadsheetWatermarkableImage value)
```


Sets the image of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | The image of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` or null if the image should be removed. |

### getImageFillFormat() {#getImageFillFormat--}
```
public final SpreadsheetImageFillFormat getImageFillFormat()
```


Gets the image fill format settings of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

**Returns:**
[SpreadsheetImageFillFormat](../../com.groupdocs.watermark.contents/spreadsheetimagefillformat) - The image fill format settings of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.
### getId() {#getId--}
```
public final int getId()
```


Gets the identifier of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

**Returns:**
int - The identifier of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.
### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Gets the descriptive (alternative) text associated with this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

**Returns:**
java.lang.String - The descriptive (alternative) text associated with this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Sets the descriptive (alternative) text associated with this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The descriptive (alternative) text associated with this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |

### isWordArt() {#isWordArt--}
```
public final boolean isWordArt()
```


Gets a value indicating whether this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` is a WordArt object.

**Returns:**
boolean - True if the shape is a WordArt object; otherwise, false.
### getName() {#getName--}
```
public final String getName()
```


Gets the name of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

**Returns:**
java.lang.String - The name of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.
### getAsposeCellsShape() {#getAsposeCellsShape--}
```
public final Shape getAsposeCellsShape()
```




**Returns:**
com.aspose.cells.Shape
### getHyperlink() {#getHyperlink--}
```
public final String getHyperlink()
```


Gets the hyperlink associated with this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

**Returns:**
java.lang.String - The hyperlink associated with this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.
### setHyperlink(String value) {#setHyperlink-java.lang.String-}
```
public final void setHyperlink(String value)
```


Sets the hyperlink associated with this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The hyperlink associated with this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |

### getX() {#getX--}
```
public final double getX()
```


Gets the horizontal offset of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` from worksheet left border in points.

**Returns:**
double - The x-coordinate of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.
### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Sets the horizontal offset of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` from worksheet left border in points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The x-coordinate of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |

### getY() {#getY--}
```
public final double getY()
```


Gets the vertical offset of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` from worksheet top border in points.

**Returns:**
double - The y-coordinate of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.
### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Sets the vertical offset of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` from worksheet top border in points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The y-coordinate of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Gets the width of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in points.

**Returns:**
double - The width of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in points.
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Sets the width of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The width of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in points. |

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Gets the height of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in points.

**Returns:**
double - The height of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in points.
### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Sets the height of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The height of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in points. |

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Gets or sets the rotate angle of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in degrees.

**Returns:**
double - The rotate angle of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in degrees.
### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Gets or sets the rotate angle of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in degrees.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The rotate angle of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in degrees. |

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

