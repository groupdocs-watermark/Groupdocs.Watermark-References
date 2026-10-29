---
title: "EmailContent"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Bir e-posta mesajını temsil eder."
type: docs
weight: 34
url: /tr/java/com.groupdocs.watermark.contents/emailcontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)
```
public final class EmailContent extends Content
```

Bir e-posta mesajını temsil eder.

**Learn more:**

* [Add watermarks to email attachments](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+email+attachments)
* [Email attachments](../https://docs.groupdocs.com/display/watermarkjava/Email+attachments)
* [Email messages](../https://docs.groupdocs.com/display/watermarkjava/Email+messages)

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [EmailContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileFormatInfo fileFormatInfo, EmailLoadOptions emailLoadOptions, WatermarkerSettings watermarkerSettings)](#EmailContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.email.FileFormatInfo-com.groupdocs.watermark.options.EmailLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | <br /> |

|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getAttachments()](#getAttachments--) | E-posta mesajının tüm eklerinin koleksiyonunu alır. |
|
|  | [getEmbeddedObjects()](#getEmbeddedObjects--) | E-posta mesajının tüm gömülü nesnelerinin koleksiyonunu alır. |
|
|  | [getFrom()](#getFrom--) | E-posta mesajının gönderici adresini alır. |
|
|  | [getTo()](#getTo--) | E-posta mesajının alıcılarının koleksiyonunu alır. |
|
|  | [getCc()](#getCc--) | E-posta mesajının CC (karbon kopya) alıcılarının koleksiyonunu alır. |
|
|  | [getBcc()](#getBcc--) | E-posta mesajının BCC (gizli karbon kopya) alıcılarının koleksiyonunu alır. |
|
|  | [getSubject()](#getSubject--) | E-posta mesajının konusunu alır. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | E-posta mesajının konusunu ayarlar. |
|
|  | [getBody()](#getBody--) | Mesaj gövdesinin düz metin temsilini alır. |
|
|  | [setBody(String value)](#setBody-java.lang.String-) | Mesaj gövdesinin düz metin temsilini ayarlar. |
|
|  | [getHtmlBody()](#getHtmlBody--) | Mesaj gövdesinin html temsilini alır. |
|
|  | [setHtmlBody(String value)](#setHtmlBody-java.lang.String-) | Mesaj gövdesinin html temsilini ayarlar. |
|
|  | [getBodyType()](#getBodyType--) | E-posta mesajı gövdesinin tipini alır. |
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
| Parametre | Tür | Açıklama |
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


E-posta mesajının tüm eklerinin koleksiyonunu alır.


**Returns:**
[EmailAttachmentCollection](../../com.groupdocs.watermark.contents/emailattachmentcollection) - The collection of all attachments of the email message.

### getEmbeddedObjects() {#getEmbeddedObjects--}
```
public final EmailEmbeddedObjectCollection getEmbeddedObjects()
```


E-posta mesajının tüm gömülü nesnelerinin koleksiyonunu alır.


**Returns:**
[EmailEmbeddedObjectCollection](../../com.groupdocs.watermark.contents/emailembeddedobjectcollection) - The collection of all embedded objects of the email message.

### getFrom() {#getFrom--}
```
public final EmailAddress getFrom()
```


E-posta mesajının gönderici adresini alır.


**Returns:**
[EmailAddress](../../com.groupdocs.watermark.contents/emailaddress) - The from address of the email message.

### getTo() {#getTo--}
```
public final EmailAddressCollection getTo()
```


E-posta mesajının alıcılarının koleksiyonunu alır.


**Returns:**
[EmailAddressCollection](../../com.groupdocs.watermark.contents/emailaddresscollection) - The collection of recipients of the email message.

### getCc() {#getCc--}
```
public final EmailAddressCollection getCc()
```


E-posta mesajının CC (karbon kopya) alıcılarının koleksiyonunu alır.


**Returns:**
[EmailAddressCollection](../../com.groupdocs.watermark.contents/emailaddresscollection) - The collection of CC (carbon copy) recipients of the email message.

### getBcc() {#getBcc--}
```
public final EmailAddressCollection getBcc()
```


E-posta mesajının BCC (gizli karbon kopya) alıcılarının koleksiyonunu alır.


**Returns:**
[EmailAddressCollection](../../com.groupdocs.watermark.contents/emailaddresscollection) - The collection of BCC (blind carbon copy) recipients of the email message.

### getSubject() {#getSubject--}
```
public final String getSubject()
```


E-posta mesajının konusunu alır.


**Returns:**
java.lang.String - E-posta mesajının konusu.

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


E-posta mesajının konusunu ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | E-posta mesajının konusu. |
|

### getBody() {#getBody--}
```
public final String getBody()
```


Mesaj gövdesinin düz metin temsilini alır.


**Returns:**
java.lang.String - Mesaj gövdesinin düz metin temsili.

### setBody(String value) {#setBody-java.lang.String-}
```
public final void setBody(String value)
```


Mesaj gövdesinin düz metin temsilini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Mesaj gövdesinin düz metin temsili. |
|

### getHtmlBody() {#getHtmlBody--}
```
public final String getHtmlBody()
```


Mesaj gövdesinin html temsilini alır.


**Returns:**
java.lang.String - Mesaj gövdesinin html temsili.

### setHtmlBody(String value) {#setHtmlBody-java.lang.String-}
```
public final void setHtmlBody(String value)
```


Mesaj gövdesinin html temsilini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Mesaj gövdesinin html temsili. |
|

### getBodyType() {#getBodyType--}
```
public final int getBodyType()
```


E-posta mesajı gövdesinin tipini alır.


**Returns:**
int - E-posta mesaj gövdesinin türü.

### performSave(String filePath) {#performSave-java.lang.String-}
```
public void performSave(String filePath)
```


<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String |  |

### performSave(String filePath, SaveOptions saveOptions) {#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(String filePath, SaveOptions saveOptions)
```


<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### performSave(OutputStream stream) {#performSave-java.io.OutputStream-}
```
public void performSave(OutputStream stream)
```


<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream |  |

### performSave(OutputStream stream, SaveOptions saveOptions) {#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(OutputStream stream, SaveOptions saveOptions)
```


<br />



**Parameters:**
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) |  |

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public void generatePreview(PreviewOptions previewOptions)
```


<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) |  |

