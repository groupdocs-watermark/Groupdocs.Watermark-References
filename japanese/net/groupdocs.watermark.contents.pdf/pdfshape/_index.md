---
title: "PdfShape"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "XObjects のアーティファクトとアノテーションの基底クラスを提供します。"
type: docs
weight: 770
url: /ja/net/groupdocs.watermark.contents.pdf/pdfshape/
---
## PdfShape class

XObjects、Artifacts、Annotations の基底クラスを提供します。

```csharp
public abstract class PdfShape : ShapeSearchAdapter, IRotatableTwoDObject
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [FormattedTextFragments](../../groupdocs.watermark.contents.pdf/pdfshape/formattedtextfragments) { get; } | この [`PdfShape`](../pdfshape) の書式設定されたテキストフラグメントのコレクションを取得します。 |
| abstract [Height](../../groupdocs.watermark.contents.pdf/pdfshape/height) { get; } | オブジェクトの高さを取得します。 |
| [Image](../../groupdocs.watermark.contents.pdf/pdfshape/image) { get; set; } | この [`PdfShape`](../pdfshape) の画像を取得または設定します。 |
| abstract [RotateAngle](../../groupdocs.watermark.contents.pdf/pdfshape/rotateangle) { get; } | オブジェクトの回転角度を度単位で取得します。 |
| virtual [Text](../../groupdocs.watermark.contents.pdf/pdfshape/text) { get; set; } | この [`PdfShape`](../pdfshape) のテキストを取得または設定します。 |
| abstract [Width](../../groupdocs.watermark.contents.pdf/pdfshape/width) { get; } | オブジェクトの幅を取得します。 |
| abstract [X](../../groupdocs.watermark.contents.pdf/pdfshape/x) { get; } | オブジェクトの x 座標を取得します。 |
| abstract [Y](../../groupdocs.watermark.contents.pdf/pdfshape/y) { get; } | オブジェクトの y 座標を取得します。 |

### 関連項目

* class [ShapeSearchAdapter](../../groupdocs.watermark.search/shapesearchadapter)
* interface [IRotatableTwoDObject](../../groupdocs.watermark.search/irotatabletwodobject)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
