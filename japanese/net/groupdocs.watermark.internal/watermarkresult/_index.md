---
title: "WatermarkResult"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "透かし処理の結果を表し、文書サイズ、処理時間、適用された透かしの数などの詳細を含みます。"
type: docs
weight: 1670
url: /ja/net/groupdocs.watermark.internal/watermarkresult/
---
## WatermarkResult class

ドキュメントサイズ、処理時間、適用された透かしの数などの詳細を含む透かし処理結果を表します。

```csharp
public class WatermarkResult
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [WatermarkResult](watermarkresult#constructor)() | [`WatermarkResult`](../watermarkresult) クラスの新しいインスタンスを初期化します。 |
| [WatermarkResult](watermarkresult#constructor_1)(long, TimeSpan, long, int) | 特定の値を使用して [`WatermarkResult`](../watermarkresult) クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [FinalDocumentSize](../../groupdocs.watermark.internal/watermarkresult/finaldocumentsize) { get; } | 最終的に処理された文書のサイズ（バイト単位）を取得または設定します。 |
| [NumberWatermarksApplied](../../groupdocs.watermark.internal/watermarkresult/numberwatermarksapplied) { get; } | 文書に適用された透かしの総数を取得または設定します。 |
| [ProcessingTime](../../groupdocs.watermark.internal/watermarkresult/processingtime) { get; } | 透かし処理の処理時間を取得または設定します。 |
| [SourceDocumentSize](../../groupdocs.watermark.internal/watermarkresult/sourcedocumentsize) { get; } | ソース文書のサイズ（バイト単位）を取得または設定します。 |

### 関連項目

* namespace [GroupDocs.Watermark.Internal](../../groupdocs.watermark.internal)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
