---
title: EmailContent
second_title: GroupDocs.Watermark for Java API Reference
description: Represents an email message.
type: docs
weight: 34
url: /java/com.groupdocs.watermark.contents/emailcontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)
```
public final class EmailContent extends Content
```

Represents an email message.

**Learn more:**

 *  [Add watermarks to email attachments][]
 *  [Email attachments][]
 *  [Email messages][]


[Add watermarks to email attachments]: https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+email+attachments
[Email attachments]: https://docs.groupdocs.com/display/watermarkjava/Email+attachments
[Email messages]: https://docs.groupdocs.com/display/watermarkjava/Email+messages
## Constructors

| Constructor | Description |
| --- | --- |
| [EmailContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileFormatInfo fileFormatInfo, EmailLoadOptions emailLoadOptions, WatermarkerSettings watermarkerSettings)](#EmailContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.email.FileFormatInfo-com.groupdocs.watermark.options.EmailLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getAttachments()](#getAttachments--) | Gets the collection of all attachments of the email message. |
| [getEmbeddedObjects()](#getEmbeddedObjects--) | Gets the collection of all embedded objects of the email message. |
| [getFrom()](#getFrom--) | Gets the from address of the email message. |
| [getTo()](#getTo--) | Gets the collection of recipients of the email message. |
| [getCc()](#getCc--) | Gets the collection of CC (carbon copy) recipients of the email message. |
| [getBcc()](#getBcc--) | Gets the collection of BCC (blind carbon copy) recipients of the email message. |
| [getSubject()](#getSubject--) | Gets the subject of the email message. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Sets the subject of the email message. |
| [getBody()](#getBody--) | Gets the plain text representation of the message body. |
| [setBody(String value)](#setBody-java.lang.String-) | Sets the plain text representation of the message body. |
| [getHtmlBody()](#getHtmlBody--) | Gets the html representation of the message body. |
| [setHtmlBody(String value)](#setHtmlBody-java.lang.String-) | Sets the html representation of the message body. |
| [getBodyType()](#getBodyType--) | Gets the type of the email message body. |
| [performSave(String filePath)](#performSave-java.lang.String-) |  |
| [performSave(String filePath, SaveOptions saveOptions)](#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-) |  |
| [performSave(OutputStream stream)](#performSave-java.io.OutputStream-) |  |
| [performSave(OutputStream stream, SaveOptions saveOptions)](#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) |  |
| [getDocumentInfo()](#getDocumentInfo--) |  |
| [getFileType()](#getFileType--) |  |
| [add(Watermark watermark, WatermarkOptions options)](#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-) |  |
| [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.watermark.options.PreviewOptions-) |  |
### EmailContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileFormatInfo fileFormatInfo, EmailLoadOptions emailLoadOptions, WatermarkerSettings watermarkerSettings) {#EmailContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.email.FileFormatInfo-com.groupdocs.watermark.options.EmailLoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public EmailContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileFormatInfo fileFormatInfo, EmailLoadOptions emailLoadOptions, WatermarkerSettings watermarkerSettings)
```




**Parameters:**
| Parameter | Type | Description |
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


Gets the collection of all attachments of the email message.

**Returns:**
[EmailAttachmentCollection](../../com.groupdocs.watermark.contents/emailattachmentcollection) - The collection of all attachments of the email message.
### getEmbeddedObjects() {#getEmbeddedObjects--}
```
public final EmailEmbeddedObjectCollection getEmbeddedObjects()
```


Gets the collection of all embedded objects of the email message.

**Returns:**
[EmailEmbeddedObjectCollection](../../com.groupdocs.watermark.contents/emailembeddedobjectcollection) - The collection of all embedded objects of the email message.
### getFrom() {#getFrom--}
```
public final EmailAddress getFrom()
```


Gets the from address of the email message.

**Returns:**
[EmailAddress](../../com.groupdocs.watermark.contents/emailaddress) - The from address of the email message.
### getTo() {#getTo--}
```
public final EmailAddressCollection getTo()
```


Gets the collection of recipients of the email message.

**Returns:**
[EmailAddressCollection](../../com.groupdocs.watermark.contents/emailaddresscollection) - The collection of recipients of the email message.
### getCc() {#getCc--}
```
public final EmailAddressCollection getCc()
```


Gets the collection of CC (carbon copy) recipients of the email message.

**Returns:**
[EmailAddressCollection](../../com.groupdocs.watermark.contents/emailaddresscollection) - The collection of CC (carbon copy) recipients of the email message.
### getBcc() {#getBcc--}
```
public final EmailAddressCollection getBcc()
```


Gets the collection of BCC (blind carbon copy) recipients of the email message.

**Returns:**
[EmailAddressCollection](../../com.groupdocs.watermark.contents/emailaddresscollection) - The collection of BCC (blind carbon copy) recipients of the email message.
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets the subject of the email message.

**Returns:**
java.lang.String - The subject of the email message.
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Sets the subject of the email message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The subject of the email message. |

### getBody() {#getBody--}
```
public final String getBody()
```


Gets the plain text representation of the message body.

**Returns:**
java.lang.String - The plain text representation of the message body.
### setBody(String value) {#setBody-java.lang.String-}
```
public final void setBody(String value)
```


Sets the plain text representation of the message body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The plain text representation of the message body. |

### getHtmlBody() {#getHtmlBody--}
```
public final String getHtmlBody()
```


Gets the html representation of the message body.

**Returns:**
java.lang.String - The html representation of the message body.
### setHtmlBody(String value) {#setHtmlBody-java.lang.String-}
```
public final void setHtmlBody(String value)
```


Sets the html representation of the message body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The html representation of the message body. |

### getBodyType() {#getBodyType--}
```
public final int getBodyType()
```


Gets the type of the email message body.

**Returns:**
int - The type of the email message body.
### performSave(String filePath) {#performSave-java.lang.String-}
```
public void performSave(String filePath)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String |  |

### performSave(String filePath, SaveOptions saveOptions) {#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(String filePath, SaveOptions saveOptions)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### performSave(OutputStream stream) {#performSave-java.io.OutputStream-}
```
public void performSave(OutputStream stream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream |  |

### performSave(OutputStream stream, SaveOptions saveOptions) {#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(OutputStream stream, SaveOptions saveOptions)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### getDocumentInfo() {#getDocumentInfo--}
```
public IDocumentInfo getDocumentInfo()
```




**Returns:**
[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo)
### getFileType() {#getFileType--}
```
public FileType getFileType()
```




**Returns:**
[FileType](../../com.groupdocs.watermark.common/filetype)
### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public void add(Watermark watermark, WatermarkOptions options)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) |  |

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public void generatePreview(PreviewOptions previewOptions)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) |  |

