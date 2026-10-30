---
title: "TextSearchCriteria"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar kriterier som möjliggör filtrering efter vattenstämpelns text."
type: docs
weight: 2750
url: /sv/net/groupdocs.watermark.search.searchcriteria/textsearchcriteria/
---
## TextSearchCriteria class

Representerar kriterier som möjliggör filtrering efter vattenstämpelns text.

```csharp
public class TextSearchCriteria : PageSearchCriteria
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextSearchCriteria](textsearchcriteria#constructor_2)(Regex) | Initierar en ny instans av klassen [`TextSearchCriteria`](../textsearchcriteria) med ett specificerat reguljärt uttryck. |
| [TextSearchCriteria](textsearchcriteria#constructor)(string) | Initierar en ny instans av klassen [`TextSearchCriteria`](../textsearchcriteria) med en söksträng. |
| [TextSearchCriteria](textsearchcriteria#constructor_1)(string, bool) | Initierar en ny instans av klassen [`TextSearchCriteria`](../textsearchcriteria) med en söksträng och en flagga för jämförelse. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | Hämtar eller anger listan med specifika sidnummer |
| [Pattern](../../groupdocs.watermark.search.searchcriteria/textsearchcriteria/pattern) { get; } | Hämtar sökmönstret. |
| [SkipUnreadableCharacters](../../groupdocs.watermark.search.searchcriteria/textsearchcriteria/skipunreadablecharacters) { get; set; } | Hämtar eller anger ett värde som indikerar att oläsliga tecken kommer att hoppas över vid strängjämförelse. |

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

Hitta och ta bort vattenmärke med hjälp av sökkriterier.

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

### Se även

* class [PageSearchCriteria](../pagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
