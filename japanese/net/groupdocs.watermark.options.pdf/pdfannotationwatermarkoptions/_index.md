---
title: "PdfAnnotationWatermarkOptions"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "PDFドキュメントに注釈透かしを追加する際の透かし追加オプションを表します。"
type: docs
weight: 1930
url: /ja/net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/
---
## PdfAnnotationWatermarkOptions class

PDFドキュメントに注釈透かしを追加する際の透かし追加オプションを表します。

```csharp
public sealed class PdfAnnotationWatermarkOptions : PdfWatermarkOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PdfAnnotationWatermarkOptions](pdfannotationwatermarkoptions)() | [`PdfAnnotationWatermarkOptions`](../pdfannotationwatermarkoptions) クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/pageindex) { get; set; } | 透かしを追加するページインデックスを取得または設定します。 |
| [PrintOnly](../../groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/printonly) { get; set; } | 注釈が印刷されるが、PDF ビューアでは表示されないかどうかを示す値を取得または設定します。 |

### 備考

**Learn more:**

* [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### 例

PDF ドキュメントに画像注釈透かしを追加します。

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf", loadOptions))
{
    using (ImageWatermark watermark = new ImageWatermark(@"D:\icon.png"))
    {
        PdfAnnotationWatermarkOptions options = new PdfAnnotationWatermarkOptions();
        options.PageIndex = -1; // default - all pages

        watermarker.Add(watermark, options);
    }

    watermarker.Save();
}
```

### 関連項目

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
