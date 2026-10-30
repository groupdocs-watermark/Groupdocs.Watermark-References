---
title: "SpreadsheetBackgroundWatermarkOptions"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "スプレッドシートのワークシートに透かしを背景として追加する際のオプションを表します。"
type: docs
weight: 2190
url: /ja/net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/
---
## SpreadsheetBackgroundWatermarkOptions class

スプレッドシートのワークシートに透かしを背景として追加する際のオプションを表します。

```csharp
public sealed class SpreadsheetBackgroundWatermarkOptions : WatermarkOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [SpreadsheetBackgroundWatermarkOptions](spreadsheetbackgroundwatermarkoptions)() | 新しい [`SpreadsheetBackgroundWatermarkOptions`](../spreadsheetbackgroundwatermarkoptions) クラスのインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BackgroundHeight](../../groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/backgroundheight) { get; set; } | 背景画像の希望高さ（ピクセル単位）を取得または設定します。 |
| [BackgroundWidth](../../groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/backgroundwidth) { get; set; } | 背景画像の希望幅（ピクセル単位）を取得または設定します。 |
| [WorksheetIndex](../../groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/worksheetindex) { get; set; } | 透かしを追加するワークシートのインデックスを取得または設定します。 |

### 備考

**Learn more:**

* [Add watermarks to spreadsheet documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)

### 例

Excel ドキュメントのワークシートにテキスト透かしを背景として追加します。

```csharp
SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.xlsx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36));

    SpreadsheetBackgroundWatermarkOptions options = new SpreadsheetBackgroundWatermarkOptions();
    options.WorksheetIndex = -1; // default
    options.BackgroundWidth = 800;
    options.BackgroundHeight = 600;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### 関連項目

* class [WatermarkOptions](../../groupdocs.watermark.options/watermarkoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
