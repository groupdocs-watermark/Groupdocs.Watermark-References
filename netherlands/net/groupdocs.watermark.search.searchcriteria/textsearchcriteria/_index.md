---
title: "TextSearchCriteria"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Geeft criteria weer die filtering op watermerktekst mogelijk maakt."
type: docs
weight: 2750
url: /nl/net/groupdocs.watermark.search.searchcriteria/textsearchcriteria/
---
## TextSearchCriteria class

Geeft criteria weer die filtering op watermerktekst mogelijk maakt.

```csharp
public class TextSearchCriteria : PageSearchCriteria
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [TextSearchCriteria](textsearchcriteria#constructor_2)(Regex) | Initialiseert een nieuw exemplaar van de [`TextSearchCriteria`](../textsearchcriteria) klasse met een opgegeven reguliere expressie. |
| [TextSearchCriteria](textsearchcriteria#constructor)(string) | Initialiseert een nieuw exemplaar van de [`TextSearchCriteria`](../textsearchcriteria) klasse met een zoektekst. |
| [TextSearchCriteria](textsearchcriteria#constructor_1)(string, bool) | Initialiseert een nieuw exemplaar van de [`TextSearchCriteria`](../textsearchcriteria) klasse met een zoektekst en een vlag voor vergelijking. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | Haalt de lijst met specifieke paginanummers op of stelt deze in |
| [Pattern](../../groupdocs.watermark.search.searchcriteria/textsearchcriteria/pattern) { get; } | Haalt het zoekpatroon op. |
| [SkipUnreadableCharacters](../../groupdocs.watermark.search.searchcriteria/textsearchcriteria/skipunreadablecharacters) { get; set; } | Haalt een waarde op of stelt deze in die aangeeft dat onleesbare tekens worden overgeslagen tijdens tekenreeksvergelijking. |

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

Zoek en verwijder watermerk met behulp van zoekcriteria.

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

### Zie ook

* class [PageSearchCriteria](../pagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
