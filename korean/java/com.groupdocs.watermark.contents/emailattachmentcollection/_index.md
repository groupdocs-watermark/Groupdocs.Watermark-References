---
title: "EmailAttachmentCollection"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "이메일 메시지의 첨부 파일 컬렉션을 나타냅니다."
type: docs
weight: 32
url: /ko/java/com.groupdocs.watermark.contents/emailattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class EmailAttachmentCollection extends RemoveOnlyListBase<EmailAttachment>
```

이메일 메시지의 첨부 파일 컬렉션을 나타냅니다.

이 컬렉션은 `[EmailAttachment](../../com.groupdocs.watermark.contents/emailattachment)` 유형의 항목을 포함합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [add(byte[] fileContent, String name)](#add-byte---java.lang.String-) | `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`에 첨부 파일을 추가합니다. |
|
|  | [removeFromDocument(EmailAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.EmailAttachment-) | <br /> |

|
### add(byte[] fileContent, String name) {#add-byte---java.lang.String-}
```
public final void add(byte[] fileContent, String name)
```


`[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`에 첨부 파일을 추가합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | fileContent | byte[] | 첨부될 파일의 내용입니다. |
|
|  | name | java.lang.String | 파일의 이름입니다. |
|

### removeFromDocument(EmailAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.EmailAttachment-}
```
public void removeFromDocument(EmailAttachment item)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| item | [EmailAttachment](../../com.groupdocs.watermark.contents/emailattachment) |  |

