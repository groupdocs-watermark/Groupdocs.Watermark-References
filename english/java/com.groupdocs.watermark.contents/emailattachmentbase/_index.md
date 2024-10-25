---
title: EmailAttachmentBase
second_title: GroupDocs.Watermark for Java API Reference
description: Provides a base class for email attachments.
type: docs
weight: 31
url: /java/com.groupdocs.watermark.contents/emailattachmentbase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)
```
public abstract class EmailAttachmentBase extends Attachment
```

Provides a base class for email attachments.
## Methods

| Method | Description |
| --- | --- |
| [getContentId()](#getContentId--) | Gets the content id of this . |
| [getMediaType()](#getMediaType--) | Gets the media type of this . |
| [getContent()](#getContent--) | Gets the attached file content. |
| [setContent(byte[] value)](#setContent-byte---) | Sets the attached file content. |
| [getContentStream()](#getContentStream--) |  |
| [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) |  |
### getContentId() {#getContentId--}
```
public final String getContentId()
```


Gets the content id of this .

**Returns:**
java.lang.String - The content id of this .
### getMediaType() {#getMediaType--}
```
public final String getMediaType()
```


Gets the media type of this .

**Returns:**
java.lang.String - The media type of this .
### getContent() {#getContent--}
```
public byte[] getContent()
```


Gets the attached file content.

**Returns:**
byte[] - The attached file content.
### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


Sets the attached file content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] | The attached file content. |

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


Gets a stream from the attached file.

**Returns:**
com.aspose.ms.System.IO.Stream
### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


Updates attached file from a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

