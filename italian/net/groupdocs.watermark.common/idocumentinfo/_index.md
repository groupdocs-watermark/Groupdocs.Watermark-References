---
title: "IDocumentInfo"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Definisce i metodi richiesti per ottenere le informazioni di base del documento."
type: docs
weight: 70
url: /it/net/groupdocs.watermark.common/idocumentinfo/
---
## IDocumentInfo interface

Definisce i metodi richiesti per ottenere le informazioni di base del documento.

```csharp
public interface IDocumentInfo
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [FileType](../../groupdocs.watermark.common/idocumentinfo/filetype) { get; } | Ottiene la descrizione del formato file. |
| [IsEncrypted](../../groupdocs.watermark.common/idocumentinfo/isencrypted) { get; } | Ottiene un valore che indica se il documento è crittografato e richiede una password per l'apertura. |
| [PageCount](../../groupdocs.watermark.common/idocumentinfo/pagecount) { get; } | Ottiene il conteggio totale delle pagine. |
| [Pages](../../groupdocs.watermark.common/idocumentinfo/pages) { get; } | Ottiene la raccolta delle descrizioni delle pagine del documento. |
| [Size](../../groupdocs.watermark.common/idocumentinfo/size) { get; } | Ottiene la dimensione del documento in byte. |

### Osservazioni

**Learn more**

* [Get document info](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### Esempi

Il seguente esempio dimostra come recuperare le informazioni generali del documento usando [`IDocumentInfo`](../idocumentinfo).

```csharp
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    IDocumentInfo docInfo = watermarker.GetDocumentInfo();
    Console.WriteLine("Document size: {0}", docInfo.Size);
    Console.WriteLine("Document format: {0}", docInfo.FileType.FileFormat);
    Console.WriteLine("Document contains {0} pages", docInfo.PageCount);
}
```

### Vedi anche

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
