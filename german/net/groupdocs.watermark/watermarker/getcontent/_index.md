---
title: "GetContent"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Gibt das Contentgroupdocs.watermark.contents/content-Objekt für das geladene Dokument zurück."
type: docs
weight: 60
url: /de/net/groupdocs.watermark/watermarker/getcontent/
---
## Watermarker.GetContent&lt;T&gt; method

Gibt das [`Content`](../../../groupdocs.watermark.contents/content)-Objekt für das geladene Dokument zurück.

```csharp
public T GetContent<T>()
    where T : Content
```

| Parameter | Beschreibung |
| --- | --- |
| T | Der angeforderte Typ eines [`Content`](../../../groupdocs.watermark.contents/content)-Objekts. |

### Rückgabewert

Das [`Content`](../../../groupdocs.watermark.contents/content)-Objekt für das geladene Dokument.

### Beispiele

Rasterisieren Sie die PDF-Dokumentseite mit hinzugefügtem Wasserzeichen.

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

### Siehe auch

* class [Content](../../../groupdocs.watermark.contents/content)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
