---
title: "ImageInpaintingPossibleWatermark"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "周囲のピクセルを使用して塗りつぶすべき、手動で指定された画像領域を表します。"
type: docs
weight: 2900
url: /ja/net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/
---
## ImageInpaintingPossibleWatermark class

手動で指定された画像領域で、周囲のピクセルを使用してインペイント（塗りつぶし）すべきものを表します。

```csharp
public class ImageInpaintingPossibleWatermark : PossibleWatermark
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [ImageInpaintingPossibleWatermark](imageinpaintingpossiblewatermark)() | 新しい [`ImageInpaintingPossibleWatermark`](../imageinpaintingpossiblewatermark) クラスのインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| virtual [FormattedTextFragments](../../groupdocs.watermark.search/possiblewatermark/formattedtextfragments) { get; } | この[`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) の書式設定されたテキストフラグメントのコレクションを取得します。 |
| virtual [Height](../../groupdocs.watermark.search/possiblewatermark/height) { get; } | この[`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) の高さを取得します。 |
| [ImageData](../../groupdocs.watermark.search/possiblewatermark/imagedata) { get; set; } | この[`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) の画像を取得または設定します。 |
| [Method](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/method) { get; set; } | インペイントアルゴリズムを取得または設定します。デフォルトは PatchBased です。 |
| virtual [PageNumber](../../groupdocs.watermark.search/possiblewatermark/pagenumber) { get; } | 透かしが配置されているページを取得します。 |
| override [Parent](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/parent) { get; } | この [`ImageInpaintingPossibleWatermark`](../imageinpaintingpossiblewatermark) の親を取得します。領域が手動で指定されているため、常に `null` を返します。 |
| [PatchSize](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/patchsize) { get; set; } | アルゴリズムで使用されるパッチサイズを取得または設定します（奇数、5〜11）。デフォルトは 7 です。Telea の場合、これは HalfPatchSize として使用されます。 |
| [Polygons](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/polygons) { get; set; } | インペイント対象の多角形領域を画像ピクセル単位で取得または設定します。各多角形は頂点の配列です。[`Rectangles`](./rectangles) または [`Polygons`](./polygons) のいずれかを指定する必要があり、両方は指定できません。 |
| [Rectangles](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/rectangles) { get; set; } | インペイント対象の矩形領域を画像ピクセル単位で取得または設定します。[`Rectangles`](./rectangles) または [`Polygons`](./polygons) のいずれかを指定する必要があり、両方は指定できません。 |
| virtual [RotateAngle](../../groupdocs.watermark.search/possiblewatermark/rotateangle) { get; } | この[`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) の回転角度を取得します（度単位）。 |
| virtual [Text](../../groupdocs.watermark.search/possiblewatermark/text) { get; set; } | この [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) のテキストを取得または設定します。 |
| virtual [UnitOfMeasurement](../../groupdocs.watermark.search/possiblewatermark/unitofmeasurement) { get; } | この[`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) の測定単位を取得します。 |
| virtual [Width](../../groupdocs.watermark.search/possiblewatermark/width) { get; } | この[`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) の幅を取得します。 |
| virtual [X](../../groupdocs.watermark.search/possiblewatermark/x) { get; } | この[`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) のX座標を取得します。 |
| virtual [Y](../../groupdocs.watermark.search/possiblewatermark/y) { get; } | この[`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) のY座標を取得します。 |

### 関連項目

* class [PossibleWatermark](../../groupdocs.watermark.search/possiblewatermark)
* namespace [GroupDocs.Watermark.Search.Watermarks](../../groupdocs.watermark.search.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
