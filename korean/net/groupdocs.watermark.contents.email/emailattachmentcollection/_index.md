---
title: EmailAttachmentCollection
second_title: .NET API 참조용 GroupDocs.Watermark
description: 전자 메일 메시지의 첨부 파일 모음을 나타냅니다.
type: docs
weight: 310
url: /ko/net/groupdocs.watermark.contents.email/emailattachmentcollection/
---
## EmailAttachmentCollection class

전자 메일 메시지의 첨부 파일 모음을 나타냅니다.

```csharp
public class EmailAttachmentCollection : RemoveOnlyListBase<EmailAttachment>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | 컬렉션에 포함된 요소의 수를 가져옵니다. |
| override [IsReadOnly](../../groupdocs.watermark.common/removeonlylistbase-1/isreadonly) { get; } | 컬렉션이 읽기 전용인지 여부를 나타내는 값을 가져옵니다. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | 컬렉션의 지정된 인덱스에 있는 요소를 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.email/emailattachmentcollection/add)(byte[], string) | 에 첨부 파일을 추가합니다.[`EmailContent`](../emailcontent) . |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() |  |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(EmailAttachment) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(EmailAttachment) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(EmailAttachment) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### 비고

이 컬렉션에는 다음 항목이 포함되어 있습니다.[`EmailAttachment`](../emailattachment) 유형.

### 또한보십시오

* class [RemoveOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/removeonlylistbase-1)
* class [EmailAttachment](../emailattachment)
* 네임스페이스 [GroupDocs.Watermark.Contents.Email](../../groupdocs.watermark.contents.email)
* 집회 [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
