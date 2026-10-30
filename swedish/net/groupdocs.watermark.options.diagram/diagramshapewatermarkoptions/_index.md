---
title: "DiagramShapeWatermarkOptions"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar alternativ för att lägga till vattenstämpel när en formvattenstämpel läggs till i ett Visio-dokument."
type: docs
weight: 1750
url: /sv/net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/
---
## DiagramShapeWatermarkOptions class

Representerar alternativ för att lägga till vattenstämpel när en formvattenstämpel läggs till i ett Visio-dokument.

```csharp
public sealed class DiagramShapeWatermarkOptions : DiagramWatermarkOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [DiagramShapeWatermarkOptions](diagramshapewatermarkoptions)() | Initierar en ny instans av klassen [`DiagramShapeWatermarkOptions`](../diagramshapewatermarkoptions). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [IsLocked](../../groupdocs.watermark.options.diagram/diagramwatermarkoptions/islocked) { get; set; } | Hämtar eller anger ett värde som indikerar om redigering av formen i Visio är förbjuden. |
| [PlacementType](../../groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/placementtype) { get; set; } | Hämtar eller anger ett värde som specificerar på vilka sidor en vattenstämpel ska läggas till. |

### Anmärkningar

**Learn more:**

* [Add watermarks to diagram documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents)

### Exempel

Lägg till skyddad vattenstämpel på alla sidor i Visio-dokumentet.

```csharp
DiagramLoadOptions loadOptions = new DiagramLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.vsdx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));

    DiagramShapeWatermarkOptions options = new DiagramShapeWatermarkOptions();
    options.IsLocked = true;
    options.PlacementType = DiagramWatermarkPlacementType.AllPages; // default

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Se även

* class [DiagramWatermarkOptions](../diagramwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Diagram](../../groupdocs.watermark.options.diagram)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
