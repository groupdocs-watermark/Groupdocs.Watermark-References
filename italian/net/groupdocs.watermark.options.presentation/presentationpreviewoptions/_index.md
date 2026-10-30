---
title: "PresentationPreviewOptions"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Fornisce opzioni per impostare requisiti e delegati di stream per la generazione dell'anteprima di un documento Presentation."
type: docs
weight: 2030
url: /it/net/groupdocs.watermark.options.presentation/presentationpreviewoptions/
---
## PresentationPreviewOptions class

Fornisce opzioni per impostare requisiti e delegati di stream per la generazione dell'anteprima di un documento Presentation.

```csharp
public class PresentationPreviewOptions : PreviewOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PresentationPreviewOptions](presentationpreviewoptions#constructor)(CreatePageStream) | Inizializza una nuova istanza della classe [`PresentationPreviewOptions`](../presentationpreviewoptions) facendo chiudere lo stream di output. |
| [PresentationPreviewOptions](presentationpreviewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Inizializza una nuova istanza della classe [`PresentationPreviewOptions`](../presentationpreviewoptions) facendo restituire lo stream di output al client per un uso successivo. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | Ottiene o imposta un'istanza del delegato di creazione del flusso di pagina. |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | Ottiene o imposta l'altezza dell'anteprima della pagina. |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | Ottiene o imposta un array di numeri di pagina per generare le anteprime. |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | Ottiene o imposta il formato dell'immagine di anteprima. |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | Ottiene o imposta un'istanza del delegato di completamento dell'anteprima della pagina. |
| [Resolution](../../groupdocs.watermark.options.presentation/presentationpreviewoptions/resolution) { get; set; } | Ottiene o imposta la risoluzione per le immagini generate, in punti per pollice. |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | Ottiene o imposta la larghezza dell'anteprima della pagina. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [DefaultResolution](../../groupdocs.watermark.options.presentation/presentationpreviewoptions/defaultresolution) | Risoluzione predefinita in punti per pollice. |

### Vedi anche

* class [PreviewOptions](../../groupdocs.watermark.options/previewoptions)
* namespace [GroupDocs.Watermark.Options.Presentation](../../groupdocs.watermark.options.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
