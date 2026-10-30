---
title: "RotateAngleSearchCriteria"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta criteri che consentono il filtraggio per angolo di rotazione della filigrana."
type: docs
weight: 2710
url: /it/net/groupdocs.watermark.search.searchcriteria/rotateanglesearchcriteria/
---
## RotateAngleSearchCriteria class

Rappresenta criteri che consentono il filtraggio per angolo di rotazione della filigrana.

```csharp
public class RotateAngleSearchCriteria : SearchCriteria
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [RotateAngleSearchCriteria](rotateanglesearchcriteria)(double, double) | Inizializza una nuova istanza della classe [`RotateAngleSearchCriteria`](../rotateanglesearchcriteria) con un angolo iniziale e un angolo finale. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [MaximumAngle](../../groupdocs.watermark.search.searchcriteria/rotateanglesearchcriteria/maximumangle) { get; } | Ottiene l'angolo finale in gradi. |
| [MinimumAngle](../../groupdocs.watermark.search.searchcriteria/rotateanglesearchcriteria/minimumangle) { get; } | Ottiene l'angolo iniziale in gradi. |

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

Trova e rimuovi le filigrane usando il criterio di ricerca.

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
