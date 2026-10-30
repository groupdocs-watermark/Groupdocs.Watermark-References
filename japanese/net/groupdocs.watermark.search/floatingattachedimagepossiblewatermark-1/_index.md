---
title: "FloatingAttachedImagePossibleWatermarkT"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "任意のサポートされている形式のコンテンツ内に添付された画像透かしを表します。"
type: docs
weight: 2440
url: /ja/net/groupdocs.watermark.search/floatingattachedimagepossiblewatermark-1/
---
## FloatingAttachedImagePossibleWatermark&lt;T&gt; class

任意のサポートされている形式のコンテンツ内に添付された画像透かしを表します。

```csharp
public class FloatingAttachedImagePossibleWatermark<T> : AttachedImagePossibleWatermark<T>
    where T : Attachment, ITwoDObject
```

| パラメーター | 説明 |
| --- | --- |
| T | 添付のタイプです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| virtual [FormattedTextFragments](../../groupdocs.watermark.search/possiblewatermark/formattedtextfragments) { get; } | この [`PossibleWatermark`](../possiblewatermark) の書式設定されたテキストフラグメントのコレクションを取得します。 |
| override [Height](../../groupdocs.watermark.search/floatingattachedimagepossiblewatermark-1/height) { get; } | この[`FloatingAttachedImagePossibleWatermark`](../floatingattachedimagepossiblewatermark-1)の高さを取得します。 |
| [ImageData](../../groupdocs.watermark.search/possiblewatermark/imagedata) { get; set; } | この [`PossibleWatermark`](../possiblewatermark) の画像を取得または設定します。 |
| virtual [PageNumber](../../groupdocs.watermark.search/possiblewatermark/pagenumber) { get; } | 透かしが配置されているページを取得します。 |
| override [Parent](../../groupdocs.watermark.search/floatingattachedimagepossiblewatermark-1/parent) { get; } | この[`FloatingAttachedImagePossibleWatermark`](../floatingattachedimagepossiblewatermark-1)の親を取得します。 |
| override [RotateAngle](../../groupdocs.watermark.search/attachedimagepossiblewatermark-1/rotateangle) { get; } | この[`AttachedImagePossibleWatermark`](../attachedimagepossiblewatermark-1)の回転角度（度）を取得します。 |
| virtual [Text](../../groupdocs.watermark.search/possiblewatermark/text) { get; set; } | この[`PossibleWatermark`](../possiblewatermark)のテキストを取得または設定します。 |
| override [UnitOfMeasurement](../../groupdocs.watermark.search/attachedimagepossiblewatermark-1/unitofmeasurement) { get; } | この[`AttachedImagePossibleWatermark`](../attachedimagepossiblewatermark-1)の測定単位を取得します。 |
| override [Width](../../groupdocs.watermark.search/floatingattachedimagepossiblewatermark-1/width) { get; } | この[`FloatingAttachedImagePossibleWatermark`](../floatingattachedimagepossiblewatermark-1)の幅を取得します。 |
| override [X](../../groupdocs.watermark.search/floatingattachedimagepossiblewatermark-1/x) { get; } | この[`FloatingAttachedImagePossibleWatermark`](../floatingattachedimagepossiblewatermark-1)のX座標を取得します。 |
| override [Y](../../groupdocs.watermark.search/floatingattachedimagepossiblewatermark-1/y) { get; } | この[`FloatingAttachedImagePossibleWatermark`](../floatingattachedimagepossiblewatermark-1)のY座標を取得します。 |

### 関連項目

* class [AttachedImagePossibleWatermark&lt;T&gt;](../attachedimagepossiblewatermark-1)
* class [Attachment](../../groupdocs.watermark.common/attachment)
* interface [ITwoDObject](../itwodobject)
* namespace [GroupDocs.Watermark.Search](../../groupdocs.watermark.search)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
