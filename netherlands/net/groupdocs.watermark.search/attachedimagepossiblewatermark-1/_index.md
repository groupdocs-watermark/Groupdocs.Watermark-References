---
title: "AttachedImagePossibleWatermarkT"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Stelt een bijgevoegd afbeeldingswatermerk voor in een inhoud van elk ondersteund formaat."
type: docs
weight: 2430
url: /nl/net/groupdocs.watermark.search/attachedimagepossiblewatermark-1/
---
## AttachedImagePossibleWatermark&lt;T&gt; class

Stelt een bijgevoegd afbeeldingswatermerk voor in een inhoud van elk ondersteund formaat.

```csharp
public abstract class AttachedImagePossibleWatermark<T> : PossibleWatermark
    where T : Attachment
```

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van de bijlage. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| virtual [FormattedTextFragments](../../groupdocs.watermark.search/possiblewatermark/formattedtextfragments) { get; } | Haalt de collectie van opgemaakte tekstfragmenten van deze [`PossibleWatermark`](../possiblewatermark) op. |
| override [Height](../../groupdocs.watermark.search/attachedimagepossiblewatermark-1/height) { get; } | Haalt de hoogte op van deze [`AttachedImagePossibleWatermark`](../attachedimagepossiblewatermark-1). |
| [ImageData](../../groupdocs.watermark.search/possiblewatermark/imagedata) { get; set; } | Haalt of stelt de afbeelding van deze [`PossibleWatermark`](../possiblewatermark) in. |
| virtual [PageNumber](../../groupdocs.watermark.search/possiblewatermark/pagenumber) { get; } | Haalt de pagina op waarop het watermerk is geplaatst. |
| override [Parent](../../groupdocs.watermark.search/attachedimagepossiblewatermark-1/parent) { get; } | Haalt de ouder van deze [`AttachedImagePossibleWatermark`](../attachedimagepossiblewatermark-1) op. |
| override [RotateAngle](../../groupdocs.watermark.search/attachedimagepossiblewatermark-1/rotateangle) { get; } | Haalt de rotatiehoek van dit [`AttachedImagePossibleWatermark`](../attachedimagepossiblewatermark-1) op in graden. |
| virtual [Text](../../groupdocs.watermark.search/possiblewatermark/text) { get; set; } | Haalt de tekst van dit [`PossibleWatermark`](../possiblewatermark) op of stelt deze in. |
| override [UnitOfMeasurement](../../groupdocs.watermark.search/attachedimagepossiblewatermark-1/unitofmeasurement) { get; } | Haalt de meeteenheid van dit [`AttachedImagePossibleWatermark`](../attachedimagepossiblewatermark-1) op. |
| override [Width](../../groupdocs.watermark.search/attachedimagepossiblewatermark-1/width) { get; } | Haalt de breedte op van deze [`AttachedImagePossibleWatermark`](../attachedimagepossiblewatermark-1). |
| override [X](../../groupdocs.watermark.search/attachedimagepossiblewatermark-1/x) { get; } | Haalt de x-coördinaat op van deze [`AttachedImagePossibleWatermark`](../attachedimagepossiblewatermark-1). |
| override [Y](../../groupdocs.watermark.search/attachedimagepossiblewatermark-1/y) { get; } | Haalt de y-coördinaat op van deze [`AttachedImagePossibleWatermark`](../attachedimagepossiblewatermark-1). |

### Zie ook

* class [PossibleWatermark](../possiblewatermark)
* class [Attachment](../../groupdocs.watermark.common/attachment)
* namespace [GroupDocs.Watermark.Search](../../groupdocs.watermark.search)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
