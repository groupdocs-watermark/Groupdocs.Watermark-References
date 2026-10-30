---
title: "ImageColorHistogramSearchCriteria"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta i criteri di ricerca per trovare immagini in un contenuto."
type: docs
weight: 2620
url: /it/net/groupdocs.watermark.search.searchcriteria/imagecolorhistogramsearchcriteria/
---
## ImageColorHistogramSearchCriteria class

Rappresenta i criteri di ricerca per trovare immagini in un contenuto.

```csharp
public class ImageColorHistogramSearchCriteria : ImageSearchCriteria
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ImageColorHistogramSearchCriteria](imagecolorhistogramsearchcriteria#constructor)(Stream) | Inizializza una nuova istanza della classe [`ImageColorHistogramSearchCriteria`](../imagecolorhistogramsearchcriteria) con uno stream specificato. |
| [ImageColorHistogramSearchCriteria](imagecolorhistogramsearchcriteria#constructor_1)(string) | Inizializza una nuova istanza della classe [`ImageColorHistogramSearchCriteria`](../imagecolorhistogramsearchcriteria) con un percorso file specificato. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BinsCount](../../groupdocs.watermark.search.searchcriteria/imagecolorhistogramsearchcriteria/binscount) { get; set; } | Ottiene o imposta il numero di bin che verrà utilizzato per costruire gli istogrammi dei colori. |
| [MaxDifference](../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria/maxdifference) { get; set; } | Ottiene o imposta la differenza massima consentita tra le immagini. |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | Ottiene o imposta l'elenco di numeri di pagina specifici |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Combina questo [`SearchCriteria`](../searchcriteria) con altri criteri usando l'operatore logico AND. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Negare questo [`SearchCriteria`](../searchcriteria). |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Combina questo [`SearchCriteria`](../searchcriteria) con altri criteri usando l'operatore logico OR. |

### Osservazioni

Questo criterio di ricerca utilizza gli istogrammi dei colori delle immagini per calcolare la somiglianza delle immagini.

### Vedi anche

* class [ImageSearchCriteria](../imagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
