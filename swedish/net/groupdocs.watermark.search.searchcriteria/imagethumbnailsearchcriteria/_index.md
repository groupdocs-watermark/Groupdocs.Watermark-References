---
title: "ImageThumbnailSearchCriteria"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar sökkriterium för att hitta bilder i ett innehåll."
type: docs
weight: 2650
url: /sv/net/groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria/
---
## ImageThumbnailSearchCriteria class

Representerar sökkriterium för att hitta bilder i ett innehåll.

```csharp
public class ImageThumbnailSearchCriteria : ImageSearchCriteria
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ImageThumbnailSearchCriteria](imagethumbnailsearchcriteria#constructor)(Stream) | Initierar en ny instans av klassen [`ImageThumbnailSearchCriteria`](../imagethumbnailsearchcriteria) med en specificerad ström. |
| [ImageThumbnailSearchCriteria](imagethumbnailsearchcriteria#constructor_1)(string) | Initierar en ny instans av klassen [`ImageThumbnailSearchCriteria`](../imagethumbnailsearchcriteria) med en specificerad filsökväg. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [MaxDifference](../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria/maxdifference) { get; set; } | Hämtar eller anger maximalt tillåten skillnad mellan bilder. |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | Hämtar eller anger listan med specifika sidnummer |
| [ThumbnailSize](../../groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria/thumbnailsize) { get; set; } | Hämtar eller anger miniatyrstorlek. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Kombinerar detta [`SearchCriteria`](../searchcriteria) med andra kriterier med logisk OCH-operator. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Negerar detta [`SearchCriteria`](../searchcriteria). |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Kombinerar detta [`SearchCriteria`](../searchcriteria) med andra kriterier med logisk ELLER-operator. |

### Anmärkningar

Detta sökkriterium använder en binäriserad bildminiatyr för att beräkna bildlikhet.

### Se även

* class [ImageSearchCriteria](../imagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
