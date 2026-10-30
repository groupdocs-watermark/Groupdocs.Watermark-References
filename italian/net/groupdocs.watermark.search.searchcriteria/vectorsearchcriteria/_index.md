---
title: "VectorSearchCriteria"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta i criteri che consentono il filtraggio per colore della filigrana."
type: docs
weight: 2760
url: /it/net/groupdocs.watermark.search.searchcriteria/vectorsearchcriteria/
---
## VectorSearchCriteria class

Rappresenta i criteri che consentono il filtraggio per colore della filigrana.

```csharp
public class VectorSearchCriteria : SearchCriteria
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [VectorSearchCriteria](vectorsearchcriteria)() | Inizializza una nuova istanza della classe [`VectorSearchCriteria`](../vectorsearchcriteria). |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [VectorColorRange](../../groupdocs.watermark.search.searchcriteria/vectorsearchcriteria/vectorcolorrange) { get; set; } | Ottiene o imposta l'intervallo di colori utilizzato per filtrare i watermark vettoriali per colore di primo piano. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Combina questo [`SearchCriteria`](../searchcriteria) con altri criteri usando l'operatore logico AND. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Negare questo [`SearchCriteria`](../searchcriteria). |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Combina questo [`SearchCriteria`](../searchcriteria) con altri criteri usando l'operatore logico OR. |

### Osservazioni

**Learn more:**

* [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

### Esempi

Trova e rimuovi il watermark usando i criteri di ricerca.

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

### Vedi anche

* class [SearchCriteria](../searchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
