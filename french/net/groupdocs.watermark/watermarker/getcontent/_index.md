---
title: "GetContent"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Renvoie l'objet Contentgroupdocs.watermark.contents/content pour le document chargé."
type: docs
weight: 60
url: /fr/net/groupdocs.watermark/watermarker/getcontent/
---
## Watermarker.GetContent&lt;T&gt; method

Renvoie l'objet [`Content`](../../../groupdocs.watermark.contents/content) pour le document chargé.

```csharp
public T GetContent<T>()
    where T : Content
```

| Paramètre | Description |
| --- | --- |
| T | Le type demandé d'un objet [`Content`](../../../groupdocs.watermark.contents/content). |

### Valeur de retour

L'objet [`Content`](../../../groupdocs.watermark.contents/content) pour le document chargé.

### Exemples

Rasterisez la page du document pdf avec le filigrane ajouté.

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

### Voir aussi

* class [Content](../../../groupdocs.watermark.contents/content)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
