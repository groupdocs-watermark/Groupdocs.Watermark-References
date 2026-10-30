---
title: "RotateAngleSearchCriteria"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Stelt criteria voor die filtering op rotatiehoek van watermerk mogelijk maakt."
type: docs
weight: 2710
url: /nl/net/groupdocs.watermark.search.searchcriteria/rotateanglesearchcriteria/
---
## RotateAngleSearchCriteria class

Stelt criteria voor die filtering op rotatiehoek van watermerk mogelijk maakt.

```csharp
public class RotateAngleSearchCriteria : SearchCriteria
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [RotateAngleSearchCriteria](rotateanglesearchcriteria)(double, double) | Initialiseert een nieuw exemplaar van de [`RotateAngleSearchCriteria`](../rotateanglesearchcriteria) klasse met een starthoek en een eindhoek. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [MaximumAngle](../../groupdocs.watermark.search.searchcriteria/rotateanglesearchcriteria/maximumangle) { get; } | Haalt de eindhoek op in graden. |
| [MinimumAngle](../../groupdocs.watermark.search.searchcriteria/rotateanglesearchcriteria/minimumangle) { get; } | Haalt de starthoek op in graden. |

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

Zoek en verwijder watermerken met behulp van zoekcriteria.

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
