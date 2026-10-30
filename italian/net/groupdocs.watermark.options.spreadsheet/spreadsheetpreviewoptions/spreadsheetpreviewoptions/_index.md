---
title: "SpreadsheetPreviewOptions"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Inizializza una nuova istanza della classe SpreadsheetPreviewOptionsgroupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions facendo chiudere lo stream di output."
type: docs
weight: 10
url: /it/net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/spreadsheetpreviewoptions/
---
## SpreadsheetPreviewOptions(CreatePageStream) {#constructor}

Inizializza una nuova istanza della classe [`SpreadsheetPreviewOptions`](../../spreadsheetpreviewoptions) facendo chiudere lo stream di output.

```csharp
public SpreadsheetPreviewOptions(CreatePageStream createPageStream)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Crea uno stream per un'anteprima di pagina specifica. |

### Vedi anche

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [SpreadsheetPreviewOptions](../../spreadsheetpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../../)

---

## SpreadsheetPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Inizializza una nuova istanza della classe [`SpreadsheetPreviewOptions`](../../spreadsheetpreviewoptions) facendo restituire lo stream di output al client per un uso successivo.

```csharp
public SpreadsheetPreviewOptions(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Crea uno stream per un'anteprima di pagina specifica. |
| releasePageStream | ReleasePageStream | Notifica che la generazione dell'anteprima di pagina è completata e ottiene lo stream di output. |

### Vedi anche

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [SpreadsheetPreviewOptions](../../spreadsheetpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
