---
title: "PreviewOptions"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Tillhandahåller alternativ för att ange krav och strömdelegeringar för förhandsgranskning."
type: docs
weight: 2140
url: /sv/net/groupdocs.watermark.options/previewoptions/
---
## PreviewOptions class

Tillhandahåller alternativ för att ange krav och strömdelegeringar för förhandsgranskning.

```csharp
public class PreviewOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PreviewOptions](previewoptions#constructor)(CreatePageStream) | Initierar en ny instans av klassen [`PreviewOptions`](../previewoptions) som gör att utdataströmmen stängs. |
| [PreviewOptions](previewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Initierar en ny instans av klassen [`PreviewOptions`](../previewoptions) som gör att utdataströmmen returneras till klienten för vidare användning. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | Hämtar eller anger en instans av delegaten för skapande av sidström. |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | Hämtar eller anger sidans förhandsgranskningshöjd. |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | Hämtar eller anger en array med sidnummer för att generera förhandsgranskningar. |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | Hämtar eller anger formatet för förhandsgranskningsbilden. |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | Hämtar eller anger en instans av delegaten för slutförande av sidförhandsgranskning. |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | Hämtar eller anger sidans förhandsgranskningsbredd. |

### Se även

* namespace [GroupDocs.Watermark.Options](../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
