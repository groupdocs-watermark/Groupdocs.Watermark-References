---
title: "EmailContent"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar ett e‑postmeddelande."
type: docs
weight: 34
url: /sv/java/com.groupdocs.watermark.contents/emailcontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)
```
public final class EmailContent extends Content
```

Representerar ett e‑postmeddelande.

**Learn more:**

* [Add watermarks to email attachments](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+email+attachments)
* [Email attachments](../https://docs.groupdocs.com/display/watermarkjava/Email+attachments)
* [Email messages](../https://docs.groupdocs.com/display/watermarkjava/Email+messages)

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [EmailContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileFormatInfo fileFormatInfo, EmailLoadOptions emailLoadOptions, WatermarkerSettings watermarkerSettings)](#EmailContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.email.FileFormatInfo-com.groupdocs.watermark.options.EmailLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | <br /> |

|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getAttachments()](#getAttachments--) | Hämtar samlingen av alla bilagor i e-postmeddelandet. |
|
|  | [getEmbeddedObjects()](#getEmbeddedObjects--) | Hämtar samlingen av alla inbäddade objekt i e-postmeddelandet. |
|
|  | [getFrom()](#getFrom--) | Hämtar avsändaradressen för e-postmeddelandet. |
|
|  | [getTo()](#getTo--) | Hämtar samlingen av mottagare för e-postmeddelandet. |
|
|  | [getCc()](#getCc--) | Hämtar samlingen av CC-mottagare (kopia) för e-postmeddelandet. |
|
|  | [getBcc()](#getBcc--) | Hämtar samlingen av BCC-mottagare (hemlig kopia) för e-postmeddelandet. |
|
|  | [getSubject()](#getSubject--) | Hämtar ämnet för e-postmeddelandet. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | Ställer in ämnet för e‑postmeddelandet. |
|
|  | [getBody()](#getBody--) | Hämtar den rena textrepresentationen av meddelandekroppen. |
|
|  | [setBody(String value)](#setBody-java.lang.String-) | Ställer in den rena textrepresentationen av meddelandekroppen. |
|
|  | [getHtmlBody()](#getHtmlBody--) | Hämtar HTML‑representationen av meddelandekroppen. |
|
|  | [setHtmlBody(String value)](#setHtmlBody-java.lang.String-) | Ställer in HTML‑representationen av meddelandekroppen. |
|
|  | [getBodyType()](#getBodyType--) | Hämtar typen av e‑postmeddelandekroppen. |
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
| Parameter | Typ | Beskrivning |
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


Hämtar samlingen av alla bilagor i e-postmeddelandet.


**Returns:**
[EmailAttachmentCollection](../../com.groupdocs.watermark.contents/emailattachmentcollection) - The collection of all attachments of the email message.

### getEmbeddedObjects() {#getEmbeddedObjects--}
```
public final EmailEmbeddedObjectCollection getEmbeddedObjects()
```


Hämtar samlingen av alla inbäddade objekt i e-postmeddelandet.


**Returns:**
[EmailEmbeddedObjectCollection](../../com.groupdocs.watermark.contents/emailembeddedobjectcollection) - The collection of all embedded objects of the email message.

### getFrom() {#getFrom--}
```
public final EmailAddress getFrom()
```


Hämtar avsändaradressen för e-postmeddelandet.


**Returns:**
[EmailAddress](../../com.groupdocs.watermark.contents/emailaddress) - The from address of the email message.

### getTo() {#getTo--}
```
public final EmailAddressCollection getTo()
```


Hämtar samlingen av mottagare för e-postmeddelandet.


**Returns:**
[EmailAddressCollection](../../com.groupdocs.watermark.contents/emailaddresscollection) - The collection of recipients of the email message.

### getCc() {#getCc--}
```
public final EmailAddressCollection getCc()
```


Hämtar samlingen av CC-mottagare (kopia) för e-postmeddelandet.


**Returns:**
[EmailAddressCollection](../../com.groupdocs.watermark.contents/emailaddresscollection) - The collection of CC (carbon copy) recipients of the email message.

### getBcc() {#getBcc--}
```
public final EmailAddressCollection getBcc()
```


Hämtar samlingen av BCC-mottagare (hemlig kopia) för e-postmeddelandet.


**Returns:**
[EmailAddressCollection](../../com.groupdocs.watermark.contents/emailaddresscollection) - The collection of BCC (blind carbon copy) recipients of the email message.

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Hämtar ämnet för e-postmeddelandet.


**Returns:**
java.lang.String - Ämnet för e‑postmeddelandet.

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Ställer in ämnet för e‑postmeddelandet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.lang.String | Ämnet för e‑postmeddelandet. |
|

### getBody() {#getBody--}
```
public final String getBody()
```


Hämtar den rena textrepresentationen av meddelandekroppen.


**Returns:**
java.lang.String - Den rena textrepresentationen av meddelandekroppen.

### setBody(String value) {#setBody-java.lang.String-}
```
public final void setBody(String value)
```


Ställer in den rena textrepresentationen av meddelandekroppen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.lang.String | Den rena textrepresentationen av meddelandekroppen. |
|

### getHtmlBody() {#getHtmlBody--}
```
public final String getHtmlBody()
```


Hämtar HTML‑representationen av meddelandekroppen.


**Returns:**
java.lang.String - HTML‑representationen av meddelandekroppen.

### setHtmlBody(String value) {#setHtmlBody-java.lang.String-}
```
public final void setHtmlBody(String value)
```


Ställer in HTML‑representationen av meddelandekroppen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.lang.String | HTML‑representationen av meddelandekroppen. |
|

### getBodyType() {#getBodyType--}
```
public final int getBodyType()
```


Hämtar typen av e‑postmeddelandekroppen.


**Returns:**
int - Typen av e‑postmeddelandekroppen.

### performSave(String filePath) {#performSave-java.lang.String-}
```
public void performSave(String filePath)
```


<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String |  |

### performSave(String filePath, SaveOptions saveOptions) {#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(String filePath, SaveOptions saveOptions)
```


<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### performSave(OutputStream stream) {#performSave-java.io.OutputStream-}
```
public void performSave(OutputStream stream)
```


<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream |  |

### performSave(OutputStream stream, SaveOptions saveOptions) {#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(OutputStream stream, SaveOptions saveOptions)
```


<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) |  |

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public void generatePreview(PreviewOptions previewOptions)
```


<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) |  |

