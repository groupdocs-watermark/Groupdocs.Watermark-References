---
title: "WatermarkableImage"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta un'immagine all'interno di un documento."
type: docs
weight: 470
url: /it/net/groupdocs.watermark.contents.image/watermarkableimage/
---
## WatermarkableImage class

Rappresenta un'immagine all'interno di un documento.

```csharp
public abstract class WatermarkableImage : ContentPart
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Height](../../groupdocs.watermark.contents.image/watermarkableimage/height) { get; } | Ottiene l'altezza di questo [`WatermarkableImage`](../watermarkableimage) in pixel. |
| [Width](../../groupdocs.watermark.contents.image/watermarkableimage/width) { get; } | Ottiene la larghezza di questo [`WatermarkableImage`](../watermarkableimage) in pixel. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.image/watermarkableimage/add)(Watermark) | Aggiunge una filigrana a questo [`WatermarkableImage`](../watermarkableimage). Questo metodo assume che lo spostamento e le dimensioni della filigrana siano misurati in pixel (se sono assegnati). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Trova tutte le immagini nel contenuto. La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Trova le immagini secondo i criteri di ricerca specificati. La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [GetBytes](../../groupdocs.watermark.contents.image/watermarkableimage/getbytes)() | Ottiene l'immagine come array di byte. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Trova tutte le possibili filigrane nel contenuto. La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Trova possibili filigrane in base ai criteri di ricerca specificati. La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Osservazioni

**Learn more:**

* [Adding watermark to images inside a document](https://docs.groupdocs.com/display/watermarknet/Adding+watermark+to+images+inside+a+document)

### Esempi

Aggiungi la filigrana a tutte le immagini all'interno di un documento di qualsiasi tipo supportato.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    // Inizializza la filigrana di testo o immagine.
    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));

    // Trova tutte le immagini nel contenuto.
    WatermarkableImageCollection images = watermarker.GetImages();

    // Aggiungi filigrana.
    foreach (WatermarkableImage watermarkableImage in images)
    {
        watermarkableImage.Add(watermark);
    }

    // Salva le modifiche.
    watermarker.Save(@"D:\output.doc");
}
```

### Vedi anche

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* namespace [GroupDocs.Watermark.Contents.Image](../../groupdocs.watermark.contents.image)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
