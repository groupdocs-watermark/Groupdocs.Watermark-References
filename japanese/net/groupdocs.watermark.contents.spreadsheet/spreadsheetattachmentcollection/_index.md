---
title: "SpreadsheetAttachmentCollection"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "Excel ドキュメント内の添付ファイルコレクションを表します。"
type: docs
weight: 1110
url: /ja/net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/
---
## SpreadsheetAttachmentCollection class

Excel ドキュメント内の添付ファイルコレクションを表します。

```csharp
public class SpreadsheetAttachmentCollection : RemoveOnlyListBase<SpreadsheetAttachment>
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
| [AddAttachment](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/addattachment)(byte[], string, byte[], double, double, double, double) | この[`SpreadsheetWorksheet`](../spreadsheetworksheet)に添付ファイルを追加します。 |
| [AddLink](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/addlink)(string, byte[], double, double, double, double) | リンクによって添付ファイルを追加します（ドキュメントには添付ファイルの内容が含まれません）。 |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() |  |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(SpreadsheetAttachment) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(SpreadsheetAttachment) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(SpreadsheetAttachment) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### 備考

このコレクションは[`SpreadsheetAttachment`](../spreadsheetattachment)型の項目を含みます。

### 関連項目

* class [RemoveOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/removeonlylistbase-1)
* class [SpreadsheetAttachment](../spreadsheetattachment)
* namespace [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
