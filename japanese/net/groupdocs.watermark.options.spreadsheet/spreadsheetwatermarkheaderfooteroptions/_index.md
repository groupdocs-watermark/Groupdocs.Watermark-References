---
title: "SpreadsheetWatermarkHeaderFooterOptions"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "Spreadsheet のヘッダー/フッターに透かしを追加する際のオプションを表します。"
type: docs
weight: 2270
url: /ja/net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/
---
## SpreadsheetWatermarkHeaderFooterOptions class

Spreadsheet のヘッダー/フッターに透かしを追加する際のオプションを表します。

```csharp
public sealed class SpreadsheetWatermarkHeaderFooterOptions : WatermarkOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [SpreadsheetWatermarkHeaderFooterOptions](spreadsheetwatermarkheaderfooteroptions)() | [`SpreadsheetWatermarkHeaderFooterOptions`](../spreadsheetwatermarkheaderfooteroptions) クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [WorksheetIndex](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/worksheetindex) { get; set; } | 透かしを追加するワークシートのインデックスを取得または設定します。 |

### 備考

**Learn more:**

* [Add watermarks to spreadsheet documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)

### 例

Excel ワークシートのヘッダーにテキスト透かしを追加します。

```csharp
SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.xls", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));

    SpreadsheetWatermarkHeaderFooterOptions options = new SpreadsheetWatermarkHeaderFooterOptions();
    options.WorksheetIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### 関連項目

* class [WatermarkOptions](../../groupdocs.watermark.options/watermarkoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
