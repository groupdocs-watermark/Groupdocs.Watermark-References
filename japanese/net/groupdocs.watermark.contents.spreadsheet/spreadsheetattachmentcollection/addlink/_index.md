---
title: "AddLink"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "リンクで添付ファイルを追加しますが、ドキュメントには添付ファイルの内容が含まれません。"
type: docs
weight: 20
url: /ja/net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/addlink/
---
## SpreadsheetAttachmentCollection.AddLink method

リンクによって添付ファイルを追加します（ドキュメントには添付ファイルの内容が含まれません）。

```csharp
public void AddLink(string sourceFullName, byte[] previewImageContent, double x, double y, 
    double width, double height)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| sourceFullName | String | リンクされたファイルのパス。 |
| previewImageContent | Byte[] | 添付ファイルのプレビュー画像をバイト配列として取得します。 |
| x | Double | 添付フレームのX座標（ポイント単位）。 |
| y | Double | 添付フレームのY座標（ポイント単位）。 |
| 幅 | Double | 添付フレームの幅（ポイント単位）。 |
| 高さ | Double | 添付フレームの高さ（ポイント単位）。 |

### 関連項目

* class [SpreadsheetAttachmentCollection](../../spreadsheetattachmentcollection)
* namespace [GroupDocs.Watermark.Contents.Spreadsheet](../../../groupdocs.watermark.contents.spreadsheet)
* assembly [GroupDocs.Watermark](../../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
