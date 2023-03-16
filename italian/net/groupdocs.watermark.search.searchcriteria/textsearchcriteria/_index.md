---
title: TextSearchCriteria
second_title: Riferimento API GroupDocs.Watermark per .NET
description: Rappresenta i criteri che consentono di filtrare in base al testo della filigrana.
type: docs
weight: 2700
url: /it/net/groupdocs.watermark.search.searchcriteria/textsearchcriteria/
---
## TextSearchCriteria class

Rappresenta i criteri che consentono di filtrare in base al testo della filigrana.

```csharp
public class TextSearchCriteria : SearchCriteria
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextSearchCriteria](textsearchcriteria#constructor_2)(Regex) | Inizializza una nuova istanza di[`TextSearchCriteria`](../textsearchcriteria) classe con un'espressione regolare specificata. |
| [TextSearchCriteria](textsearchcriteria#constructor)(string) | Inizializza una nuova istanza di[`TextSearchCriteria`](../textsearchcriteria) classe con una stringa di ricerca. |
| [TextSearchCriteria](textsearchcriteria#constructor_1)(string, bool) | Inizializza una nuova istanza di[`TextSearchCriteria`](../textsearchcriteria) class con una stringa di ricerca e un flag per il confronto. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Pattern](../../groupdocs.watermark.search.searchcriteria/textsearchcriteria/pattern) { get; } | Ottiene il modello di ricerca. |
| [SkipUnreadableCharacters](../../groupdocs.watermark.search.searchcriteria/textsearchcriteria/skipunreadablecharacters) { get; set; } | Ottiene o imposta un valore che indica che i caratteri illeggibili verranno ignorati durante il confronto tra stringhe. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Combina questo[`SearchCriteria`](../searchcriteria) con altri criteri utilizzando l'operatore AND logico. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Nega questo[`SearchCriteria`](../searchcriteria) . |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Combina questo[`SearchCriteria`](../searchcriteria) con altri criteri utilizzando l'operatore OR logico. |

### Osservazioni

**Saperne di più:**

* [Ricerca di filigrane](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

### Esempi

Trova e rimuovi la filigrana utilizzando i criteri di ricerca.

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

### Guarda anche

* class [SearchCriteria](../searchcriteria)
* spazio dei nomi [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assemblea [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->