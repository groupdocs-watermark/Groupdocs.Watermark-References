---
title: "PresentationBaseShape"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "提供 PowerPoint 文档中所有类型形状的抽象基类。"
type: docs
weight: 77
url: /zh/java/com.groupdocs.watermark.contents/presentationbaseshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.ITwoDObject](../../com.groupdocs.watermark.search/itwodobject), [com.groupdocs.watermark.contents.IPresentationHyperlinkContainer](../../com.groupdocs.watermark.contents/ipresentationhyperlinkcontainer)
```
public abstract class PresentationBaseShape extends ShapeSearchAdapter implements ITwoDObject, IPresentationHyperlinkContainer
```

提供 PowerPoint 文档中所有类型形状的抽象基类。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPresentation()](#getPresentation--) | 获取此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 的父演示文稿。 |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | 获取此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 的图像填充格式设置。 |
|
|  | [getName()](#getName--) | 获取此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 的名称。 |
|
|  | [getAlternativeText()](#getAlternativeText--) | 获取与此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 关联的描述性（替代）文本。 |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | 设置与此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 关联的描述性（替代）文本。 |
|
|  | [getId()](#getId--) | 获取此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 的标识符。 |
|
|  | [getZOrderPosition()](#getZOrderPosition--) | 获取此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 在 Z 顺序中的位置。 |
|
|  | [getHyperlink(int actionType)](#getHyperlink-int-) | 获取与此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 关联的超链接。 |
|
|  | [setHyperlink(int actionType, String url)](#setHyperlink-int-java.lang.String-) | 设置与此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 关联的超链接。 |
|
|  | [getX()](#getX--) | 获取此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 相对于演示文稿左边框的水平偏移（单位：点）。 |
|
|  | [setX(double value)](#setX-double-) | 设置此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 相对于演示文稿左边框的水平偏移（单位：点）。 |
|
|  | [getY()](#getY--) | 获取或设置此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 相对于演示文稿上边框的垂直偏移（单位：点）。 |
|
|  | [setY(double value)](#setY-double-) | 获取或设置此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 相对于演示文稿上边框的垂直偏移（单位：点）。 |
|
|  | [getWidth()](#getWidth--) | 获取此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 的宽度（单位：点）。 |
|
|  | [setWidth(double value)](#setWidth-double-) | 设置此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 的宽度（单位：点）。 |
|
|  | [getHeight()](#getHeight--) | 获取此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 的高度（单位：点）。 |
|
|  | [setHeight(double value)](#setHeight-double-) | 设置此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 的高度（单位：点）。 |
|
### getPresentation() {#getPresentation--}
```
public final PresentationBaseSlide getPresentation()
```


获取此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 的父演示文稿。


**Returns:**
[PresentationBaseSlide](../../com.groupdocs.watermark.contents/presentationbaseslide) - The parent presentation of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getImageFillFormat() {#getImageFillFormat--}
```
public final PresentationImageFillFormat getImageFillFormat()
```


获取此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 的图像填充格式设置。


**Returns:**
[PresentationImageFillFormat](../../com.groupdocs.watermark.contents/presentationimagefillformat) - The image fill format settings of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getName() {#getName--}
```
public final String getName()
```


获取此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 的名称。


**Returns:**
java.lang.String - 此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 的名称。

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


获取与此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 关联的描述性（替代）文本。


**Returns:**
java.lang.String - 与此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 关联的描述性（替代）文本。

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


设置与此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 关联的描述性（替代）文本。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | java.lang.String | 与此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 关联的描述性（替代）文本。 |
|

### getId() {#getId--}
```
public final long getId()
```


获取此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 的标识符。


**Returns:**
long - 此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 的标识符。

### getZOrderPosition() {#getZOrderPosition--}
```
public final int getZOrderPosition()
```


获取此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 在 Z 顺序中的位置。

z 顺序更高的形状始终位于 z 顺序更低的形状前面。


**Returns:**
int - 此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 在 z 顺序中的位置。

### getHyperlink(int actionType) {#getHyperlink-int-}
```
public final String getHyperlink(int actionType)
```


获取与此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 关联的超链接。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | actionType | int | 激活超链接的操作。 |
|

**Returns:**
java.lang.String - 在指定操作上激活的超链接的 URL。

### setHyperlink(int actionType, String url) {#setHyperlink-int-java.lang.String-}
```
public final void setHyperlink(int actionType, String url)
```


设置与此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 关联的超链接。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | actionType | int | 激活超链接的操作。 |
|
|  | url | java.lang.String | 超链接 URL。 |
|

### getX() {#getX--}
```
public final double getX()
```


获取此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 相对于演示文稿左边框的水平偏移（单位：点）。


**Returns:**
double - 此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 的 x 坐标。

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


设置此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 相对于演示文稿左边框的水平偏移（单位：点）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 的 x 坐标。 |
|

### getY() {#getY--}
```
public final double getY()
```


获取或设置此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 相对于演示文稿上边框的垂直偏移（单位：点）。


**Returns:**
double - 此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 的 y 坐标。

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


获取或设置此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 相对于演示文稿上边框的垂直偏移（单位：点）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 的 y 坐标。 |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


获取此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 的宽度（单位：点）。


**Returns:**
double - 此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 的宽度（以点为单位）。

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


设置此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 的宽度（单位：点）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 的宽度（以点为单位）。 |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


获取此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 的高度（单位：点）。


**Returns:**
double - 此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 的高度（以点为单位）。

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


设置此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 的高度（单位：点）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 此 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` 的高度（以点为单位）。 |
|

