---
title: "MultiframeImageWatermarkOptions"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta le opzioni di aggiunta della filigrana quando si aggiunge una filigrana a un'immagine multiframe."
type: docs
weight: 1870
url: /it/net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/
---
## MultiframeImageWatermarkOptions class

Rappresenta le opzioni di aggiunta della filigrana quando si aggiunge una filigrana a un'immagine multi-frame.

```csharp
public class MultiframeImageWatermarkOptions : WatermarkOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MultiframeImageWatermarkOptions](multiframeimagewatermarkoptions#constructor)() | Inizializza una nuova istanza della classe [`MultiframeImageWatermarkOptions`](../multiframeimagewatermarkoptions). |
| [MultiframeImageWatermarkOptions](multiframeimagewatermarkoptions#constructor_1)(int) | Inizializza una nuova istanza della classe [`MultiframeImageWatermarkOptions`](../multiframeimagewatermarkoptions) con un indice specificato del fotogramma. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [FrameIndex](../../groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frameindex) { get; set; } | Ottiene o imposta l'indice del fotogramma su cui aggiungere la filigrana. |

### Osservazioni

**Learn more:**

* [Add watermarks to images](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### Esempi

Aggiungi la filigrana a un fotogramma specifico di un'immagine multi-frame.

```csharp
ImageLoadOptions loadOptions = new ImageLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\test.gif", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));

    MultiframeImageWatermarkOptions options = new MultiframeImageWatermarkOptions();
    options.FrameIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Vedi anche

* class [WatermarkOptions](../../groupdocs.watermark.options/watermarkoptions)
* namespace [GroupDocs.Watermark.Options.Image](../../groupdocs.watermark.options.image)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
