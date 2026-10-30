---
title: "SearchableObjects"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Ottiene o imposta gli oggetti di contenuto da includere in una ricerca di watermark."
type: docs
weight: 20
url: /it/net/groupdocs.watermark/watermarker/searchableobjects/
---
## Watermarker.SearchableObjects property

Ottiene o imposta gli oggetti di contenuto da includere in una ricerca di watermark.

```csharp
public SearchableObjects SearchableObjects { get; set; }
```

### Property Value

Gli oggetti da includere in una ricerca di filigrane.

### Osservazioni

Questa proprietà specifica anche gli oggetti di contenuto utilizzati nella ricerca di immagini. Per ulteriori informazioni vedere i metodi [`Search`](../search) e [`GetImages`](../getimages).

Maggiori informazioni sulla ricerca di filigrane: [Ricerca di filigrane](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Esempi

Rimuovi tutti gli XObject e gli Artifact da un documento PDF.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf"))
{
    // Specifica che devono essere cercati solo gli XObject e gli Artifact.
    watermarker.SearchableObjects.PdfSearchableObjects
        = PdfSearchableObjects.XObjects | PdfSearchableObjects.Artifacts; 

    PossibleWatermarkCollection watermarks = watermarker.Search();

    // Rimuovi tutti gli oggetti trovati.
    watermarks.Clear();

    // Salva le modifiche.
    watermarker.Save();
}
```

### Vedi anche

* class [SearchableObjects](../../../groupdocs.watermark.search.objects/searchableobjects)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
