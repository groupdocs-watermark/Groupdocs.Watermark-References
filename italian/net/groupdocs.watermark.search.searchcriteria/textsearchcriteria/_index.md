---
title: "TextSearchCriteria"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta i criteri che consentono il filtraggio per il testo della filigrana."
type: docs
weight: 2750
url: /it/net/groupdocs.watermark.search.searchcriteria/textsearchcriteria/
---
## TextSearchCriteria class

Rappresenta i criteri che consentono il filtraggio per il testo della filigrana.

```csharp
public class TextSearchCriteria : PageSearchCriteria
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextSearchCriteria](textsearchcriteria#constructor_2)(Regex) | Inizializza una nuova istanza della classe [`TextSearchCriteria`](../textsearchcriteria) con un'espressione regolare specificata. |
| [TextSearchCriteria](textsearchcriteria#constructor)(string) | Inizializza una nuova istanza della classe [`TextSearchCriteria`](../textsearchcriteria) con una stringa di ricerca. |
| [TextSearchCriteria](textsearchcriteria#constructor_1)(string, bool) | Inizializza una nuova istanza della classe [`TextSearchCriteria`](../textsearchcriteria) con una stringa di ricerca e un flag per il confronto. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | Ottiene o imposta l'elenco di numeri di pagina specifici |
| [Pattern](../../groupdocs.watermark.search.searchcriteria/textsearchcriteria/pattern) { get; } | Ottiene il modello di ricerca. |
| [SkipUnreadableCharacters](../../groupdocs.watermark.search.searchcriteria/textsearchcriteria/skipunreadablecharacters) { get; set; } | Ottiene o imposta un valore che indica che i caratteri illeggibili saranno ignorati durante il confronto delle stringhe. |

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

* class [PageSearchCriteria](../pagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
