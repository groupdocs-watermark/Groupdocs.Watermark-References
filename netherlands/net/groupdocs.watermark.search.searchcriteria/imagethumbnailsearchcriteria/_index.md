---
title: "ImageThumbnailSearchCriteria"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Stelt zoekcriteria voor het vinden van afbeeldingen in een inhoud voor."
type: docs
weight: 2650
url: /nl/net/groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria/
---
## ImageThumbnailSearchCriteria class

Stelt zoekcriteria voor het vinden van afbeeldingen in een inhoud voor.

```csharp
public class ImageThumbnailSearchCriteria : ImageSearchCriteria
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [ImageThumbnailSearchCriteria](imagethumbnailsearchcriteria#constructor)(Stream) | Initialiseert een nieuw exemplaar van de [`ImageThumbnailSearchCriteria`](../imagethumbnailsearchcriteria) klasse met een opgegeven stream. |
| [ImageThumbnailSearchCriteria](imagethumbnailsearchcriteria#constructor_1)(string) | Initialiseert een nieuw exemplaar van de [`ImageThumbnailSearchCriteria`](../imagethumbnailsearchcriteria) klasse met een opgegeven bestandspad. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [MaxDifference](../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria/maxdifference) { get; set; } | Haalt op of stelt het maximaal toegestane verschil tussen afbeeldingen in. |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | Haalt de lijst met specifieke paginanummers op of stelt deze in |
| [ThumbnailSize](../../groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria/thumbnailsize) { get; set; } | Haalt de miniatuurgrootte op of stelt deze in. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Combineert deze [`SearchCriteria`](../searchcriteria) met andere criteria met behulp van de logische EN-operator. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Negereert deze [`SearchCriteria`](../searchcriteria). |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Combineert deze [`SearchCriteria`](../searchcriteria) met andere criteria met behulp van de logische OF-operator. |

### Opmerkingen

Deze zoekcriteria gebruikt een binair gemaakte miniatuur van de afbeelding voor het berekenen van afbeeldingsgelijkenis.

### Zie ook

* class [ImageSearchCriteria](../imagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
