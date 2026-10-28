---
title: "SpreadsheetShape"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示 Excel 文档中的绘图形状。"
type: docs
weight: 117
url: /zh/java/com.groupdocs.watermark.contents/spreadsheetshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject), [com.groupdocs.watermark.search.IHyperlinkContainer](../../com.groupdocs.watermark.search/ihyperlinkcontainer)
```
public class SpreadsheetShape extends ShapeSearchAdapter implements IRotatableTwoDObject, IHyperlinkContainer
```

表示 Excel 文档中的绘图形状。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getWorksheet()](#getWorksheet--) | 获取此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的父工作表。 |
|
|  | [getAutoShapeType()](#getAutoShapeType--) | 获取自动形状类型。 |
|
|  | [getMsoDrawingType()](#getMsoDrawingType--) | 获取 MSO 绘图类型。 |
|
|  | [getText()](#getText--) | 获取此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的文本。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | 设置此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的文本。 |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | 获取此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的格式化文本片段集合。 |
|
|  | [getImage()](#getImage--) | 获取此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的图像。 |
|
|  | [setImage(SpreadsheetWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | 设置此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的图像。 |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | 获取此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的图像填充格式设置。 |
|
|  | [getId()](#getId--) | 获取此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的标识符。 |
|
|  | [getAlternativeText()](#getAlternativeText--) | 获取与此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 关联的描述性（替代）文本。 |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | 设置与此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 关联的描述性（替代）文本。 |
|
|  | [isWordArt()](#isWordArt--) | 获取一个值，指示此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 是否为 WordArt 对象。 |
|
|  | [getName()](#getName--) | 获取此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的名称。 |
|
|  | [getAsposeCellsShape()](#getAsposeCellsShape--) | <br /> |

|
|  | [getHyperlink()](#getHyperlink--) | 获取与此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 关联的超链接。 |
|
|  | [setHyperlink(String value)](#setHyperlink-java.lang.String-) | 设置此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 关联的超链接。 |
|
|  | [getX()](#getX--) | 获取此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 相对于工作表左边界的水平偏移（单位：点）。 |
|
|  | [setX(double value)](#setX-double-) | 设置此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 相对于工作表左边界的水平偏移（单位：点）。 |
|
|  | [getY()](#getY--) | 获取此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 相对于工作表上边界的垂直偏移（单位：点）。 |
|
|  | [setY(double value)](#setY-double-) | 设置此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 相对于工作表上边界的垂直偏移（单位：点）。 |
|
|  | [getWidth()](#getWidth--) | 获取此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的宽度（单位：点）。 |
|
|  | [setWidth(double value)](#setWidth-double-) | 设置此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的宽度（单位：点）。 |
|
|  | [getHeight()](#getHeight--) | 获取此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的高度（单位：点）。 |
|
|  | [setHeight(double value)](#setHeight-double-) | 设置此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的高度（单位：点）。 |
|
|  | [getRotateAngle()](#getRotateAngle--) | 获取或设置此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的旋转角度（单位：度）。 |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | 获取或设置此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的旋转角度（单位：度）。 |
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
### getWorksheet() {#getWorksheet--}
```
public final SpreadsheetWorksheet getWorksheet()
```


获取此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的父工作表。


**Returns:**
[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) - The parent worksheet of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getAutoShapeType() {#getAutoShapeType--}
```
public final int getAutoShapeType()
```


获取自动形状类型。


**Returns:**
int - 自动形状类型。

### getMsoDrawingType() {#getMsoDrawingType--}
```
public final int getMsoDrawingType()
```


获取 MSO 绘图类型。


**Returns:**
int - mso 绘图类型。

### getText() {#getText--}
```
public final String getText()
```


获取此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的文本。


**Returns:**
java.lang.String - 此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的文本。

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


设置此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的文本。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | java.lang.String | 此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的文本。 |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


获取此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的格式化文本片段集合。


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getImage() {#getImage--}
```
public final SpreadsheetWatermarkableImage getImage()
```


获取此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的图像。


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The image of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` or null if the shape has no image.

### setImage(SpreadsheetWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public final void setImage(SpreadsheetWatermarkableImage value)
```


设置此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的图像。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | 此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的图像，若应移除图像则为 null。 |
|

### getImageFillFormat() {#getImageFillFormat--}
```
public final SpreadsheetImageFillFormat getImageFillFormat()
```


获取此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的图像填充格式设置。


**Returns:**
[SpreadsheetImageFillFormat](../../com.groupdocs.watermark.contents/spreadsheetimagefillformat) - The image fill format settings of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getId() {#getId--}
```
public final int getId()
```


获取此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的标识符。


**Returns:**
int - 此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的标识符。

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


获取与此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 关联的描述性（替代）文本。


**Returns:**
java.lang.String - 与此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 关联的描述性（替代）文本。

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


设置与此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 关联的描述性（替代）文本。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | java.lang.String | 与此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 关联的描述性（替代）文本。 |
|

### isWordArt() {#isWordArt--}
```
public final boolean isWordArt()
```


获取一个值，指示此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 是否为 WordArt 对象。


**Returns:**
boolean - 若形状是 WordArt 对象则为 true；否则为 false。

### getName() {#getName--}
```
public final String getName()
```


获取此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的名称。


**Returns:**
java.lang.String - 此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的名称。

### getAsposeCellsShape() {#getAsposeCellsShape--}
```
public final Shape getAsposeCellsShape()
```


<br />



**Returns:**
com.aspose.cells.Shape
### getHyperlink() {#getHyperlink--}
```
public final String getHyperlink()
```


获取与此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 关联的超链接。


**Returns:**
java.lang.String - 与此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 关联的超链接。

### setHyperlink(String value) {#setHyperlink-java.lang.String-}
```
public final void setHyperlink(String value)
```


设置此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 关联的超链接。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | java.lang.String | 与此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 关联的超链接。 |
|

### getX() {#getX--}
```
public final double getX()
```


获取此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 相对于工作表左边界的水平偏移（单位：点）。


**Returns:**
double - 此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的 x 坐标。

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


设置此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 相对于工作表左边界的水平偏移（单位：点）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的 x 坐标。 |
|

### getY() {#getY--}
```
public final double getY()
```


获取此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 相对于工作表上边界的垂直偏移（单位：点）。


**Returns:**
double - 此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的 y 坐标。

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


设置此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 相对于工作表上边界的垂直偏移（单位：点）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的 y 坐标。 |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


获取此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的宽度（单位：点）。


**Returns:**
double - 此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的宽度（单位：点）。

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


设置此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的宽度（单位：点）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的宽度（单位：点）。 |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


获取此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的高度（单位：点）。


**Returns:**
double - 此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的高度（单位：点）。

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


设置此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的高度（单位：点）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的高度（单位：点）。 |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


获取或设置此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的旋转角度（单位：度）。


**Returns:**
double - 此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的旋转角度（单位：度）。

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


获取或设置此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的旋转角度（单位：度）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 此 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` 的旋转角度（单位：度）。 |
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
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

