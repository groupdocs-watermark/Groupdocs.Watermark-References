---
title: "DiagramPage"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示 Visio 文档页面。"
type: docs
weight: 22
url: /zh/java/com.groupdocs.watermark.contents/diagrampage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class DiagramPage extends ContentPart
```

表示 Visio 文档页面。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
|  | [getShapes()](#getShapes--) | 获取页面中所有形状的集合。 |
|
|  | [isBackground()](#isBackground--) | 获取指示页面是否为背景页的值。 |
|
|  | [getBackgroundPage()](#getBackgroundPage--) | 获取此的背景页。 |
|
|  | [getWidth()](#getWidth--) | 获取此的宽度（以点为单位）。 |
|
|  | [getHeight()](#getHeight--) | 获取此的高度（以点为单位）。 |
|
|  | [getTopMargin()](#getTopMargin--) | 获取上边距的大小（单位：点）。 |
|
|  | [getRightMargin()](#getRightMargin--) | 获取右边距的大小（单位：点）。 |
|
|  | [getBottomMargin()](#getBottomMargin--) | 获取下边距的大小（单位：点）。 |
|
|  | [getLeftMargin()](#getLeftMargin--) | 获取左边距的大小（单位：点）。 |
|
|  | [isVisible()](#isVisible--) | 获取指示页面在 UI 中是否可见的值。 |
|
|  | [setVisible(boolean value)](#setVisible-boolean-) | 设置指示页面在 UI 中是否可见的值。 |
|
|  | [getName()](#getName--) | 获取此的名称 |
DiagramPage
.
|
|  | [getAsposeDiagramPage()](#getAsposeDiagramPage--) | <br /> |

|
|  | [getContent()](#getContent--) | <br /> |

|
|  | [getPageToDrawingScale()](#getPageToDrawingScale--) | <br /> |

|
|  | [addWatermark(Watermark watermark, DiagramShapeSettings shapeSettings)](#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.internal.DiagramShapeSettings-) | <br /> |

|
|  | [convertValueFromDrawingScaleToPageScale(DoubleValue value)](#convertValueFromDrawingScaleToPageScale-com.aspose.diagram.DoubleValue-) | <br /> |

|
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


获取页面中所有形状的集合。


**Returns:**
[DiagramShapeCollection](../../com.groupdocs.watermark.contents/diagramshapecollection) - The collection of all shapes of the page.

### isBackground() {#isBackground--}
```
public final boolean isBackground()
```


获取指示页面是否为背景页的值。


**Returns:**
boolean - 如果页面是背景页则为 True；否则为 false。

### getBackgroundPage() {#getBackgroundPage--}
```
public final DiagramPage getBackgroundPage()
```


获取此的背景页。


**Returns:**
[DiagramPage](../../com.groupdocs.watermark.contents/diagrampage) - The background page for this .

### getWidth() {#getWidth--}
```
public final double getWidth()
```


获取此的宽度（以点为单位）。


**Returns:**
double - 此的宽度（以点为单位）。

### getHeight() {#getHeight--}
```
public final double getHeight()
```


获取此的高度（以点为单位）。


**Returns:**
double - 此的高度（以点为单位）。

### getTopMargin() {#getTopMargin--}
```
public final double getTopMargin()
```


获取上边距的大小（单位：点）。


**Returns:**
double - 顶部边距的大小（单位：点）。

### getRightMargin() {#getRightMargin--}
```
public final double getRightMargin()
```


获取右边距的大小（单位：点）。


**Returns:**
double - 右边距的大小（单位：点）。

### getBottomMargin() {#getBottomMargin--}
```
public final double getBottomMargin()
```


获取下边距的大小（单位：点）。


**Returns:**
double - 底部边距的大小（单位：点）。

### getLeftMargin() {#getLeftMargin--}
```
public final double getLeftMargin()
```


获取左边距的大小（单位：点）。


**Returns:**
double - 左边距的大小（单位：点）。

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


获取指示页面在 UI 中是否可见的值。


**Returns:**
boolean - 指示页面在 UI 中是否可见的值。如果页面可见则为 True；否则为 false。

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


设置指示页面在 UI 中是否可见的值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 指示页面在 UI 中是否可见的值。如果页面可见则为 true；否则为 false。 |
|

### getName() {#getName--}
```
public final String getName()
```


获取此的名称
DiagramPage
.


**Returns:**
java.lang.String - 此 DiagramPage 的名称。

### getAsposeDiagramPage() {#getAsposeDiagramPage--}
```
public final Page getAsposeDiagramPage()
```


<br />



**Returns:**
com.aspose.diagram.Page
### getContent() {#getContent--}
```
public final DiagramContent getContent()
```


<br />



**Returns:**
[DiagramContent](../../com.groupdocs.watermark.contents/diagramcontent)
### getPageToDrawingScale() {#getPageToDrawingScale--}
```
public final double getPageToDrawingScale()
```


<br />



**Returns:**
double
### addWatermark(Watermark watermark, DiagramShapeSettings shapeSettings) {#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.internal.DiagramShapeSettings-}
```
public final void addWatermark(Watermark watermark, DiagramShapeSettings shapeSettings)
```


<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [DiagramShapeSettings](../../com.groupdocs.watermark.internal/diagramshapesettings) |  |

### convertValueFromDrawingScaleToPageScale(DoubleValue value) {#convertValueFromDrawingScaleToPageScale-com.aspose.diagram.DoubleValue-}
```
public final double convertValueFromDrawingScaleToPageScale(DoubleValue value)
```


<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | com.aspose.diagram.DoubleValue |  |

**Returns:**
double
