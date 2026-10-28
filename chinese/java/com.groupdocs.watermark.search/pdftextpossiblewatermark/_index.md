---
title: "PdfTextPossibleWatermark"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示 PDF 文档文本中可能的水印。"
type: docs
weight: 43
url: /zh/java/com.groupdocs.watermark.search/pdftextpossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)
```
public class PdfTextPossibleWatermark extends PossibleWatermark
```

表示 PDF 文档文本中可能的水印。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfTextPossibleWatermark(PdfPage parent, TextFragment fragment)](#PdfTextPossibleWatermark-com.groupdocs.watermark.contents.PdfPage-com.aspose.pdf.TextFragment-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getParent()](#getParent--) | 获取此 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` 的父对象。 |
|
|  | [getWidth()](#getWidth--) | 获取此 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` 的宽度（单位：点）。 |
|
|  | [getHeight()](#getHeight--) | 获取此 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` 的高度（单位：点）。 |
|
|  | [getX()](#getX--) | 获取此 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` 相对于页面左边缘的水平偏移量（单位：点）。 |
|
|  | [getY()](#getY--) | 获取此 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` 相对于页面底部边缘的垂直偏移量（单位：点）。 |
|
|  | [getRotateAngle()](#getRotateAngle--) | 获取此 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` 的旋转角度（单位：度）。 |
|
|  | [getText()](#getText--) | 获取此 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` 的文本。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | 设置此 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` 的文本。 |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | 获取此 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` 的格式化文本片段集合。 |
|
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | 获取此 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` 的 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`。 |
|
| [remove()](#remove--) |  |
### PdfTextPossibleWatermark(PdfPage parent, TextFragment fragment) {#PdfTextPossibleWatermark-com.groupdocs.watermark.contents.PdfPage-com.aspose.pdf.TextFragment-}
```
public PdfTextPossibleWatermark(PdfPage parent, TextFragment fragment)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| parent | [PdfPage](../../com.groupdocs.watermark.contents/pdfpage) |  |
| 片段 | com.aspose.pdf.TextFragment |  |

### getParent() {#getParent--}
```
public ContentPart getParent()
```


获取此 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` 的父对象。


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


获取此 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` 的宽度（单位：点）。


**Returns:**
double - 此 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` 的宽度（单位：点）。

### getHeight() {#getHeight--}
```
public double getHeight()
```


获取此 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` 的高度（单位：点）。


**Returns:**
double - 此 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` 的高度（单位：点）。

### getX() {#getX--}
```
public double getX()
```


获取此 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` 相对于页面左边缘的水平偏移量（单位：点）。


**Returns:**
double - 此 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` 的 x 坐标。

### getY() {#getY--}
```
public double getY()
```


获取此 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` 相对于页面底部边缘的垂直偏移量（单位：点）。


**Returns:**
double - 此 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` 的 y 坐标。

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


获取此 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` 的旋转角度（单位：度）。


**Returns:**
double - 此类可能的水印的值始终为 0。

### getText() {#getText--}
```
public String getText()
```


获取此 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` 的文本。


**Returns:**
java.lang.String - 此 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` 的文本。

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


设置此 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` 的文本。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | java.lang.String | 此 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` 的文本。 |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


获取此 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` 的格式化文本片段集合。


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


获取此 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` 的 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`。


**Returns:**
int - 此 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` 的 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`。

### remove() {#remove--}
```
public void remove()
```




