---
title: "GetContent"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Returnerar Contentgroupdocs.watermark.contents/content-objektet för det inlästa dokumentet."
type: docs
weight: 60
url: /sv/net/groupdocs.watermark/watermarker/getcontent/
---
## Watermarker.GetContent&lt;T&gt; method

Returnerar [`Content`](../../../groupdocs.watermark.contents/content)-objektet för det inlästa dokumentet.

```csharp
public T GetContent<T>()
    where T : Content
```

| Parameter | Beskrivning |
| --- | --- |
| T | Den begärda typen av ett [`Content`](../../../groupdocs.watermark.contents/content)-objekt. |

### Returvärde

[`Content`](../../../groupdocs.watermark.contents/content)-objektet för det inlästa dokumentet.

### Exempel

Rasterisera pdf-dokumentsida med tillagd vattenstämpel.

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

### Se även

* class [Content](../../../groupdocs.watermark.contents/content)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
