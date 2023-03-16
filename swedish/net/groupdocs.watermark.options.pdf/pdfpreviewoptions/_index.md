---
title: PdfPreviewOptions
second_title: GroupDocs.Watermark for .NET API-referens
description: Ger alternativ för att ställa krav och strömma delegater för förhandsgranskningsgenerering av PDFdokument.
type: docs
weight: 1890
url: /sv/net/groupdocs.watermark.options.pdf/pdfpreviewoptions/
---
## PdfPreviewOptions class

Ger alternativ för att ställa krav och strömma delegater för förhandsgranskningsgenerering av PDF-dokument.

```csharp
public class PdfPreviewOptions : PreviewOptions
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PdfPreviewOptions](pdfpreviewoptions#constructor)(CreatePageStream) | Initierar en ny instans av[`PdfPreviewOptions`](../pdfpreviewoptions) klass som gör att utgångsströmmen stängs. |
| [PdfPreviewOptions](pdfpreviewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Initierar en ny instans av[`PdfPreviewOptions`](../pdfpreviewoptions) klass som gör att utgångsströmmen returneras till klienten för vidare användning. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | Hämtar eller ställer in en instans av delegaten för att skapa sidström. |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | Hämtar eller ställer in sidförhandsvisningshöjden. |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | Hämtar eller ställer in en rad sidnummer för att generera förhandsvisningar. |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | Hämtar eller ställer in bildformatet för förhandsgranskning. |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | Hämtar eller ställer in en instans av delegaten för slutförandet av sidförhandsgranskningen. |
| [Resolution](../../groupdocs.watermark.options.pdf/pdfpreviewoptions/resolution) { get; set; } | Hämtar eller ställer in upplösningen för de genererade bilderna, i punkter per tum. |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | Hämtar eller ställer in sidans förhandsvisningsbredd. |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [DefaultResolution](../../groupdocs.watermark.options.pdf/pdfpreviewoptions/defaultresolution) | Standardupplösning i punkter per tum. |

### Se även

* class [PreviewOptions](../../groupdocs.watermark.options/previewoptions)
* namnutrymme [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* hopsättning [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->