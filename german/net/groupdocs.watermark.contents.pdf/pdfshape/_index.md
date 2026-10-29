---
title: "PdfShape"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt die Basisklasse für XObjects-Artefakte und Anmerkungen bereit."
type: docs
weight: 770
url: /de/net/groupdocs.watermark.contents.pdf/pdfshape/
---
## PdfShape class

Stellt die Basisklasse für XObjects, Artefakte und Anmerkungen bereit.

```csharp
public abstract class PdfShape : ShapeSearchAdapter, IRotatableTwoDObject
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [FormattedTextFragments](../../groupdocs.watermark.contents.pdf/pdfshape/formattedtextfragments) { get; } | Gibt die Sammlung formatierter Textfragmente dieses [`PdfShape`](../pdfshape) zurück. |
| abstract [Height](../../groupdocs.watermark.contents.pdf/pdfshape/height) { get; } | Ermittelt die Höhe des Objekts. |
| [Image](../../groupdocs.watermark.contents.pdf/pdfshape/image) { get; set; } | Liest oder setzt das Bild dieses [`PdfShape`](../pdfshape). |
| abstract [RotateAngle](../../groupdocs.watermark.contents.pdf/pdfshape/rotateangle) { get; } | Ermittelt den Rotationswinkel des Objekts in Grad. |
| virtual [Text](../../groupdocs.watermark.contents.pdf/pdfshape/text) { get; set; } | Liest oder setzt den Text dieses [`PdfShape`](../pdfshape). |
| abstract [Width](../../groupdocs.watermark.contents.pdf/pdfshape/width) { get; } | Ermittelt die Breite des Objekts. |
| abstract [X](../../groupdocs.watermark.contents.pdf/pdfshape/x) { get; } | Ermittelt die x-Koordinate des Objekts. |
| abstract [Y](../../groupdocs.watermark.contents.pdf/pdfshape/y) { get; } | Ermittelt die y-Koordinate des Objekts. |

### Siehe auch

* class [ShapeSearchAdapter](../../groupdocs.watermark.search/shapesearchadapter)
* interface [IRotatableTwoDObject](../../groupdocs.watermark.search/irotatabletwodobject)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
