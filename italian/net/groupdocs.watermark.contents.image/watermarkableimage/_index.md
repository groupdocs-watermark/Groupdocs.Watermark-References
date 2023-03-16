---
title: WatermarkableImage
second_title: Riferimento API GroupDocs.Watermark per .NET
description: Rappresenta unimmagine allinterno di un documento.
type: docs
weight: 420
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
| [Height](../../groupdocs.watermark.contents.image/watermarkableimage/height) { get; } | Ottiene l'altezza di questo[`WatermarkableImage`](../watermarkableimage) in pixel. |
| [Width](../../groupdocs.watermark.contents.image/watermarkableimage/width) { get; } | Ottiene la larghezza di this[`WatermarkableImage`](../watermarkableimage) in pixel. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.image/watermarkableimage/add)(Watermark) | Aggiunge una filigrana a questo[`WatermarkableImage`](../watermarkableimage) . Questo metodo presuppone che l'offset e la dimensione della filigrana siano misurati in pixel (se assegnati). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Trova tutte le immagini nel contenuto. La ricerca viene condotta negli oggetti specificati in[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Trova le immagini in base ai criteri di ricerca specificati. La ricerca viene eseguita negli oggetti specificati in[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [GetBytes](../../groupdocs.watermark.contents.image/watermarkableimage/getbytes)() | Ottiene l'immagine come array di byte. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Trova tutte le possibili filigrane nel contenuto. La ricerca viene condotta negli oggetti specificati in[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Trova filigrane possibili in base ai criteri di ricerca specificati. La ricerca viene eseguita negli oggetti specificati in[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |

### Osservazioni

**Saperne di più:**

* [Aggiunta di filigrana alle immagini all'interno di un documento](https://docs.groupdocs.com/display/watermarknet/Adding+watermark+to+images+inside+a+document)

### Esempi

Aggiungi filigrana a tutte le immagini all'interno di un documento di qualsiasi tipo supportato.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    // Inizializza il testo o la filigrana dell'immagine.
    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));

    // Trova tutte le immagini nel contenuto.
    WatermarkableImageCollection images = watermarker.GetImages();

    // Aggiungi filigrana.
    foreach (WatermarkableImage watermarkableImage in images)
    {
        watermarkableImage.Add(watermark);
    }

    // Salvare le modifiche.
    watermarker.Save(@"D:\output.doc");
}
```

### Guarda anche

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* spazio dei nomi [GroupDocs.Watermark.Contents.Image](../../groupdocs.watermark.contents.image)
* assemblea [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->