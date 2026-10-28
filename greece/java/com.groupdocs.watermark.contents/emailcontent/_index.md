---
title: "EmailContent"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αντιπροσωπεύει ένα μήνυμα email."
type: docs
weight: 34
url: /el/java/com.groupdocs.watermark.contents/emailcontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)
```
public final class EmailContent extends Content
```

Αντιπροσωπεύει ένα μήνυμα email.

**Learn more:**

* [Add watermarks to email attachments](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+email+attachments)
* [Email attachments](../https://docs.groupdocs.com/display/watermarkjava/Email+attachments)
* [Email messages](../https://docs.groupdocs.com/display/watermarkjava/Email+messages)

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [EmailContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileFormatInfo fileFormatInfo, EmailLoadOptions emailLoadOptions, WatermarkerSettings watermarkerSettings)](#EmailContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.email.FileFormatInfo-com.groupdocs.watermark.options.EmailLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | <br /> |

|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getAttachments()](#getAttachments--) | Αποκτά τη συλλογή όλων των συνημμένων του μηνύματος email. |
|
|  | [getEmbeddedObjects()](#getEmbeddedObjects--) | Αποκτά τη συλλογή όλων των ενσωματωμένων αντικειμένων του μηνύματος email. |
|
|  | [getFrom()](#getFrom--) | Αποκτά τη διεύθυνση αποστολέα του μηνύματος email. |
|
|  | [getTo()](#getTo--) | Αποκτά τη συλλογή των παραληπτών του μηνύματος email. |
|
|  | [getCc()](#getCc--) | Αποκτά τη συλλογή των παραληπτών CC (carbon copy) του μηνύματος email. |
|
|  | [getBcc()](#getBcc--) | Αποκτά τη συλλογή των παραληπτών BCC (blind carbon copy) του μηνύματος email. |
|
|  | [getSubject()](#getSubject--) | Αποκτά το θέμα του μηνύματος email. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | Ορίζει το θέμα του μηνύματος email. |
|
|  | [getBody()](#getBody--) | Αποκτά την αναπαράσταση απλού κειμένου του σώματος του μηνύματος. |
|
|  | [setBody(String value)](#setBody-java.lang.String-) | Ορίζει την αναπαράσταση απλού κειμένου του σώματος του μηνύματος. |
|
|  | [getHtmlBody()](#getHtmlBody--) | Αποκτά την αναπαράσταση html του σώματος του μηνύματος. |
|
|  | [setHtmlBody(String value)](#setHtmlBody-java.lang.String-) | Ορίζει την αναπαράσταση html του σώματος του μηνύματος. |
|
|  | [getBodyType()](#getBodyType--) | Αποκτά τον τύπο του σώματος του μηνύματος email. |
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
| Παράμετρος | Τύπος | Περιγραφή |
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


Αποκτά τη συλλογή όλων των συνημμένων του μηνύματος email.


**Returns:**
[EmailAttachmentCollection](../../com.groupdocs.watermark.contents/emailattachmentcollection) - The collection of all attachments of the email message.

### getEmbeddedObjects() {#getEmbeddedObjects--}
```
public final EmailEmbeddedObjectCollection getEmbeddedObjects()
```


Αποκτά τη συλλογή όλων των ενσωματωμένων αντικειμένων του μηνύματος email.


**Returns:**
[EmailEmbeddedObjectCollection](../../com.groupdocs.watermark.contents/emailembeddedobjectcollection) - The collection of all embedded objects of the email message.

### getFrom() {#getFrom--}
```
public final EmailAddress getFrom()
```


Αποκτά τη διεύθυνση αποστολέα του μηνύματος email.


**Returns:**
[EmailAddress](../../com.groupdocs.watermark.contents/emailaddress) - The from address of the email message.

### getTo() {#getTo--}
```
public final EmailAddressCollection getTo()
```


Αποκτά τη συλλογή των παραληπτών του μηνύματος email.


**Returns:**
[EmailAddressCollection](../../com.groupdocs.watermark.contents/emailaddresscollection) - The collection of recipients of the email message.

### getCc() {#getCc--}
```
public final EmailAddressCollection getCc()
```


Αποκτά τη συλλογή των παραληπτών CC (carbon copy) του μηνύματος email.


**Returns:**
[EmailAddressCollection](../../com.groupdocs.watermark.contents/emailaddresscollection) - The collection of CC (carbon copy) recipients of the email message.

### getBcc() {#getBcc--}
```
public final EmailAddressCollection getBcc()
```


Αποκτά τη συλλογή των παραληπτών BCC (blind carbon copy) του μηνύματος email.


**Returns:**
[EmailAddressCollection](../../com.groupdocs.watermark.contents/emailaddresscollection) - The collection of BCC (blind carbon copy) recipients of the email message.

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Αποκτά το θέμα του μηνύματος email.


**Returns:**
java.lang.String - Το θέμα του μηνύματος email.

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Ορίζει το θέμα του μηνύματος email.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.String | Το θέμα του μηνύματος email. |
|

### getBody() {#getBody--}
```
public final String getBody()
```


Αποκτά την αναπαράσταση απλού κειμένου του σώματος του μηνύματος.


**Returns:**
java.lang.String - Η αναπαράσταση απλού κειμένου του σώματος του μηνύματος.

### setBody(String value) {#setBody-java.lang.String-}
```
public final void setBody(String value)
```


Ορίζει την αναπαράσταση απλού κειμένου του σώματος του μηνύματος.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.String | Η απλή κειμενική αναπαράσταση του σώματος του μηνύματος. |
|

### getHtmlBody() {#getHtmlBody--}
```
public final String getHtmlBody()
```


Αποκτά την αναπαράσταση html του σώματος του μηνύματος.


**Returns:**
java.lang.String - Η αναπαράσταση html του σώματος του μηνύματος.

### setHtmlBody(String value) {#setHtmlBody-java.lang.String-}
```
public final void setHtmlBody(String value)
```


Ορίζει την αναπαράσταση html του σώματος του μηνύματος.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.String | Η αναπαράσταση html του σώματος του μηνύματος. |
|

### getBodyType() {#getBodyType--}
```
public final int getBodyType()
```


Αποκτά τον τύπο του σώματος του μηνύματος email.


**Returns:**
int - Ο τύπος του σώματος του email μηνύματος.

### performSave(String filePath) {#performSave-java.lang.String-}
```
public void performSave(String filePath)
```


<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String |  |

### performSave(String filePath, SaveOptions saveOptions) {#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(String filePath, SaveOptions saveOptions)
```


<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### performSave(OutputStream stream) {#performSave-java.io.OutputStream-}
```
public void performSave(OutputStream stream)
```


<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | java.io.OutputStream |  |

### performSave(OutputStream stream, SaveOptions saveOptions) {#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(OutputStream stream, SaveOptions saveOptions)
```


<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | java.io.OutputStream |  |
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) |  |

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public void generatePreview(PreviewOptions previewOptions)
```


<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) |  |

