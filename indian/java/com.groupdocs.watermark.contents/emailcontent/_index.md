---
title: "EmailContent"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "एक ईमेल संदेश का प्रतिनिधित्व करता है।"
type: docs
weight: 34
url: /hi/java/com.groupdocs.watermark.contents/emailcontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)
```
public final class EmailContent extends Content
```

एक ईमेल संदेश का प्रतिनिधित्व करता है।

**Learn more:**

* [Add watermarks to email attachments](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+email+attachments)
* [Email attachments](../https://docs.groupdocs.com/display/watermarkjava/Email+attachments)
* [Email messages](../https://docs.groupdocs.com/display/watermarkjava/Email+messages)

## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [EmailContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileFormatInfo fileFormatInfo, EmailLoadOptions emailLoadOptions, WatermarkerSettings watermarkerSettings)](#EmailContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.email.FileFormatInfo-com.groupdocs.watermark.options.EmailLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | <br /> |

|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getAttachments()](#getAttachments--) | ईमेल संदेश के सभी अटैचमेंट्स का संग्रह प्राप्त करता है। |
|
|  | [getEmbeddedObjects()](#getEmbeddedObjects--) | ईमेल संदेश के सभी एम्बेडेड ऑब्जेक्ट्स का संग्रह प्राप्त करता है। |
|
|  | [getFrom()](#getFrom--) | ईमेल संदेश का प्रेषक पता प्राप्त करता है। |
|
|  | [getTo()](#getTo--) | ईमेल संदेश के प्राप्तकर्ताओं का संग्रह प्राप्त करता है। |
|
|  | [getCc()](#getCc--) | ईमेल संदेश के CC (कार्बन कॉपी) प्राप्तकर्ताओं का संग्रह प्राप्त करता है। |
|
|  | [getBcc()](#getBcc--) | ईमेल संदेश के BCC (ब्लाइंड कार्बन कॉपी) प्राप्तकर्ताओं का संग्रह प्राप्त करता है। |
|
|  | [getSubject()](#getSubject--) | ईमेल संदेश का विषय प्राप्त करता है। |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | ईमेल संदेश का विषय सेट करता है। |
|
|  | [getBody()](#getBody--) | संदेश बॉडी का प्लेन टेक्स्ट प्रतिनिधित्व प्राप्त करता है। |
|
|  | [setBody(String value)](#setBody-java.lang.String-) | संदेश बॉडी का प्लेन टेक्स्ट प्रतिनिधित्व सेट करता है। |
|
|  | [getHtmlBody()](#getHtmlBody--) | संदेश बॉडी का HTML प्रतिनिधित्व प्राप्त करता है। |
|
|  | [setHtmlBody(String value)](#setHtmlBody-java.lang.String-) | संदेश बॉडी का HTML प्रतिनिधित्व सेट करता है। |
|
|  | [getBodyType()](#getBodyType--) | ईमेल संदेश बॉडी का प्रकार प्राप्त करता है। |
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
| पैरामीटर | प्रकार | विवरण |
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


ईमेल संदेश के सभी अटैचमेंट्स का संग्रह प्राप्त करता है।


**Returns:**
[EmailAttachmentCollection](../../com.groupdocs.watermark.contents/emailattachmentcollection) - The collection of all attachments of the email message.

### getEmbeddedObjects() {#getEmbeddedObjects--}
```
public final EmailEmbeddedObjectCollection getEmbeddedObjects()
```


ईमेल संदेश के सभी एम्बेडेड ऑब्जेक्ट्स का संग्रह प्राप्त करता है।


**Returns:**
[EmailEmbeddedObjectCollection](../../com.groupdocs.watermark.contents/emailembeddedobjectcollection) - The collection of all embedded objects of the email message.

### getFrom() {#getFrom--}
```
public final EmailAddress getFrom()
```


ईमेल संदेश का प्रेषक पता प्राप्त करता है।


**Returns:**
[EmailAddress](../../com.groupdocs.watermark.contents/emailaddress) - The from address of the email message.

### getTo() {#getTo--}
```
public final EmailAddressCollection getTo()
```


ईमेल संदेश के प्राप्तकर्ताओं का संग्रह प्राप्त करता है।


**Returns:**
[EmailAddressCollection](../../com.groupdocs.watermark.contents/emailaddresscollection) - The collection of recipients of the email message.

### getCc() {#getCc--}
```
public final EmailAddressCollection getCc()
```


ईमेल संदेश के CC (कार्बन कॉपी) प्राप्तकर्ताओं का संग्रह प्राप्त करता है।


**Returns:**
[EmailAddressCollection](../../com.groupdocs.watermark.contents/emailaddresscollection) - The collection of CC (carbon copy) recipients of the email message.

### getBcc() {#getBcc--}
```
public final EmailAddressCollection getBcc()
```


ईमेल संदेश के BCC (ब्लाइंड कार्बन कॉपी) प्राप्तकर्ताओं का संग्रह प्राप्त करता है।


**Returns:**
[EmailAddressCollection](../../com.groupdocs.watermark.contents/emailaddresscollection) - The collection of BCC (blind carbon copy) recipients of the email message.

### getSubject() {#getSubject--}
```
public final String getSubject()
```


ईमेल संदेश का विषय प्राप्त करता है।


**Returns:**
java.lang.String - ईमेल संदेश का विषय।

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


ईमेल संदेश का विषय सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | ईमेल संदेश का विषय। |
|

### getBody() {#getBody--}
```
public final String getBody()
```


संदेश बॉडी का प्लेन टेक्स्ट प्रतिनिधित्व प्राप्त करता है।


**Returns:**
java.lang.String - संदेश बॉडी का प्लेन टेक्स्ट प्रतिनिधित्व।

### setBody(String value) {#setBody-java.lang.String-}
```
public final void setBody(String value)
```


संदेश बॉडी का प्लेन टेक्स्ट प्रतिनिधित्व सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | संदेश बॉडी का साधारण टेक्स्ट प्रतिनिधित्व। |
|

### getHtmlBody() {#getHtmlBody--}
```
public final String getHtmlBody()
```


संदेश बॉडी का HTML प्रतिनिधित्व प्राप्त करता है।


**Returns:**
java.lang.String - संदेश बॉडी का HTML प्रतिनिधित्व।

### setHtmlBody(String value) {#setHtmlBody-java.lang.String-}
```
public final void setHtmlBody(String value)
```


संदेश बॉडी का HTML प्रतिनिधित्व सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | संदेश बॉडी का HTML प्रतिनिधित्व। |
|

### getBodyType() {#getBodyType--}
```
public final int getBodyType()
```


ईमेल संदेश बॉडी का प्रकार प्राप्त करता है।


**Returns:**
int - ईमेल संदेश बॉडी का प्रकार।

### performSave(String filePath) {#performSave-java.lang.String-}
```
public void performSave(String filePath)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String |  |

### performSave(String filePath, SaveOptions saveOptions) {#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(String filePath, SaveOptions saveOptions)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### performSave(OutputStream stream) {#performSave-java.io.OutputStream-}
```
public void performSave(OutputStream stream)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream |  |

### performSave(OutputStream stream, SaveOptions saveOptions) {#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(OutputStream stream, SaveOptions saveOptions)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) |  |

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public void generatePreview(PreviewOptions previewOptions)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) |  |

