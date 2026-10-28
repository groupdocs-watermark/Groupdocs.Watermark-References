---
title: "PdfAttachment"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示附加到 PDF 内容的文件。"
type: docs
weight: 58
url: /zh/java/com.groupdocs.watermark.contents/pdfattachment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)
```
public class PdfAttachment extends Attachment
```

表示附加到 PDF 内容的文件。

**Learn more:**

* [Attachments in PDF document](../https://docs.groupdocs.com/display/watermarkjava/Attachments+in+PDF+document)

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getName()](#getName--) | 获取附加文件的名称。 |
|
|  | [setName(String value)](#setName-java.lang.String-) | 设置附件文件的名称。 |
|
|  | [getDescription()](#getDescription--) | 获取附加文件的描述。 |
|
|  | [setDescription(String value)](#setDescription-java.lang.String-) | 设置附加文件的描述。 |
|
|  | [getContent()](#getContent--) | 获取附件文件的内容。 |
|
|  | [setContent(byte[] value)](#setContent-byte---) | 设置附件文件的内容。 |
|
| [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) |  |
| [getContentStream()](#getContentStream--) |  |
### getName() {#getName--}
```
public final String getName()
```


获取附加文件的名称。


**Returns:**
java.lang.String - 附件文件的名称。

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


设置附件文件的名称。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 附件文件的名称。 |
|

### getDescription() {#getDescription--}
```
public final String getDescription()
```


获取附加文件的描述。


**Returns:**
java.lang.String - 附加文件的描述。

### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```


设置附加文件的描述。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 附加文件的描述。 |
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

### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


从流更新附件文件。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


获取附件文件的流。


**Returns:**
com.aspose.ms.System.IO.Stream
