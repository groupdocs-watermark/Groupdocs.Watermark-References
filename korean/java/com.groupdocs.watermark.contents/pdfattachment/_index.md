---
title: "PdfAttachment"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "pdf 콘텐츠에 첨부된 파일을 나타냅니다."
type: docs
weight: 58
url: /ko/java/com.groupdocs.watermark.contents/pdfattachment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)
```
public class PdfAttachment extends Attachment
```

pdf 콘텐츠에 첨부된 파일을 나타냅니다.

**Learn more:**

* [Attachments in PDF document](../https://docs.groupdocs.com/display/watermarkjava/Attachments+in+PDF+document)

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getName()](#getName--) | 첨부된 파일의 이름을 가져옵니다. |
|
|  | [setName(String value)](#setName-java.lang.String-) | 첨부된 파일의 이름을 설정합니다. |
|
|  | [getDescription()](#getDescription--) | 첨부된 파일의 설명을 가져옵니다. |
|
|  | [setDescription(String value)](#setDescription-java.lang.String-) | 첨부된 파일의 설명을 설정합니다. |
|
|  | [getContent()](#getContent--) | 첨부된 파일 내용을 가져옵니다. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | 첨부된 파일 내용을 설정합니다. |
|
| [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) |  |
| [getContentStream()](#getContentStream--) |  |
### getName() {#getName--}
```
public final String getName()
```


첨부된 파일의 이름을 가져옵니다.


**Returns:**
java.lang.String - 첨부된 파일의 이름.

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


첨부된 파일의 이름을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 첨부된 파일의 이름. |
|

### getDescription() {#getDescription--}
```
public final String getDescription()
```


첨부된 파일의 설명을 가져옵니다.


**Returns:**
java.lang.String - 첨부된 파일의 설명.

### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```


첨부된 파일의 설명을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 첨부된 파일의 설명. |
|

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

### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


스트림을 사용하여 첨부된 파일을 업데이트합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 스트림 | com.aspose.ms.System.IO.Stream |  |

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


첨부된 파일에서 스트림을 가져옵니다.


**Returns:**
com.aspose.ms.System.IO.Stream
