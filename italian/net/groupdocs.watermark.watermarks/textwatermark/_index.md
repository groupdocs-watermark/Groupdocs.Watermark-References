---
title: "TextWatermark"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta una filigrana di testo."
type: docs
weight: 3320
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
| [TextWatermark](textwatermark)(string, Font) | Inizializza una nuova istanza della classe [`TextWatermark`](../textwatermark) con un testo specificato e un font. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BackgroundColor](../../groupdocs.watermark.watermarks/textwatermark/backgroundcolor) { get; set; } | Ottiene o imposta il colore di sfondo del testo. |
| [ConsiderParentMargins](../../groupdocs.watermark/watermark/considerparentmargins) { get; set; } | Ottiene o imposta un valore che indica se le dimensioni e le coordinate della filigrana sono calcolate tenendo conto dei margini del genitore. |
| [Font](../../groupdocs.watermark.watermarks/textwatermark/font) { get; set; } | Ottiene o imposta il font del testo. |
| [ForegroundColor](../../groupdocs.watermark.watermarks/textwatermark/foregroundcolor) { get; set; } | Ottiene o imposta il colore di primo piano del testo. |
| [Height](../../groupdocs.watermark/watermark/height) { get; set; } | Ottiene o imposta l'altezza desiderata di questa [`Watermark`](../../groupdocs.watermark/watermark). |
| [HorizontalAlignment](../../groupdocs.watermark/watermark/horizontalalignment) { get; set; } | Ottiene o imposta l'allineamento orizzontale di questa [`Watermark`](../../groupdocs.watermark/watermark). |
| [IsBackground](../../groupdocs.watermark/watermark/isbackground) { get; set; } | Ottiene o imposta un valore che indica se il watermark deve essere posizionato sullo sfondo. |
| [Margins](../../groupdocs.watermark/watermark/margins) { get; set; } | Ottiene o imposta le impostazioni del margine di questa [`Watermark`](../../groupdocs.watermark/watermark). |
| [Opacity](../../groupdocs.watermark/watermark/opacity) { get; set; } | Ottiene o imposta l'opacità di questa [`Watermark`](../../groupdocs.watermark/watermark). |
| [Padding](../../groupdocs.watermark.watermarks/textwatermark/padding) { get; set; } | Ottiene o imposta le impostazioni di padding di questo [`TextWatermark`](../textwatermark). Questa proprietà è applicabile solo ai file immagine. |
| [PagesSetup](../../groupdocs.watermark/watermark/pagessetup) { get; set; } | Ottiene o imposta le impostazioni di configurazione delle pagine di questa [`Watermark`](../../groupdocs.watermark/watermark). |
| [RotateAngle](../../groupdocs.watermark/watermark/rotateangle) { get; set; } | Ottiene o imposta l'angolo di rotazione di questo [`Watermark`](../../groupdocs.watermark/watermark) in gradi. |
| [SaveResultInMetadata](../../groupdocs.watermark/watermark/saveresultinmetadata) { get; set; } | Ottiene o imposta un valore che indica se salvare le informazioni sui watermark aggiunti nei metadati del documento. |
| [ScaleFactor](../../groupdocs.watermark/watermark/scalefactor) { get; set; } | Ottiene o imposta un valore che definisce come la dimensione del watermark dipende dalla dimensione del genitore. |
| [SizingType](../../groupdocs.watermark/watermark/sizingtype) { get; set; } | Ottiene o imposta un valore che specifica il modo in cui il watermark deve essere dimensionato. |
| [Text](../../groupdocs.watermark.watermarks/textwatermark/text) { get; set; } | Ottiene o imposta il testo da utilizzare come filigrana. |
| [TextAlignment](../../groupdocs.watermark.watermarks/textwatermark/textalignment) { get; set; } | Ottiene o imposta l'allineamento del testo della filigrana. |
| [TileOptions](../../groupdocs.watermark/watermark/tileoptions) { get; set; } | Ottiene o imposta le opzioni per definire il watermark ripetuto |
| [VerticalAlignment](../../groupdocs.watermark/watermark/verticalalignment) { get; set; } | Ottiene o imposta l'allineamento verticale di questo [`Watermark`](../../groupdocs.watermark/watermark). |
| [Width](../../groupdocs.watermark/watermark/width) { get; set; } | Ottiene o imposta la larghezza desiderata di questo [`Watermark`](../../groupdocs.watermark/watermark). |
| [X](../../groupdocs.watermark/watermark/x) { get; set; } | Ottiene o imposta la coordinata x di questo [`Watermark`](../../groupdocs.watermark/watermark). |
| [Y](../../groupdocs.watermark/watermark/y) { get; set; } | Ottiene o imposta la coordinata y di questo [`Watermark`](../../groupdocs.watermark/watermark). |

### Osservazioni

**Learn more:**

* [Adding text watermarks](https://docs.groupdocs.com/display/watermarknet/Adding+text+watermarks)

### Esempi

Scala la filigrana di testo in base alle dimensioni del contenitore.

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

### Vedi anche

* class [Watermark](../../groupdocs.watermark/watermark)
* namespace [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
