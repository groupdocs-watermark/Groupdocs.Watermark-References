---
title: "DiagramCommentPossibleWatermark"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示 Visio 文档注释中可能的水印。"
type: docs
weight: 13
url: /zh/java/com.groupdocs.watermark.search/diagramcommentpossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)
```
public class DiagramCommentPossibleWatermark extends PossibleWatermark
```

表示 Visio 文档注释中可能的水印。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DiagramCommentPossibleWatermark(Annotation annotation, AnnotationCollection annotationCollection, DiagramPage page)](#DiagramCommentPossibleWatermark-com.aspose.diagram.Annotation-com.aspose.diagram.AnnotationCollection-com.groupdocs.watermark.contents.DiagramPage-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getParent()](#getParent--) | 获取此 `[DiagramCommentPossibleWatermark](../../com.groupdocs.watermark.search/diagramcommentpossiblewatermark)` 的父对象。 |
|
|  | [getWidth()](#getWidth--) | 获取此 `[DiagramCommentPossibleWatermark](../../com.groupdocs.watermark.search/diagramcommentpossiblewatermark)` 的宽度（单位：点）。 |
|
|  | [getHeight()](#getHeight--) | 获取此 `[DiagramCommentPossibleWatermark](../../com.groupdocs.watermark.search/diagramcommentpossiblewatermark)` 的高度（单位：点）。 |
|
|  | [getX()](#getX--) | 获取此 `[DiagramCommentPossibleWatermark](../../com.groupdocs.watermark.search/diagramcommentpossiblewatermark)` 相对于页面左边界的水平偏移量（单位：点）。 |
|
|  | [getY()](#getY--) | 获取此 `[DiagramCommentPossibleWatermark](../../com.groupdocs.watermark.search/diagramcommentpossiblewatermark)` 相对于页面底部边界的垂直偏移量（单位：点）。 |
|
|  | [getRotateAngle()](#getRotateAngle--) | 获取此 `[DiagramCommentPossibleWatermark](../../com.groupdocs.watermark.search/diagramcommentpossiblewatermark)` 的旋转角度（单位：度）。 |
|
|  | [getText()](#getText--) | 获取此 `[DiagramCommentPossibleWatermark](../../com.groupdocs.watermark.search/diagramcommentpossiblewatermark)` 的文本。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | 设置此 `[DiagramCommentPossibleWatermark](../../com.groupdocs.watermark.search/diagramcommentpossiblewatermark)` 的文本。 |
|
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | 获取此 `[DiagramCommentPossibleWatermark](../../com.groupdocs.watermark.search/diagramcommentpossiblewatermark)` 的 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`。 |
|
| [remove()](#remove--) |  |
### DiagramCommentPossibleWatermark(Annotation annotation, AnnotationCollection annotationCollection, DiagramPage page) {#DiagramCommentPossibleWatermark-com.aspose.diagram.Annotation-com.aspose.diagram.AnnotationCollection-com.groupdocs.watermark.contents.DiagramPage-}
```
public DiagramCommentPossibleWatermark(Annotation annotation, AnnotationCollection annotationCollection, DiagramPage page)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 注释 | com.aspose.diagram.Annotation |  |
| annotationCollection | com.aspose.diagram.AnnotationCollection |  |
| page | [DiagramPage](../../com.groupdocs.watermark.contents/diagrampage) |  |

### getParent() {#getParent--}
```
public ContentPart getParent()
```


获取此 `[DiagramCommentPossibleWatermark](../../com.groupdocs.watermark.search/diagramcommentpossiblewatermark)` 的父对象。


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[DiagramCommentPossibleWatermark](../../com.groupdocs.watermark.search/diagramcommentpossiblewatermark)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


获取此 `[DiagramCommentPossibleWatermark](../../com.groupdocs.watermark.search/diagramcommentpossiblewatermark)` 的宽度（单位：点）。


**Returns:**
double - 此类可能的水印的值始终为 0。

### getHeight() {#getHeight--}
```
public double getHeight()
```


获取此 `[DiagramCommentPossibleWatermark](../../com.groupdocs.watermark.search/diagramcommentpossiblewatermark)` 的高度（单位：点）。


**Returns:**
double - 此类可能的水印的值始终为 0。

### getX() {#getX--}
```
public double getX()
```


获取此 `[DiagramCommentPossibleWatermark](../../com.groupdocs.watermark.search/diagramcommentpossiblewatermark)` 相对于页面左边界的水平偏移量（单位：点）。


**Returns:**
double - 此 `[DiagramCommentPossibleWatermark](../../com.groupdocs.watermark.search/diagramcommentpossiblewatermark)` 的 x 坐标。

### getY() {#getY--}
```
public double getY()
```


获取此 `[DiagramCommentPossibleWatermark](../../com.groupdocs.watermark.search/diagramcommentpossiblewatermark)` 相对于页面底部边界的垂直偏移量（单位：点）。


**Returns:**
double - 此 `[DiagramCommentPossibleWatermark](../../com.groupdocs.watermark.search/diagramcommentpossiblewatermark)` 的 y 坐标。

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


获取此 `[DiagramCommentPossibleWatermark](../../com.groupdocs.watermark.search/diagramcommentpossiblewatermark)` 的旋转角度（单位：度）。


**Returns:**
double - 此类可能的水印的值始终为 0。

### getText() {#getText--}
```
public String getText()
```


获取此 `[DiagramCommentPossibleWatermark](../../com.groupdocs.watermark.search/diagramcommentpossiblewatermark)` 的文本。


**Returns:**
java.lang.String - 此 `[DiagramCommentPossibleWatermark](../../com.groupdocs.watermark.search/diagramcommentpossiblewatermark)` 的文本。

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


设置此 `[DiagramCommentPossibleWatermark](../../com.groupdocs.watermark.search/diagramcommentpossiblewatermark)` 的文本。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | java.lang.String | 此 `[DiagramCommentPossibleWatermark](../../com.groupdocs.watermark.search/diagramcommentpossiblewatermark)` 的文本。 |
|

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


获取此 `[DiagramCommentPossibleWatermark](../../com.groupdocs.watermark.search/diagramcommentpossiblewatermark)` 的 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`。


**Returns:**
int - 此 `[DiagramCommentPossibleWatermark](../../com.groupdocs.watermark.search/diagramcommentpossiblewatermark)` 的 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`。

### remove() {#remove--}
```
public void remove()
```




