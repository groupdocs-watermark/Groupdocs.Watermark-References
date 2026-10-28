---
title: "EmailContent"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt een e-mailbericht voor."
type: docs
weight: 34
url: /nl/java/com.groupdocs.watermark.contents/emailcontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)
```
public final class EmailContent extends Content
```

Stelt een e-mailbericht voor.

**Learn more:**

* [Add watermarks to email attachments](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+email+attachments)
* [Email attachments](../https://docs.groupdocs.com/display/watermarkjava/Email+attachments)
* [Email messages](../https://docs.groupdocs.com/display/watermarkjava/Email+messages)

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [EmailContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileFormatInfo fileFormatInfo, EmailLoadOptions emailLoadOptions, WatermarkerSettings watermarkerSettings)](#EmailContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.email.FileFormatInfo-com.groupdocs.watermark.options.EmailLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | <br /> |

|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getAttachments()](#getAttachments--) | Haalt de collectie op van alle bijlagen van het e‑mailbericht. |
|
|  | [getEmbeddedObjects()](#getEmbeddedObjects--) | Haalt de collectie op van alle ingesloten objecten van het e‑mailbericht. |
|
|  | [getFrom()](#getFrom--) | Haalt het afzenderadres op van het e‑mailbericht. |
|
|  | [getTo()](#getTo--) | Haalt de collectie op van de ontvangers van het e‑mailbericht. |
|
|  | [getCc()](#getCc--) | Haalt de collectie op van CC‑ontvangers (carbon copy) van het e‑mailbericht. |
|
|  | [getBcc()](#getBcc--) | Haalt de collectie op van BCC‑ontvangers (blind carbon copy) van het e‑mailbericht. |
|
|  | [getSubject()](#getSubject--) | Haalt het onderwerp op van het e‑mailbericht. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | Stelt het onderwerp in van het e‑mailbericht. |
|
|  | [getBody()](#getBody--) | Haalt de platte-tekstrepresentatie op van de berichtinhoud. |
|
|  | [setBody(String value)](#setBody-java.lang.String-) | Stelt de platte-tekstrepresentatie in van de berichtinhoud. |
|
|  | [getHtmlBody()](#getHtmlBody--) | Haalt de html‑representatie op van de berichtinhoud. |
|
|  | [setHtmlBody(String value)](#setHtmlBody-java.lang.String-) | Stelt de html‑representatie in van de berichtinhoud. |
|
|  | [getBodyType()](#getBodyType--) | Haalt het type op van de berichtinhoud van het e‑mailbericht. |
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
| Parameter | Type | Beschrijving |
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


Haalt de collectie op van alle bijlagen van het e‑mailbericht.


**Returns:**
[EmailAttachmentCollection](../../com.groupdocs.watermark.contents/emailattachmentcollection) - The collection of all attachments of the email message.

### getEmbeddedObjects() {#getEmbeddedObjects--}
```
public final EmailEmbeddedObjectCollection getEmbeddedObjects()
```


Haalt de collectie op van alle ingesloten objecten van het e‑mailbericht.


**Returns:**
[EmailEmbeddedObjectCollection](../../com.groupdocs.watermark.contents/emailembeddedobjectcollection) - The collection of all embedded objects of the email message.

### getFrom() {#getFrom--}
```
public final EmailAddress getFrom()
```


Haalt het afzenderadres op van het e‑mailbericht.


**Returns:**
[EmailAddress](../../com.groupdocs.watermark.contents/emailaddress) - The from address of the email message.

### getTo() {#getTo--}
```
public final EmailAddressCollection getTo()
```


Haalt de collectie op van de ontvangers van het e‑mailbericht.


**Returns:**
[EmailAddressCollection](../../com.groupdocs.watermark.contents/emailaddresscollection) - The collection of recipients of the email message.

### getCc() {#getCc--}
```
public final EmailAddressCollection getCc()
```


Haalt de collectie op van CC‑ontvangers (carbon copy) van het e‑mailbericht.


**Returns:**
[EmailAddressCollection](../../com.groupdocs.watermark.contents/emailaddresscollection) - The collection of CC (carbon copy) recipients of the email message.

### getBcc() {#getBcc--}
```
public final EmailAddressCollection getBcc()
```


Haalt de collectie op van BCC‑ontvangers (blind carbon copy) van het e‑mailbericht.


**Returns:**
[EmailAddressCollection](../../com.groupdocs.watermark.contents/emailaddresscollection) - The collection of BCC (blind carbon copy) recipients of the email message.

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Haalt het onderwerp op van het e‑mailbericht.


**Returns:**
java.lang.String - Het onderwerp van het e‑mailbericht.

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Stelt het onderwerp in van het e‑mailbericht.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | Het onderwerp van het e‑mailbericht. |
|

### getBody() {#getBody--}
```
public final String getBody()
```


Haalt de platte-tekstrepresentatie op van de berichtinhoud.


**Returns:**
java.lang.String - De platte-tekstrepresentatie van de berichtinhoud.

### setBody(String value) {#setBody-java.lang.String-}
```
public final void setBody(String value)
```


Stelt de platte-tekstrepresentatie in van de berichtinhoud.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | De platte-tekstrepresentatie van de berichtinhoud. |
|

### getHtmlBody() {#getHtmlBody--}
```
public final String getHtmlBody()
```


Haalt de html‑representatie op van de berichtinhoud.


**Returns:**
java.lang.String - De html-representatie van de berichtinhoud.

### setHtmlBody(String value) {#setHtmlBody-java.lang.String-}
```
public final void setHtmlBody(String value)
```


Stelt de html‑representatie in van de berichtinhoud.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | De html-representatie van de berichtinhoud. |
|

### getBodyType() {#getBodyType--}
```
public final int getBodyType()
```


Haalt het type op van de berichtinhoud van het e‑mailbericht.


**Returns:**
int - Het type van de e-mailberichtinhoud.

### performSave(String filePath) {#performSave-java.lang.String-}
```
public void performSave(String filePath)
```


<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String |  |

### performSave(String filePath, SaveOptions saveOptions) {#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(String filePath, SaveOptions saveOptions)
```


<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### performSave(OutputStream stream) {#performSave-java.io.OutputStream-}
```
public void performSave(OutputStream stream)
```


<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream |  |

### performSave(OutputStream stream, SaveOptions saveOptions) {#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(OutputStream stream, SaveOptions saveOptions)
```


<br />



**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) |  |

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public void generatePreview(PreviewOptions previewOptions)
```


<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) |  |

