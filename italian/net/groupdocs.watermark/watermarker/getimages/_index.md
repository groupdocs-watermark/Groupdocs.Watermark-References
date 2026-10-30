---
title: "GetImages"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Trova le immagini secondo i criteri di ricerca specificati."
type: docs
weight: 80
url: /it/net/groupdocs.watermark/watermarker/getimages/
---
## GetImages(ImageSearchCriteria) {#getimages_1}

Trova le immagini secondo i criteri di ricerca specificati.

```csharp
public WatermarkableImageCollection GetImages(ImageSearchCriteria searchCriteria)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| searchCriteria | ImageSearchCriteria | I criteri di ricerca da utilizzare. |

### Valore di ritorno

La raccolta di immagini trovate.

### Osservazioni

La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../searchableobjects).

Scopri di più sulla ricerca delle filigrane [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Esempi

Rimuovi tutte le immagini simili al riferimento da un documento di qualsiasi tipo supportato.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageThumbnailSearchCriteria criteria = new ImageThumbnailSearchCriteria("reference.png");
    WatermarkableImageCollection images = watermarker.GetImages(criteria);
    images.Clear();
    watermarker.Save(@"D:\output.doc");
}
```

### Vedi anche

* class [WatermarkableImageCollection](../../../groupdocs.watermark.contents.image/watermarkableimagecollection)
* class [ImageSearchCriteria](../../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## GetImages() {#getimages}

Trova tutte le immagini nel documento.

```csharp
public WatermarkableImageCollection GetImages()
```

### Valore di ritorno

La raccolta di immagini trovate.

### Osservazioni

La ricerca viene eseguita negli oggetti specificati in [`SearchableObjects`](../searchableobjects).

Scopri di più sulla ricerca delle filigrane [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Esempi

Aggiungi una filigrana a tutte le immagini in un documento di qualsiasi tipo supportato.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    // Inizializza la filigrana di testo o immagine.
    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));

    // Trova tutte le immagini nel documento.
    WatermarkableImageCollection images = watermarker.GetImages();

    // Aggiungi filigrana.
    foreach (WatermarkableImage watermarkableImage in images)
    {
        watermarkableImage.AddWatermark(watermark);
    }

    // Salva le modifiche.
    watermarker.Save(@"D:\output.doc");
}
```

### Vedi anche

* class [WatermarkableImageCollection](../../../groupdocs.watermark.contents.image/watermarkableimagecollection)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
