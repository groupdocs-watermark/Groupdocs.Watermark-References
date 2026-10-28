---
title: "EmailAttachmentBase"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يوفر فئة أساسية لمرفقات البريد الإلكتروني."
type: docs
weight: 31
url: /ar/java/com.groupdocs.watermark.contents/emailattachmentbase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)
```
public abstract class EmailAttachmentBase extends Attachment
```

يوفر فئة أساسية لمرفقات البريد الإلكتروني.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getContentId()](#getContentId--) | يحصل على معرف المحتوى لهذا `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`. |
|
|  | [getMediaType()](#getMediaType--) | يحصل على نوع الوسائط لهذا `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`. |
|
|  | [getContent()](#getContent--) | يحصل على محتوى الملف المرفق. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | يضبط محتوى الملف المرفق. |
|
| [getContentStream()](#getContentStream--) |  |
| [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) |  |
### getContentId() {#getContentId--}
```
public final String getContentId()
```


يحصل على معرف المحتوى لهذا `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`.


**Returns:**
java.lang.String - معرف المحتوى لهذا `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`.

### getMediaType() {#getMediaType--}
```
public final String getMediaType()
```


يحصل على نوع الوسائط لهذا `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`.


**Returns:**
java.lang.String - نوع الوسائط لهذا `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`.

### getContent() {#getContent--}
```
public byte[] getContent()
```


يحصل على محتوى الملف المرفق.


**Returns:**
byte[] - محتوى الملف المرفق.

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


يضبط محتوى الملف المرفق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | byte[] | محتوى الملف المرفق. |
|

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


يحصل على تدفق من الملف المرفق.


**Returns:**
com.aspose.ms.System.IO.Stream
### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


يقوم بتحديث الملف المرفق من تدفق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

