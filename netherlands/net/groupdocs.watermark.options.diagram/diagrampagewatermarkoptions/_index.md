---
title: "DiagramPageWatermarkOptions"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Stelt watermerk-toevoegopties voor wanneer een vormwatermerk wordt toegevoegd aan een specifieke pagina van een Visio-document."
type: docs
weight: 1720
url: /nl/net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/
---
## DiagramPageWatermarkOptions class

Stelt watermerk-toevoegopties voor wanneer een vormwatermerk wordt toegevoegd aan een specifieke pagina van een Visio-document.

```csharp
public sealed class DiagramPageWatermarkOptions : DiagramWatermarkOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [DiagramPageWatermarkOptions](diagrampagewatermarkoptions)() | Initialiseert een nieuw exemplaar van de [`DiagramPageWatermarkOptions`](../diagrampagewatermarkoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [IsLocked](../../groupdocs.watermark.options.diagram/diagramwatermarkoptions/islocked) { get; set; } | Haalt een waarde op of stelt deze in die aangeeft of bewerken van de vorm in Visio verboden is. |
| [PageIndex](../../groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/pageindex) { get; set; } | Gets of sets het paginanummer waarop het watermerk moet worden toegevoegd. |

### Opmerkingen

**Learn more:**

* [Add watermarks to diagram documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents)

### Voorbeelden

Voeg een beschermd watermerk toe aan de eerste pagina van een Visio‑document.

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

### Zie ook

* class [DiagramWatermarkOptions](../diagramwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Diagram](../../groupdocs.watermark.options.diagram)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
