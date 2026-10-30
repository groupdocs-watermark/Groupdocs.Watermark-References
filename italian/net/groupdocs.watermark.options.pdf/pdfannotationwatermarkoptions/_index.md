---
title: "PdfAnnotationWatermarkOptions"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta le opzioni di aggiunta della filigrana quando si aggiunge una filigrana di annotazione a un documento pdf."
type: docs
weight: 1930
url: /it/net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/
---
## PdfAnnotationWatermarkOptions class

Rappresenta le opzioni di aggiunta della filigrana quando si aggiunge una filigrana di annotazione a un documento pdf.

```csharp
public sealed class PdfAnnotationWatermarkOptions : PdfWatermarkOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfAnnotationWatermarkOptions](pdfannotationwatermarkoptions)() | Inizializza una nuova istanza della classe [`PdfAnnotationWatermarkOptions`](../pdfannotationwatermarkoptions). |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/pageindex) { get; set; } | Ottiene o imposta l'indice della pagina a cui aggiungere la filigrana. |
| [PrintOnly](../../groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/printonly) { get; set; } | Ottiene o imposta il valore che indica se l'annotazione verrà stampata, ma non visualizzata nell'applicazione di visualizzazione PDF. |

### Osservazioni

**Learn more:**

* [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### Esempi

Aggiungi una filigrana di annotazione immagine a un documento PDF.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf", loadOptions))
{
    using (ImageWatermark watermark = new ImageWatermark(@"D:\icon.png"))
    {
        PdfAnnotationWatermarkOptions options = new PdfAnnotationWatermarkOptions();
        options.PageIndex = -1; // default - all pages

        watermarker.Add(watermark, options);
    }

    watermarker.Save();
}
```

### Vedi anche

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
