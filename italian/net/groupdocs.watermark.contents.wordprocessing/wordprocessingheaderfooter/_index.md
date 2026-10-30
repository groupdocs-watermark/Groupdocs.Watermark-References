---
title: "WordProcessingHeaderFooter"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta un'intestazione/piè di pagina in un documento Word."
type: docs
weight: 1360
url: /it/net/groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfooter/
---
## WordProcessingHeaderFooter class

Rappresenta un'intestazione/piè di pagina in un documento Word.

```csharp
public class WordProcessingHeaderFooter : ContentPart
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [HeaderFooterType](../../groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfooter/headerfootertype) { get; } | Ottiene il tipo di questo [`WordProcessingHeaderFooter`](../wordprocessingheaderfooter). |
| [IsLinkedToPrevious](../../groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfooter/islinkedtoprevious) { get; set; } | Ottiene o imposta un valore che indica se questa intestazione/piè di pagina è collegata all'intestazione/piè di pagina corrispondente nella sezione precedente. |
| [Section](../../groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfooter/section) { get; } | Ottiene la sezione padre di questo [`WordProcessingHeaderFooter`](../wordprocessingheaderfooter). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Trova tutte le immagini nel contenuto. La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Trova le immagini secondo i criteri di ricerca specificati. La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Trova tutte le possibili filigrane nel contenuto. La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Trova possibili filigrane in base ai criteri di ricerca specificati. La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Vedi anche

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* namespace [GroupDocs.Watermark.Contents.WordProcessing](../../groupdocs.watermark.contents.wordprocessing)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
