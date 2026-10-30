---
title: "ImageDctHashSearchCriteria"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar ett sökkriterium för att hitta bilder i ett dokument."
type: docs
weight: 2630
url: /sv/net/groupdocs.watermark.search.searchcriteria/imagedcthashsearchcriteria/
---
## ImageDctHashSearchCriteria class

Representerar ett sökkriterium för att hitta bilder i ett dokument.

```csharp
public class ImageDctHashSearchCriteria : ImageSearchCriteria
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ImageDctHashSearchCriteria](imagedcthashsearchcriteria#constructor)(Stream) | Initierar en ny instans av klassen [`ImageDctHashSearchCriteria`](../imagedcthashsearchcriteria) med en specificerad ström. |
| [ImageDctHashSearchCriteria](imagedcthashsearchcriteria#constructor_1)(string) | Initierar en ny instans av klassen [`ImageDctHashSearchCriteria`](../imagedcthashsearchcriteria) med en specificerad filsökväg. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [MaxDifference](../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria/maxdifference) { get; set; } | Hämtar eller anger maximalt tillåten skillnad mellan bilder. |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | Hämtar eller anger listan med specifika sidnummer |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Kombinerar detta [`SearchCriteria`](../searchcriteria) med andra kriterier med logisk OCH-operator. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Negerar detta [`SearchCriteria`](../searchcriteria). |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Kombinerar detta [`SearchCriteria`](../searchcriteria) med andra kriterier med logisk ELLER-operator. |

### Anmärkningar

Detta sökkriterium använder DCT-baserad perceptuell bildhash för att beräkna bildlikhet. **Läs mer:**

* [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

### Exempel

Sök efter bilder i de bifogade filerna (pdf).

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    PdfSearchableObjects = PdfSearchableObjects.All
};
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf", loadOptions, settings))
{
    // Ange exempelbild att jämföra dokumentbilder med
    ImageSearchCriteria criteria = new ImageDctHashSearchCriteria(@"D:\sample.png");
    // Sök efter liknande bilder
    PossibleWatermarkCollection possibleWatermarks = watermarker.Search(criteria);
    // Ta bort eller ändra hittade bildvattenstämplar
    // ...
}
```

### Se även

* class [ImageSearchCriteria](../imagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
