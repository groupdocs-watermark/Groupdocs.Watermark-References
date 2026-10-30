---
title: "ImageInpaintingPossibleWatermark"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Stelt een handmatig gespecificeerde afbeeldingsregio voor die moet worden ingepaint en gevuld met omringende pixels."
type: docs
weight: 2900
url: /nl/net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/
---
## ImageInpaintingPossibleWatermark class

Geeft een handmatig gespecificeerde afbeeldingsregio weer die moet worden ingekleurd (gevuld met omliggende pixels).

```csharp
public class ImageInpaintingPossibleWatermark : PossibleWatermark
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [ImageInpaintingPossibleWatermark](imageinpaintingpossiblewatermark)() | Initialiseert een nieuw exemplaar van de klasse [`ImageInpaintingPossibleWatermark`](../imageinpaintingpossiblewatermark). |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| virtual [FormattedTextFragments](../../groupdocs.watermark.search/possiblewatermark/formattedtextfragments) { get; } | Haalt de collectie van geformatteerde tekstfragmenten van deze [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) op. |
| virtual [Height](../../groupdocs.watermark.search/possiblewatermark/height) { get; } | Haalt de hoogte op van dit [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| [ImageData](../../groupdocs.watermark.search/possiblewatermark/imagedata) { get; set; } | Haalt de afbeelding van deze [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) op of stelt deze in. |
| [Method](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/method) { get; set; } | Haalt de inpainting-algoritme op of stelt deze in. Standaard is PatchBased. |
| virtual [PageNumber](../../groupdocs.watermark.search/possiblewatermark/pagenumber) { get; } | Haalt de pagina op waarop het watermerk is geplaatst. |
| override [Parent](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/parent) { get; } | Haalt de bovenliggende van deze [`ImageInpaintingPossibleWatermark`](../imageinpaintingpossiblewatermark) op. Retourneert altijd `null` omdat de regio handmatig is gespecificeerd. |
| [PatchSize](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/patchsize) { get; set; } | Haalt de patchgrootte op die door het algoritme wordt gebruikt (oneven, 5-11) of stelt deze in. Standaard is 7. Voor Telea wordt dit gebruikt als HalfPatchSize. |
| [Polygons](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/polygons) { get; set; } | Haalt de polygonale regio's op die moeten worden ingepaint, in afbeeldingspixels, of stelt deze in. Elke polygoon is een array van hoekpunten. Ofwel [`Rectangles`](./rectangles) of [`Polygons`](./polygons) moet worden opgegeven, maar niet beide. |
| [Rectangles](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/rectangles) { get; set; } | Haalt de rechthoekige gebieden op die moeten worden ingepaint, in afbeeldingspixels, of stelt deze in. Ofwel [`Rectangles`](./rectangles) of [`Polygons`](./polygons) moet worden opgegeven, maar niet beide. |
| virtual [RotateAngle](../../groupdocs.watermark.search/possiblewatermark/rotateangle) { get; } | Haalt de rotatiehoek op van dit [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) in graden. |
| virtual [Text](../../groupdocs.watermark.search/possiblewatermark/text) { get; set; } | Haalt op of stelt de tekst in van dit [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [UnitOfMeasurement](../../groupdocs.watermark.search/possiblewatermark/unitofmeasurement) { get; } | Haalt de meeteenheid op van dit [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [Width](../../groupdocs.watermark.search/possiblewatermark/width) { get; } | Haalt de breedte op van dit [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [X](../../groupdocs.watermark.search/possiblewatermark/x) { get; } | Haalt de x-coördinaat op van dit [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [Y](../../groupdocs.watermark.search/possiblewatermark/y) { get; } | Haalt de y-coördinaat op van dit [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |

### Zie ook

* class [PossibleWatermark](../../groupdocs.watermark.search/possiblewatermark)
* namespace [GroupDocs.Watermark.Search.Watermarks](../../groupdocs.watermark.search.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
