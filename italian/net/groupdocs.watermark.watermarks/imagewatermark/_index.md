---
title: "ImageWatermark"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta una filigrana immagine."
type: docs
weight: 3190
url: /it/net/groupdocs.watermark.watermarks/imagewatermark/
---
## ImageWatermark class

Rappresenta una filigrana immagine.

```csharp
public sealed class ImageWatermark : Watermark, IDisposable
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ImageWatermark](imagewatermark#constructor)(Stream) | Inizializza una nuova istanza della classe [`ImageWatermark`](../imagewatermark) con uno stream specificato. |
| [ImageWatermark](imagewatermark#constructor_1)(string) | Inizializza una nuova istanza della classe [`ImageWatermark`](../imagewatermark) con un percorso file specificato. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ConsiderParentMargins](../../groupdocs.watermark/watermark/considerparentmargins) { get; set; } | Ottiene o imposta un valore che indica se le dimensioni e le coordinate della filigrana sono calcolate tenendo conto dei margini del genitore. |
| [Height](../../groupdocs.watermark/watermark/height) { get; set; } | Ottiene o imposta l'altezza desiderata di questa [`Watermark`](../../groupdocs.watermark/watermark). |
| [HorizontalAlignment](../../groupdocs.watermark/watermark/horizontalalignment) { get; set; } | Ottiene o imposta l'allineamento orizzontale di questa [`Watermark`](../../groupdocs.watermark/watermark). |
| [IsBackground](../../groupdocs.watermark/watermark/isbackground) { get; set; } | Ottiene o imposta un valore che indica se il watermark deve essere posizionato sullo sfondo. |
| [Margins](../../groupdocs.watermark/watermark/margins) { get; set; } | Ottiene o imposta le impostazioni del margine di questa [`Watermark`](../../groupdocs.watermark/watermark). |
| [Opacity](../../groupdocs.watermark/watermark/opacity) { get; set; } | Ottiene o imposta l'opacità di questa [`Watermark`](../../groupdocs.watermark/watermark). |
| [PagesSetup](../../groupdocs.watermark/watermark/pagessetup) { get; set; } | Ottiene o imposta le impostazioni di configurazione delle pagine di questa [`Watermark`](../../groupdocs.watermark/watermark). |
| [RotateAngle](../../groupdocs.watermark/watermark/rotateangle) { get; set; } | Ottiene o imposta l'angolo di rotazione di questo [`Watermark`](../../groupdocs.watermark/watermark) in gradi. |
| [SaveResultInMetadata](../../groupdocs.watermark/watermark/saveresultinmetadata) { get; set; } | Ottiene o imposta un valore che indica se salvare le informazioni sui watermark aggiunti nei metadati del documento. |
| [ScaleFactor](../../groupdocs.watermark/watermark/scalefactor) { get; set; } | Ottiene o imposta un valore che definisce come la dimensione del watermark dipende dalla dimensione del genitore. |
| [SizingType](../../groupdocs.watermark/watermark/sizingtype) { get; set; } | Ottiene o imposta un valore che specifica il modo in cui il watermark deve essere dimensionato. |
| [TileOptions](../../groupdocs.watermark/watermark/tileoptions) { get; set; } | Ottiene o imposta le opzioni per definire il watermark ripetuto |
| [VerticalAlignment](../../groupdocs.watermark/watermark/verticalalignment) { get; set; } | Ottiene o imposta l'allineamento verticale di questo [`Watermark`](../../groupdocs.watermark/watermark). |
| [Width](../../groupdocs.watermark/watermark/width) { get; set; } | Ottiene o imposta la larghezza desiderata di questo [`Watermark`](../../groupdocs.watermark/watermark). |
| [X](../../groupdocs.watermark/watermark/x) { get; set; } | Ottiene o imposta la coordinata x di questo [`Watermark`](../../groupdocs.watermark/watermark). |
| [Y](../../groupdocs.watermark/watermark/y) { get; set; } | Ottiene o imposta la coordinata y di questo [`Watermark`](../../groupdocs.watermark/watermark). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../groupdocs.watermark.watermarks/imagewatermark/dispose)() | Elimina l'istanza corrente. |

### Osservazioni

**Learn more:**

* [Adding image watermarks](https://docs.groupdocs.com/display/watermarknet/Adding+image+watermarks)

### Esempi

Aggiungi una filigrana immagine a un documento di qualsiasi tipo supportato.

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

### Vedi anche

* class [Watermark](../../groupdocs.watermark/watermark)
* namespace [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
