---
title: "TiffImageWatermarkOptions"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta le opzioni di aggiunta della filigrana quando si aggiunge una filigrana a un'immagine TIFF."
type: docs
weight: 1900
url: /it/net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/
---
## TiffImageWatermarkOptions class

Rappresenta le opzioni di aggiunta della filigrana quando si aggiunge una filigrana a un'immagine TIFF.

```csharp
public sealed class TiffImageWatermarkOptions : MultiframeImageWatermarkOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TiffImageWatermarkOptions](tiffimagewatermarkoptions#constructor)() | Inizializza una nuova istanza della classe [`TiffImageWatermarkOptions`](../tiffimagewatermarkoptions). |
| [TiffImageWatermarkOptions](tiffimagewatermarkoptions#constructor_1)(int) | Inizializza una nuova istanza della classe [`TiffImageWatermarkOptions`](../tiffimagewatermarkoptions) con un indice specificato del fotogramma. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [FrameIndex](../../groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frameindex) { get; set; } | Ottiene o imposta l'indice del fotogramma su cui aggiungere la filigrana. |

### Osservazioni

**Learn more:**

* [Add watermarks to images](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### Esempi

Aggiungi una filigrana a un fotogramma particolare dell'immagine TIFF.

```csharp
TiffImageLoadOptions loadOptions = new TiffImageLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\test.tiff", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));

    TiffImageWatermarkOptions options = new TiffImageWatermarkOptions();
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
