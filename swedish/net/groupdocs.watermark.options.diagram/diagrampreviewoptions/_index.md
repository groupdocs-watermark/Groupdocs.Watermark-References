---
title: "DiagramPreviewOptions"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Tillhandahåller alternativ för att ange krav och strömbegäranden för generering av förhandsgranskning av Diagram-dokument."
type: docs
weight: 1730
url: /sv/net/groupdocs.watermark.options.diagram/diagrampreviewoptions/
---
## DiagramPreviewOptions class

Tillhandahåller alternativ för att ange krav och strömbegäranden för generering av förhandsgranskning av Diagram-dokument.

```csharp
public class DiagramPreviewOptions : PreviewOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [DiagramPreviewOptions](diagrampreviewoptions#constructor)(CreatePageStream) | Initierar en ny instans av klassen [`DiagramPreviewOptions`](../diagrampreviewoptions) som gör att utdataströmmen stängs. |
| [DiagramPreviewOptions](diagrampreviewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Initierar en ny instans av klassen [`DiagramPreviewOptions`](../diagrampreviewoptions) som gör att utdataströmmen returneras till klienten för vidare användning. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | Hämtar eller anger en instans av delegaten för skapande av sidström. |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | Hämtar eller anger sidans förhandsgranskningshöjd. |
| [HighQualityRendering](../../groupdocs.watermark.options.diagram/diagrampreviewoptions/highqualityrendering) { get; set; } | Hämtar eller anger flaggan för rendering med hög kvalitet. |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | Hämtar eller anger en array med sidnummer för att generera förhandsgranskningar. |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | Hämtar eller anger formatet för förhandsgranskningsbilden. |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | Hämtar eller anger en instans av delegaten för slutförande av sidförhandsgranskning. |
| [Resolution](../../groupdocs.watermark.options.diagram/diagrampreviewoptions/resolution) { get; set; } | Hämtar eller anger upplösningen för de genererade bilderna, i punkter per tum. |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | Hämtar eller anger sidans förhandsgranskningsbredd. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [DefaultResolution](../../groupdocs.watermark.options.diagram/diagrampreviewoptions/defaultresolution) | Standardupplösning i punkter per tum. |

### Se även

* class [PreviewOptions](../../groupdocs.watermark.options/previewoptions)
* namespace [GroupDocs.Watermark.Options.Diagram](../../groupdocs.watermark.options.diagram)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
