---
title: "WordProcessingPreviewOptions"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Inizializza una nuova istanza della classe WordProcessingPreviewOptionsgroupdocs.watermark.options.wordprocessing/wordprocessingpreviewoptions facendo chiudere lo stream di output."
type: docs
weight: 10
url: /it/net/groupdocs.watermark.options.wordprocessing/wordprocessingpreviewoptions/wordprocessingpreviewoptions/
---
## WordProcessingPreviewOptions(CreatePageStream) {#constructor}

Inizializza una nuova istanza della classe [`WordProcessingPreviewOptions`](../../wordprocessingpreviewoptions) facendo chiudere lo stream di output.

```csharp
public WordProcessingPreviewOptions(CreatePageStream createPageStream)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Crea uno stream per un'anteprima di pagina specifica. |

### Vedi anche

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [WordProcessingPreviewOptions](../../wordprocessingpreviewoptions)
* namespace [GroupDocs.Watermark.Options.WordProcessing](../../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../../)

---

## WordProcessingPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Inizializza una nuova istanza della classe [`WordProcessingPreviewOptions`](../../wordprocessingpreviewoptions) facendo restituire lo stream di output al client per un uso successivo.

```csharp
public WordProcessingPreviewOptions(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Crea uno stream per un'anteprima di pagina specifica. |
| releasePageStream | ReleasePageStream | Notifica che la generazione dell'anteprima di pagina è completata e ottiene lo stream di output. |

### Vedi anche

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [WordProcessingPreviewOptions](../../wordprocessingpreviewoptions)
* namespace [GroupDocs.Watermark.Options.WordProcessing](../../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
