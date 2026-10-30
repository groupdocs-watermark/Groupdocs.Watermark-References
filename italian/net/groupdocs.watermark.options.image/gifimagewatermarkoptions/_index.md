---
title: "GifImageWatermarkOptions"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta le opzioni di aggiunta della filigrana quando si aggiunge la filigrana a un'immagine GIF."
type: docs
weight: 1830
url: /it/net/groupdocs.watermark.options.image/gifimagewatermarkoptions/
---
## GifImageWatermarkOptions class

Rappresenta le opzioni di aggiunta della filigrana quando si aggiunge la filigrana a un'immagine GIF.

```csharp
public sealed class GifImageWatermarkOptions : MultiframeImageWatermarkOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [GifImageWatermarkOptions](gifimagewatermarkoptions#constructor)() | Inizializza una nuova istanza della classe [`GifImageWatermarkOptions`](../gifimagewatermarkoptions). |
| [GifImageWatermarkOptions](gifimagewatermarkoptions#constructor_1)(int) | Inizializza una nuova istanza della classe [`GifImageWatermarkOptions`](../gifimagewatermarkoptions) con un indice specificato di un fotogramma. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [FrameIndex](../../groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frameindex) { get; set; } | Ottiene o imposta l'indice del fotogramma su cui aggiungere la filigrana. |

### Osservazioni

**Learn more:**

* [Add watermarks to images](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### Esempi

Aggiungi una filigrana a un fotogramma particolare dell'immagine GIF.

```csharp
GifImageLoadOptions loadOptions = new GifImageLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\test.gif", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));

    GifImageWatermarkOptions options = new GifImageWatermarkOptions();
    options.FrameIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Vedi anche

* class [MultiframeImageWatermarkOptions](../multiframeimagewatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Image](../../groupdocs.watermark.options.image)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
