---
title: "WatermarkResult"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta il risultato dell'operazione di watermarking includendo dettagli come le dimensioni dei documenti, il tempo di elaborazione e il numero di watermark applicati."
type: docs
weight: 1670
url: /it/net/groupdocs.watermark.internal/watermarkresult/
---
## WatermarkResult class

Rappresenta il risultato dell'operazione di filigranatura, includendo dettagli come le dimensioni del documento, il tempo di elaborazione e il numero di filigrane applicate.

```csharp
public class WatermarkResult
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [WatermarkResult](watermarkresult#constructor)() | Inizializza una nuova istanza della classe [`WatermarkResult`](../watermarkresult). |
| [WatermarkResult](watermarkresult#constructor_1)(long, TimeSpan, long, int) | Inizializza una nuova istanza della classe [`WatermarkResult`](../watermarkresult) con valori specifici. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [FinalDocumentSize](../../groupdocs.watermark.internal/watermarkresult/finaldocumentsize) { get; } | Ottiene o imposta la dimensione del documento finale elaborato in byte. |
| [NumberWatermarksApplied](../../groupdocs.watermark.internal/watermarkresult/numberwatermarksapplied) { get; } | Ottiene o imposta il numero totale di watermark applicati al documento. |
| [ProcessingTime](../../groupdocs.watermark.internal/watermarkresult/processingtime) { get; } | Ottiene o imposta il tempo di elaborazione per l'operazione di watermarking. |
| [SourceDocumentSize](../../groupdocs.watermark.internal/watermarkresult/sourcedocumentsize) { get; } | Ottiene o imposta la dimensione del documento sorgente in byte. |

### Vedi anche

* namespace [GroupDocs.Watermark.Internal](../../groupdocs.watermark.internal)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
