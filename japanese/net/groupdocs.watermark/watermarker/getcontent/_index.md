---
title: "GetContent"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "ロードされたドキュメントの Contentgroupdocs.watermark.contents/content オブジェクトを返します。"
type: docs
weight: 60
url: /ja/net/groupdocs.watermark/watermarker/getcontent/
---
## Watermarker.GetContent&lt;T&gt; method

ロードされたドキュメントの [`Content`](../../../groupdocs.watermark.contents/content) オブジェクトを返します。

```csharp
public T GetContent<T>()
    where T : Content
```

| パラメーター | 説明 |
| --- | --- |
| T | 要求された [`Content`](../../../groupdocs.watermark.contents/content) オブジェクトのタイプです。 |

### 戻り値

ロードされたドキュメントの [`Content`](../../../groupdocs.watermark.contents/content) オブジェクトです。

### 例

追加された透かし付きの PDF ドキュメントページをラスタライズします。

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\doc.pdf", loadOptions))
{ 
    using (ImageWatermark watermark = new ImageWatermark(@"C:\watermark.png"))
    {
        watermarker.Add(watermark);
    }

    PdfContent content = watermarker.GetContent<PdfContent>();
    content.Rasterize(300, 300, PdfImageConversionFormat.Png);

    watermarker.Save();
}
```

### 関連項目

* class [Content](../../../groupdocs.watermark.contents/content)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
