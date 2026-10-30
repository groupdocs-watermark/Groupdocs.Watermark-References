---
title: "GetDocumentInfo"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Ottiene le informazioni sul formato del documento caricato."
type: docs
weight: 70
url: /it/net/groupdocs.watermark/watermarker/getdocumentinfo/
---
## Watermarker.GetDocumentInfo method

Ottiene le informazioni sul formato del documento caricato.

```csharp
public IDocumentInfo GetDocumentInfo()
```

### Valore di ritorno

L'istanza [`IDocumentInfo`](../../../groupdocs.watermark.common/idocumentinfo) che contiene le informazioni rilevate.

### Osservazioni

Maggiori informazioni sull'ottenimento delle informazioni del documento [Ottieni informazioni sul documento](https://docs.groupdocs.com/display/watermarknet/Get+document+info).

### Esempi

Ottieni informazioni su un documento di qualsiasi tipo supportato.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.ppt"))
{
    IDocumentInfo docInfo = watermarker.GetDocumentInfo();
    Console.WriteLine("Document size: {0}", docInfo.Size);
    Console.WriteLine("Document format: {0}", docInfo.FileType.FileFormat);
    Console.WriteLine("Document contains {0} pages", docInfo.PageCount);
}
```

### Vedi anche

* interface [IDocumentInfo](../../../groupdocs.watermark.common/idocumentinfo)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
