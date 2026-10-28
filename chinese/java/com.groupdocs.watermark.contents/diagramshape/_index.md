---
title: "DiagramShape"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示 Visio 文档中的绘图形状。"
type: docs
weight: 24
url: /zh/java/com.groupdocs.watermark.contents/diagramshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public class DiagramShape extends ShapeSearchAdapter implements IRotatableTwoDObject
```

表示 Visio 文档中的绘图形状。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
|  | [getPage()](#getPage--) | 获取此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的父页面。 |
|
|  | [getWidth()](#getWidth--) | 获取此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的宽度（单位为点）。 |
|
|  | [setWidth(double value)](#setWidth-double-) | 设置此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的宽度（单位为点）。 |
|
|  | [getHeight()](#getHeight--) | 获取此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的高度（单位为点）。 |
|
|  | [setHeight(double value)](#setHeight-double-) | 设置此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的高度（单位为点）。 |
|
|  | [getX()](#getX--) | 获取此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 相对于页面左边界的水平偏移量（单位为点）。 |
|
|  | [setX(double value)](#setX-double-) | 设置此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 相对于页面左边界的水平偏移量（单位为点）。 |
|
|  | [getY()](#getY--) | 获取此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 相对于页面底部边界的垂直偏移量（单位为点）。 |
|
|  | [setY(double value)](#setY-double-) | 设置此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 相对于页面底部边界的垂直偏移量（单位为点）。 |
|
|  | [getRotateAngle()](#getRotateAngle--) | 获取或设置此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的旋转角度（单位为度）。 |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | 获取或设置此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的旋转角度（单位为度）。 |
|
|  | [getText()](#getText--) | 获取或设置此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的文本。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | 获取或设置此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的文本。 |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | 获取此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的格式化文本片段集合。 |
|
|  | [getImage()](#getImage--) | 获取此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的图像。 |
|
|  | [setImage(DiagramWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.DiagramWatermarkableImage-) | 设置此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的图像。 |
|
|  | [getId()](#getId--) | 获取此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的标识符。 |
|
|  | [getName()](#getName--) | 获取此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的名称。 |
|
|  | [getHyperlinks()](#getHyperlinks--) | 获取附加到此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的超链接集合。 |
|
|  | [getAsposeShape()](#getAsposeShape--) | <br /> |

|
|  | [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) | <br /> |

|
|  | [getImageForSearch()](#getImageForSearch--) | <br /> |

|
|  | [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) | <br /> |

|
|  | [getTextForSearch()](#getTextForSearch--) | <br /> |

|
|  | [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) | <br /> |

|
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


获取此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的父页面。


**Returns:**
[DiagramPage](../../com.groupdocs.watermark.contents/diagrampage) - The parent page of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getWidth() {#getWidth--}
```
public final double getWidth()
```


获取此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的宽度（单位为点）。


**Returns:**
double - 此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的宽度（单位为点）。

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


设置此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的宽度（单位为点）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的宽度（单位为点）。 |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


获取此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的高度（单位为点）。


**Returns:**
double - 此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的高度（单位为点）。

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


设置此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的高度（单位为点）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的高度（单位为点）。 |
|

### getX() {#getX--}
```
public final double getX()
```


获取此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 相对于页面左边界的水平偏移量（单位为点）。


**Returns:**
double - 此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 相对于页面左边界的水平偏移（单位：点）。

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


设置此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 相对于页面左边界的水平偏移量（单位为点）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 相对于页面左边界的水平偏移（单位：点）。 |
|

### getY() {#getY--}
```
public final double getY()
```


获取此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 相对于页面底部边界的垂直偏移量（单位为点）。


**Returns:**
double - 此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 相对于页面底部边界的垂直偏移（单位：点）。

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


设置此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 相对于页面底部边界的垂直偏移量（单位为点）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 相对于页面底部边界的垂直偏移（单位：点）。 |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


获取或设置此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的旋转角度（单位为度）。


**Returns:**
double - 此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的旋转角度（单位：度）。

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


获取或设置此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的旋转角度（单位为度）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的旋转角度（单位：度）。 |
|

### getText() {#getText--}
```
public final String getText()
```


获取或设置此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的文本。


**Returns:**
java.lang.String - 此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的文本。

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


获取或设置此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的文本。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | java.lang.String | 此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的文本。 |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


获取此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的格式化文本片段集合。


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getImage() {#getImage--}
```
public final DiagramWatermarkableImage getImage()
```


获取此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的图像。


**Returns:**
[DiagramWatermarkableImage](../../com.groupdocs.watermark.contents/diagramwatermarkableimage) - The image of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### setImage(DiagramWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.DiagramWatermarkableImage-}
```
public final void setImage(DiagramWatermarkableImage value)
```


设置此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的图像。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [DiagramWatermarkableImage](../../com.groupdocs.watermark.contents/diagramwatermarkableimage) | 此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的图像。 |
|

### getId() {#getId--}
```
public final long getId()
```


获取此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的标识符。


**Returns:**
long - 此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的标识符。

### getName() {#getName--}
```
public final String getName()
```


获取此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的名称。


**Returns:**
java.lang.String - 此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的名称。

### getHyperlinks() {#getHyperlinks--}
```
public final DiagramHyperlinkCollection getHyperlinks()
```


获取附加到此 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` 的超链接集合。


**Returns:**
[DiagramHyperlinkCollection](../../com.groupdocs.watermark.contents/diagramhyperlinkcollection) - The collection of hyperlinks attached to this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getAsposeShape() {#getAsposeShape--}
```
public final Shape getAsposeShape()
```


<br />



**Returns:**
com.aspose.diagram.Shape
### getFormattedTextFragmentsForSearch() {#getFormattedTextFragmentsForSearch--}
```
public FormattedTextFragmentCollection getFormattedTextFragmentsForSearch()
```


<br />



**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageData | byte[] |  |

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

