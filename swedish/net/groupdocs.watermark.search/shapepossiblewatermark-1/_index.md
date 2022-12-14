---
title: ShapePossibleWatermarkT
second_title: GroupDocs.Watermark for .NET API-referens
description: Representerar formvattenstämpel i ett innehåll av vilket format som helst.
type: docs
weight: 2710
url: /sv/net/groupdocs.watermark.search/shapepossiblewatermark-1/
---
## ShapePossibleWatermark&lt;T&gt; class

Representerar formvattenstämpel i ett innehåll av vilket format som helst.

```csharp
public abstract class ShapePossibleWatermark<T> : TwoDObjectPossibleWatermark
    where T : ShapeSearchAdapter, ITwoDObject
```

| Parameter | Beskrivning |
| --- | --- |
| T | Formens typ. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| override [FormattedTextFragments](../../groupdocs.watermark.search/shapepossiblewatermark-1/formattedtextfragments) { get; } | Hämtar samlingen av formaterade textfragment av formen. |
| override [Height](../../groupdocs.watermark.search/twodobjectpossiblewatermark/height) { get; } | Får höjden på 2D-objektet. |
| [ImageData](../../groupdocs.watermark.search/possiblewatermark/imagedata) { get; set; } | Hämtar eller ställer in bilden av detta[`PossibleWatermark`](../possiblewatermark) . |
| abstract [Parent](../../groupdocs.watermark.search/possiblewatermark/parent) { get; } | Hämtar föräldern till detta[`PossibleWatermark`](../possiblewatermark) . |
| override [RotateAngle](../../groupdocs.watermark.search/shapepossiblewatermark-1/rotateangle) { get; } | Får formens rotationsvinkel i grader. |
| override [Text](../../groupdocs.watermark.search/shapepossiblewatermark-1/text) { get; set; } | Hämtar eller ställer in formens text. |
| override [UnitOfMeasurement](../../groupdocs.watermark.search/twodobjectpossiblewatermark/unitofmeasurement) { get; } | Får måttenheten för 2D-objektet. |
| override [Width](../../groupdocs.watermark.search/twodobjectpossiblewatermark/width) { get; } | Hämtar bredden på 2D-objektet. |
| override [X](../../groupdocs.watermark.search/twodobjectpossiblewatermark/x) { get; } | Får x-koordinaten för 2D-objektet. |
| override [Y](../../groupdocs.watermark.search/twodobjectpossiblewatermark/y) { get; } | Hämtar y-koordinaten för 2D-objektet. |

### Se även

* class [TwoDObjectPossibleWatermark](../twodobjectpossiblewatermark)
* class [ShapeSearchAdapter](../shapesearchadapter)
* interface [ITwoDObject](../itwodobject)
* namnutrymme [GroupDocs.Watermark.Search](../../groupdocs.watermark.search)
* hopsättning [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
