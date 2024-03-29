---
title: ImageWatermark
second_title: Riferimento API GroupDocs.Watermark per .NET
description: Rappresenta una filigrana dellimmagine.
type: docs
weight: 3110
url: /it/net/groupdocs.watermark.watermarks/imagewatermark/
---
## ImageWatermark class

Rappresenta una filigrana dell'immagine.

```csharp
public sealed class ImageWatermark : Watermark, IDisposable
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ImageWatermark](imagewatermark#constructor)(Stream) | Inizializza una nuova istanza di[`ImageWatermark`](../imagewatermark) classe con un flusso specificato. |
| [ImageWatermark](imagewatermark#constructor_1)(string) | Inizializza una nuova istanza di[`ImageWatermark`](../imagewatermark) classe con un percorso di file specificato. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ConsiderParentMargins](../../groupdocs.watermark/watermark/considerparentmargins) { get; set; } | Ottiene o imposta un valore che indica se le dimensioni e le coordinate della filigrana vengono calcolate considerando i margini padre. |
| [Height](../../groupdocs.watermark/watermark/height) { get; set; } | Ottiene o imposta l'altezza desiderata di this[`Watermark`](../../groupdocs.watermark/watermark) . |
| [HorizontalAlignment](../../groupdocs.watermark/watermark/horizontalalignment) { get; set; } | Ottiene o imposta l'allineamento orizzontale di this[`Watermark`](../../groupdocs.watermark/watermark) . |
| [IsBackground](../../groupdocs.watermark/watermark/isbackground) { get; set; } | Ottiene o imposta un valore che indica se la filigrana deve essere posizionata sullo sfondo. |
| [Margins](../../groupdocs.watermark/watermark/margins) { get; set; } | Ottiene o imposta le impostazioni dei margini di this[`Watermark`](../../groupdocs.watermark/watermark) . |
| [Opacity](../../groupdocs.watermark/watermark/opacity) { get; set; } | Ottiene o imposta l'opacità di this[`Watermark`](../../groupdocs.watermark/watermark) . |
| [RotateAngle](../../groupdocs.watermark/watermark/rotateangle) { get; set; } | Ottiene o imposta l'angolo di rotazione di this[`Watermark`](../../groupdocs.watermark/watermark) in gradi. |
| [ScaleFactor](../../groupdocs.watermark/watermark/scalefactor) { get; set; } | Ottiene o imposta un valore che definisce in che modo la dimensione della filigrana dipende dalla dimensione principale. |
| [SizingType](../../groupdocs.watermark/watermark/sizingtype) { get; set; } | Ottiene o imposta un valore che specifica la dimensione della filigrana. |
| [VerticalAlignment](../../groupdocs.watermark/watermark/verticalalignment) { get; set; } | Ottiene o imposta l'allineamento verticale di this[`Watermark`](../../groupdocs.watermark/watermark) . |
| [Width](../../groupdocs.watermark/watermark/width) { get; set; } | Ottiene o imposta la larghezza desiderata di this[`Watermark`](../../groupdocs.watermark/watermark) . |
| [X](../../groupdocs.watermark/watermark/x) { get; set; } | Ottiene o imposta la coordinata x di this[`Watermark`](../../groupdocs.watermark/watermark) . |
| [Y](../../groupdocs.watermark/watermark/y) { get; set; } | Ottiene o imposta la coordinata y di this[`Watermark`](../../groupdocs.watermark/watermark) . |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../groupdocs.watermark.watermarks/imagewatermark/dispose)() | Elimina l'istanza corrente. |

### Osservazioni

**Saperne di più:**

* [Aggiunta di filigrane alle immagini](https://docs.groupdocs.com/display/watermarknet/Adding+image+watermarks)

### Esempi

Aggiungi filigrana immagine a un documento di qualsiasi tipo supportato.

```csharp
foreach (string filePath in Directory.GetFiles(@"C:\Documents"))
{
    using (Watermarker watermarker = new Watermarker(filePath))
    {
        using (ImageWatermark watermark = new ImageWatermark(@"C:\watermark.png"))
        {
            watermark.HorizontalAlignment = HorizontalAlignment.Center;
            watermark.VerticalAlignment = VerticalAlignment.Center;
            watermarker.Add(watermark);
        }

        watermarker.Save();
    }
}
```

### Guarda anche

* class [Watermark](../../groupdocs.watermark/watermark)
* spazio dei nomi [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* assemblea [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
