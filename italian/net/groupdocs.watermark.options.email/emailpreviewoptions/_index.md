---
title: "EmailPreviewOptions"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Fornisce opzioni per impostare i requisiti e i delegati di flusso per la generazione dell'anteprima del documento Email."
type: docs
weight: 1780
url: /it/net/groupdocs.watermark.options.email/emailpreviewoptions/
---
## EmailPreviewOptions class

Fornisce opzioni per impostare i requisiti e i delegati di flusso per la generazione dell'anteprima del documento Email.

```csharp
public class EmailPreviewOptions : PreviewOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmailPreviewOptions](emailpreviewoptions#constructor)(CreatePageStream) | Inizializza una nuova istanza della classe [`EmailPreviewOptions`](../emailpreviewoptions) facendo chiudere il flusso di output. |
| [EmailPreviewOptions](emailpreviewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Inizializza una nuova istanza della classe [`EmailPreviewOptions`](../emailpreviewoptions) facendo restituire il flusso di output al client per un uso successivo. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | Ottiene o imposta un'istanza del delegato di creazione del flusso di pagina. |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | Ottiene o imposta l'altezza dell'anteprima della pagina. |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | Ottiene o imposta un array di numeri di pagina per generare le anteprime. |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | Ottiene o imposta il formato dell'immagine di anteprima. |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | Ottiene o imposta un'istanza del delegato di completamento dell'anteprima della pagina. |
| [Resolution](../../groupdocs.watermark.options.email/emailpreviewoptions/resolution) { get; set; } | Ottiene o imposta la risoluzione per le immagini generate, in punti per pollice. |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | Ottiene o imposta la larghezza dell'anteprima della pagina. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [DefaultResolution](../../groupdocs.watermark.options.email/emailpreviewoptions/defaultresolution) | Risoluzione predefinita in punti per pollice. |

### Vedi anche

* class [PreviewOptions](../../groupdocs.watermark.options/previewoptions)
* namespace [GroupDocs.Watermark.Options.Email](../../groupdocs.watermark.options.email)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
