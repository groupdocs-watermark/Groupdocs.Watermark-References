---
title: "AttachedImagePossibleWatermarkT"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar bifogat bildvattenmärke i ett innehåll av vilket som helst stödformat."
type: docs
weight: 2430
url: /sv/net/groupdocs.watermark.search/attachedimagepossiblewatermark-1/
---
## AttachedImagePossibleWatermark&lt;T&gt; class

Representerar bifogat bildvattenmärke i ett innehåll av vilket som helst stödformat.

```csharp
public abstract class AttachedImagePossibleWatermark<T> : PossibleWatermark
    where T : Attachment
```

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av bilagan. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| virtual [FormattedTextFragments](../../groupdocs.watermark.search/possiblewatermark/formattedtextfragments) { get; } | Hämtar samlingen av formaterade textfragment för detta [`PossibleWatermark`](../possiblewatermark). |
| override [Height](../../groupdocs.watermark.search/attachedimagepossiblewatermark-1/height) { get; } | Hämtar höjden på detta [`AttachedImagePossibleWatermark`](../attachedimagepossiblewatermark-1). |
| [ImageData](../../groupdocs.watermark.search/possiblewatermark/imagedata) { get; set; } | Hämtar eller anger bilden för detta [`PossibleWatermark`](../possiblewatermark). |
| virtual [PageNumber](../../groupdocs.watermark.search/possiblewatermark/pagenumber) { get; } | Hämtar sidan som watermark är placerad på. |
| override [Parent](../../groupdocs.watermark.search/attachedimagepossiblewatermark-1/parent) { get; } | Hämtar föräldern till detta [`AttachedImagePossibleWatermark`](../attachedimagepossiblewatermark-1). |
| override [RotateAngle](../../groupdocs.watermark.search/attachedimagepossiblewatermark-1/rotateangle) { get; } | Hämtar rotationsvinkeln för detta [`AttachedImagePossibleWatermark`](../attachedimagepossiblewatermark-1) i grader. |
| virtual [Text](../../groupdocs.watermark.search/possiblewatermark/text) { get; set; } | Hämtar eller anger texten för detta [`PossibleWatermark`](../possiblewatermark). |
| override [UnitOfMeasurement](../../groupdocs.watermark.search/attachedimagepossiblewatermark-1/unitofmeasurement) { get; } | Hämtar måttenheten för detta [`AttachedImagePossibleWatermark`](../attachedimagepossiblewatermark-1). |
| override [Width](../../groupdocs.watermark.search/attachedimagepossiblewatermark-1/width) { get; } | Hämtar bredden på detta [`AttachedImagePossibleWatermark`](../attachedimagepossiblewatermark-1). |
| override [X](../../groupdocs.watermark.search/attachedimagepossiblewatermark-1/x) { get; } | Hämtar x-koordinaten för detta [`AttachedImagePossibleWatermark`](../attachedimagepossiblewatermark-1). |
| override [Y](../../groupdocs.watermark.search/attachedimagepossiblewatermark-1/y) { get; } | Hämtar y-koordinaten för detta [`AttachedImagePossibleWatermark`](../attachedimagepossiblewatermark-1). |

### Se även

* class [PossibleWatermark](../possiblewatermark)
* class [Attachment](../../groupdocs.watermark.common/attachment)
* namespace [GroupDocs.Watermark.Search](../../groupdocs.watermark.search)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
