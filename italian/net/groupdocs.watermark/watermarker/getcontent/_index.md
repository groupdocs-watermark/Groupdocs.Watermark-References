---
title: "GetContent"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Restituisce l'oggetto Contentgroupdocs.watermark.contents/content per il documento caricato."
type: docs
weight: 60
url: /it/net/groupdocs.watermark/watermarker/getcontent/
---
## Watermarker.GetContent&lt;T&gt; method

Restituisce l'oggetto [`Content`](../../../groupdocs.watermark.contents/content) per il documento caricato.

```csharp
public T GetContent<T>()
    where T : Content
```

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo richiesto di un oggetto [`Content`](../../../groupdocs.watermark.contents/content). |

### Valore di ritorno

L'oggetto [`Content`](../../../groupdocs.watermark.contents/content) per il documento caricato.

### Esempi

Rasterizza la pagina del documento pdf con la filigrana aggiunta.

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

### Vedi anche

* class [Content](../../../groupdocs.watermark.contents/content)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
