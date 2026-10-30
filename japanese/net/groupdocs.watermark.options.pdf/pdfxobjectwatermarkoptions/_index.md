---
title: "PdfXObjectWatermarkOptions"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "PDFドキュメントにXObject透かしを追加する際の透かし追加オプションを表します。"
type: docs
weight: 1990
url: /ja/net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/
---
## PdfXObjectWatermarkOptions class

PDFドキュメントにXObject透かしを追加する際の透かし追加オプションを表します。

```csharp
public sealed class PdfXObjectWatermarkOptions : PdfWatermarkOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PdfXObjectWatermarkOptions](pdfxobjectwatermarkoptions)() | [`PdfXObjectWatermarkOptions`](../pdfxobjectwatermarkoptions) クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/pageindex) { get; set; } | 透かしを追加するページインデックスを取得または設定します。 |

### 備考

**Learn more:**

* [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### 例

PDF ドキュメントの特定のページに透かしを追加します。

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\doc.pdf", loadOptions))
using (ImageWatermark watermark = new ImageWatermark(@"C:\watermark.png"))
{
    PdfXObjectWatermarkOptions options = new PdfXObjectWatermarkOptions();
    options.PageIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### 関連項目

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
