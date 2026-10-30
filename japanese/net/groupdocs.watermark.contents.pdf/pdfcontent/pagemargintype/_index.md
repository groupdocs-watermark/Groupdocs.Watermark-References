---
title: "PageMarginType"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "透かし追加時に使用される pdf ページ余白を取得または設定します。"
type: docs
weight: 20
url: /ja/net/groupdocs.watermark.contents.pdf/pdfcontent/pagemargintype/
---
## PdfContent.PageMarginType property

透かし追加時に使用される pdf ページ余白を取得または設定します。

```csharp
public PdfPageMarginType PageMarginType { get; set; }
```

### Property Value

透かし追加時に使用される PDF ページ余白。

### 備考

このプロパティは、[`ConsiderParentMargins`](../../../groupdocs.watermark/watermark/considerparentmargins) が true に設定されている場合にのみ機能します。[`ConsiderParentMargins`](../../../groupdocs.watermark/watermark/considerparentmargins) が false の場合、PDF の CropBox が透かし領域として使用されます。

デフォルト値は TrimBox です。

### 関連項目

* enum [PdfPageMarginType](../../pdfpagemargintype)
* class [PdfContent](../../pdfcontent)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
