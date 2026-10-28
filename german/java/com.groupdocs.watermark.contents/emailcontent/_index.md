---
title: "EmailContent"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt eine E-Mail-Nachricht dar."
type: docs
weight: 34
url: /de/java/com.groupdocs.watermark.contents/emailcontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)
```
public final class EmailContent extends Content
```

Stellt eine E-Mail-Nachricht dar.

**Learn more:**

* [Add watermarks to email attachments](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+email+attachments)
* [Email attachments](../https://docs.groupdocs.com/display/watermarkjava/Email+attachments)
* [Email messages](../https://docs.groupdocs.com/display/watermarkjava/Email+messages)

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [EmailContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileFormatInfo fileFormatInfo, EmailLoadOptions emailLoadOptions, WatermarkerSettings watermarkerSettings)](#EmailContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.email.FileFormatInfo-com.groupdocs.watermark.options.EmailLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | <br /> |

|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getAttachments()](#getAttachments--) | Ruft die Sammlung aller Anhänge der E‑Mail‑Nachricht ab. |
|
|  | [getEmbeddedObjects()](#getEmbeddedObjects--) | Ruft die Sammlung aller eingebetteten Objekte der E‑Mail‑Nachricht ab. |
|
|  | [getFrom()](#getFrom--) | Ruft die Absenderadresse der E‑Mail‑Nachricht ab. |
|
|  | [getTo()](#getTo--) | Ruft die Sammlung der Empfänger der E‑Mail‑Nachricht ab. |
|
|  | [getCc()](#getCc--) | Ruft die Sammlung der CC‑Empfänger (Carbon Copy) der E‑Mail‑Nachricht ab. |
|
|  | [getBcc()](#getBcc--) | Ruft die Sammlung der BCC‑Empfänger (Blind Carbon Copy) der E‑Mail‑Nachricht ab. |
|
|  | [getSubject()](#getSubject--) | Ruft den Betreff der E‑Mail‑Nachricht ab. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | Setzt den Betreff der E‑Mail‑Nachricht. |
|
|  | [getBody()](#getBody--) | Ruft die Klartextdarstellung des Nachrichtenkörpers ab. |
|
|  | [setBody(String value)](#setBody-java.lang.String-) | Setzt die Klartextdarstellung des Nachrichtenkörpers. |
|
|  | [getHtmlBody()](#getHtmlBody--) | Ruft die HTML-Darstellung des Nachrichtenkörpers ab. |
|
|  | [setHtmlBody(String value)](#setHtmlBody-java.lang.String-) | Setzt die HTML-Darstellung des Nachrichtenkörpers. |
|
|  | [getBodyType()](#getBodyType--) | Ruft den Typ des E‑Mail‑Nachrichtenkörpers ab. |
|
|  | [performSave(String filePath)](#performSave-java.lang.String-) | <br /> |

|
|  | [performSave(String filePath, SaveOptions saveOptions)](#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-) | <br /> |

|
|  | [performSave(OutputStream stream)](#performSave-java.io.OutputStream-) | <br /> |

|
|  | [performSave(OutputStream stream, SaveOptions saveOptions)](#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) | <br /> |

|
|  | [getDocumentInfo()](#getDocumentInfo--) | <br /> |

|
|  | [getFileType()](#getFileType--) | <br /> |

|
|  | [add(Watermark watermark, WatermarkOptions options)](#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-) | <br /> |

|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.watermark.options.PreviewOptions-) | <br /> |

|
### EmailContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileFormatInfo fileFormatInfo, EmailLoadOptions emailLoadOptions, WatermarkerSettings watermarkerSettings) {#EmailContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.email.FileFormatInfo-com.groupdocs.watermark.options.EmailLoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public EmailContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileFormatInfo fileFormatInfo, EmailLoadOptions emailLoadOptions, WatermarkerSettings watermarkerSettings)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [StreamContainer](../../com.groupdocs.watermark.internal/streamcontainer) |  |
| strategyManager | com.groupdocs.watermark.internal.StrategyManager<java.lang.Integer> |  |
| fileFormatInfo | com.aspose.email.FileFormatInfo |  |
| emailLoadOptions | [EmailLoadOptions](../../com.groupdocs.watermark.options/emailloadoptions) |  |
| watermarkerSettings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) |  |

### getAttachments() {#getAttachments--}
```
public final EmailAttachmentCollection getAttachments()
```


Ruft die Sammlung aller Anhänge der E‑Mail‑Nachricht ab.


**Returns:**
[EmailAttachmentCollection](../../com.groupdocs.watermark.contents/emailattachmentcollection) - The collection of all attachments of the email message.

### getEmbeddedObjects() {#getEmbeddedObjects--}
```
public final EmailEmbeddedObjectCollection getEmbeddedObjects()
```


Ruft die Sammlung aller eingebetteten Objekte der E‑Mail‑Nachricht ab.


**Returns:**
[EmailEmbeddedObjectCollection](../../com.groupdocs.watermark.contents/emailembeddedobjectcollection) - The collection of all embedded objects of the email message.

### getFrom() {#getFrom--}
```
public final EmailAddress getFrom()
```


Ruft die Absenderadresse der E‑Mail‑Nachricht ab.


**Returns:**
[EmailAddress](../../com.groupdocs.watermark.contents/emailaddress) - The from address of the email message.

### getTo() {#getTo--}
```
public final EmailAddressCollection getTo()
```


Ruft die Sammlung der Empfänger der E‑Mail‑Nachricht ab.


**Returns:**
[EmailAddressCollection](../../com.groupdocs.watermark.contents/emailaddresscollection) - The collection of recipients of the email message.

### getCc() {#getCc--}
```
public final EmailAddressCollection getCc()
```


Ruft die Sammlung der CC‑Empfänger (Carbon Copy) der E‑Mail‑Nachricht ab.


**Returns:**
[EmailAddressCollection](../../com.groupdocs.watermark.contents/emailaddresscollection) - The collection of CC (carbon copy) recipients of the email message.

### getBcc() {#getBcc--}
```
public final EmailAddressCollection getBcc()
```


Ruft die Sammlung der BCC‑Empfänger (Blind Carbon Copy) der E‑Mail‑Nachricht ab.


**Returns:**
[EmailAddressCollection](../../com.groupdocs.watermark.contents/emailaddresscollection) - The collection of BCC (blind carbon copy) recipients of the email message.

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Ruft den Betreff der E‑Mail‑Nachricht ab.


**Returns:**
java.lang.String - Der Betreff der E-Mail-Nachricht.

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Setzt den Betreff der E‑Mail‑Nachricht.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Der Betreff der E-Mail-Nachricht. |
|

### getBody() {#getBody--}
```
public final String getBody()
```


Ruft die Klartextdarstellung des Nachrichtenkörpers ab.


**Returns:**
java.lang.String - Die reine Textdarstellung des Nachrichtenkörpers.

### setBody(String value) {#setBody-java.lang.String-}
```
public final void setBody(String value)
```


Setzt die Klartextdarstellung des Nachrichtenkörpers.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Die reine Textdarstellung des Nachrichtenkörpers. |
|

### getHtmlBody() {#getHtmlBody--}
```
public final String getHtmlBody()
```


Ruft die HTML-Darstellung des Nachrichtenkörpers ab.


**Returns:**
java.lang.String - Die HTML-Darstellung des Nachrichtenkörpers.

### setHtmlBody(String value) {#setHtmlBody-java.lang.String-}
```
public final void setHtmlBody(String value)
```


Setzt die HTML-Darstellung des Nachrichtenkörpers.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Die HTML-Darstellung des Nachrichtenkörpers. |
|

### getBodyType() {#getBodyType--}
```
public final int getBodyType()
```


Ruft den Typ des E‑Mail‑Nachrichtenkörpers ab.


**Returns:**
int - Der Typ des E-Mail-Nachrichtenkörpers.

### performSave(String filePath) {#performSave-java.lang.String-}
```
public void performSave(String filePath)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String |  |

### performSave(String filePath, SaveOptions saveOptions) {#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(String filePath, SaveOptions saveOptions)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### performSave(OutputStream stream) {#performSave-java.io.OutputStream-}
```
public void performSave(OutputStream stream)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream |  |

### performSave(OutputStream stream, SaveOptions saveOptions) {#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(OutputStream stream, SaveOptions saveOptions)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### getDocumentInfo() {#getDocumentInfo--}
```
public IDocumentInfo getDocumentInfo()
```


<br />



**Returns:**
[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo)
### getFileType() {#getFileType--}
```
public FileType getFileType()
```


<br />



**Returns:**
[FileType](../../com.groupdocs.watermark.common/filetype)
### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public void add(Watermark watermark, WatermarkOptions options)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) |  |

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public void generatePreview(PreviewOptions previewOptions)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) |  |

