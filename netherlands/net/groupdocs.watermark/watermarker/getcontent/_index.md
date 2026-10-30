---
title: "GetContent"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Retourneert het Contentgroupdocs.watermark.contents/content-object voor het geladen document."
type: docs
weight: 60
url: /nl/net/groupdocs.watermark/watermarker/getcontent/
---
## Watermarker.GetContent&lt;T&gt; method

Retourneert het [`Content`](../../../groupdocs.watermark.contents/content)-object voor het geladen document.

```csharp
public T GetContent<T>()
    where T : Content
```

| Parameter | Beschrijving |
| --- | --- |
| T | Het aangevraagde type van een [`Content`](../../../groupdocs.watermark.contents/content)-object. |

### Retourwaarde

Het [`Content`](../../../groupdocs.watermark.contents/content)-object voor het geladen document.

### Voorbeelden

Rasteriseer een pdf-pagina met toegevoegd watermerk.

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

### Zie ook

* class [Content](../../../groupdocs.watermark.contents/content)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
