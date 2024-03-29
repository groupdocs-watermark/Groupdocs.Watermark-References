---
title: TextWatermark
second_title: Riferimento API GroupDocs.Watermark per .NET
description: Rappresenta una filigrana di testo.
type: docs
weight: 3160
url: /it/net/groupdocs.watermark.watermarks/textwatermark/
---
## TextWatermark class

Rappresenta una filigrana di testo.

```csharp
public class TextWatermark : Watermark
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextWatermark](textwatermark)(string, Font) | Inizializza una nuova istanza di[`TextWatermark`](../textwatermark)classe con un testo specificato e un font. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BackgroundColor](../../groupdocs.watermark.watermarks/textwatermark/backgroundcolor) { get; set; } | Ottiene o imposta il colore di sfondo del testo. |
| [ConsiderParentMargins](../../groupdocs.watermark/watermark/considerparentmargins) { get; set; } | Ottiene o imposta un valore che indica se le dimensioni e le coordinate della filigrana vengono calcolate considerando i margini padre. |
| [Font](../../groupdocs.watermark.watermarks/textwatermark/font) { get; set; } | Ottiene o imposta il carattere del testo. |
| [ForegroundColor](../../groupdocs.watermark.watermarks/textwatermark/foregroundcolor) { get; set; } | Ottiene o imposta il colore di primo piano del testo. |
| [Height](../../groupdocs.watermark/watermark/height) { get; set; } | Ottiene o imposta l'altezza desiderata di this[`Watermark`](../../groupdocs.watermark/watermark) . |
| [HorizontalAlignment](../../groupdocs.watermark/watermark/horizontalalignment) { get; set; } | Ottiene o imposta l'allineamento orizzontale di this[`Watermark`](../../groupdocs.watermark/watermark) . |
| [IsBackground](../../groupdocs.watermark/watermark/isbackground) { get; set; } | Ottiene o imposta un valore che indica se la filigrana deve essere posizionata sullo sfondo. |
| [Margins](../../groupdocs.watermark/watermark/margins) { get; set; } | Ottiene o imposta le impostazioni dei margini di this[`Watermark`](../../groupdocs.watermark/watermark) . |
| [Opacity](../../groupdocs.watermark/watermark/opacity) { get; set; } | Ottiene o imposta l'opacità di this[`Watermark`](../../groupdocs.watermark/watermark) . |
| [Padding](../../groupdocs.watermark.watermarks/textwatermark/padding) { get; set; } | Ottiene o imposta le impostazioni di riempimento di this[`TextWatermark`](../textwatermark) . Questa proprietà è applicabile solo ai file immagine. |
| [RotateAngle](../../groupdocs.watermark/watermark/rotateangle) { get; set; } | Ottiene o imposta l'angolo di rotazione di this[`Watermark`](../../groupdocs.watermark/watermark) in gradi. |
| [ScaleFactor](../../groupdocs.watermark/watermark/scalefactor) { get; set; } | Ottiene o imposta un valore che definisce in che modo la dimensione della filigrana dipende dalla dimensione principale. |
| [SizingType](../../groupdocs.watermark/watermark/sizingtype) { get; set; } | Ottiene o imposta un valore che specifica la dimensione della filigrana. |
| [Text](../../groupdocs.watermark.watermarks/textwatermark/text) { get; set; } | Ottiene o imposta il testo da utilizzare come filigrana. |
| [TextAlignment](../../groupdocs.watermark.watermarks/textwatermark/textalignment) { get; set; } | Ottiene o imposta l'allineamento del testo della filigrana. |
| [VerticalAlignment](../../groupdocs.watermark/watermark/verticalalignment) { get; set; } | Ottiene o imposta l'allineamento verticale di this[`Watermark`](../../groupdocs.watermark/watermark) . |
| [Width](../../groupdocs.watermark/watermark/width) { get; set; } | Ottiene o imposta la larghezza desiderata di this[`Watermark`](../../groupdocs.watermark/watermark) . |
| [X](../../groupdocs.watermark/watermark/x) { get; set; } | Ottiene o imposta la coordinata x di this[`Watermark`](../../groupdocs.watermark/watermark) . |
| [Y](../../groupdocs.watermark/watermark/y) { get; set; } | Ottiene o imposta la coordinata y di this[`Watermark`](../../groupdocs.watermark/watermark) . |

### Osservazioni

**Saperne di più:**

* [Aggiunta di filigrane di testo](https://docs.groupdocs.com/display/watermarknet/Adding+text+watermarks)

### Esempi

Ridimensiona la filigrana del testo in base alla dimensione del genitore.

```csharp
foreach (string file in Directory.GetFiles("C:\\test"))
{
    using (Watermarker watermarker = new Watermarker(file))
    {
        TextWatermark watermark = new TextWatermark("test watermark", new Font("Arial", 36));
        watermark.HorizontalAlignment = HorizontalAlignment.Center;
        watermark.VerticalAlignment = VerticalAlignment.Center;
        watermark.SizingType = SizingType.ScaleToParentDimensions;
        watermark.RotateAngle = 45;
        watermark.ScaleFactor = 0.4;

        watermarker.Add(watermark);
        watermarker.Save();
    }
}
```

### Guarda anche

* class [Watermark](../../groupdocs.watermark/watermark)
* spazio dei nomi [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* assemblea [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
