---
title: "PdfAnnotation"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示 PDF 文档中的批注。"
type: docs
weight: 51
url: /zh/java/com.groupdocs.watermark.contents/pdfannotation/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public class PdfAnnotation extends PdfShape
```

表示 PDF 文档中的批注。

**Learn more:**

* [Working with annotations](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-Workingwithannotations)

## 字段

| 字段 | 描述 |
| --- | --- |
|  | [NormalAppearanceKey](#NormalAppearanceKey) | <br /> |

|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPage()](#getPage--) | 获取此 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` 的父页面。 |
|
|  | [getAnnotationType()](#getAnnotationType--) | 获取此 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` 的类型。 |
|
|  | [getX()](#getX--) | 获取此 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` 相对于页面左边界的水平偏移（单位：点）。 |
|
|  | [getY()](#getY--) | 获取此 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` 相对于工作表底部边界的垂直偏移（单位：点）。 |
|
|  | [getRotateAngle()](#getRotateAngle--) | 获取此 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` 的旋转角度（单位：度）。 |
|
|  | [getWidth()](#getWidth--) | 获取此 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` 的宽度（单位：点）。 |
|
|  | [getHeight()](#getHeight--) | 获取此 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` 的高度（单位：点）。 |
|
|  | [getAsposePdfAnnotation()](#getAsposePdfAnnotation--) | <br /> |

|
|  | [getOuterForm()](#getOuterForm--) | <br /> |

|
### NormalAppearanceKey {#NormalAppearanceKey}
```
public static final String NormalAppearanceKey
```


<br />



### getPage() {#getPage--}
```
public final PdfPage getPage()
```


获取此 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` 的父页面。


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.

### getAnnotationType() {#getAnnotationType--}
```
public final int getAnnotationType()
```


获取此 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` 的类型。


**Returns:**
int - 此 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` 的类型。

### getX() {#getX--}
```
public double getX()
```


获取此 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` 相对于页面左边界的水平偏移（单位：点）。


**Returns:**
double - 此 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` 相对于页面左边缘的水平偏移，以点为单位。

### getY() {#getY--}
```
public double getY()
```


获取此 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` 相对于工作表底部边界的垂直偏移（单位：点）。


**Returns:**
double - 此 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` 相对于工作表底部边缘的垂直偏移，以点为单位。

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


获取此 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` 的旋转角度（单位：度）。


**Returns:**
double - 此 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` 的旋转角度，以度为单位。

### getWidth() {#getWidth--}
```
public double getWidth()
```


获取此 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` 的宽度（单位：点）。


**Returns:**
double - 此 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` 的宽度，以点为单位。

### getHeight() {#getHeight--}
```
public double getHeight()
```


获取此 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` 的高度（单位：点）。


**Returns:**
double - 此 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` 的高度，以点为单位。

### getAsposePdfAnnotation() {#getAsposePdfAnnotation--}
```
public final Annotation getAsposePdfAnnotation()
```


<br />



**Returns:**
com.aspose.pdf.Annotation
### getOuterForm() {#getOuterForm--}
```
public XForm getOuterForm()
```


<br />



**Returns:**
com.aspose.pdf.XForm
