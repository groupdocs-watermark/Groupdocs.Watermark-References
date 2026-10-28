---
title: "PdfXObject"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示 pdf 文档中的 XObject。"
type: docs
weight: 75
url: /zh/java/com.groupdocs.watermark.contents/pdfxobject/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public abstract class PdfXObject extends PdfShape
```

表示 pdf 文档中的 XObject。

**Learn more:**

* [Working with XObjects](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-WorkingwithXObjects)

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPage()](#getPage--) | 获取此 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` 的父页面。 |
|
|  | [getX()](#getX--) | 获取此 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` 相对于页面左边界的水平偏移（单位：点）。 |
|
|  | [getY()](#getY--) | 获取此 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` 相对于页面底部边界的垂直偏移（单位：点）。 |
|
|  | [getWidth()](#getWidth--) | 获取此 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` 的宽度（单位：点）。 |
|
|  | [getHeight()](#getHeight--) | 获取此 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` 的高度（单位：点）。 |
|
|  | [getRotateAngle()](#getRotateAngle--) | 获取此 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` 的旋转角度（单位：度）。 |
|
|  | [getMatrix()](#getMatrix--) | <br /> |

|
### getPage() {#getPage--}
```
public final PdfPage getPage()
```


获取此 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` 的父页面。


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.

### getX() {#getX--}
```
public double getX()
```


获取此 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` 相对于页面左边界的水平偏移（单位：点）。


**Returns:**
double - 此 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` 的 x 坐标。

### getY() {#getY--}
```
public double getY()
```


获取此 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` 相对于页面底部边界的垂直偏移（单位：点）。


**Returns:**
double - 此 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` 的 y 坐标。

### getWidth() {#getWidth--}
```
public double getWidth()
```


获取此 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` 的宽度（单位：点）。


**Returns:**
double - 此 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` 的宽度（单位：点）。

### getHeight() {#getHeight--}
```
public double getHeight()
```


获取此 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` 的高度（单位：点）。


**Returns:**
double - 此 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` 的高度（单位：点）。

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


获取此 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` 的旋转角度（单位：度）。


**Returns:**
double - 此 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` 的旋转角度（单位：度）。

### getMatrix() {#getMatrix--}
```
public final Matrix getMatrix()
```


<br />



**Returns:**
com.aspose.pdf.Matrix
