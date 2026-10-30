---
title: "ImageColorHistogramSearchCriteria"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar sökkriterium för att hitta bilder i ett innehåll."
type: docs
weight: 2620
url: /sv/net/groupdocs.watermark.search.searchcriteria/imagecolorhistogramsearchcriteria/
---
## ImageColorHistogramSearchCriteria class

Representerar sökkriterium för att hitta bilder i ett innehåll.

```csharp
public class ImageColorHistogramSearchCriteria : ImageSearchCriteria
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ImageColorHistogramSearchCriteria](imagecolorhistogramsearchcriteria#constructor)(Stream) | Initierar en ny instans av klassen [`ImageColorHistogramSearchCriteria`](../imagecolorhistogramsearchcriteria) med en angiven ström. |
| [ImageColorHistogramSearchCriteria](imagecolorhistogramsearchcriteria#constructor_1)(string) | Initierar en ny instans av klassen [`ImageColorHistogramSearchCriteria`](../imagecolorhistogramsearchcriteria) med en angiven filsökväg. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BinsCount](../../groupdocs.watermark.search.searchcriteria/imagecolorhistogramsearchcriteria/binscount) { get; set; } | Hämtar eller anger ett antal fack som ska användas för att bygga färg‑histogram. |
| [MaxDifference](../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria/maxdifference) { get; set; } | Hämtar eller anger maximalt tillåten skillnad mellan bilder. |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | Hämtar eller anger listan med specifika sidnummer |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Kombinerar detta [`SearchCriteria`](../searchcriteria) med andra kriterier med logisk OCH-operator. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Negerar detta [`SearchCriteria`](../searchcriteria). |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Kombinerar detta [`SearchCriteria`](../searchcriteria) med andra kriterier med logisk ELLER-operator. |

### Anmärkningar

Detta sökkriterium använder bildfärgshistogram för att beräkna bildlikhet.

### Se även

* class [ImageSearchCriteria](../imagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
