---
title: "ImageInpaintingPossibleWatermark"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt einen manuell angegebenen Bildbereich dar, der mithilfe benachbarter Pixel ausgefüllt werden soll."
type: docs
weight: 2900
url: /de/net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/
---
## ImageInpaintingPossibleWatermark class

Stellt einen manuell angegebenen Bildbereich dar, der nachbearbeitet (mit umliegenden Pixeln gefüllt) werden soll.

```csharp
public class ImageInpaintingPossibleWatermark : PossibleWatermark
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ImageInpaintingPossibleWatermark](imageinpaintingpossiblewatermark)() | Initialisiert eine neue Instanz der Klasse [`ImageInpaintingPossibleWatermark`](../imageinpaintingpossiblewatermark). |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [FormattedTextFragments](../../groupdocs.watermark.search/possiblewatermark/formattedtextfragments) { get; } | Liest die Sammlung formatierter Textfragmente dieses [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [Height](../../groupdocs.watermark.search/possiblewatermark/height) { get; } | Ermittelt die Höhe dieses [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| [ImageData](../../groupdocs.watermark.search/possiblewatermark/imagedata) { get; set; } | Liest oder legt das Bild dieses [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) fest. |
| [Method](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/method) { get; set; } | Liest den Inpainting-Algorithmus aus oder legt ihn fest. Standard ist PatchBased. |
| virtual [PageNumber](../../groupdocs.watermark.search/possiblewatermark/pagenumber) { get; } | Liest die Seite, auf der das Wasserzeichen platziert ist. |
| override [Parent](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/parent) { get; } | Ermittelt das übergeordnete Element dieses [`ImageInpaintingPossibleWatermark`](../imageinpaintingpossiblewatermark). Gibt immer `null` zurück, weil der Bereich manuell angegeben wird. |
| [PatchSize](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/patchsize) { get; set; } | Liest die vom Algorithmus verwendete Patch-Größe aus oder legt sie fest (ungerade, 5‑11). Standard ist 7. Für Telea wird dies als HalfPatchSize verwendet. |
| [Polygons](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/polygons) { get; set; } | Liest die zu inpaintenden polygonalen Regionen aus oder legt sie fest, in Bildpixeln. Jeder Polygon ist ein Array von Eckpunkten. Entweder [`Rectangles`](./rectangles) oder [`Polygons`](./polygons) muss angegeben werden, jedoch nicht beides. |
| [Rectangles](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/rectangles) { get; set; } | Liest die zu inpaintenden rechteckigen Bereiche aus oder legt sie fest, in Bildpixeln. Entweder [`Rectangles`](./rectangles) oder [`Polygons`](./polygons) muss angegeben werden, jedoch nicht beides. |
| virtual [RotateAngle](../../groupdocs.watermark.search/possiblewatermark/rotateangle) { get; } | Ermittelt den Rotationswinkel dieses [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) in Grad. |
| virtual [Text](../../groupdocs.watermark.search/possiblewatermark/text) { get; set; } | Liest oder setzt den Text dieses [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [UnitOfMeasurement](../../groupdocs.watermark.search/possiblewatermark/unitofmeasurement) { get; } | Ermittelt die Maßeinheit dieses [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [Width](../../groupdocs.watermark.search/possiblewatermark/width) { get; } | Ermittelt die Breite dieses [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [X](../../groupdocs.watermark.search/possiblewatermark/x) { get; } | Ermittelt die x-Koordinate dieses [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [Y](../../groupdocs.watermark.search/possiblewatermark/y) { get; } | Ermittelt die y-Koordinate dieses [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |

### Siehe auch

* class [PossibleWatermark](../../groupdocs.watermark.search/possiblewatermark)
* namespace [GroupDocs.Watermark.Search.Watermarks](../../groupdocs.watermark.search.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
