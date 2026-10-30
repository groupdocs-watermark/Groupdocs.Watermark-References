---
title: "WordProcessingPreviewOptions"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Tillhandahåller alternativ för att ange krav och strömbaserade delegater för generering av förhandsgranskning av WordProcessing-dokument."
type: docs
weight: 2360
url: /sv/net/groupdocs.watermark.options.wordprocessing/wordprocessingpreviewoptions/
---
## WordProcessingPreviewOptions class

Tillhandahåller alternativ för att ange krav och strömbaserade delegater för generering av förhandsgranskning av WordProcessing-dokument.

```csharp
public class WordProcessingPreviewOptions : PreviewOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [WordProcessingPreviewOptions](wordprocessingpreviewoptions#constructor)(CreatePageStream) | Initierar en ny instans av klassen [`WordProcessingPreviewOptions`](../wordprocessingpreviewoptions) som gör att utdataflödet stängs. |
| [WordProcessingPreviewOptions](wordprocessingpreviewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Initierar en ny instans av klassen [`WordProcessingPreviewOptions`](../wordprocessingpreviewoptions) som gör att utdataflödet returneras till klienten för vidare användning. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | Hämtar eller anger en instans av delegaten för skapande av sidström. |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | Hämtar eller anger sidans förhandsgranskningshöjd. |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | Hämtar eller anger en array med sidnummer för att generera förhandsgranskningar. |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | Hämtar eller anger formatet för förhandsgranskningsbilden. |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | Hämtar eller anger en instans av delegaten för slutförande av sidförhandsgranskning. |
| [Resolution](../../groupdocs.watermark.options.wordprocessing/wordprocessingpreviewoptions/resolution) { get; set; } | Hämtar eller anger upplösningen för de genererade bilderna, i punkter per tum. |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | Hämtar eller anger sidans förhandsgranskningsbredd. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [DefaultResolution](../../groupdocs.watermark.options.wordprocessing/wordprocessingpreviewoptions/defaultresolution) | Standardupplösning i punkter per tum. |

### Se även

* class [PreviewOptions](../../groupdocs.watermark.options/previewoptions)
* namespace [GroupDocs.Watermark.Options.WordProcessing](../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
