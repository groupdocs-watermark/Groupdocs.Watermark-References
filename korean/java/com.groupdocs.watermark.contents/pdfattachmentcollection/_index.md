---
title: "PdfAttachmentCollection"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "pdf 문서의 첨부 파일 컬렉션을 나타냅니다."
type: docs
weight: 59
url: /ko/java/com.groupdocs.watermark.contents/pdfattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class PdfAttachmentCollection extends RemoveOnlyListBase<PdfAttachment>
```

pdf 문서의 첨부 파일 컬렉션을 나타냅니다.

이 컬렉션은 `[PdfAttachment](../../com.groupdocs.watermark.contents/pdfattachment)` 유형의 항목을 포함합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [add(byte[] fileContent, String name, String description)](#add-byte---java.lang.String-java.lang.String-) | `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`에 첨부 파일을 추가합니다. |
|
|  | [removeFromDocument(PdfAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.PdfAttachment-) | <br /> |

|
### add(byte[] fileContent, String name, String description) {#add-byte---java.lang.String-java.lang.String-}
```
public final void add(byte[] fileContent, String name, String description)
```


`[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`에 첨부 파일을 추가합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | fileContent | byte[] | 첨부될 파일의 내용입니다. |
|
|  | name | java.lang.String | 파일의 이름입니다. |
|
|  | description | java.lang.String | 파일에 대한 설명입니다. |
|

### removeFromDocument(PdfAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.PdfAttachment-}
```
public void removeFromDocument(PdfAttachment item)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| item | [PdfAttachment](../../com.groupdocs.watermark.contents/pdfattachment) |  |

