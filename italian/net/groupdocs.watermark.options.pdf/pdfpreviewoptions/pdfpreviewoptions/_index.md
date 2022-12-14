---
title: PdfPreviewOptions
second_title: Riferimento API GroupDocs.Watermark per .NET
description: Inizializza una nuova istanza diPdfPreviewOptionsgroupdocs.watermark.options.pdf/pdfpreviewoptions classe che causa la chiusura del flusso di output.
type: docs
weight: 10
url: /it/net/groupdocs.watermark.options.pdf/pdfpreviewoptions/pdfpreviewoptions/
---
## PdfPreviewOptions(CreatePageStream) {#constructor}

Inizializza una nuova istanza di[`PdfPreviewOptions`](../../pdfpreviewoptions) classe che causa la chiusura del flusso di output.

```csharp
public PdfPreviewOptions(CreatePageStream createPageStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Crea un flusso per un'anteprima di pagina specifica. |

### Guarda anche

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [PdfPreviewOptions](../../pdfpreviewoptions)
* spazio dei nomi [GroupDocs.Watermark.Options.Pdf](../../pdfpreviewoptions)
* assemblea [GroupDocs.Watermark](../../../)

---

## PdfPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Inizializza una nuova istanza di[`PdfPreviewOptions`](../../pdfpreviewoptions) class che causa la restituzione del flusso di output al client per un ulteriore utilizzo.

```csharp
public PdfPreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Crea un flusso per un'anteprima di pagina specifica. |
| releasePageStream | ReleasePageStream | Notifica che la generazione dell'anteprima della pagina è terminata e ottiene il flusso di output. |

### Guarda anche

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [PdfPreviewOptions](../../pdfpreviewoptions)
* spazio dei nomi [GroupDocs.Watermark.Options.Pdf](../../pdfpreviewoptions)
* assemblea [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
