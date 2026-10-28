---
title: "PdfShape"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "提供 XObjects 工件和注释的基类。"
type: docs
weight: 69
url: /zh/java/com.groupdocs.watermark.contents/pdfshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public abstract class PdfShape extends ShapeSearchAdapter implements IRotatableTwoDObject
```

提供 XObjects、Artifacts 和 Annotations 的基类。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getText()](#getText--) | 获取此 `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` 的文本。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | 获取或设置此 `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` 的文本。 |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | 获取此 `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` 的格式化文本片段集合。 |
|
|  | [getImage()](#getImage--) | 获取此 `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` 的图像。 |
|
|  | [setImage(PdfWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.PdfWatermarkableImage-) | 设置此 `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` 的图像。 |
|
|  | [getX()](#getX--) | 获取对象的 x 坐标。 |
|
|  | [getY()](#getY--) | 获取对象的 y 坐标。 |
|
|  | [getWidth()](#getWidth--) | 获取对象的宽度。 |
|
|  | [getHeight()](#getHeight--) | 获取对象的高度。 |
|
|  | [getRotateAngle()](#getRotateAngle--) | 获取对象的旋转角度（以度为单位）。 |
|
|  | [getOuterForm()](#getOuterForm--) | <br /> |

|
|  | [extractImageAppearance()](#extractImageAppearance--) | <br /> |

|
|  | [getTextForSearch()](#getTextForSearch--) | <br /> |

|
|  | [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) | <br /> |

|
|  | [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) | <br /> |

|
|  | [getImageForSearch()](#getImageForSearch--) | <br /> |

|
|  | [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) | <br /> |

|
### getText() {#getText--}
```
public String getText()
```


获取此 `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` 的文本。


**Returns:**
java.lang.String - 此 `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` 的文本。

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


获取或设置此 `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` 的文本。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | java.lang.String | 此 `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` 的文本。 |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


获取此 `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` 的格式化文本片段集合。


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.

### getImage() {#getImage--}
```
public final PdfWatermarkableImage getImage()
```


获取此 `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` 的图像。


**Returns:**
[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage) - The image of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.

### setImage(PdfWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.PdfWatermarkableImage-}
```
public final void setImage(PdfWatermarkableImage value)
```


设置此 `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` 的图像。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage) | 此 `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` 的图像。 |
|

### getX() {#getX--}
```
public abstract double getX()
```


获取对象的 x 坐标。


**Returns:**
double - 对象的 x 坐标。

### getY() {#getY--}
```
public abstract double getY()
```


获取对象的 y 坐标。


**Returns:**
double - 对象的 y 坐标。

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


获取对象的宽度。


**Returns:**
double - 对象的宽度。

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


获取对象的高度。


**Returns:**
double - 对象的高度。

### getRotateAngle() {#getRotateAngle--}
```
public abstract double getRotateAngle()
```


获取对象的旋转角度（以度为单位）。


**Returns:**
double - 对象的旋转角度（以度为单位）。

### getOuterForm() {#getOuterForm--}
```
public abstract XForm getOuterForm()
```


<br />



**Returns:**
com.aspose.pdf.XForm
### extractImageAppearance() {#extractImageAppearance--}
```
public PdfXImageAppearance extractImageAppearance()
```


<br />



**Returns:**
[PdfXImageAppearance](../../com.groupdocs.watermark.internal/pdfximageappearance)
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

