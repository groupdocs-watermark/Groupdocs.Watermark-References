---
title: "EmailPreviewOptions"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Inizializza una nuova istanza della classe EmailPreviewOptionsgroupdocs.watermark.options.email/emailpreviewoptions facendo chiudere lo stream di output."
type: docs
weight: 10
url: /it/net/groupdocs.watermark.options.email/emailpreviewoptions/emailpreviewoptions/
---
## EmailPreviewOptions(CreatePageStream) {#constructor}

Inizializza una nuova istanza della classe [`EmailPreviewOptions`](../../emailpreviewoptions) facendo chiudere lo stream di output.

```csharp
public EmailPreviewOptions(CreatePageStream createPageStream)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Crea uno stream per un'anteprima di pagina specifica. |

### Vedi anche

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [EmailPreviewOptions](../../emailpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Email](../../../groupdocs.watermark.options.email)
* assembly [GroupDocs.Watermark](../../../)

---

## EmailPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Inizializza una nuova istanza della classe [`EmailPreviewOptions`](../../emailpreviewoptions) facendo restituire lo stream di output al client per un uso successivo.

```csharp
public EmailPreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Crea uno stream per un'anteprima di pagina specifica. |
| releasePageStream | ReleasePageStream | Notifica che la generazione dell'anteprima di pagina è completata e ottiene lo stream di output. |

### Vedi anche

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [EmailPreviewOptions](../../emailpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Email](../../../groupdocs.watermark.options.email)
* assembly [GroupDocs.Watermark](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
