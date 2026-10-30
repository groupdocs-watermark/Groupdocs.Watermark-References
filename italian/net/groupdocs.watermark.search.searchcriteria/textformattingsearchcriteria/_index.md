---
title: "TextFormattingSearchCriteria"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta i criteri che consentono il filtraggio per formattazione del testo."
type: docs
weight: 2740
url: /it/net/groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/
---
## TextFormattingSearchCriteria class

Rappresenta i criteri che consentono il filtraggio per formattazione del testo.

```csharp
public class TextFormattingSearchCriteria : SearchCriteria
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextFormattingSearchCriteria](textformattingsearchcriteria)() | Inizializza una nuova istanza della classe [`TextFormattingSearchCriteria`](../textformattingsearchcriteria). |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BackgroundColorRange](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/backgroundcolorrange) { get; set; } | Ottiene o imposta l'intervallo di colori utilizzato per filtrare i watermark in base al colore di sfondo del testo. |
| [FontBold](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontbold) { get; set; } | Ottiene o imposta un valore che indica se il carattere usato nella formattazione del testo del watermark è in grassetto. |
| [FontItalic](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontitalic) { get; set; } | Ottiene o imposta un valore che indica se il carattere usato nella formattazione del testo del watermark è in corsivo. |
| [FontName](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontname) { get; set; } | Ottiene o imposta il nome del carattere utilizzato nella possibile formattazione del testo del watermark. |
| [FontStrikeout](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontstrikeout) { get; set; } | Ottiene o imposta un valore che indica se il carattere usato nella formattazione del testo del watermark è barrato. |
| [FontUnderline](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontunderline) { get; set; } | Ottiene o imposta un valore che indica se il carattere usato nella formattazione del testo del watermark è sottolineato. |
| [ForegroundColorRange](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/foregroundcolorrange) { get; set; } | Ottiene o imposta l'intervallo di colori utilizzato per filtrare i watermark in base al colore di primo piano del testo. |
| [MaxFontSize](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/maxfontsize) { get; set; } | Ottiene o imposta il valore finale della dimensione del carattere. |
| [MinFontSize](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/minfontsize) { get; set; } | Ottiene o imposta il valore iniziale della dimensione del carattere. |

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

Rimuovi i possibili watermark con una particolare formattazione del testo (indipendentemente dal tipo di documento).

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.doc"))
{
    TextFormattingSearchCriteria criteria = new TextFormattingSearchCriteria();
    criteria.ForegroundColorRange = new ColorRange();
    criteria.ForegroundColorRange.MinHue = -5;
    criteria.ForegroundColorRange.MaxHue = 10;
    criteria.ForegroundColorRange.MinBrightness = 0.01f;
    criteria.ForegroundColorRange.MaxBrightness = 0.99f;
    criteria.BackgroundColorRange = new ColorRange();
    criteria.BackgroundColorRange.IsEmpty = true;
    criteria.FontName = "Arial";
    criteria.MinFontSize = 19;
    criteria.MaxFontSize = 42;
    criteria.FontBold = true;

    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    watermarks.Clear();
    watermarker.Save();
}
```

### Vedi anche

* class [SearchCriteria](../searchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
