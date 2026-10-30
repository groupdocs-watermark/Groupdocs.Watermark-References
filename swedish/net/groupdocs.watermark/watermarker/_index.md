---
title: "Watermarker"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar en klass för hantering av vattenstämplar i ett dokument."
type: docs
weight: 3140
url: /sv/net/groupdocs.watermark/watermarker/
---
## Watermarker class

Representerar en klass för hantering av vattenstämplar i ett dokument.

```csharp
public class Watermarker : IDisposable
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Watermarker](watermarker#constructor)(Stream) | Initierar en ny instans av klassen [`Watermarker`](../watermarker) med den specificerade strömmen. |
| [Watermarker](watermarker#constructor_4)(string) | Initierar en ny instans av klassen [`Watermarker`](../watermarker) med den angivna dokumentvägen. |
| [Watermarker](watermarker#constructor_1)(Stream, LoadOptions) | Initierar en ny instans av klassen [`Watermarker`](../watermarker) med den angivna strömmen och laddningsalternativen. |
| [Watermarker](watermarker#constructor_3)(Stream, WatermarkerSettings) | Initierar en ny instans av klassen [`Watermarker`](../watermarker) med den angivna strömmen och inställningarna. |
| [Watermarker](watermarker#constructor_5)(string, LoadOptions) | Initierar en ny instans av klassen [`Watermarker`](../watermarker) med den angivna dokumentvägen och laddningsalternativen. |
| [Watermarker](watermarker#constructor_7)(string, WatermarkerSettings) | Initierar en ny instans av klassen [`Watermarker`](../watermarker) med den angivna dokumentvägen och inställningarna. |
| [Watermarker](watermarker#constructor_2)(Stream, LoadOptions, WatermarkerSettings) | Initierar en ny instans av klassen [`Watermarker`](../watermarker) med den angivna strömmen, laddningsalternativen och inställningarna. |
| [Watermarker](watermarker#constructor_6)(string, LoadOptions, WatermarkerSettings) | Initierar en ny instans av klassen [`Watermarker`](../watermarker) med den angivna dokumentvägen, laddningsalternativen och inställningarna. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [SearchableObjects](../../groupdocs.watermark/watermarker/searchableobjects) { get; set; } | Hämtar eller anger innehållsobjekten som ska inkluderas i en vattenmärkesökning. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Add](../../groupdocs.watermark/watermarker/add#add)(Watermark) | Lägger till ett vattenmärke i det inlästa dokumentet. |
| [Add](../../groupdocs.watermark/watermarker/add#add_1)(Watermark, WatermarkOptions) | Lägger till ett vattenmärke i det inlästa dokumentet med hjälp av vattenmärkesalternativ. |
| [Dispose](../../groupdocs.watermark/watermarker/dispose)() | Avslutar den aktuella instansen. |
| [GeneratePreview](../../groupdocs.watermark/watermarker/generatepreview)(PreviewOptions) | Genererar förhandsgranskningsbilder för dokumentet. |
| [GetContent&lt;T&gt;](../../groupdocs.watermark/watermarker/getcontent)() | Returnerar objektet [`Content`](../../groupdocs.watermark.contents/content) för det inlästa dokumentet. |
| [GetDocumentInfo](../../groupdocs.watermark/watermarker/getdocumentinfo)() | Hämtar information om formatet för det inlästa dokumentet. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages)() | Hittar alla bilder i dokumentet. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages_1)(ImageSearchCriteria) | Hittar bilder enligt angivna sökkriterier. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove)(PossibleWatermark) | Tar bort vattenmärke från dokumentet. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove_1)(PossibleWatermarkCollection) | Tar bort alla vattenmärken i samlingen från dokumentet. |
| [Save](../../groupdocs.watermark/watermarker/save#save)() | Sparar dokumentdata till den underliggande strömmen. |
| [Save](../../groupdocs.watermark/watermarker/save#save_1)(SaveOptions) | Sparar dokumentdata till den underliggande strömmen med hjälp av sparalternativ. |
| [Save](../../groupdocs.watermark/watermarker/save#save_2)(Stream) | Sparar dokumentet till den angivna strömmen. |
| [Save](../../groupdocs.watermark/watermarker/save#save_4)(string) | Sparar dokumentet till den angivna filplatsen. |
| [Save](../../groupdocs.watermark/watermarker/save#save_3)(Stream, SaveOptions) | Sparar dokumentet till den angivna strömmen med hjälp av sparalternativ. |
| [Save](../../groupdocs.watermark/watermarker/save#save_5)(string, SaveOptions) | Sparar dokumentet till den angivna filplatsen med hjälp av sparalternativ. |
| [Search](../../groupdocs.watermark/watermarker/search#search)() | Söker igenom alla möjliga vattenmärken i dokumentet. |
| [Search](../../groupdocs.watermark/watermarker/search#search_1)(SearchCriteria) | Söker möjliga vattenmärken enligt angivna sökkriterier. |

### Exempel

Läs in och spara innehåll i vilket som helst stödd format.

```csharp
// Läs in ett innehåll från en fil.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Använd metoder i Watermarker-klassen för att lägga till, söka eller ta bort vattenmärken.

    // Spara ändringar.
    watermarker.Save("D:\\output.pdf");
}
```

### Se även

* namespace [GroupDocs.Watermark](../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
