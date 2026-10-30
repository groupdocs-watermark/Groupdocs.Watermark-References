---
title: "TextFormattingSearchCriteria"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Geeft criteria weer die filtering op tekstopmaak mogelijk maakt."
type: docs
weight: 2740
url: /nl/net/groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/
---
## TextFormattingSearchCriteria class

Geeft criteria weer die filtering op tekstopmaak mogelijk maakt.

```csharp
public class TextFormattingSearchCriteria : SearchCriteria
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [TextFormattingSearchCriteria](textformattingsearchcriteria)() | Initialiseert een nieuw exemplaar van de [`TextFormattingSearchCriteria`](../textformattingsearchcriteria) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BackgroundColorRange](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/backgroundcolorrange) { get; set; } | Haalt op of stelt het bereik van kleuren in die worden gebruikt om watermerken te filteren op basis van de achtergrondkleur van de tekst. |
| [FontBold](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontbold) { get; set; } | Haalt op of stelt een waarde in die aangeeft of het lettertype dat wordt gebruikt in de opmaak van watermerktekst vetgedrukt is. |
| [FontItalic](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontitalic) { get; set; } | Haalt op of stelt een waarde in die aangeeft of het lettertype dat wordt gebruikt in de opmaak van watermerktekst cursief is. |
| [FontName](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontname) { get; set; } | Haalt op of stelt de naam van het lettertype in dat wordt gebruikt in mogelijke opmaak van watermerktekst. |
| [FontStrikeout](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontstrikeout) { get; set; } | Haalt op of stelt een waarde in die aangeeft of het lettertype dat wordt gebruikt in de opmaak van watermerktekst doorgestreept is. |
| [FontUnderline](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontunderline) { get; set; } | Haalt op of stelt een waarde in die aangeeft of het lettertype dat wordt gebruikt in de opmaak van watermerktekst onderstreept is. |
| [ForegroundColorRange](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/foregroundcolorrange) { get; set; } | Haalt op of stelt het bereik van kleuren in die worden gebruikt om watermerken te filteren op basis van de voorgrondkleur van de tekst. |
| [MaxFontSize](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/maxfontsize) { get; set; } | Haalt op of stelt de eindwaarde van de lettergrootte in. |
| [MinFontSize](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/minfontsize) { get; set; } | Haalt op of stelt de startwaarde van de lettergrootte in. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Combineert deze [`SearchCriteria`](../searchcriteria) met andere criteria met behulp van de logische EN-operator. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Negereert deze [`SearchCriteria`](../searchcriteria). |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Combineert deze [`SearchCriteria`](../searchcriteria) met andere criteria met behulp van de logische OF-operator. |

### Opmerkingen

**Learn more:**

* [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

### Voorbeelden

Verwijder mogelijke watermerken met een specifieke tekstopmaak (ongeacht het documenttype).

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

### Zie ook

* class [SearchCriteria](../searchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
