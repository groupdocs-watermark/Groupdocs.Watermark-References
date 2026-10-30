---
title: "DiagramPageWatermarkOptions"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "Visio ドキュメントの特定ページにシェイプ透かしを追加する際の透かし追加オプションを表します。"
type: docs
weight: 1720
url: /ja/net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/
---
## DiagramPageWatermarkOptions class

Visio ドキュメントの特定ページにシェイプ透かしを追加する際の透かし追加オプションを表します。

```csharp
public sealed class DiagramPageWatermarkOptions : DiagramWatermarkOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [DiagramPageWatermarkOptions](diagrampagewatermarkoptions)() | `[`DiagramPageWatermarkOptions`](../diagrampagewatermarkoptions)` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [IsLocked](../../groupdocs.watermark.options.diagram/diagramwatermarkoptions/islocked) { get; set; } | Visio のシェイプ編集が禁止されているかどうかを示す値を取得または設定します。 |
| [PageIndex](../../groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/pageindex) { get; set; } | 透かしを追加するページインデックスを取得または設定します。 |

### 備考

**Learn more:**

* [Add watermarks to diagram documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents)

### 例

Visio ドキュメントの最初のページに保護された透かしを追加します。

```csharp
DiagramLoadOptions loadOptions = new DiagramLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.vsdx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));

    DiagramPageWatermarkOptions options = new DiagramPageWatermarkOptions();
    options.IsLocked = true;
    options.PageIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### 関連項目

* class [DiagramWatermarkOptions](../diagramwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Diagram](../../groupdocs.watermark.options.diagram)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
