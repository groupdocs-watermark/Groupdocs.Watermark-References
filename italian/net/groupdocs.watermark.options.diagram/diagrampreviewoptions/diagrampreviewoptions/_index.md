---
title: "DiagramPreviewOptions"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Inizializza una nuova istanza della classe DiagramPreviewOptionsgroupdocs.watermark.options.diagram/diagrampreviewoptions facendo chiudere lo stream di output."
type: docs
weight: 10
url: /it/net/groupdocs.watermark.options.diagram/diagrampreviewoptions/diagrampreviewoptions/
---
## DiagramPreviewOptions(CreatePageStream) {#constructor}

Inizializza una nuova istanza della classe [`DiagramPreviewOptions`](../../diagrampreviewoptions) facendo chiudere lo stream di output.

```csharp
public DiagramPreviewOptions(CreatePageStream createPageStream)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Crea uno stream per un'anteprima di pagina specifica. |

### Vedi anche

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [DiagramPreviewOptions](../../diagrampreviewoptions)
* namespace [GroupDocs.Watermark.Options.Diagram](../../../groupdocs.watermark.options.diagram)
* assembly [GroupDocs.Watermark](../../../)

---

## DiagramPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Inizializza una nuova istanza della classe [`DiagramPreviewOptions`](../../diagrampreviewoptions) facendo restituire lo stream di output al client per un uso successivo.

```csharp
public DiagramPreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Crea uno stream per un'anteprima di pagina specifica. |
| releasePageStream | ReleasePageStream | Notifica che la generazione dell'anteprima di pagina è completata e ottiene lo stream di output. |

### Vedi anche

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [DiagramPreviewOptions](../../diagrampreviewoptions)
* namespace [GroupDocs.Watermark.Options.Diagram](../../../groupdocs.watermark.options.diagram)
* assembly [GroupDocs.Watermark](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
