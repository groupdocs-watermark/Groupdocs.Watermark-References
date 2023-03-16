---
title: IDocumentInfo
second_title: Riferimento API GroupDocs.Watermark per .NET
description: Definisce i metodi richiesti per ottenere le informazioni di base sul documento.
type: docs
weight: 70
url: /it/net/groupdocs.watermark.common/idocumentinfo/
---
## IDocumentInfo interface

Definisce i metodi richiesti per ottenere le informazioni di base sul documento.

```csharp
public interface IDocumentInfo
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [FileType](../../groupdocs.watermark.common/idocumentinfo/filetype) { get; } | Ottiene la descrizione del formato del file. |
| [IsEncrypted](../../groupdocs.watermark.common/idocumentinfo/isencrypted) { get; } | Ottiene un valore che indica se il documento è crittografato e richiede una password per essere aperto. |
| [PageCount](../../groupdocs.watermark.common/idocumentinfo/pagecount) { get; } | Ottiene il conteggio totale delle pagine. |
| [Pages](../../groupdocs.watermark.common/idocumentinfo/pages) { get; } | Ottiene la raccolta delle descrizioni delle pagine del documento. |
| [Size](../../groupdocs.watermark.common/idocumentinfo/size) { get; } | Ottiene la dimensione del documento in byte. |

### Osservazioni

**Saperne di più**

* [Ottieni informazioni sul documento](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### Esempi

L'esempio seguente mostra come recuperare le informazioni generali sul documento utilizzando[`IDocumentInfo`](../idocumentinfo) .

```csharp
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    IDocumentInfo docInfo = watermarker.GetDocumentInfo();
    Console.WriteLine("Document size: {0}", docInfo.Size);
    Console.WriteLine("Document format: {0}", docInfo.FileType.FileFormat);
    Console.WriteLine("Document contains {0} pages", docInfo.PageCount);
}
```

### Guarda anche

* spazio dei nomi [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assemblea [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->