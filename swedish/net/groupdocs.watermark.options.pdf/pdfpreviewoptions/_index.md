---
title: "PdfPreviewOptions"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Tillhandahåller alternativ för att ställa in krav och strömbaserade delegater för generering av förhandsgranskning av PDF‑dokument."
type: docs
weight: 1960
url: /sv/net/groupdocs.watermark.options.pdf/pdfpreviewoptions/
---
## PdfPreviewOptions class

Tillhandahåller alternativ för att ställa in krav och strömbaserade delegater för generering av förhandsgranskning av PDF‑dokument.

```csharp
public class PdfPreviewOptions : PreviewOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfPreviewOptions](pdfpreviewoptions#constructor)(CreatePageStream) | Initierar en ny instans av klassen [`PdfPreviewOptions`](../pdfpreviewoptions) som stänger utdataflödet. |
| [PdfPreviewOptions](pdfpreviewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Initierar en ny instans av klassen [`PdfPreviewOptions`](../pdfpreviewoptions) som returnerar utdataflödet till klienten för vidare användning. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | Hämtar eller anger en instans av delegaten för skapande av sidström. |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | Hämtar eller anger sidans förhandsgranskningshöjd. |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | Hämtar eller anger en array med sidnummer för att generera förhandsgranskningar. |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | Hämtar eller anger formatet för förhandsgranskningsbilden. |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | Hämtar eller anger en instans av delegaten för slutförande av sidförhandsgranskning. |
| [Resolution](../../groupdocs.watermark.options.pdf/pdfpreviewoptions/resolution) { get; set; } | Hämtar eller anger upplösningen för de genererade bilderna, i punkter per tum. |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | Hämtar eller anger sidans förhandsgranskningsbredd. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [DefaultResolution](../../groupdocs.watermark.options.pdf/pdfpreviewoptions/defaultresolution) | Standardupplösning i punkter per tum. |

### Se även

* class [PreviewOptions](../../groupdocs.watermark.options/previewoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
