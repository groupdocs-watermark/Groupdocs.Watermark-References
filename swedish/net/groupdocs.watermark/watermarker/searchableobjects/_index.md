---
title: "SearchableObjects"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Hämtar eller anger innehållsobjekten som ska inkluderas i en vattenmärkesökning."
type: docs
weight: 20
url: /sv/net/groupdocs.watermark/watermarker/searchableobjects/
---
## Watermarker.SearchableObjects property

Hämtar eller anger innehållsobjekten som ska inkluderas i en vattenmärkesökning.

```csharp
public SearchableObjects SearchableObjects { get; set; }
```

### Property Value

Objekten som ska inkluderas i en vattenmärkesökning.

### Anmärkningar

Denna egenskap specificerar också innehållsobjekt som används i bildsökning. För mer information, se metoderna [`Search`](../search) och [`GetImages`](../getimages).

Läs mer om att söka vattenmärken: [Söka vattenmärken](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Exempel

Ta bort alla XObjects och Artefakter från ett pdf-dokument.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf"))
{
    // Ange att endast XObjects och Artifacts ska sökas efter.
    watermarker.SearchableObjects.PdfSearchableObjects
        = PdfSearchableObjects.XObjects | PdfSearchableObjects.Artifacts; 

    PossibleWatermarkCollection watermarks = watermarker.Search();

    // Ta bort alla hittade objekt.
    watermarks.Clear();

    // Spara ändringar.
    watermarker.Save();
}
```

### Se även

* class [SearchableObjects](../../../groupdocs.watermark.search.objects/searchableobjects)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
