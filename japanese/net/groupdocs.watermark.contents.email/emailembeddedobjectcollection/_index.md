---
title: "EmailEmbeddedObjectCollection"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "メールメッセージ内の埋め込みオブジェクトのコレクションを表します。"
type: docs
weight: 380
url: /ja/net/groupdocs.watermark.contents.email/emailembeddedobjectcollection/
---
## EmailEmbeddedObjectCollection class

メールメッセージ内の埋め込みオブジェクトのコレクションを表します。

```csharp
public class EmailEmbeddedObjectCollection : RemoveOnlyListBase<EmailEmbeddedObject>
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
| [Add](../../groupdocs.watermark.contents.email/emailembeddedobjectcollection/add)(byte[], string) | 埋め込みリソースを [`EmailContent`](../emailcontent) に追加します。 |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() |  |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(EmailEmbeddedObject) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(EmailEmbeddedObject) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(EmailEmbeddedObject) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### 備考

このコレクションには [`EmailEmbeddedObject`](../emailembeddedobject) タイプの項目が含まれます。

### 関連項目

* class [RemoveOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/removeonlylistbase-1)
* class [EmailEmbeddedObject](../emailembeddedobject)
* namespace [GroupDocs.Watermark.Contents.Email](../../groupdocs.watermark.contents.email)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
