---
title: "GifImageContent"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta un'immagine gif in cui è possibile posizionare una filigrana."
type: docs
weight: 390
url: /it/net/groupdocs.watermark.contents.image/gifimagecontent/
---
## GifImageContent class

Rappresenta un'immagine gif in cui è possibile posizionare una filigrana.

```csharp
public sealed class GifImageContent : MultiframeImageContent
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Frames](../../groupdocs.watermark.contents.image/multiframeimagecontent/frames) { get; } | Ottiene la collezione di tutti i fotogrammi dell'immagine. |
| virtual [Height](../../groupdocs.watermark.contents.image/imagecontent/height) { get; } | Ottiene l'altezza di questo [`ImageContent`](../imagecontent) in pixel. |
| virtual [Width](../../groupdocs.watermark.contents.image/imagecontent/width) { get; } | Ottiene la larghezza di questo [`ImageContent`](../imagecontent) in pixel. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Elimina l'istanza corrente. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Trova tutte le immagini nel contenuto. La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Trova le immagini secondo i criteri di ricerca specificati. La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Trova tutte le possibili filigrane nel contenuto. La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Trova possibili filigrane in base ai criteri di ricerca specificati. La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Vedi anche

* class [MultiframeImageContent](../multiframeimagecontent)
* namespace [GroupDocs.Watermark.Contents.Image](../../groupdocs.watermark.contents.image)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
