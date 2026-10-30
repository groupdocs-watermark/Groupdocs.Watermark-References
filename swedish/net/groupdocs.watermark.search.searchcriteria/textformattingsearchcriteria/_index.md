---
title: "TextFormattingSearchCriteria"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar kriterier som möjliggör filtrering efter textformatering."
type: docs
weight: 2740
url: /sv/net/groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/
---
## TextFormattingSearchCriteria class

Representerar kriterier som möjliggör filtrering efter textformatering.

```csharp
public class TextFormattingSearchCriteria : SearchCriteria
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextFormattingSearchCriteria](textformattingsearchcriteria)() | Initierar en ny instans av klassen [`TextFormattingSearchCriteria`](../textformattingsearchcriteria). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BackgroundColorRange](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/backgroundcolorrange) { get; set; } | Hämtar eller anger färgomfånget som används för att filtrera vattenstämplar efter textbakgrundsfärg. |
| [FontBold](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontbold) { get; set; } | Hämtar eller anger ett värde som indikerar om typsnittet som används i vattenstämpelns textformatering är fetstil. |
| [FontItalic](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontitalic) { get; set; } | Hämtar eller anger ett värde som indikerar om typsnittet som används i vattenstämpelns textformatering är kursiv. |
| [FontName](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontname) { get; set; } | Hämtar eller anger namnet på typsnittet som används i möjlig vattenstämpelns textformatering. |
| [FontStrikeout](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontstrikeout) { get; set; } | Hämtar eller anger ett värde som indikerar om typsnittet som används i vattenstämpelns textformatering är genomstruket. |
| [FontUnderline](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontunderline) { get; set; } | Hämtar eller anger ett värde som indikerar om typsnittet som används i vattenstämpelns textformatering är understruket. |
| [ForegroundColorRange](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/foregroundcolorrange) { get; set; } | Hämtar eller anger färgomfånget som används för att filtrera vattenstämplar efter textförgrundsfärg. |
| [MaxFontSize](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/maxfontsize) { get; set; } | Hämtar eller anger slutvärdet för teckenstorleken. |
| [MinFontSize](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/minfontsize) { get; set; } | Hämtar eller anger startvärdet för teckenstorleken. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Kombinerar detta [`SearchCriteria`](../searchcriteria) med andra kriterier med logisk OCH-operator. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Negerar detta [`SearchCriteria`](../searchcriteria). |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Kombinerar detta [`SearchCriteria`](../searchcriteria) med andra kriterier med logisk ELLER-operator. |

### Anmärkningar

**Learn more:**

* [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

### Exempel

Ta bort möjliga vattenstämplar med en viss textformatering (oavsett dokumenttyp).

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

### Se även

* class [SearchCriteria](../searchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
