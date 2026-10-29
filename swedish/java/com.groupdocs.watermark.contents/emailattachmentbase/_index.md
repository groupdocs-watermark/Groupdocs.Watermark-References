---
title: "EmailAttachmentBase"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Tillhandahåller en basklass för e‑postbilagor."
type: docs
weight: 31
url: /sv/java/com.groupdocs.watermark.contents/emailattachmentbase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)
```
public abstract class EmailAttachmentBase extends Attachment
```

Tillhandahåller en basklass för e‑postbilagor.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getContentId()](#getContentId--) | Hämtar innehålls‑id för detta `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`. |
|
|  | [getMediaType()](#getMediaType--) | Hämtar mediatypen för detta `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`. |
|
|  | [getContent()](#getContent--) | Hämtar det bifogade filinnehållet. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | Ställer in det bifogade filinnehållet. |
|
| [getContentStream()](#getContentStream--) |  |
| [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) |  |
### getContentId() {#getContentId--}
```
public final String getContentId()
```


Hämtar innehålls‑id för detta `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`.


**Returns:**
java.lang.String - Innehålls‑id för detta `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`.

### getMediaType() {#getMediaType--}
```
public final String getMediaType()
```


Hämtar mediatypen för detta `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`.


**Returns:**
java.lang.String - Mediatypen för detta `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`.

### getContent() {#getContent--}
```
public byte[] getContent()
```


Hämtar det bifogade filinnehållet.


**Returns:**
byte[] - Det bifogade filinnehållet.

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


Ställer in det bifogade filinnehållet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | byte[] | Det bifogade filinnehållet. |
|

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


Hämtar en ström från den bifogade filen.


**Returns:**
com.aspose.ms.System.IO.Stream
### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


Uppdaterar den bifogade filen från en ström.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

