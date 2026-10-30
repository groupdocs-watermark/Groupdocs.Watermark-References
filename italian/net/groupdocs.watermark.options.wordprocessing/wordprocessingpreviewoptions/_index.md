---
title: "WordProcessingPreviewOptions"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Fornisce opzioni per impostare requisiti e delegati di stream per la generazione dell'anteprima di un documento WordProcessing."
type: docs
weight: 2360
url: /it/net/groupdocs.watermark.options.wordprocessing/wordprocessingpreviewoptions/
---
## WordProcessingPreviewOptions class

Fornisce opzioni per impostare requisiti e delegati di stream per la generazione dell'anteprima di un documento WordProcessing.

```csharp
public class WordProcessingPreviewOptions : PreviewOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [WordProcessingPreviewOptions](wordprocessingpreviewoptions#constructor)(CreatePageStream) | Inizializza una nuova istanza della classe [`WordProcessingPreviewOptions`](../wordprocessingpreviewoptions) facendo chiudere lo stream di output. |
| [WordProcessingPreviewOptions](wordprocessingpreviewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Inizializza una nuova istanza della classe [`WordProcessingPreviewOptions`](../wordprocessingpreviewoptions) facendo restituire lo stream di output al client per un uso successivo. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | Ottiene o imposta un'istanza del delegato di creazione del flusso di pagina. |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | Ottiene o imposta l'altezza dell'anteprima della pagina. |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | Ottiene o imposta un array di numeri di pagina per generare le anteprime. |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | Ottiene o imposta il formato dell'immagine di anteprima. |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | Ottiene o imposta un'istanza del delegato di completamento dell'anteprima della pagina. |
| [Resolution](../../groupdocs.watermark.options.wordprocessing/wordprocessingpreviewoptions/resolution) { get; set; } | Ottiene o imposta la risoluzione per le immagini generate, in punti per pollice. |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | Ottiene o imposta la larghezza dell'anteprima della pagina. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [DefaultResolution](../../groupdocs.watermark.options.wordprocessing/wordprocessingpreviewoptions/defaultresolution) | Risoluzione predefinita in punti per pollice. |

### Vedi anche

* class [PreviewOptions](../../groupdocs.watermark.options/previewoptions)
* namespace [GroupDocs.Watermark.Options.WordProcessing](../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
