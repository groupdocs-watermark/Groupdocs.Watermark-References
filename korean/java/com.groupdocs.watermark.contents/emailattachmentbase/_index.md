---
title: "EmailAttachmentBase"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "이메일 첨부 파일을 위한 기본 클래스를 제공합니다."
type: docs
weight: 31
url: /ko/java/com.groupdocs.watermark.contents/emailattachmentbase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)
```
public abstract class EmailAttachmentBase extends Attachment
```

이메일 첨부 파일을 위한 기본 클래스를 제공합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getContentId()](#getContentId--) | 이 `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`의 콘텐츠 ID를 가져옵니다. |
|
|  | [getMediaType()](#getMediaType--) | 이 `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`의 미디어 유형을 가져옵니다. |
|
|  | [getContent()](#getContent--) | 첨부된 파일 내용을 가져옵니다. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | 첨부된 파일 내용을 설정합니다. |
|
| [getContentStream()](#getContentStream--) |  |
| [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) |  |
### getContentId() {#getContentId--}
```
public final String getContentId()
```


이 `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`의 콘텐츠 ID를 가져옵니다.


**Returns:**
java.lang.String - 이 `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`의 콘텐츠 ID.

### getMediaType() {#getMediaType--}
```
public final String getMediaType()
```


이 `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`의 미디어 유형을 가져옵니다.


**Returns:**
java.lang.String - 이 `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`의 미디어 유형.

### getContent() {#getContent--}
```
public byte[] getContent()
```


첨부된 파일 내용을 가져옵니다.


**Returns:**
byte[] - 첨부된 파일 내용.

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


첨부된 파일 내용을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | byte[] | 첨부된 파일 내용. |
|

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


첨부된 파일에서 스트림을 가져옵니다.


**Returns:**
com.aspose.ms.System.IO.Stream
### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


스트림을 사용하여 첨부된 파일을 업데이트합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 스트림 | com.aspose.ms.System.IO.Stream |  |

