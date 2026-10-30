---
title: "DiagramShapeWatermarkOptions"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "Visio ドキュメントにシェイプ透かしを追加する際の透かし追加オプションを表します。"
type: docs
weight: 1750
url: /ja/net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/
---
## DiagramShapeWatermarkOptions class

Visio ドキュメントにシェイプ透かしを追加する際の透かし追加オプションを表します。

```csharp
public sealed class DiagramShapeWatermarkOptions : DiagramWatermarkOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [DiagramShapeWatermarkOptions](diagramshapewatermarkoptions)() | `[`DiagramShapeWatermarkOptions`](../diagramshapewatermarkoptions)` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [IsLocked](../../groupdocs.watermark.options.diagram/diagramwatermarkoptions/islocked) { get; set; } | Visio のシェイプ編集が禁止されているかどうかを示す値を取得または設定します。 |
| [PlacementType](../../groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/placementtype) { get; set; } | 透かしを追加するページを指定する値を取得または設定します。 |

### 備考

**Learn more:**

* [Add watermarks to diagram documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents)

### 例

Visio ドキュメントのすべてのページに保護された透かしを追加します。

```csharp
DiagramLoadOptions loadOptions = new DiagramLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.vsdx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));

    DiagramShapeWatermarkOptions options = new DiagramShapeWatermarkOptions();
    options.IsLocked = true;
    options.PlacementType = DiagramWatermarkPlacementType.AllPages; // default

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### 関連項目

* class [DiagramWatermarkOptions](../diagramwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Diagram](../../groupdocs.watermark.options.diagram)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
