---
title: "EmailAttachmentBase"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "提供电子邮件附件的基类。"
type: docs
weight: 31
url: /zh/java/com.groupdocs.watermark.contents/emailattachmentbase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)
```
public abstract class EmailAttachmentBase extends Attachment
```

提供电子邮件附件的基类。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getContentId()](#getContentId--) | 获取此 `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)` 的内容 ID。 |
|
|  | [getMediaType()](#getMediaType--) | 获取此 `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)` 的媒体类型。 |
|
|  | [getContent()](#getContent--) | 获取附件文件的内容。 |
|
|  | [setContent(byte[] value)](#setContent-byte---) | 设置附件文件的内容。 |
|
| [getContentStream()](#getContentStream--) |  |
| [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) |  |
### getContentId() {#getContentId--}
```
public final String getContentId()
```


获取此 `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)` 的内容 ID。


**Returns:**
java.lang.String - 此 `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)` 的内容 ID。

### getMediaType() {#getMediaType--}
```
public final String getMediaType()
```


获取此 `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)` 的媒体类型。


**Returns:**
java.lang.String - 此 `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)` 的媒体类型。

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

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


获取附件文件的流。


**Returns:**
com.aspose.ms.System.IO.Stream
### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


从流更新附件文件。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

