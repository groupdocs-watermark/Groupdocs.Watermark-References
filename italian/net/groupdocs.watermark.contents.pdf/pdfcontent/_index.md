---
title: "PdfContent"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta un documento pdf dove è possibile posizionare un watermark."
type: docs
weight: 660
url: /it/net/groupdocs.watermark.contents.pdf/pdfcontent/
---
## PdfContent class

Rappresenta un documento pdf dove è possibile posizionare un watermark.

```csharp
public class PdfContent : Content
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Attachments](../../groupdocs.watermark.contents.pdf/pdfcontent/attachments) { get; } | Ottiene la collezione di tutti gli allegati di questo [`PdfContent`](../pdfcontent). |
| [PageMarginType](../../groupdocs.watermark.contents.pdf/pdfcontent/pagemargintype) { get; set; } | Ottiene o imposta i margini della pagina pdf da utilizzare durante l'aggiunta della filigrana. |
| [Pages](../../groupdocs.watermark.contents.pdf/pdfcontent/pages) { get; } | Ottiene la collezione di tutte le pagine di questo [`PdfContent`](../pdfcontent). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Decrypt](../../groupdocs.watermark.contents.pdf/pdfcontent/decrypt)() | Decripta il contenuto. |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Elimina l'istanza corrente. |
| [Encrypt](../../groupdocs.watermark.contents.pdf/pdfcontent/encrypt#encrypt)(string) | Cifra il documento usando la stessa password per la password utente e la password proprietario. |
| [Encrypt](../../groupdocs.watermark.contents.pdf/pdfcontent/encrypt#encrypt_1)(string, string, PdfPermissions, PdfCryptoAlgorithm) | Cifra il contenuto. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Trova tutte le immagini nel contenuto. La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Trova le immagini secondo i criteri di ricerca specificati. La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Rasterize](../../groupdocs.watermark.contents.pdf/pdfcontent/rasterize)(int, int, PdfImageConversionFormat) | Converte tutte le pagine del contenuto in immagini. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Trova tutte le possibili filigrane nel contenuto. La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Trova possibili filigrane in base ai criteri di ricerca specificati. La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Osservazioni

**Learn more:**

* [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)
* [Existing objects in PDF document](https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+PDF+document)
* [Rasterize document or page](https://docs.groupdocs.com/display/watermarknet/Rasterize+document+or+page)
* [Watermarks in PDF document](https://docs.groupdocs.com/display/watermarknet/Watermarks+in+PDF+document)

### Vedi anche

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
