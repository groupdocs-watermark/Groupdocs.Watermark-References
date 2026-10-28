---
title: "SpreadsheetAttachment"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示附加到 Excel 文档的文件。"
type: docs
weight: 101
url: /zh/java/com.groupdocs.watermark.contents/spreadsheetattachment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.ITwoDObject](../../com.groupdocs.watermark.search/itwodobject)
```
public class SpreadsheetAttachment extends Attachment implements ITwoDObject
```

表示附加到 Excel 文档的文件。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getContent()](#getContent--) | 获取附件文件的内容。 |
|
|  | [setContent(byte[] value)](#setContent-byte---) | 设置附件文件的内容。 |
|
|  | [getPreviewImageContent()](#getPreviewImageContent--) | 获取附件文件的预览图像，返回字节数组。 |
|
|  | [setPreviewImageContent(byte[] value)](#setPreviewImageContent-byte---) | 设置附件文件的预览图像，使用字节数组。 |
|
|  | [isLink()](#isLink--) | 获取一个值，指示内容是否仅包含指向文件的链接。 |
|
|  | [getSourceFullName()](#getSourceFullName--) | 获取附件文件的完整名称。 |
|
|  | [getAlternativeText()](#getAlternativeText--) | 获取与附件文件关联的描述性（替代）文本。 |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | 设置与附件文件关联的描述性（替代）文本。 |
|
|  | [getAsposeOleObject()](#getAsposeOleObject--) | <br /> |

|
|  | [getX()](#getX--) | 获取附件框相对于工作表左边界的水平偏移量（单位：点）。 |
|
|  | [setX(double value)](#setX-double-) | 设置附件框相对于工作表左边界的水平偏移量（单位：点）。 |
|
|  | [getY()](#getY--) | 获取附件框相对于工作表顶部边界的垂直偏移量（单位：点）。 |
|
|  | [setY(double value)](#setY-double-) | 设置附件框相对于工作表顶部边界的垂直偏移量（单位：点）。 |
|
|  | [getWidth()](#getWidth--) | 获取附件框的宽度（单位：点）。 |
|
|  | [setWidth(double value)](#setWidth-double-) | 设置附件框的宽度（单位：点）。 |
|
|  | [getHeight()](#getHeight--) | 获取附件框的高度（单位：点）。 |
|
|  | [setHeight(double value)](#setHeight-double-) | 设置附件框的高度（单位：点）。 |
|
|  | [checkImageType()](#checkImageType--) | <br /> |

|
### getContent() {#getContent--}
```
public byte[] getContent()
```


获取附件文件的内容。


**Returns:**
byte[] - 附件文件的内容。

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


设置附件文件的内容。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | byte[] | 附件文件的内容。 |
|

### getPreviewImageContent() {#getPreviewImageContent--}
```
public final byte[] getPreviewImageContent()
```


获取附件文件的预览图像，返回字节数组。


**Returns:**
byte[] - 附件文件的预览图像，字节数组形式。

### setPreviewImageContent(byte[] value) {#setPreviewImageContent-byte---}
```
public final void setPreviewImageContent(byte[] value)
```


设置附件文件的预览图像，使用字节数组。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | byte[] | 附件文件的预览图像，字节数组形式。 |
|

### isLink() {#isLink--}
```
public final boolean isLink()
```


获取一个值，指示内容是否仅包含指向文件的链接。


**Returns:**
boolean - 如果附件文件是通过链接引用的（内容不包含附件文件本身），则为 true；否则为 false。

### getSourceFullName() {#getSourceFullName--}
```
public final String getSourceFullName()
```


获取附件文件的完整名称。


**Returns:**
java.lang.String - 附件文件的完整名称。

<br />

*** ** * ** ***

扩展名用于确定打开文件的合适应用程序。

<br />


### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


获取与附件文件关联的描述性（替代）文本。


**Returns:**
java.lang.String - 与附件文件关联的描述性（替代）文本。

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


设置与附件文件关联的描述性（替代）文本。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 与附件文件关联的描述性（替代）文本。 |
|

### getAsposeOleObject() {#getAsposeOleObject--}
```
public final OleObject getAsposeOleObject()
```


<br />



**Returns:**
com.aspose.cells.OleObject
### getX() {#getX--}
```
public final double getX()
```


获取附件框相对于工作表左边界的水平偏移量（单位：点）。


**Returns:**
double - 附件框架的 x 坐标。

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


设置附件框相对于工作表左边界的水平偏移量（单位：点）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | double | 附件框架的 x 坐标。 |
|

### getY() {#getY--}
```
public final double getY()
```


获取附件框相对于工作表顶部边界的垂直偏移量（单位：点）。


**Returns:**
double - 附件框架的 y 坐标。

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


设置附件框相对于工作表顶部边界的垂直偏移量（单位：点）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | double | 附件框架的 y 坐标。 |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


获取附件框的宽度（单位：点）。


**Returns:**
double - 附件框架的宽度（单位：点）。

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


设置附件框的宽度（单位：点）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | double | 附件框架的宽度（单位：点）。 |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


获取附件框的高度（单位：点）。


**Returns:**
double - 附件框架的高度（单位：点）。

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


设置附件框的高度（单位：点）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | double | 附件框架的高度（单位：点）。 |
|

### checkImageType() {#checkImageType--}
```
public final void checkImageType()
```


<br />



