---
title: "ShapePossibleWatermarkT"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Stelt een vormwatermerk voor in een inhoud van elk ondersteund formaat."
type: docs
weight: 2770
url: /nl/net/groupdocs.watermark.search/shapepossiblewatermark-1/
---
## ShapePossibleWatermark&lt;T&gt; class

Stelt een vormwatermerk voor in een inhoud van elk ondersteund formaat.

```csharp
public abstract class ShapePossibleWatermark<T> : TwoDObjectPossibleWatermark
    where T : ShapeSearchAdapter, ITwoDObject
```

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van de vorm. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| override [FormattedTextFragments](../../groupdocs.watermark.search/shapepossiblewatermark-1/formattedtextfragments) { get; } | Haalt de collectie van opgemaakte tekstfragmenten van de vorm op. |
| override [Height](../../groupdocs.watermark.search/twodobjectpossiblewatermark/height) { get; } | Haalt de hoogte op van het 2D-object. |
| [ImageData](../../groupdocs.watermark.search/possiblewatermark/imagedata) { get; set; } | Haalt of stelt de afbeelding van deze [`PossibleWatermark`](../possiblewatermark) in. |
| override [PageNumber](../../groupdocs.watermark.search/shapepossiblewatermark-1/pagenumber) { get; } | Haalt de pagina op waarop het watermerk is geplaatst. |
| abstract [Parent](../../groupdocs.watermark.search/possiblewatermark/parent) { get; } | Haalt de ouder van dit [`PossibleWatermark`](../possiblewatermark) op. |
| override [RotateAngle](../../groupdocs.watermark.search/shapepossiblewatermark-1/rotateangle) { get; } | Haalt de rotatiehoek van de vorm op in graden. |
| override [Text](../../groupdocs.watermark.search/shapepossiblewatermark-1/text) { get; set; } | Haalt op of stelt de tekst van de vorm in. |
| override [UnitOfMeasurement](../../groupdocs.watermark.search/twodobjectpossiblewatermark/unitofmeasurement) { get; } | Haalt de meeteenheid op van het 2D-object. |
| override [Width](../../groupdocs.watermark.search/twodobjectpossiblewatermark/width) { get; } | Haalt de breedte op van het 2D-object. |
| override [X](../../groupdocs.watermark.search/twodobjectpossiblewatermark/x) { get; } | Haalt de x-coördinaat op van het 2D-object. |
| override [Y](../../groupdocs.watermark.search/twodobjectpossiblewatermark/y) { get; } | Haalt de y-coördinaat op van het 2D-object. |

### Zie ook

* class [TwoDObjectPossibleWatermark](../twodobjectpossiblewatermark)
* class [ShapeSearchAdapter](../shapesearchadapter)
* interface [ITwoDObject](../itwodobject)
* namespace [GroupDocs.Watermark.Search](../../groupdocs.watermark.search)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
