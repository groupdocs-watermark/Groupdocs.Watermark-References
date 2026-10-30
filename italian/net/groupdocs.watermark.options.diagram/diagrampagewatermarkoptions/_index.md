---
title: "DiagramPageWatermarkOptions"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta le opzioni di aggiunta della filigrana quando si aggiunge una filigrana di forma a una pagina specifica di un documento Visio."
type: docs
weight: 1720
url: /it/net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/
---
## DiagramPageWatermarkOptions class

Rappresenta le opzioni di aggiunta della filigrana quando si aggiunge una filigrana di forma a una pagina specifica di un documento Visio.

```csharp
public sealed class DiagramPageWatermarkOptions : DiagramWatermarkOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [DiagramPageWatermarkOptions](diagrampagewatermarkoptions)() | Inizializza una nuova istanza della classe [`DiagramPageWatermarkOptions`](../diagrampagewatermarkoptions). |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [IsLocked](../../groupdocs.watermark.options.diagram/diagramwatermarkoptions/islocked) { get; set; } | Ottiene o imposta un valore che indica se la modifica della forma in Visio è vietata. |
| [PageIndex](../../groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/pageindex) { get; set; } | Ottiene o imposta l'indice della pagina a cui aggiungere la filigrana. |

### Osservazioni

**Learn more:**

* [Add watermarks to diagram documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents)

### Esempi

Aggiungi una filigrana protetta alla prima pagina di un documento Visio.

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

### Vedi anche

* class [DiagramWatermarkOptions](../diagramwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Diagram](../../groupdocs.watermark.options.diagram)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
