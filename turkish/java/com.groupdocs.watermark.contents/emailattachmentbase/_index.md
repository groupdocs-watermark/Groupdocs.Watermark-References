---
title: "EmailAttachmentBase"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "E-posta ekleri için temel bir sınıf sağlar."
type: docs
weight: 31
url: /tr/java/com.groupdocs.watermark.contents/emailattachmentbase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)
```
public abstract class EmailAttachmentBase extends Attachment
```

E-posta ekleri için temel bir sınıf sağlar.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getContentId()](#getContentId--) | Bu `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)` öğesinin içerik kimliğini alır. |
|
|  | [getMediaType()](#getMediaType--) | Bu `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)` öğesinin medya tipini alır. |
|
|  | [getContent()](#getContent--) | Ekli dosya içeriğini alır. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | Ekli dosya içeriğini ayarlar. |
|
| [getContentStream()](#getContentStream--) |  |
| [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) |  |
### getContentId() {#getContentId--}
```
public final String getContentId()
```


Bu `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)` öğesinin içerik kimliğini alır.


**Returns:**
java.lang.String - Bu `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)` öğesinin içerik kimliği.

### getMediaType() {#getMediaType--}
```
public final String getMediaType()
```


Bu `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)` öğesinin medya tipini alır.


**Returns:**
java.lang.String - Bu `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)` öğesinin medya tipi.

### getContent() {#getContent--}
```
public byte[] getContent()
```


Ekli dosya içeriğini alır.


**Returns:**
byte[] - Ekli dosya içeriği.

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


Ekli dosya içeriğini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | byte[] | Ekli dosya içeriği. |
|

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


Ekli dosyadan bir akış alır.


**Returns:**
com.aspose.ms.System.IO.Stream
### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


Bir akıştan ekli dosyayı günceller.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

