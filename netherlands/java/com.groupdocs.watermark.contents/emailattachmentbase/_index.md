---
title: "EmailAttachmentBase"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Biedt een basisklasse voor e-mailbijlagen."
type: docs
weight: 31
url: /nl/java/com.groupdocs.watermark.contents/emailattachmentbase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)
```
public abstract class EmailAttachmentBase extends Attachment
```

Biedt een basisklasse voor e-mailbijlagen.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getContentId()](#getContentId--) | Haalt de content-id op van deze `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`. |
|
|  | [getMediaType()](#getMediaType--) | Haalt het mediatype op van deze `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`. |
|
|  | [getContent()](#getContent--) | Haalt de inhoud van het bijgevoegde bestand op. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | Stelt de inhoud van het bijgevoegde bestand in. |
|
| [getContentStream()](#getContentStream--) |  |
| [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) |  |
### getContentId() {#getContentId--}
```
public final String getContentId()
```


Haalt de content-id op van deze `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`.


**Returns:**
java.lang.String - De content-id van deze `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`.

### getMediaType() {#getMediaType--}
```
public final String getMediaType()
```


Haalt het mediatype op van deze `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`.


**Returns:**
java.lang.String - Het mediatype van deze `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`.

### getContent() {#getContent--}
```
public byte[] getContent()
```


Haalt de inhoud van het bijgevoegde bestand op.


**Returns:**
byte[] - De inhoud van het bijgevoegde bestand.

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


Stelt de inhoud van het bijgevoegde bestand in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | byte[] | De inhoud van het bijgevoegde bestand. |
|

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


Haalt een stream op van het bijgevoegde bestand.


**Returns:**
com.aspose.ms.System.IO.Stream
### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


Werk het bijgevoegde bestand bij vanuit een stream.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

