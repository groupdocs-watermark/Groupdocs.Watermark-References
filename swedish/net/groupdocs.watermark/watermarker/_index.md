---
title: Watermarker
second_title: GroupDocs.Watermark for .NET API-referens
description: Representerar en klass för vattenstämpelhantering i ett dokument.
type: docs
weight: 3060
url: /sv/net/groupdocs.watermark/watermarker/
---
## Watermarker class

Representerar en klass för vattenstämpelhantering i ett dokument.

```csharp
public class Watermarker : IDisposable
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Watermarker](watermarker#constructor)(Stream) | Initierar en ny instans av[`Watermarker`](../watermarker) klass med den angivna strömmen. |
| [Watermarker](watermarker#constructor_4)(string) | Initierar en ny instans av[`Watermarker`](../watermarker) klass med den angivna dokumentsökvägen. |
| [Watermarker](watermarker#constructor_1)(Stream, LoadOptions) | Initierar en ny instans av[`Watermarker`](../watermarker) klass med de angivna stream och laddningsalternativ. |
| [Watermarker](watermarker#constructor_3)(Stream, WatermarkerSettings) | Initierar en ny instans av[`Watermarker`](../watermarker) klass med den angivna stream och inställningar. |
| [Watermarker](watermarker#constructor_5)(string, LoadOptions) | Initierar en ny instans av[`Watermarker`](../watermarker)klass med specificerad dokumentsökväg och laddningsalternativ. |
| [Watermarker](watermarker#constructor_7)(string, WatermarkerSettings) | Initierar en ny instans av[`Watermarker`](../watermarker) klass med specificerad dokumentsökväg och inställningar. |
| [Watermarker](watermarker#constructor_2)(Stream, LoadOptions, WatermarkerSettings) | Initierar en ny instans av[`Watermarker`](../watermarker) klass med den angivna strömmen, laddningsalternativ och inställningar. |
| [Watermarker](watermarker#constructor_6)(string, LoadOptions, WatermarkerSettings) | Initierar en ny instans av[`Watermarker`](../watermarker) klass med specificerad dokumentsökväg, laddningsalternativ och inställningar. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [SearchableObjects](../../groupdocs.watermark/watermarker/searchableobjects) { get; set; } | Hämtar eller ställer in innehållsobjekten som ska inkluderas i en vattenstämpelsökning. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Add](../../groupdocs.watermark/watermarker/add#add)(Watermark) | Lägger till en vattenstämpel till det laddade dokumentet. |
| [Add](../../groupdocs.watermark/watermarker/add#add_1)(Watermark, WatermarkOptions) | Lägger till en vattenstämpel till det laddade dokumentet med vattenstämpelalternativ. |
| [Dispose](../../groupdocs.watermark/watermarker/dispose)() | Tar bort den aktuella instansen. |
| [GeneratePreview](../../groupdocs.watermark/watermarker/generatepreview)(PreviewOptions) | Genererar förhandsgranskningsbilder för dokumentet. |
| [GetContent&lt;T&gt;](../../groupdocs.watermark/watermarker/getcontent)() | Returnerar[`Content`](../../groupdocs.watermark.contents/content) objekt för det inlästa dokumentet. |
| [GetDocumentInfo](../../groupdocs.watermark/watermarker/getdocumentinfo)() | Får information om formatet på det laddade dokumentet. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages)() | Hittar alla bilder i dokumentet. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages_1)(ImageSearchCriteria) | Hittar bilder enligt angivna sökkriterier. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove)(PossibleWatermark) | Tar bort vattenstämpel från dokumentet. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove_1)(PossibleWatermarkCollection) | Tar bort alla vattenstämplar i samlingen från dokumentet. |
| [Save](../../groupdocs.watermark/watermarker/save#save)() | Sparar dokumentdata till den underliggande strömmen. |
| [Save](../../groupdocs.watermark/watermarker/save#save_1)(SaveOptions) | Sparar dokumentdata till den underliggande strömmen med hjälp av sparalternativ. |
| [Save](../../groupdocs.watermark/watermarker/save#save_2)(Stream) | Sparar dokumentet i den angivna strömmen. |
| [Save](../../groupdocs.watermark/watermarker/save#save_4)(string) | Sparar dokumentet till den angivna filplatsen. |
| [Save](../../groupdocs.watermark/watermarker/save#save_3)(Stream, SaveOptions) | Sparar dokumentet till den angivna strömmen med hjälp av sparaalternativ. |
| [Save](../../groupdocs.watermark/watermarker/save#save_5)(string, SaveOptions) | Sparar dokumentet till den angivna filplatsen med hjälp av sparaalternativ. |
| [Search](../../groupdocs.watermark/watermarker/search#search)() | Söker efter alla möjliga vattenstämplar i dokumentet. |
| [Search](../../groupdocs.watermark/watermarker/search#search_1)(SearchCriteria) | Söker efter möjliga vattenstämplar enligt angivna sökkriterier. |

### Exempel

Ladda och spara ett innehåll i valfritt format som stöds.

```csharp
// Ladda ett innehåll från en fil.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Använd metoder i klassen Watermarker för att lägga till, söka eller ta bort vattenstämplar.

    // Spara ändringar.
    watermarker.Save("D:\\output.pdf");
}
```

### Se även

* namnutrymme [GroupDocs.Watermark](../../groupdocs.watermark)
* hopsättning [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
