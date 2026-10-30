---
title: "PresentationWatermarkableImage"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta un'immagine all'interno di un documento PowerPoint."
type: docs
weight: 1090
url: /it/net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/
---
## PresentationWatermarkableImage class

Rappresenta un'immagine all'interno di un documento PowerPoint.

```csharp
public class PresentationWatermarkableImage : WatermarkableImage
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PresentationWatermarkableImage](presentationwatermarkableimage)(byte[]) | Inizializza una nuova istanza della classe [`PresentationWatermarkableImage`](../presentationwatermarkableimage) utilizzando i dati immagine specificati. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Height](../../groupdocs.watermark.contents.image/watermarkableimage/height) { get; } | Ottiene l'altezza di questo [`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) in pixel. |
| [Width](../../groupdocs.watermark.contents.image/watermarkableimage/width) { get; } | Ottiene la larghezza di questo [`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) in pixel. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.image/watermarkableimage/add)(Watermark) | Aggiunge una filigrana a questo [`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage). Questo metodo presume che lo spostamento e le dimensioni della filigrana siano misurati in pixel (se sono assegnati). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Trova tutte le immagini nel contenuto. La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Trova le immagini secondo i criteri di ricerca specificati. La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [GetBytes](../../groupdocs.watermark.contents.image/watermarkableimage/getbytes)() | Ottiene l'immagine come array di byte. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Trova tutte le possibili filigrane nel contenuto. La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Trova possibili filigrane in base ai criteri di ricerca specificati. La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Vedi anche

* class [WatermarkableImage](../../groupdocs.watermark.contents.image/watermarkableimage)
* namespace [GroupDocs.Watermark.Contents.Presentation](../../groupdocs.watermark.contents.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
