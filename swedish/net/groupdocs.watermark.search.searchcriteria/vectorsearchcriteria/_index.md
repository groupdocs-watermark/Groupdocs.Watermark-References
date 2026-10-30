---
title: "VectorSearchCriteria"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar kriterier som möjliggör filtrering efter vattenstämpelns färg."
type: docs
weight: 2760
url: /sv/net/groupdocs.watermark.search.searchcriteria/vectorsearchcriteria/
---
## VectorSearchCriteria class

Representerar kriterier som möjliggör filtrering efter vattenstämpelns färg.

```csharp
public class VectorSearchCriteria : SearchCriteria
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [VectorSearchCriteria](vectorsearchcriteria)() | Initierar en ny instans av klassen [`VectorSearchCriteria`](../vectorsearchcriteria). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [VectorColorRange](../../groupdocs.watermark.search.searchcriteria/vectorsearchcriteria/vectorcolorrange) { get; set; } | Hämtar eller anger färgområdet som används för att filtrera vektorvattenmärken efter förgrundsfärg. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Kombinerar detta [`SearchCriteria`](../searchcriteria) med andra kriterier med logisk OCH-operator. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Negerar detta [`SearchCriteria`](../searchcriteria). |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Kombinerar detta [`SearchCriteria`](../searchcriteria) med andra kriterier med logisk ELLER-operator. |

### Anmärkningar

**Learn more:**

* [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

### Exempel

Hitta och ta bort vattenmärke med hjälp av sökkriterier.

```csharp
using (Watermarker watermarker = new Watermarker(@"C:\test.pdf"))
{
    VectorSearchCriteria searchCriteria = new VectorSearchCriteria();
    Color watermarkColor = ColorTranslator.FromHtml("#a9aaae");
    GroupDocs.Watermark.Watermarks.Color fromSystemColor = GroupDocs.Watermark.Watermarks.Color.FromArgb(watermarkColor.A, watermarkColor.R, watermarkColor.G, watermarkColor.B);
    ColorRange criteriaVectorColorRange = new ColorRange(fromSystemColor)
    {
       MinBrightness = 0.1f,
       MaxBrightness = 0.7f
    };
    searchCriteria.VectorColorRange = criteriaVectorColorRange;
    PossibleWatermarkCollection possibleWatermarkCollection = watermarker.Search(searchCriteria);
    possibleWatermarkCollection.Clear();
    watermarker.Save(@"C:\modified_test.pdf");
}
```

### Se även

* class [SearchCriteria](../searchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
