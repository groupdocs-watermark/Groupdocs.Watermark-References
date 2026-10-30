---
title: "DiagramShapeWatermarkOptions"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta le opzioni di aggiunta della filigrana quando si aggiunge una filigrana di forma a un documento Visio."
type: docs
weight: 1750
url: /it/net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/
---
## DiagramShapeWatermarkOptions class

Rappresenta le opzioni di aggiunta della filigrana quando si aggiunge una filigrana di forma a un documento Visio.

```csharp
public sealed class DiagramShapeWatermarkOptions : DiagramWatermarkOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [DiagramShapeWatermarkOptions](diagramshapewatermarkoptions)() | Inizializza una nuova istanza della classe [`DiagramShapeWatermarkOptions`](../diagramshapewatermarkoptions). |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [IsLocked](../../groupdocs.watermark.options.diagram/diagramwatermarkoptions/islocked) { get; set; } | Ottiene o imposta un valore che indica se la modifica della forma in Visio è vietata. |
| [PlacementType](../../groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/placementtype) { get; set; } | Ottiene o imposta un valore che specifica a quali pagine deve essere aggiunta una filigrana. |

### Osservazioni

**Learn more:**

* [Add watermarks to diagram documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents)

### Esempi

Aggiungi una filigrana protetta a tutte le pagine del documento Visio.

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

### Vedi anche

* class [DiagramWatermarkOptions](../diagramwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Diagram](../../groupdocs.watermark.options.diagram)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
