---
title: "ShapePossibleWatermarkT"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "任意のサポートされている形式のコンテンツ内のシェイプ透かしを表します。"
type: docs
weight: 2770
url: /ja/net/groupdocs.watermark.search/shapepossiblewatermark-1/
---
## ShapePossibleWatermark&lt;T&gt; class

任意のサポートされている形式のコンテンツ内のシェイプ透かしを表します。

```csharp
public abstract class ShapePossibleWatermark<T> : TwoDObjectPossibleWatermark
    where T : ShapeSearchAdapter, ITwoDObject
```

| パラメーター | 説明 |
| --- | --- |
| T | 形状のタイプです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [FormattedTextFragments](../../groupdocs.watermark.search/shapepossiblewatermark-1/formattedtextfragments) { get; } | 形状の書式設定されたテキストフラグメントのコレクションを取得します。 |
| override [Height](../../groupdocs.watermark.search/twodobjectpossiblewatermark/height) { get; } | 2Dオブジェクトの高さを取得します。 |
| [ImageData](../../groupdocs.watermark.search/possiblewatermark/imagedata) { get; set; } | この [`PossibleWatermark`](../possiblewatermark) の画像を取得または設定します。 |
| override [PageNumber](../../groupdocs.watermark.search/shapepossiblewatermark-1/pagenumber) { get; } | 透かしが配置されているページを取得します。 |
| abstract [Parent](../../groupdocs.watermark.search/possiblewatermark/parent) { get; } | この[`PossibleWatermark`](../possiblewatermark)の親を取得します。 |
| override [RotateAngle](../../groupdocs.watermark.search/shapepossiblewatermark-1/rotateangle) { get; } | 形状の回転角度を取得します（度単位）。 |
| override [Text](../../groupdocs.watermark.search/shapepossiblewatermark-1/text) { get; set; } | 形状のテキストを取得または設定します。 |
| override [UnitOfMeasurement](../../groupdocs.watermark.search/twodobjectpossiblewatermark/unitofmeasurement) { get; } | 2Dオブジェクトの測定単位を取得します。 |
| override [Width](../../groupdocs.watermark.search/twodobjectpossiblewatermark/width) { get; } | 2Dオブジェクトの幅を取得します。 |
| override [X](../../groupdocs.watermark.search/twodobjectpossiblewatermark/x) { get; } | 2DオブジェクトのX座標を取得します。 |
| override [Y](../../groupdocs.watermark.search/twodobjectpossiblewatermark/y) { get; } | 2DオブジェクトのY座標を取得します。 |

### 関連項目

* class [TwoDObjectPossibleWatermark](../twodobjectpossiblewatermark)
* class [ShapeSearchAdapter](../shapesearchadapter)
* interface [ITwoDObject](../itwodobject)
* namespace [GroupDocs.Watermark.Search](../../groupdocs.watermark.search)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
