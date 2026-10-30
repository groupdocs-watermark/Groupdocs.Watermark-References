---
title: "EmailAttachmentCollection"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "メールメッセージ内の添付ファイルのコレクションを表します。"
type: docs
weight: 340
url: /ja/net/groupdocs.watermark.contents.email/emailattachmentcollection/
---
## EmailAttachmentCollection class

メールメッセージ内の添付ファイルのコレクションを表します。

```csharp
public class EmailAttachmentCollection : RemoveOnlyListBase<EmailAttachment>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | コレクションに含まれる要素数を取得します。 |
| override [IsReadOnly](../../groupdocs.watermark.common/removeonlylistbase-1/isreadonly) { get; } | コレクションが読み取り専用かどうかを示す値を取得します。 |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | コレクション内の指定インデックスにある要素を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.email/emailattachmentcollection/add)(byte[], string) | `[`EmailContent`](../emailcontent) に添付ファイルを追加します。` |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() |  |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(EmailAttachment) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(EmailAttachment) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(EmailAttachment) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### 備考

このコレクションには [`EmailAttachment`](../emailattachment) タイプの項目が含まれます。

### 関連項目

* class [RemoveOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/removeonlylistbase-1)
* class [EmailAttachment](../emailattachment)
* namespace [GroupDocs.Watermark.Contents.Email](../../groupdocs.watermark.contents.email)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
