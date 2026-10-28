---
title: "EmailContent"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل رسالة بريد إلكتروني."
type: docs
weight: 34
url: /ar/java/com.groupdocs.watermark.contents/emailcontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)
```
public final class EmailContent extends Content
```

يمثل رسالة بريد إلكتروني.

**Learn more:**

* [Add watermarks to email attachments](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+email+attachments)
* [Email attachments](../https://docs.groupdocs.com/display/watermarkjava/Email+attachments)
* [Email messages](../https://docs.groupdocs.com/display/watermarkjava/Email+messages)

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [EmailContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileFormatInfo fileFormatInfo, EmailLoadOptions emailLoadOptions, WatermarkerSettings watermarkerSettings)](#EmailContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.email.FileFormatInfo-com.groupdocs.watermark.options.EmailLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | <br /> |

|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getAttachments()](#getAttachments--) | يحصل على مجموعة جميع المرفقات في رسالة البريد الإلكتروني. |
|
|  | [getEmbeddedObjects()](#getEmbeddedObjects--) | يحصل على مجموعة جميع الكائنات المدمجة في رسالة البريد الإلكتروني. |
|
|  | [getFrom()](#getFrom--) | يحصل على عنوان المرسل في رسالة البريد الإلكتروني. |
|
|  | [getTo()](#getTo--) | يحصل على مجموعة المستلمين في رسالة البريد الإلكتروني. |
|
|  | [getCc()](#getCc--) | يحصل على مجموعة مستلمي النسخة (CC) في رسالة البريد الإلكتروني. |
|
|  | [getBcc()](#getBcc--) | يحصل على مجموعة مستلمي النسخة المخفية (BCC) في رسالة البريد الإلكتروني. |
|
|  | [getSubject()](#getSubject--) | يحصل على موضوع رسالة البريد الإلكتروني. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | يضبط موضوع رسالة البريد الإلكتروني. |
|
|  | [getBody()](#getBody--) | يحصل على تمثيل النص العادي لمحتوى الرسالة. |
|
|  | [setBody(String value)](#setBody-java.lang.String-) | يضبط تمثيل النص العادي لمحتوى الرسالة. |
|
|  | [getHtmlBody()](#getHtmlBody--) | يحصل على تمثيل HTML لمحتوى الرسالة. |
|
|  | [setHtmlBody(String value)](#setHtmlBody-java.lang.String-) | يضبط تمثيل HTML لمحتوى الرسالة. |
|
|  | [getBodyType()](#getBodyType--) | يحصل على نوع محتوى رسالة البريد الإلكتروني. |
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
| معامل | نوع | الوصف |
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


يحصل على مجموعة جميع المرفقات في رسالة البريد الإلكتروني.


**Returns:**
[EmailAttachmentCollection](../../com.groupdocs.watermark.contents/emailattachmentcollection) - The collection of all attachments of the email message.

### getEmbeddedObjects() {#getEmbeddedObjects--}
```
public final EmailEmbeddedObjectCollection getEmbeddedObjects()
```


يحصل على مجموعة جميع الكائنات المدمجة في رسالة البريد الإلكتروني.


**Returns:**
[EmailEmbeddedObjectCollection](../../com.groupdocs.watermark.contents/emailembeddedobjectcollection) - The collection of all embedded objects of the email message.

### getFrom() {#getFrom--}
```
public final EmailAddress getFrom()
```


يحصل على عنوان المرسل في رسالة البريد الإلكتروني.


**Returns:**
[EmailAddress](../../com.groupdocs.watermark.contents/emailaddress) - The from address of the email message.

### getTo() {#getTo--}
```
public final EmailAddressCollection getTo()
```


يحصل على مجموعة المستلمين في رسالة البريد الإلكتروني.


**Returns:**
[EmailAddressCollection](../../com.groupdocs.watermark.contents/emailaddresscollection) - The collection of recipients of the email message.

### getCc() {#getCc--}
```
public final EmailAddressCollection getCc()
```


يحصل على مجموعة مستلمي النسخة (CC) في رسالة البريد الإلكتروني.


**Returns:**
[EmailAddressCollection](../../com.groupdocs.watermark.contents/emailaddresscollection) - The collection of CC (carbon copy) recipients of the email message.

### getBcc() {#getBcc--}
```
public final EmailAddressCollection getBcc()
```


يحصل على مجموعة مستلمي النسخة المخفية (BCC) في رسالة البريد الإلكتروني.


**Returns:**
[EmailAddressCollection](../../com.groupdocs.watermark.contents/emailaddresscollection) - The collection of BCC (blind carbon copy) recipients of the email message.

### getSubject() {#getSubject--}
```
public final String getSubject()
```


يحصل على موضوع رسالة البريد الإلكتروني.


**Returns:**
java.lang.String - موضوع رسالة البريد الإلكتروني.

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


يضبط موضوع رسالة البريد الإلكتروني.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | java.lang.String | موضوع رسالة البريد الإلكتروني. |
|

### getBody() {#getBody--}
```
public final String getBody()
```


يحصل على تمثيل النص العادي لمحتوى الرسالة.


**Returns:**
java.lang.String - تمثيل النص العادي لمحتوى الرسالة.

### setBody(String value) {#setBody-java.lang.String-}
```
public final void setBody(String value)
```


يضبط تمثيل النص العادي لمحتوى الرسالة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | java.lang.String | تمثيل النص العادي لمحتوى الرسالة. |
|

### getHtmlBody() {#getHtmlBody--}
```
public final String getHtmlBody()
```


يحصل على تمثيل HTML لمحتوى الرسالة.


**Returns:**
java.lang.String - تمثيل html لمحتوى الرسالة.

### setHtmlBody(String value) {#setHtmlBody-java.lang.String-}
```
public final void setHtmlBody(String value)
```


يضبط تمثيل HTML لمحتوى الرسالة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | java.lang.String | تمثيل html لمحتوى الرسالة. |
|

### getBodyType() {#getBodyType--}
```
public final int getBodyType()
```


يحصل على نوع محتوى رسالة البريد الإلكتروني.


**Returns:**
int - نوع محتوى رسالة البريد الإلكتروني.

### performSave(String filePath) {#performSave-java.lang.String-}
```
public void performSave(String filePath)
```


<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String |  |

### performSave(String filePath, SaveOptions saveOptions) {#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(String filePath, SaveOptions saveOptions)
```


<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### performSave(OutputStream stream) {#performSave-java.io.OutputStream-}
```
public void performSave(OutputStream stream)
```


<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream |  |

### performSave(OutputStream stream, SaveOptions saveOptions) {#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(OutputStream stream, SaveOptions saveOptions)
```


<br />



**Parameters:**
| معامل | نوع | الوصف |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) |  |

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public void generatePreview(PreviewOptions previewOptions)
```


<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) |  |

