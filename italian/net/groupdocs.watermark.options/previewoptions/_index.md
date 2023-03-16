---
title: PreviewOptions
second_title: Riferimento API GroupDocs.Watermark per .NET
description: Fornisce opzioni per impostare i requisiti e trasmettere i delegati per la generazione dellanteprima.
type: docs
weight: 2070
url: /it/net/groupdocs.watermark.options/previewoptions/
---
## PreviewOptions class

Fornisce opzioni per impostare i requisiti e trasmettere i delegati per la generazione dell'anteprima.

```csharp
public class PreviewOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PreviewOptions](previewoptions#constructor)(CreatePageStream) | Inizializza una nuova istanza di[`PreviewOptions`](../previewoptions) classe che causa la chiusura del flusso di output. |
| [PreviewOptions](previewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Inizializza una nuova istanza di[`PreviewOptions`](../previewoptions) class che causa la restituzione del flusso di output al client per un ulteriore utilizzo. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | Ottiene o imposta un'istanza del delegato per la creazione del flusso di pagine. |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | Ottiene o imposta l'altezza dell'anteprima della pagina. |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | Ottiene o imposta un array di numeri di pagina per generare anteprime. |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | Ottiene o imposta il formato dell'immagine di anteprima. |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | Ottiene o imposta un'istanza del delegato di completamento dell'anteprima della pagina. |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | Ottiene o imposta la larghezza dell'anteprima della pagina. |

### Guarda anche

* spazio dei nomi [GroupDocs.Watermark.Options](../../groupdocs.watermark.options)
* assemblea [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->