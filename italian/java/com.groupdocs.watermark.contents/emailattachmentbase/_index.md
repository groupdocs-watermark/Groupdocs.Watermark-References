---
title: "EmailAttachmentBase"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Fornisce una classe base per gli allegati email."
type: docs
weight: 31
url: /it/java/com.groupdocs.watermark.contents/emailattachmentbase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)
```
public abstract class EmailAttachmentBase extends Attachment
```

Fornisce una classe base per gli allegati email.

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getContentId()](#getContentId--) | Ottiene l'ID del contenuto di questo `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`. |
|
|  | [getMediaType()](#getMediaType--) | Ottiene il tipo media di questo `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`. |
|
|  | [getContent()](#getContent--) | Ottiene il contenuto del file allegato. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | Imposta il contenuto del file allegato. |
|
| [getContentStream()](#getContentStream--) |  |
| [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) |  |
### getContentId() {#getContentId--}
```
public final String getContentId()
```


Ottiene l'ID del contenuto di questo `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`.


**Returns:**
java.lang.String - L'ID del contenuto di questo `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`.

### getMediaType() {#getMediaType--}
```
public final String getMediaType()
```


Ottiene il tipo media di questo `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`.


**Returns:**
java.lang.String - Il tipo media di questo `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`.

### getContent() {#getContent--}
```
public byte[] getContent()
```


Ottiene il contenuto del file allegato.


**Returns:**
byte[] - Il contenuto del file allegato.

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


Imposta il contenuto del file allegato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | byte[] | Il contenuto del file allegato. |
|

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


Ottiene uno stream dal file allegato.


**Returns:**
com.aspose.ms.System.IO.Stream
### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


Aggiorna il file allegato da uno stream.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

