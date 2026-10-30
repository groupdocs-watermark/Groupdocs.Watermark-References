---
title: "ReleasePageStream"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta un metodo che rilascia lo stream creato dal delegato CreatePageStream./createpagestream."
type: docs
weight: 2160
url: /it/net/groupdocs.watermark.options/releasepagestream/
---
## ReleasePageStream delegate

Rappresenta un metodo che rilascia lo stream creato dal delegato [`CreatePageStream`](../createpagestream).

```csharp
public delegate void ReleasePageStream(int pageNumber, Stream pageStream);
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| pageNumber | Int32 | Il numero di pagina di un'anteprima di pagina generata. |
| pageStream | Stream | Lo stream contenente l'anteprima di pagina generata. |

### Vedi anche

* namespace [GroupDocs.Watermark.Options](../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
