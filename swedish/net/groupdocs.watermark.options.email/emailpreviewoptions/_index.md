---
title: "EmailPreviewOptions"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Tillhandahåller alternativ för att ange krav och strömdelegeringar för förhandsgranskning av e‑postdokument."
type: docs
weight: 1780
url: /sv/net/groupdocs.watermark.options.email/emailpreviewoptions/
---
## EmailPreviewOptions class

Tillhandahåller alternativ för att ange krav och strömdelegeringar för förhandsgranskning av e‑postdokument.

```csharp
public class EmailPreviewOptions : PreviewOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [EmailPreviewOptions](emailpreviewoptions#constructor)(CreatePageStream) | Initierar en ny instans av klassen [`EmailPreviewOptions`](../emailpreviewoptions) som stänger utdataströmmen. |
| [EmailPreviewOptions](emailpreviewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Initierar en ny instans av klassen [`EmailPreviewOptions`](../emailpreviewoptions) som returnerar utdataströmmen till klienten för vidare användning. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | Hämtar eller anger en instans av delegaten för skapande av sidström. |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | Hämtar eller anger sidans förhandsgranskningshöjd. |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | Hämtar eller anger en array med sidnummer för att generera förhandsgranskningar. |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | Hämtar eller anger formatet för förhandsgranskningsbilden. |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | Hämtar eller anger en instans av delegaten för slutförande av sidförhandsgranskning. |
| [Resolution](../../groupdocs.watermark.options.email/emailpreviewoptions/resolution) { get; set; } | Hämtar eller anger upplösningen för de genererade bilderna, i punkter per tum. |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | Hämtar eller anger sidans förhandsgranskningsbredd. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [DefaultResolution](../../groupdocs.watermark.options.email/emailpreviewoptions/defaultresolution) | Standardupplösning i punkter per tum. |

### Se även

* class [PreviewOptions](../../groupdocs.watermark.options/previewoptions)
* namespace [GroupDocs.Watermark.Options.Email](../../groupdocs.watermark.options.email)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
