---
title: "PdfArtifact"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示 PDF 内容中的人工制品。"
type: docs
weight: 54
url: /zh/java/com.groupdocs.watermark.contents/pdfartifact/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public class PdfArtifact extends PdfShape
```

表示 PDF 内容中的人工制品。

**Lean more**

* [Working with artifacts](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-Workingwithartifacts)

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPage()](#getPage--) | 获取此 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` 的父页面。 |
|
|  | [getText()](#getText--) | 获取此 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` 的文本。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | 设置此 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` 的文本。 |
|
|  | [getArtifactType()](#getArtifactType--) | 获取此 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` 的类型。 |
|
|  | [getArtifactSubtype()](#getArtifactSubtype--) | 获取此 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` 的子类型。 |
|
|  | [getOpacity()](#getOpacity--) | 获取此 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` 的不透明度。 |
|
|  | [getX()](#getX--) | 获取此 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` 相对于页面左边界的水平偏移（单位：点）。 |
|
|  | [getY()](#getY--) | 获取此 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` 相对于页面底部边界的垂直偏移（单位：点）。 |
|
|  | [getRotateAngle()](#getRotateAngle--) | 获取此 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` 的旋转角度（单位：度）。 |
|
|  | [getWidth()](#getWidth--) | 获取此 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` 的宽度（单位：点）。 |
|
|  | [getHeight()](#getHeight--) | 获取此 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` 的高度（单位：点）。 |
|
|  | [getAsposePdfArtifact()](#getAsposePdfArtifact--) | <br /> |

|
|  | [getOuterForm()](#getOuterForm--) | <br /> |

|
### getPage() {#getPage--}
```
public final PdfPage getPage()
```


获取此 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` 的父页面。


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getText() {#getText--}
```
public String getText()
```


获取此 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` 的文本。


**Returns:**
java.lang.String - 此 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` 的文本。

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


设置此 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` 的文本。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | java.lang.String | 此 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` 的文本。 |
|

### getArtifactType() {#getArtifactType--}
```
public final int getArtifactType()
```


获取此 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` 的类型。


**Returns:**
int - 此 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` 的类型。

### getArtifactSubtype() {#getArtifactSubtype--}
```
public final int getArtifactSubtype()
```


获取此 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` 的子类型。


**Returns:**
int - 此 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` 的子类型。

### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


获取此 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` 的不透明度。

可能的取值范围是 [0, 1]。


**Returns:**
double - 此 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` 的不透明度。

### getX() {#getX--}
```
public double getX()
```


获取此 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` 相对于页面左边界的水平偏移（单位：点）。


**Returns:**
double - 此 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` 的 X 坐标。

### getY() {#getY--}
```
public double getY()
```


获取此 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` 相对于页面底部边界的垂直偏移（单位：点）。


**Returns:**
double - 此 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` 的 Y 坐标。

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


获取此 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` 的旋转角度（单位：度）。


**Returns:**
double - 此 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` 的旋转角度（单位：度）。

### getWidth() {#getWidth--}
```
public double getWidth()
```


获取此 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` 的宽度（单位：点）。


**Returns:**
double - 此 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` 的宽度（单位：点）。

### getHeight() {#getHeight--}
```
public double getHeight()
```


获取此 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` 的高度（单位：点）。


**Returns:**
double - 此 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` 的高度（单位：点）。

### getAsposePdfArtifact() {#getAsposePdfArtifact--}
```
public final Artifact getAsposePdfArtifact()
```


<br />



**Returns:**
com.aspose.pdf.Artifact
### getOuterForm() {#getOuterForm--}
```
public XForm getOuterForm()
```


<br />



**Returns:**
com.aspose.pdf.XForm
