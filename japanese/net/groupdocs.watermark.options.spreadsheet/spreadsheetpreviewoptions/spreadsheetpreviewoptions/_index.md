---
title: "SpreadsheetPreviewOptions"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "SpreadsheetPreviewOptionsgroupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions クラスの新しいインスタンスを初期化し、出力ストリームを閉じます。"
type: docs
weight: 10
url: /ja/net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/spreadsheetpreviewoptions/
---
## SpreadsheetPreviewOptions(CreatePageStream) {#constructor}

[`SpreadsheetPreviewOptions`](../../spreadsheetpreviewoptions) クラスの新しいインスタンスを初期化し、出力ストリームを閉じます。

```csharp
public SpreadsheetPreviewOptions(CreatePageStream createPageStream)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 特定のページプレビュー用のストリームを作成します。 |

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [SpreadsheetPreviewOptions](../../spreadsheetpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../../)

---

## SpreadsheetPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

[`SpreadsheetPreviewOptions`](../../spreadsheetpreviewoptions) クラスの新しいインスタンスを初期化し、出力ストリームをクライアントに返してさらに使用できるようにします。

```csharp
public SpreadsheetPreviewOptions(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 特定のページプレビュー用のストリームを作成します。 |
| releasePageStream | ReleasePageStream | ページプレビューの生成が完了したことを通知し、出力ストリームを取得します。 |

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [SpreadsheetPreviewOptions](../../spreadsheetpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
