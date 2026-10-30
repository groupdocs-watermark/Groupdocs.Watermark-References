---
title: "VectorSearchCriteria"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Geeft criteria weer die filtering op watermerk kleur mogelijk maakt."
type: docs
weight: 2760
url: /nl/net/groupdocs.watermark.search.searchcriteria/vectorsearchcriteria/
---
## VectorSearchCriteria class

Geeft criteria weer die filtering op watermerk kleur mogelijk maakt.

```csharp
public class VectorSearchCriteria : SearchCriteria
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [VectorSearchCriteria](vectorsearchcriteria)() | Initialiseert een nieuw exemplaar van de klasse [`VectorSearchCriteria`](../vectorsearchcriteria). |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [VectorColorRange](../../groupdocs.watermark.search.searchcriteria/vectorsearchcriteria/vectorcolorrange) { get; set; } | Haalt het bereik van kleuren op of stelt het in dat wordt gebruikt om vectorwatermerken te filteren op voorgrondkleur. |

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
using (Watermarker watermarker = new Watermarker(@"C:\test.pdf"))
{
    VectorSearchCriteria searchCriteria = new VectorSearchCriteria();
    Color watermarkColor = ColorTranslator.FromHtml("#a9aaae");
    GroupDocs.Watermark.Watermarks.Color fromSystemColor = GroupDocs.Watermark.Watermarks.Color.FromArgb(watermarkColor.A, watermarkColor.R, watermarkColor.G, watermarkColor.B);
    ColorRange criteriaVectorColorRange = new ColorRange(fromSystemColor)
    {
       MinBrightness = 0.1f,
       MaxBrightness = 0.7f
    };
    searchCriteria.VectorColorRange = criteriaVectorColorRange;
    PossibleWatermarkCollection possibleWatermarkCollection = watermarker.Search(searchCriteria);
    possibleWatermarkCollection.Clear();
    watermarker.Save(@"C:\modified_test.pdf");
}
```

### Zie ook

* class [SearchCriteria](../searchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
