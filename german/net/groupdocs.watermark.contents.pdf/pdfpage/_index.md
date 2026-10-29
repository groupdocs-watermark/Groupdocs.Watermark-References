---
title: "PdfPage"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt eine pdf-Dokumentseite dar."
type: docs
weight: 730
url: /de/net/groupdocs.watermark.contents.pdf/pdfpage/
---
## PdfPage class

Stellt eine pdf-Dokumentseite dar.

```csharp
public class PdfPage : ContentPart
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Annotations](../../groupdocs.watermark.contents.pdf/pdfpage/annotations) { get; } | Liest die Sammlung aller Annotationen dieser [`PdfPage`](../pdfpage). |
| [Artifacts](../../groupdocs.watermark.contents.pdf/pdfpage/artifacts) { get; } | Liest die Sammlung aller Artefakte dieser [`PdfPage`](../pdfpage). |
| [Height](../../groupdocs.watermark.contents.pdf/pdfpage/height) { get; } | Liest die Höhe dieser [`PdfPage`](../pdfpage) in Punkten. |
| [Width](../../groupdocs.watermark.contents.pdf/pdfpage/width) { get; } | Liest die Breite dieser [`PdfPage`](../pdfpage) in Punkten. |
| [XObjects](../../groupdocs.watermark.contents.pdf/pdfpage/xobjects) { get; } | Liest die Sammlung aller XObjects dieser [`PdfPage`](../pdfpage). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Findet alle Bilder im Inhalt. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Findet Bilder gemäß den angegebenen Suchkriterien. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |
| virtual [Rasterize](../../groupdocs.watermark.contents.pdf/pdfpage/rasterize)(int, int, PdfImageConversionFormat) | Konvertiert den Seiteninhalt in ein Bild. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Findet alle möglichen Wasserzeichen im Inhalt. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Findet mögliche Wasserzeichen gemäß den angegebenen Suchkriterien. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |

### Siehe auch

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
