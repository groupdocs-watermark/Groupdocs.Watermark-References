---
title: EmailPreviewOptions
second_title: Riferimento API GroupDocs.Watermark per .NET
description: Fornisce opzioni per impostare i requisiti e trasmettere i delegati per la generazione dellanteprima del documento email.
type: docs
weight: 1710
url: /it/net/groupdocs.watermark.options.email/emailpreviewoptions/
---
## EmailPreviewOptions class

Fornisce opzioni per impostare i requisiti e trasmettere i delegati per la generazione dell'anteprima del documento e-mail.

```csharp
public class EmailPreviewOptions : PreviewOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmailPreviewOptions](emailpreviewoptions#constructor)(CreatePageStream) | Inizializza una nuova istanza di[`EmailPreviewOptions`](../emailpreviewoptions) classe che causa la chiusura del flusso di output. |
| [EmailPreviewOptions](emailpreviewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Inizializza una nuova istanza di[`EmailPreviewOptions`](../emailpreviewoptions) class che causa la restituzione del flusso di output al client per un ulteriore utilizzo. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | Ottiene o imposta un'istanza del delegato per la creazione del flusso di pagine. |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | Ottiene o imposta l'altezza dell'anteprima della pagina. |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | Ottiene o imposta un array di numeri di pagina per generare anteprime. |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | Ottiene o imposta il formato dell'immagine di anteprima. |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | Ottiene o imposta un'istanza del delegato di completamento dell'anteprima della pagina. |
| [Resolution](../../groupdocs.watermark.options.email/emailpreviewoptions/resolution) { get; set; } | Ottiene o imposta la risoluzione per le immagini generate, in punti per pollice. |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | Ottiene o imposta la larghezza dell'anteprima della pagina. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [DefaultResolution](../../groupdocs.watermark.options.email/emailpreviewoptions/defaultresolution) | Risoluzione predefinita in punti per pollice. |

### Guarda anche

* class [PreviewOptions](../../groupdocs.watermark.options/previewoptions)
* spazio dei nomi [GroupDocs.Watermark.Options.Email](../../groupdocs.watermark.options.email)
* assemblea [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
