---
title: "DiagramShapeWatermarkOptions"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Stelt watermerk-toevoegopties voor wanneer een vormwatermerk wordt toegevoegd aan een Visio-document voor."
type: docs
weight: 1750
url: /nl/net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/
---
## DiagramShapeWatermarkOptions class

Stelt watermerk-toevoegopties voor wanneer een vormwatermerk wordt toegevoegd aan een Visio-document voor.

```csharp
public sealed class DiagramShapeWatermarkOptions : DiagramWatermarkOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [DiagramShapeWatermarkOptions](diagramshapewatermarkoptions)() | Initialiseert een nieuw exemplaar van de klasse [`DiagramShapeWatermarkOptions`](../diagramshapewatermarkoptions). |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [IsLocked](../../groupdocs.watermark.options.diagram/diagramwatermarkoptions/islocked) { get; set; } | Haalt een waarde op of stelt deze in die aangeeft of bewerken van de vorm in Visio verboden is. |
| [PlacementType](../../groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/placementtype) { get; set; } | Haalt een waarde op of stelt een waarde in die aangeeft op welke pagina's een watermerk moet worden toegevoegd. |

### Opmerkingen

**Learn more:**

* [Add watermarks to diagram documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents)

### Voorbeelden

Voeg een beschermd watermerk toe aan alle pagina's van het Visio‑document.

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

### Zie ook

* class [DiagramWatermarkOptions](../diagramwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Diagram](../../groupdocs.watermark.options.diagram)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
