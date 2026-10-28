---
title: "EmailContent"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "이메일 메시지를 나타냅니다."
type: docs
weight: 34
url: /ko/java/com.groupdocs.watermark.contents/emailcontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)
```
public final class EmailContent extends Content
```

이메일 메시지를 나타냅니다.

**Learn more:**

* [Add watermarks to email attachments](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+email+attachments)
* [Email attachments](../https://docs.groupdocs.com/display/watermarkjava/Email+attachments)
* [Email messages](../https://docs.groupdocs.com/display/watermarkjava/Email+messages)

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [EmailContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileFormatInfo fileFormatInfo, EmailLoadOptions emailLoadOptions, WatermarkerSettings watermarkerSettings)](#EmailContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.email.FileFormatInfo-com.groupdocs.watermark.options.EmailLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | <br /> |

|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getAttachments()](#getAttachments--) | 이메일 메시지의 모든 첨부 파일 컬렉션을 가져옵니다. |
|
|  | [getEmbeddedObjects()](#getEmbeddedObjects--) | 이메일 메시지의 모든 임베디드 객체 컬렉션을 가져옵니다. |
|
|  | [getFrom()](#getFrom--) | 이메일 메시지의 발신자 주소를 가져옵니다. |
|
|  | [getTo()](#getTo--) | 이메일 메시지의 수신자 컬렉션을 가져옵니다. |
|
|  | [getCc()](#getCc--) | 이메일 메시지의 CC(참조) 수신자 컬렉션을 가져옵니다. |
|
|  | [getBcc()](#getBcc--) | 이메일 메시지의 BCC(숨은 참조) 수신자 컬렉션을 가져옵니다. |
|
|  | [getSubject()](#getSubject--) | 이메일 메시지의 제목을 가져옵니다. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | 이메일 메시지의 제목을 설정합니다. |
|
|  | [getBody()](#getBody--) | 메시지 본문의 일반 텍스트 표현을 가져옵니다. |
|
|  | [setBody(String value)](#setBody-java.lang.String-) | 메시지 본문의 일반 텍스트 표현을 설정합니다. |
|
|  | [getHtmlBody()](#getHtmlBody--) | 메시지 본문의 HTML 표현을 가져옵니다. |
|
|  | [setHtmlBody(String value)](#setHtmlBody-java.lang.String-) | 메시지 본문의 HTML 표현을 설정합니다. |
|
|  | [getBodyType()](#getBodyType--) | 이메일 메시지 본문의 유형을 가져옵니다. |
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
| 매개변수 | 유형 | 설명 |
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


이메일 메시지의 모든 첨부 파일 컬렉션을 가져옵니다.


**Returns:**
[EmailAttachmentCollection](../../com.groupdocs.watermark.contents/emailattachmentcollection) - The collection of all attachments of the email message.

### getEmbeddedObjects() {#getEmbeddedObjects--}
```
public final EmailEmbeddedObjectCollection getEmbeddedObjects()
```


이메일 메시지의 모든 임베디드 객체 컬렉션을 가져옵니다.


**Returns:**
[EmailEmbeddedObjectCollection](../../com.groupdocs.watermark.contents/emailembeddedobjectcollection) - The collection of all embedded objects of the email message.

### getFrom() {#getFrom--}
```
public final EmailAddress getFrom()
```


이메일 메시지의 발신자 주소를 가져옵니다.


**Returns:**
[EmailAddress](../../com.groupdocs.watermark.contents/emailaddress) - The from address of the email message.

### getTo() {#getTo--}
```
public final EmailAddressCollection getTo()
```


이메일 메시지의 수신자 컬렉션을 가져옵니다.


**Returns:**
[EmailAddressCollection](../../com.groupdocs.watermark.contents/emailaddresscollection) - The collection of recipients of the email message.

### getCc() {#getCc--}
```
public final EmailAddressCollection getCc()
```


이메일 메시지의 CC(참조) 수신자 컬렉션을 가져옵니다.


**Returns:**
[EmailAddressCollection](../../com.groupdocs.watermark.contents/emailaddresscollection) - The collection of CC (carbon copy) recipients of the email message.

### getBcc() {#getBcc--}
```
public final EmailAddressCollection getBcc()
```


이메일 메시지의 BCC(숨은 참조) 수신자 컬렉션을 가져옵니다.


**Returns:**
[EmailAddressCollection](../../com.groupdocs.watermark.contents/emailaddresscollection) - The collection of BCC (blind carbon copy) recipients of the email message.

### getSubject() {#getSubject--}
```
public final String getSubject()
```


이메일 메시지의 제목을 가져옵니다.


**Returns:**
java.lang.String - 이메일 메시지의 제목.

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


이메일 메시지의 제목을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 이메일 메시지의 제목. |
|

### getBody() {#getBody--}
```
public final String getBody()
```


메시지 본문의 일반 텍스트 표현을 가져옵니다.


**Returns:**
java.lang.String - 메시지 본문의 일반 텍스트 표현.

### setBody(String value) {#setBody-java.lang.String-}
```
public final void setBody(String value)
```


메시지 본문의 일반 텍스트 표현을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 메시지 본문의 일반 텍스트 표현. |
|

### getHtmlBody() {#getHtmlBody--}
```
public final String getHtmlBody()
```


메시지 본문의 HTML 표현을 가져옵니다.


**Returns:**
java.lang.String - 메시지 본문의 HTML 표현.

### setHtmlBody(String value) {#setHtmlBody-java.lang.String-}
```
public final void setHtmlBody(String value)
```


메시지 본문의 HTML 표현을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 메시지 본문의 HTML 표현. |
|

### getBodyType() {#getBodyType--}
```
public final int getBodyType()
```


이메일 메시지 본문의 유형을 가져옵니다.


**Returns:**
int - 이메일 메시지 본문의 유형.

### performSave(String filePath) {#performSave-java.lang.String-}
```
public void performSave(String filePath)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String |  |

### performSave(String filePath, SaveOptions saveOptions) {#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(String filePath, SaveOptions saveOptions)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### performSave(OutputStream stream) {#performSave-java.io.OutputStream-}
```
public void performSave(OutputStream stream)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.OutputStream |  |

### performSave(OutputStream stream, SaveOptions saveOptions) {#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(OutputStream stream, SaveOptions saveOptions)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.OutputStream |  |
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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) |  |

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public void generatePreview(PreviewOptions previewOptions)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) |  |

