---
title: "DiagramPageWatermarkOptions"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar alternativ för att lägga till vattenstämpel när en formvattenstämpel läggs till på en specifik sida i ett Visio-dokument."
type: docs
weight: 1720
url: /sv/net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/
---
## DiagramPageWatermarkOptions class

Representerar alternativ för att lägga till vattenstämpel när en formvattenstämpel läggs till på en specifik sida i ett Visio-dokument.

```csharp
public sealed class DiagramPageWatermarkOptions : DiagramWatermarkOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [DiagramPageWatermarkOptions](diagrampagewatermarkoptions)() | Initierar en ny instans av klassen [`DiagramPageWatermarkOptions`](../diagrampagewatermarkoptions). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [IsLocked](../../groupdocs.watermark.options.diagram/diagramwatermarkoptions/islocked) { get; set; } | Hämtar eller anger ett värde som indikerar om redigering av formen i Visio är förbjuden. |
| [PageIndex](../../groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/pageindex) { get; set; } | Hämtar eller anger sidindexet att lägga till vattenstämpeln på. |

### Anmärkningar

**Learn more:**

* [Add watermarks to diagram documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents)

### Exempel

Lägg till en skyddad vattenstämpel på den första sidan i ett Visio-dokument.

```csharp
DiagramLoadOptions loadOptions = new DiagramLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.vsdx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));

    DiagramPageWatermarkOptions options = new DiagramPageWatermarkOptions();
    options.IsLocked = true;
    options.PageIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Se även

* class [DiagramWatermarkOptions](../diagramwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Diagram](../../groupdocs.watermark.options.diagram)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
