---
title: DiagramPage
second_title: GroupDocs.Watermark for Java API Reference
description: Represents a Visio document page.
type: docs
weight: 22
url: /java/com.groupdocs.watermark.contents/diagrampage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class DiagramPage extends ContentPart
```

Represents a Visio document page.
## Methods

| Method | Description |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
| [getShapes()](#getShapes--) | Gets the collection of all shapes of the page. |
| [isBackground()](#isBackground--) | Gets a value indicating whether the page is a background page. |
| [getBackgroundPage()](#getBackgroundPage--) | Gets the background page for this . |
| [getWidth()](#getWidth--) | Gets the width of this  in points. |
| [getHeight()](#getHeight--) | Gets the height of this  in points. |
| [getTopMargin()](#getTopMargin--) | Gets the size of the top margin in points. |
| [getRightMargin()](#getRightMargin--) | Gets the size of the right margin in points. |
| [getBottomMargin()](#getBottomMargin--) | Gets the size of the bottom margin in points. |
| [getLeftMargin()](#getLeftMargin--) | Gets the size of the left margin in points. |
| [isVisible()](#isVisible--) | Gets a value indicating whether the page is visible in UI. |
| [setVisible(boolean value)](#setVisible-boolean-) | Sets a value indicating whether the page is visible in UI. |
| [getName()](#getName--) | Gets the name of this  DiagramPage . |
| [getAsposeDiagramPage()](#getAsposeDiagramPage--) |  |
| [getContent()](#getContent--) |  |
| [getPageToDrawingScale()](#getPageToDrawingScale--) |  |
| [addWatermark(Watermark watermark, DiagramShapeSettings shapeSettings)](#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.internal.DiagramShapeSettings-) |  |
| [convertValueFromDrawingScaleToPageScale(DoubleValue value)](#convertValueFromDrawingScaleToPageScale-com.aspose.diagram.DoubleValue-) |  |
### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```




**Returns:**
java.lang.Integer
### getShapes() {#getShapes--}
```
public final DiagramShapeCollection getShapes()
```


Gets the collection of all shapes of the page.

**Returns:**
[DiagramShapeCollection](../../com.groupdocs.watermark.contents/diagramshapecollection) - The collection of all shapes of the page.
### isBackground() {#isBackground--}
```
public final boolean isBackground()
```


Gets a value indicating whether the page is a background page.

**Returns:**
boolean - True if the page is a background page; otherwise, false.
### getBackgroundPage() {#getBackgroundPage--}
```
public final DiagramPage getBackgroundPage()
```


Gets the background page for this .

**Returns:**
[DiagramPage](../../com.groupdocs.watermark.contents/diagrampage) - The background page for this .
### getWidth() {#getWidth--}
```
public final double getWidth()
```


Gets the width of this  in points.

**Returns:**
double - The width of this  in points.
### getHeight() {#getHeight--}
```
public final double getHeight()
```


Gets the height of this  in points.

**Returns:**
double - The height of this  in points.
### getTopMargin() {#getTopMargin--}
```
public final double getTopMargin()
```


Gets the size of the top margin in points.

**Returns:**
double - The size of the top margin in points.
### getRightMargin() {#getRightMargin--}
```
public final double getRightMargin()
```


Gets the size of the right margin in points.

**Returns:**
double - The size of the right margin in points.
### getBottomMargin() {#getBottomMargin--}
```
public final double getBottomMargin()
```


Gets the size of the bottom margin in points.

**Returns:**
double - The size of the bottom margin in points.
### getLeftMargin() {#getLeftMargin--}
```
public final double getLeftMargin()
```


Gets the size of the left margin in points.

**Returns:**
double - The size of the left margin in points.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Gets a value indicating whether the page is visible in UI.

**Returns:**
boolean - The value indicating whether the page is visible in UI. True if the page is visible; otherwise, false.
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Sets a value indicating whether the page is visible in UI.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | The value indicating whether the page is visible in UI. True if the page is visible; otherwise, false. |

### getName() {#getName--}
```
public final String getName()
```


Gets the name of this  DiagramPage .

**Returns:**
java.lang.String - The name of this  DiagramPage .
### getAsposeDiagramPage() {#getAsposeDiagramPage--}
```
public final Page getAsposeDiagramPage()
```




**Returns:**
com.aspose.diagram.Page
### getContent() {#getContent--}
```
public final DiagramContent getContent()
```




**Returns:**
[DiagramContent](../../com.groupdocs.watermark.contents/diagramcontent)
### getPageToDrawingScale() {#getPageToDrawingScale--}
```
public final double getPageToDrawingScale()
```




**Returns:**
double
### addWatermark(Watermark watermark, DiagramShapeSettings shapeSettings) {#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.internal.DiagramShapeSettings-}
```
public final void addWatermark(Watermark watermark, DiagramShapeSettings shapeSettings)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [DiagramShapeSettings](../../com.groupdocs.watermark.internal/diagramshapesettings) |  |

### convertValueFromDrawingScaleToPageScale(DoubleValue value) {#convertValueFromDrawingScaleToPageScale-com.aspose.diagram.DoubleValue-}
```
public final double convertValueFromDrawingScaleToPageScale(DoubleValue value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.diagram.DoubleValue |  |

**Returns:**
double
