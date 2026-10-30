---
title: "TextWatermarkResult"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "テキスト透かしのプロパティを含みます。"
type: docs
weight: 3270
url: /ja/net/groupdocs.watermark.watermarks.results/textwatermarkresult/
---
## TextWatermarkResult class

テキスト透かしのプロパティを含みます。

```csharp
public class TextWatermarkResult : BaseWatermarkResult
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [TextWatermarkResult](textwatermarkresult)(string) | 検索プロセス後に取得した透かし識別子で TextWatermarkResult オブジェクトを初期化します。この一意の識別子は、ドキュメントの透かし情報レイヤーからこの透かしの追加プロパティを取得するために使用されます。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CreatedOn](../../groupdocs.watermark.watermarks.results/basewatermarkresult/createdon) { get; set; } | 透かしの作成日を取得または設定します。 |
| [Height](../../groupdocs.watermark.watermarks.results/basewatermarkresult/height) { get; set; } | 透かしの高さを指定します。 |
| [Left](../../groupdocs.watermark.watermarks.results/basewatermarkresult/left) { get; set; } | 透かしの左位置を指定します。 |
| [ModifiedOn](../../groupdocs.watermark.watermarks.results/basewatermarkresult/modifiedon) { get; set; } | 透かしの変更日を取得または設定します。 |
| [PageNumber](../../groupdocs.watermark.watermarks.results/basewatermarkresult/pagenumber) { get; } | 透かしが配置されたページを指定します。 |
| [Text](../../groupdocs.watermark.watermarks.results/textwatermarkresult/text) { get; set; } | 透かしのテキストを指定します。 |
| [Top](../../groupdocs.watermark.watermarks.results/basewatermarkresult/top) { get; set; } | 透かしの上位置を指定します。 |
| [WatermarkId](../../groupdocs.watermark.watermarks.results/basewatermarkresult/watermarkid) { get; } | Update または Delete メソッドでドキュメント内の透かしを変更するための一意の透かし識別子です。このプロパティは Add メソッドが呼び出された後に自動的に設定されます。以前に保存されている場合は、透かしを操作するために手動で設定することができます。 |
| [WatermarkPosition](../../groupdocs.watermark.watermarks.results/basewatermarkresult/watermarkposition) { get; } | 透かしの位置を指定します。 |
| [WatermarkType](../../groupdocs.watermark.watermarks.results/basewatermarkresult/watermarktype) { get; } | 透かしのタイプを指定します。 |
| [Width](../../groupdocs.watermark.watermarks.results/basewatermarkresult/width) { get; set; } | 透かしの幅を指定します。 |

### 関連項目

* class [BaseWatermarkResult](../basewatermarkresult)
* namespace [GroupDocs.Watermark.Watermarks.Results](../../groupdocs.watermark.watermarks.results)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
