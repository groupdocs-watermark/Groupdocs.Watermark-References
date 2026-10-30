---
title: "ImageInpaintingPossibleWatermark"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar en manuellt specificerad bildregion som ska fyllas i med inpainting med hjälp av omgivande pixlar."
type: docs
weight: 2900
url: /sv/net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/
---
## ImageInpaintingPossibleWatermark class

Representerar en manuellt specificerad bildregion som ska fyllas i (fylld med omgivande pixlar).

```csharp
public class ImageInpaintingPossibleWatermark : PossibleWatermark
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ImageInpaintingPossibleWatermark](imageinpaintingpossiblewatermark)() | Initierar en ny instans av klassen [`ImageInpaintingPossibleWatermark`](../imageinpaintingpossiblewatermark). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| virtual [FormattedTextFragments](../../groupdocs.watermark.search/possiblewatermark/formattedtextfragments) { get; } | Hämtar samlingen av formaterade textfragment för detta [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [Height](../../groupdocs.watermark.search/possiblewatermark/height) { get; } | Hämtar höjden på detta [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| [ImageData](../../groupdocs.watermark.search/possiblewatermark/imagedata) { get; set; } | Hämtar eller anger bilden för detta [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| [Method](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/method) { get; set; } | Hämtar eller anger inpainting‑algoritmen. Standard är PatchBased. |
| virtual [PageNumber](../../groupdocs.watermark.search/possiblewatermark/pagenumber) { get; } | Hämtar sidan som watermark är placerad på. |
| override [Parent](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/parent) { get; } | Hämtar föräldern till detta [`ImageInpaintingPossibleWatermark`](../imageinpaintingpossiblewatermark). Returnerar alltid `null` eftersom regionen är specificerad manuellt. |
| [PatchSize](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/patchsize) { get; set; } | Hämtar eller anger patch‑storlek som används av algoritmen (udda, 5‑11). Standard är 7. För Telea används detta som HalfPatchSize. |
| [Polygons](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/polygons) { get; set; } | Hämtar eller anger polygonala regioner som ska inpaintas, i bildpixlar. Varje polygon är en array av hörn. Antingen [`Rectangles`](./rectangles) eller [`Polygons`](./polygons) måste anges, men inte båda. |
| [Rectangles](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/rectangles) { get; set; } | Hämtar eller anger rektangulära områden som ska inpaintas, i bildpixlar. Antingen [`Rectangles`](./rectangles) eller [`Polygons`](./polygons) måste anges, men inte båda. |
| virtual [RotateAngle](../../groupdocs.watermark.search/possiblewatermark/rotateangle) { get; } | Hämtar rotationsvinkeln för detta [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) i grader. |
| virtual [Text](../../groupdocs.watermark.search/possiblewatermark/text) { get; set; } | Hämtar eller anger texten för detta [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [UnitOfMeasurement](../../groupdocs.watermark.search/possiblewatermark/unitofmeasurement) { get; } | Hämtar måttenheten för detta [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [Width](../../groupdocs.watermark.search/possiblewatermark/width) { get; } | Hämtar bredden för detta [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [X](../../groupdocs.watermark.search/possiblewatermark/x) { get; } | Hämtar x-koordinaten för detta [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [Y](../../groupdocs.watermark.search/possiblewatermark/y) { get; } | Hämtar y-koordinaten för detta [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |

### Se även

* class [PossibleWatermark](../../groupdocs.watermark.search/possiblewatermark)
* namespace [GroupDocs.Watermark.Search.Watermarks](../../groupdocs.watermark.search.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
