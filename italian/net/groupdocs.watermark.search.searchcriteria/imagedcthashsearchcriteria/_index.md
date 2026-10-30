---
title: "ImageDctHashSearchCriteria"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta un criterio di ricerca per trovare immagini in un documento."
type: docs
weight: 2630
url: /it/net/groupdocs.watermark.search.searchcriteria/imagedcthashsearchcriteria/
---
## ImageDctHashSearchCriteria class

Rappresenta un criterio di ricerca per trovare immagini in un documento.

```csharp
public class ImageDctHashSearchCriteria : ImageSearchCriteria
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ImageDctHashSearchCriteria](imagedcthashsearchcriteria#constructor)(Stream) | Inizializza una nuova istanza della classe [`ImageDctHashSearchCriteria`](../imagedcthashsearchcriteria) con uno stream specificato. |
| [ImageDctHashSearchCriteria](imagedcthashsearchcriteria#constructor_1)(string) | Inizializza una nuova istanza della classe [`ImageDctHashSearchCriteria`](../imagedcthashsearchcriteria) con un percorso file specificato. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [MaxDifference](../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria/maxdifference) { get; set; } | Ottiene o imposta la differenza massima consentita tra le immagini. |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | Ottiene o imposta l'elenco di numeri di pagina specifici |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Combina questo [`SearchCriteria`](../searchcriteria) con altri criteri usando l'operatore logico AND. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Negare questo [`SearchCriteria`](../searchcriteria). |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Combina questo [`SearchCriteria`](../searchcriteria) con altri criteri usando l'operatore logico OR. |

### Osservazioni

Questo criterio di ricerca utilizza hash percettivo delle immagini basato su DCT per calcolare la somiglianza delle immagini. **Scopri di più:**

* [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

### Esempi

Cerca immagini nei file allegati (pdf).

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    PdfSearchableObjects = PdfSearchableObjects.All
};
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf", loadOptions, settings))
{
    // Specifica l'immagine di esempio con cui confrontare le immagini del documento
    ImageSearchCriteria criteria = new ImageDctHashSearchCriteria(@"D:\sample.png");
    // Cerca immagini simili
    PossibleWatermarkCollection possibleWatermarks = watermarker.Search(criteria);
    // Rimuovi o modifica le filigrane delle immagini trovate
    // ...
}
```

### Vedi anche

* class [ImageSearchCriteria](../imagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
