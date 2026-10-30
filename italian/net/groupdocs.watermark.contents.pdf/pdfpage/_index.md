---
title: "PdfPage"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta la pagina di un documento pdf."
type: docs
weight: 730
url: /it/net/groupdocs.watermark.contents.pdf/pdfpage/
---
## PdfPage class

Rappresenta la pagina di un documento pdf.

```csharp
public class PdfPage : ContentPart
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Annotations](../../groupdocs.watermark.contents.pdf/pdfpage/annotations) { get; } | Ottiene la collezione di tutte le annotazioni di questo [`PdfPage`](../pdfpage). |
| [Artifacts](../../groupdocs.watermark.contents.pdf/pdfpage/artifacts) { get; } | Ottiene la collezione di tutti gli artefatti di questo [`PdfPage`](../pdfpage). |
| [Height](../../groupdocs.watermark.contents.pdf/pdfpage/height) { get; } | Ottiene l'altezza di questo [`PdfPage`](../pdfpage) in punti. |
| [Width](../../groupdocs.watermark.contents.pdf/pdfpage/width) { get; } | Ottiene la larghezza di questo [`PdfPage`](../pdfpage) in punti. |
| [XObjects](../../groupdocs.watermark.contents.pdf/pdfpage/xobjects) { get; } | Ottiene la collezione di tutti gli XObject di questo [`PdfPage`](../pdfpage). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Trova tutte le immagini nel contenuto. La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Trova le immagini secondo i criteri di ricerca specificati. La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| virtual [Rasterize](../../groupdocs.watermark.contents.pdf/pdfpage/rasterize)(int, int, PdfImageConversionFormat) | Converte il contenuto della pagina in un'immagine. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Trova tutte le possibili filigrane nel contenuto. La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Trova possibili filigrane in base ai criteri di ricerca specificati. La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Vedi anche

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
