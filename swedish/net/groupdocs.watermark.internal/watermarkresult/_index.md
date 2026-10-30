---
title: "WatermarkResult"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar resultatet av vattenmärkningsoperationen inklusive detaljer såsom dokumentstorlekar, bearbetningstid och antalet tillämpade vattenmärken."
type: docs
weight: 1670
url: /sv/net/groupdocs.watermark.internal/watermarkresult/
---
## WatermarkResult class

Representerar resultatet av vattenstämplingsoperationen, inklusive detaljer såsom dokumentstorlekar, bearbetningstid och antalet tillämpade vattenstämplar.

```csharp
public class WatermarkResult
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [WatermarkResult](watermarkresult#constructor)() | Initierar en ny instans av klassen [`WatermarkResult`](../watermarkresult). |
| [WatermarkResult](watermarkresult#constructor_1)(long, TimeSpan, long, int) | Initierar en ny instans av klassen [`WatermarkResult`](../watermarkresult) med specifika värden. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [FinalDocumentSize](../../groupdocs.watermark.internal/watermarkresult/finaldocumentsize) { get; } | Hämtar eller anger storleken på det slutgiltiga bearbetade dokumentet i byte. |
| [NumberWatermarksApplied](../../groupdocs.watermark.internal/watermarkresult/numberwatermarksapplied) { get; } | Hämtar eller anger det totala antalet vattenstämplar som tillämpats på dokumentet. |
| [ProcessingTime](../../groupdocs.watermark.internal/watermarkresult/processingtime) { get; } | Hämtar eller anger bearbetningstiden för vattenstämplingsoperationen. |
| [SourceDocumentSize](../../groupdocs.watermark.internal/watermarkresult/sourcedocumentsize) { get; } | Hämtar eller anger storleken på källdokumentet i byte. |

### Se även

* namespace [GroupDocs.Watermark.Internal](../../groupdocs.watermark.internal)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
