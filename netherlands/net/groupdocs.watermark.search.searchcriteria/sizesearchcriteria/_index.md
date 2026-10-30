---
title: "SizeSearchCriteria"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Geeft criteria weer die filtering op watermerkgrootte mogelijk maakt."
type: docs
weight: 2730
url: /nl/net/groupdocs.watermark.search.searchcriteria/sizesearchcriteria/
---
## SizeSearchCriteria class

Geeft criteria weer die filtering op watermerkgrootte mogelijk maakt.

```csharp
public class SizeSearchCriteria : SearchCriteria
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [SizeSearchCriteria](sizesearchcriteria)(Dimension, double, double) | Initialiseert een nieuw exemplaar van de [`SizeSearchCriteria`](../sizesearchcriteria) klasse met een opgegeven dimensie, een startwaarde en een eindwaarde. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Dimension](../../groupdocs.watermark.search.searchcriteria/sizesearchcriteria/dimension) { get; } | Haalt de dimensie van het watermerk op waarop gezocht wordt. |
| [Maximum](../../groupdocs.watermark.search.searchcriteria/sizesearchcriteria/maximum) { get; } | Haalt de eindwaarde op. |
| [Minimum](../../groupdocs.watermark.search.searchcriteria/sizesearchcriteria/minimum) { get; } | Haalt de startwaarde op. |

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

* class [SearchCriteria](../searchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
