---
title: PdfAttachment
second_title: GroupDocs.Watermark for Java API Reference
description: Represents a file attached to a pdf content.
type: docs
weight: 58
url: /java/com.groupdocs.watermark.contents/pdfattachment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)
```
public class PdfAttachment extends Attachment
```

Represents a file attached to a pdf content.

**Learn more:**

 *  [Attachments in PDF document][]


[Attachments in PDF document]: https://docs.groupdocs.com/display/watermarkjava/Attachments+in+PDF+document
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Gets the name of the attached file. |
| [setName(String value)](#setName-java.lang.String-) | Sets the name of the attached file. |
| [getDescription()](#getDescription--) | Gets the description of the attached file. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Sets the description of the attached file. |
| [getContent()](#getContent--) | Gets the attached file content. |
| [setContent(byte[] value)](#setContent-byte---) | Sets the attached file content. |
| [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) |  |
| [getContentStream()](#getContentStream--) |  |
### getName() {#getName--}
```
public final String getName()
```


Gets the name of the attached file.

**Returns:**
java.lang.String - The name of the attached file.
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Sets the name of the attached file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name of the attached file. |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Gets the description of the attached file.

**Returns:**
java.lang.String - The description of the attached file.
### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```


Sets the description of the attached file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The description of the attached file. |

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

### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


Updates attached file from a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


Gets a stream from the attached file.

**Returns:**
com.aspose.ms.System.IO.Stream
