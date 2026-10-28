---
title: "EmailAttachmentBase"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Menyediakan kelas dasar untuk lampiran email."
type: docs
weight: 31
url: /id/java/com.groupdocs.watermark.contents/emailattachmentbase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)
```
public abstract class EmailAttachmentBase extends Attachment
```

Menyediakan kelas dasar untuk lampiran email.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getContentId()](#getContentId--) | Mendapatkan content id dari `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)` ini. |
|
|  | [getMediaType()](#getMediaType--) | Mendapatkan tipe media dari `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)` ini. |
|
|  | [getContent()](#getContent--) | Mendapatkan konten file terlampir. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | Mengatur konten file terlampir. |
|
| [getContentStream()](#getContentStream--) |  |
| [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) |  |
### getContentId() {#getContentId--}
```
public final String getContentId()
```


Mendapatkan content id dari `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)` ini.


**Returns:**
java.lang.String - Content id dari `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)` ini.

### getMediaType() {#getMediaType--}
```
public final String getMediaType()
```


Mendapatkan tipe media dari `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)` ini.


**Returns:**
java.lang.String - Tipe media dari `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)` ini.

### getContent() {#getContent--}
```
public byte[] getContent()
```


Mendapatkan konten file terlampir.


**Returns:**
byte[] - Konten file terlampir.

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


Mengatur konten file terlampir.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | byte[] | Konten file terlampir. |
|

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


Mendapatkan aliran dari file terlampir.


**Returns:**
com.aspose.ms.System.IO.Stream
### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


Memperbarui file terlampir dari aliran.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

