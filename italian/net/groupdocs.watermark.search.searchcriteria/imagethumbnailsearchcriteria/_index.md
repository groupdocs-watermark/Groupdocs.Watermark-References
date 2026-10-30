---
title: "ImageThumbnailSearchCriteria"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta i criteri di ricerca per trovare immagini in un contenuto."
type: docs
weight: 2650
url: /it/net/groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria/
---
## ImageThumbnailSearchCriteria class

Rappresenta i criteri di ricerca per trovare immagini in un contenuto.

```csharp
public class ImageThumbnailSearchCriteria : ImageSearchCriteria
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ImageThumbnailSearchCriteria](imagethumbnailsearchcriteria#constructor)(Stream) | Inizializza una nuova istanza della classe [`ImageThumbnailSearchCriteria`](../imagethumbnailsearchcriteria) con uno stream specificato. |
| [ImageThumbnailSearchCriteria](imagethumbnailsearchcriteria#constructor_1)(string) | Inizializza una nuova istanza della classe [`ImageThumbnailSearchCriteria`](../imagethumbnailsearchcriteria) con un percorso file specificato. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [MaxDifference](../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria/maxdifference) { get; set; } | Ottiene o imposta la differenza massima consentita tra le immagini. |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | Ottiene o imposta l'elenco di numeri di pagina specifici |
| [ThumbnailSize](../../groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria/thumbnailsize) { get; set; } | Ottiene o imposta la dimensione della miniatura. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Combina questo [`SearchCriteria`](../searchcriteria) con altri criteri usando l'operatore logico AND. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Negare questo [`SearchCriteria`](../searchcriteria). |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Combina questo [`SearchCriteria`](../searchcriteria) con altri criteri usando l'operatore logico OR. |

### Osservazioni

Questo criterio di ricerca utilizza una miniatura binarizzata dell'immagine per calcolare la similarità delle immagini.

### Vedi anche

* class [ImageSearchCriteria](../imagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
