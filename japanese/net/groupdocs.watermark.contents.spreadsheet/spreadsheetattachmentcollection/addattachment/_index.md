---
title: "AddAttachment"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "SpreadsheetWorksheetgroupdocs.watermark.contents.spreadsheet/spreadsheetworksheet に添付ファイルを追加します。"
type: docs
weight: 10
url: /ja/net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/addattachment/
---
## SpreadsheetAttachmentCollection.AddAttachment method

`[`SpreadsheetWorksheet`](../../spreadsheetworksheet)` に添付ファイルを追加します。

```csharp
public void AddAttachment(byte[] fileContent, string sourceFullName, byte[] previewImageContent, 
    double x, double y, double width, double height)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| fileContent | Byte[] | 添付するファイルの内容。 |
| sourceFullName | String | 添付ファイルのフルネーム（拡張子はファイルを開く適切なアプリケーションを判別するために使用されます）。 |
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
