---
title: "ShapePossibleWatermarkT"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt ein Form-Wasserzeichen in einem Inhalt eines beliebigen unterstützten Formats dar."
type: docs
weight: 2770
url: /de/net/groupdocs.watermark.search/shapepossiblewatermark-1/
---
## ShapePossibleWatermark&lt;T&gt; class

Stellt ein Form-Wasserzeichen in einem Inhalt eines beliebigen unterstützten Formats dar.

```csharp
public abstract class ShapePossibleWatermark<T> : TwoDObjectPossibleWatermark
    where T : ShapeSearchAdapter, ITwoDObject
```

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Form. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [FormattedTextFragments](../../groupdocs.watermark.search/shapepossiblewatermark-1/formattedtextfragments) { get; } | Ermittelt die Sammlung formatierter Textfragmente der Form. |
| override [Height](../../groupdocs.watermark.search/twodobjectpossiblewatermark/height) { get; } | Ermittelt die Höhe des 2D-Objekts. |
| [ImageData](../../groupdocs.watermark.search/possiblewatermark/imagedata) { get; set; } | Liest oder setzt das Bild dieses [`PossibleWatermark`](../possiblewatermark). |
| override [PageNumber](../../groupdocs.watermark.search/shapepossiblewatermark-1/pagenumber) { get; } | Liest die Seite, auf der das Wasserzeichen platziert ist. |
| abstract [Parent](../../groupdocs.watermark.search/possiblewatermark/parent) { get; } | Gibt das übergeordnete Element dieses [`PossibleWatermark`](../possiblewatermark) zurück. |
| override [RotateAngle](../../groupdocs.watermark.search/shapepossiblewatermark-1/rotateangle) { get; } | Ermittelt den Rotationswinkel der Form in Grad. |
| override [Text](../../groupdocs.watermark.search/shapepossiblewatermark-1/text) { get; set; } | Liest oder setzt den Text der Form. |
| override [UnitOfMeasurement](../../groupdocs.watermark.search/twodobjectpossiblewatermark/unitofmeasurement) { get; } | Ermittelt die Maßeinheit des 2D-Objekts. |
| override [Width](../../groupdocs.watermark.search/twodobjectpossiblewatermark/width) { get; } | Ermittelt die Breite des 2D-Objekts. |
| override [X](../../groupdocs.watermark.search/twodobjectpossiblewatermark/x) { get; } | Ermittelt die x-Koordinate des 2D-Objekts. |
| override [Y](../../groupdocs.watermark.search/twodobjectpossiblewatermark/y) { get; } | Ermittelt die y-Koordinate des 2D-Objekts. |

### Siehe auch

* class [TwoDObjectPossibleWatermark](../twodobjectpossiblewatermark)
* class [ShapeSearchAdapter](../shapesearchadapter)
* interface [ITwoDObject](../itwodobject)
* namespace [GroupDocs.Watermark.Search](../../groupdocs.watermark.search)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
