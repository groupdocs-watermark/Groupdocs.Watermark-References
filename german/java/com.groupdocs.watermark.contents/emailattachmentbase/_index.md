---
title: "EmailAttachmentBase"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt eine Basisklasse für E-Mail-Anhänge bereit."
type: docs
weight: 31
url: /de/java/com.groupdocs.watermark.contents/emailattachmentbase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)
```
public abstract class EmailAttachmentBase extends Attachment
```

Stellt eine Basisklasse für E-Mail-Anhänge bereit.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getContentId()](#getContentId--) | Ruft die Content-ID dieses `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)` ab. |
|
|  | [getMediaType()](#getMediaType--) | Ruft den Medientyp dieses `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)` ab. |
|
|  | [getContent()](#getContent--) | Liest den Inhalt der angehängten Datei. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | Setzt den Inhalt der angehängten Datei. |
|
| [getContentStream()](#getContentStream--) |  |
| [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) |  |
### getContentId() {#getContentId--}
```
public final String getContentId()
```


Ruft die Content-ID dieses `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)` ab.


**Returns:**
java.lang.String - Die Content-ID dieses `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`.

### getMediaType() {#getMediaType--}
```
public final String getMediaType()
```


Ruft den Medientyp dieses `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)` ab.


**Returns:**
java.lang.String - Der Medientyp dieses `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`.

### getContent() {#getContent--}
```
public byte[] getContent()
```


Liest den Inhalt der angehängten Datei.


**Returns:**
byte[] - Der Inhalt der angehängten Datei.

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


Setzt den Inhalt der angehängten Datei.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | byte[] | Der Inhalt der angehängten Datei. |
|

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


Liest einen Stream aus der angehängten Datei.


**Returns:**
com.aspose.ms.System.IO.Stream
### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


Aktualisiert die angehängte Datei aus einem Stream.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

