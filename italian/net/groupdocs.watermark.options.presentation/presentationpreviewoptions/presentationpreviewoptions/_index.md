---
title: "PresentationPreviewOptions"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Inizializza una nuova istanza della classe PresentationPreviewOptionsgroupdocs.watermark.options.presentation/presentationpreviewoptions, causando la chiusura dello stream di output."
type: docs
weight: 10
url: /it/net/groupdocs.watermark.options.presentation/presentationpreviewoptions/presentationpreviewoptions/
---
## PresentationPreviewOptions(CreatePageStream) {#constructor}

Inizializza una nuova istanza della classe [`PresentationPreviewOptions`](../../presentationpreviewoptions) causando la chiusura dello stream di output.

```csharp
public PresentationPreviewOptions(CreatePageStream createPageStream)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Crea uno stream per un'anteprima di pagina specifica. |

### Vedi anche

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [PresentationPreviewOptions](../../presentationpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Presentation](../../../groupdocs.watermark.options.presentation)
* assembly [GroupDocs.Watermark](../../../)

---

## PresentationPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Inizializza una nuova istanza della classe [`PresentationPreviewOptions`](../../presentationpreviewoptions) facendo ritornare lo stream di output al client per ulteriori utilizzi.

```csharp
public PresentationPreviewOptions(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Crea uno stream per un'anteprima di pagina specifica. |
| releasePageStream | ReleasePageStream | Notifica che la generazione dell'anteprima di pagina è completata e ottiene lo stream di output. |

### Vedi anche

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [PresentationPreviewOptions](../../presentationpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Presentation](../../../groupdocs.watermark.options.presentation)
* assembly [GroupDocs.Watermark](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
