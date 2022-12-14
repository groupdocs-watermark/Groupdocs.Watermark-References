---
title: DiagramPreviewOptions
second_title: Riferimento API GroupDocs.Watermark per .NET
description: Fornisce opzioni per impostare i requisiti e trasmettere i delegati per la generazione dellanteprima del documento Diagramma.
type: docs
weight: 1660
url: /it/net/groupdocs.watermark.options.diagram/diagrampreviewoptions/
---
## DiagramPreviewOptions class

Fornisce opzioni per impostare i requisiti e trasmettere i delegati per la generazione dell'anteprima del documento Diagramma.

```csharp
public class DiagramPreviewOptions : PreviewOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [DiagramPreviewOptions](diagrampreviewoptions#constructor)(CreatePageStream) | Inizializza una nuova istanza di[`DiagramPreviewOptions`](../diagrampreviewoptions) classe che causa la chiusura del flusso di output. |
| [DiagramPreviewOptions](diagrampreviewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Inizializza una nuova istanza di[`DiagramPreviewOptions`](../diagrampreviewoptions) class che causa la restituzione del flusso di output al client per un ulteriore utilizzo. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | Ottiene o imposta un'istanza del delegato per la creazione del flusso di pagine. |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | Ottiene o imposta l'altezza dell'anteprima della pagina. |
| [HighQualityRendering](../../groupdocs.watermark.options.diagram/diagrampreviewoptions/highqualityrendering) { get; set; } | Ottiene o imposta il flag per il rendering di alta qualità. |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | Ottiene o imposta un array di numeri di pagina per generare anteprime. |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | Ottiene o imposta il formato dell'immagine di anteprima. |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | Ottiene o imposta un'istanza del delegato di completamento dell'anteprima della pagina. |
| [Resolution](../../groupdocs.watermark.options.diagram/diagrampreviewoptions/resolution) { get; set; } | Ottiene o imposta la risoluzione per le immagini generate, in punti per pollice. |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | Ottiene o imposta la larghezza dell'anteprima della pagina. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [DefaultResolution](../../groupdocs.watermark.options.diagram/diagrampreviewoptions/defaultresolution) | Risoluzione predefinita in punti per pollice. |

### Guarda anche

* class [PreviewOptions](../../groupdocs.watermark.options/previewoptions)
* spazio dei nomi [GroupDocs.Watermark.Options.Diagram](../../groupdocs.watermark.options.diagram)
* assemblea [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
