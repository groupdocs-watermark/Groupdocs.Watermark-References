---
title: SpreadsheetWatermarkShapeOptions
second_title: GroupDocs.Watermark for .NET API リファレンス
description: 図形の透かしをスプレッドシート ワークシートに追加するときのオプションを表します
type: docs
weight: 2230
url: /ja/net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/
---
## SpreadsheetWatermarkShapeOptions class

図形の透かしをスプレッドシート ワークシートに追加するときのオプションを表します。

```csharp
public sealed class SpreadsheetWatermarkShapeOptions : SpreadsheetWatermarkBaseOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [SpreadsheetWatermarkShapeOptions](spreadsheetwatermarkshapeoptions)() | の新しいインスタンスを初期化します[`SpreadsheetWatermarkShapeOptions`](../spreadsheetwatermarkshapeoptions)class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/alternativetext) { get; set; } | 形状に関連付けられる説明 (代替) テキストを取得または設定します。 |
| [Effects](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/effects) { get; set; } | の値を取得または設定します[`SpreadsheetImageEffects`](../spreadsheetimageeffects)or [`SpreadsheetTextEffects`](../spreadsheettexteffects)透かしに適用する必要がある効果用. |
| [IsLocked](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/islocked) { get; set; } | Excel での形状の編集が禁止されているかどうかを示す値を取得または設定します。 |
| [Name](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/name) { get; set; } | シェイプの名前を取得または設定します。 |
| [WorksheetIndex](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/worksheetindex) { get; set; } | 透かしを追加するワークシートのインデックスを取得または設定します。 |

### 備考

**もっと詳しく知る：**

* [スプレッドシート ドキュメントに透かしを追加する](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)

### 例

Excel ドキュメントの特定のワークシートに透かしを追加します。

```csharp
SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.xls", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36, FontStyle.Bold | FontStyle.Italic));
    watermark.HorizontalAlignment = HorizontalAlignment.Center;
    watermark.VerticalAlignment = VerticalAlignment.Center;

    SpreadsheetWatermarkShapeOptions options = new SpreadsheetWatermarkShapeOptions();
    options.WorksheetIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### 関連項目

* class [SpreadsheetWatermarkBaseOptions](../spreadsheetwatermarkbaseoptions)
* 名前空間 [GroupDocs.Watermark.Options.Spreadsheet](../../groupdocs.watermark.options.spreadsheet)
* 組み立て [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->