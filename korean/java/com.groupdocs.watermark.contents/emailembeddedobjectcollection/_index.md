---
title: "EmailEmbeddedObjectCollection"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "이메일 메시지의 삽입된 객체 컬렉션을 나타냅니다."
type: docs
weight: 36
url: /ko/java/com.groupdocs.watermark.contents/emailembeddedobjectcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class EmailEmbeddedObjectCollection extends RemoveOnlyListBase<EmailEmbeddedObject>
```

이메일 메시지의 삽입된 객체 컬렉션을 나타냅니다.

이 컬렉션은 `[EmailEmbeddedObject](../../com.groupdocs.watermark.contents/emailembeddedobject)` 유형의 항목을 포함합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [add(byte[] fileContent, String name)](#add-byte---java.lang.String-) | `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`에 임베디드 리소스를 추가합니다. |
|
|  | [removeFromDocument(EmailEmbeddedObject item)](#removeFromDocument-com.groupdocs.watermark.contents.EmailEmbeddedObject-) | <br /> |

|
### add(byte[] fileContent, String name) {#add-byte---java.lang.String-}
```
public final void add(byte[] fileContent, String name)
```


`[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`에 임베디드 리소스를 추가합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | fileContent | byte[] | 추가될 파일의 내용입니다. |
|
|  | name | java.lang.String | 파일의 이름입니다. |
|

### removeFromDocument(EmailEmbeddedObject item) {#removeFromDocument-com.groupdocs.watermark.contents.EmailEmbeddedObject-}
```
public void removeFromDocument(EmailEmbeddedObject item)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| item | [EmailEmbeddedObject](../../com.groupdocs.watermark.contents/emailembeddedobject) |  |

