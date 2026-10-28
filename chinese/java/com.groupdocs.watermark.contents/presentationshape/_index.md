---
title: "PresentationShape"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示 PowerPoint 文档中的绘图形状。"
type: docs
weight: 93
url: /zh/java/com.groupdocs.watermark.contents/presentationshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public class PresentationShape extends PresentationBaseShape implements IRotatableTwoDObject
```

表示 PowerPoint 文档中的绘图形状。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getRotateAngle()](#getRotateAngle--) | 获取此 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` 的旋转角度（单位：度）。 |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | 设置此 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` 的旋转角度（单位：度）。 |
|
|  | [getText()](#getText--) | 获取此 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` 的文本。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | 设置此 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` 的文本。 |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | 获取此 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` 的格式化文本片段集合。 |
|
|  | [getShapeType()](#getShapeType--) | 获取形状几何预设类型。 |
|
|  | [getImage()](#getImage--) | 获取此 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` 的图像。 |
|
|  | [setImage(PresentationWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-) | 设置此 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` 的图像。 |
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
### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


获取此 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` 的旋转角度（单位：度）。


**Returns:**
double - 此 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` 的旋转角度（单位：度）。

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


设置此 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` 的旋转角度（单位：度）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 此 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` 的旋转角度（单位：度）。 |
|

### getText() {#getText--}
```
public final String getText()
```


获取此 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` 的文本。


**Returns:**
java.lang.String - 此 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` 的文本。

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


设置此 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` 的文本。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | java.lang.String | 此 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` 的文本。 |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


获取此 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` 的格式化文本片段集合。


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


获取形状几何预设类型。


**Returns:**
int - 几何预设类型。

### getImage() {#getImage--}
```
public final PresentationWatermarkableImage getImage()
```


获取此 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` 的图像。


**Returns:**
[PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) - The image of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` or null if the shape has no image.

### setImage(PresentationWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-}
```
public final void setImage(PresentationWatermarkableImage value)
```


设置此 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` 的图像。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) | 此 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` 的图像，若应删除图像则为 null。 |
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

