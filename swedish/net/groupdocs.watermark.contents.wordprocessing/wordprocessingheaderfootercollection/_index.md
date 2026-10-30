---
title: "WordProcessingHeaderFooterCollection"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar en samling av sidhuvuden och sidfötter i ett Word-dokument."
type: docs
weight: 1370
url: /sv/net/groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfootercollection/
---
## WordProcessingHeaderFooterCollection class

Representerar en samling av sidhuvuden och sidfötter i ett Word-dokument.

```csharp
public class WordProcessingHeaderFooterCollection : ReadOnlyListBase<WordProcessingHeaderFooter>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Hämtar antalet element som finns i samlingen. |
| virtual [IsReadOnly](../../groupdocs.watermark.common/readonlylistbase-1/isreadonly) { get; } | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Hämtar elementet på det angivna indexet i samlingen. |
| [Item](../../groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfootercollection/item) { get; } | Hämtar sidhuvudet eller sidfoten av angiven typ. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(WordProcessingHeaderFooter) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(WordProcessingHeaderFooter) |  |
| [LinkToPrevious](../../groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfootercollection/linktoprevious)(bool) | Länkar eller avlänkar alla sidhuvuden och sidfötter till motsvarande sidhuvuden och sidfötter i föregående avsnitt. |

### Anmärkningar

Denna samling innehåller objekt av typen [`WordProcessingHeaderFooter`](../wordprocessingheaderfooter).

### Se även

* class [ReadOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/readonlylistbase-1)
* class [WordProcessingHeaderFooter](../wordprocessingheaderfooter)
* namespace [GroupDocs.Watermark.Contents.WordProcessing](../../groupdocs.watermark.contents.wordprocessing)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
