---
title: "SizeSearchCriteria"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta i criteri che consentono il filtraggio per dimensione della filigrana."
type: docs
weight: 2730
url: /it/net/groupdocs.watermark.search.searchcriteria/sizesearchcriteria/
---
## SizeSearchCriteria class

Rappresenta i criteri che consentono il filtraggio per dimensione della filigrana.

```csharp
public class SizeSearchCriteria : SearchCriteria
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SizeSearchCriteria](sizesearchcriteria)(Dimension, double, double) | Inizializza una nuova istanza della classe [`SizeSearchCriteria`](../sizesearchcriteria) con una dimensione specificata, un valore iniziale e un valore finale. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Dimension](../../groupdocs.watermark.search.searchcriteria/sizesearchcriteria/dimension) { get; } | Ottiene la dimensione del watermark per la ricerca. |
| [Maximum](../../groupdocs.watermark.search.searchcriteria/sizesearchcriteria/maximum) { get; } | Ottiene il valore finale. |
| [Minimum](../../groupdocs.watermark.search.searchcriteria/sizesearchcriteria/minimum) { get; } | Ottiene il valore iniziale. |

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
using (Watermarker watermarker = new Watermarker(@"C:\test.some_ext"))
{
    SizeSearchCriteria widthRange = new SizeSearchCriteria(Dimension.Width, 50, 100);
    RotateAngleSearchCriteria rotateAngle = new RotateAngleSearchCriteria(0, 45);
    TextSearchCriteria textCriteria = new TextSearchCriteria(new Regex("^Test watermark$"));
    PossibleWatermarkCollection watermarks = watermarker.Search(textCriteria.And(widthRange.Or(rotateAngle)));
    watermarks.Clear();
    watermarker.Save();
}
```

### Vedi anche

* class [SearchCriteria](../searchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
