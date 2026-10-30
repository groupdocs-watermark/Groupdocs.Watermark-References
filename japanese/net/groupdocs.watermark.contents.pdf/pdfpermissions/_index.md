---
title: "PdfPermissions"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "PDF ドキュメントに対するユーザーの権限を表します。"
type: docs
weight: 760
url: /ja/net/groupdocs.watermark.contents.pdf/pdfpermissions/
---
## PdfPermissions enumeration

PDFドキュメントに対するユーザーの権限を表します。

```csharp
[Flags]
public enum PdfPermissions
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| PrintDocument | `4` | コンテンツを印刷します。 |
| ModifyContent | `8` | コンテンツを変更します。 |
| ExtractContent | `10` | 文書からテキストやグラフィックをコピーまたは抽出します。 |
| ModifyTextAnnotations | `20` | テキスト注釈を追加または変更します。 |
| FillForm | `100` | 既存のインタラクティブなフォームフィールドに入力します。 |
| ExtractContentWithDisabilities | `200` | テキストとグラフィックを抽出します。 |
| AssembleDocument | `400` | コンテンツを組み立てます。 |
| PrintingQuality | `800` | PDF ドキュメントの忠実なデジタルコピーを生成できる形式にコンテンツを印刷します。 |

### 関連項目

* namespace [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
