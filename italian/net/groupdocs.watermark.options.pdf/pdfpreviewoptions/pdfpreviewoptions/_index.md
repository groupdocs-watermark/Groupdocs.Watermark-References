---
title: "PdfPreviewOptions"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Inizializza una nuova istanza della classe PdfPreviewOptionsgroupdocs.watermark.options.pdf/pdfpreviewoptions facendo chiudere lo stream di output."
type: docs
weight: 10
url: /it/net/groupdocs.watermark.options.pdf/pdfpreviewoptions/pdfpreviewoptions/
---
## PdfPreviewOptions(CreatePageStream) {#constructor}

Inizializza una nuova istanza della classe [`PdfPreviewOptions`](../../pdfpreviewoptions) facendo chiudere lo stream di output.

```csharp
public PdfPreviewOptions(CreatePageStream createPageStream)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Crea uno stream per un'anteprima di pagina specifica. |

### Vedi anche

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [PdfPreviewOptions](../../pdfpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../../)

---

## PdfPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Inizializza una nuova istanza della classe [`PdfPreviewOptions`](../../pdfpreviewoptions) facendo restituire lo stream di output al client per un uso successivo.

```csharp
public PdfPreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Crea uno stream per un'anteprima di pagina specifica. |
| releasePageStream | ReleasePageStream | Notifica che la generazione dell'anteprima di pagina è completata e ottiene lo stream di output. |

### Vedi anche

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [PdfPreviewOptions](../../pdfpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
