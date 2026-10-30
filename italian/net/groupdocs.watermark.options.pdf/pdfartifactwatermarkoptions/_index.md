---
title: "PdfArtifactWatermarkOptions"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta le opzioni di aggiunta della filigrana quando si aggiunge una filigrana di artefatto a un documento pdf."
type: docs
weight: 1940
url: /it/net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/
---
## PdfArtifactWatermarkOptions class

Rappresenta le opzioni di aggiunta della filigrana quando si aggiunge una filigrana di artefatto a un documento pdf.

```csharp
public sealed class PdfArtifactWatermarkOptions : PdfWatermarkOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfArtifactWatermarkOptions](pdfartifactwatermarkoptions)() | Inizializza una nuova istanza della classe [`PdfArtifactWatermarkOptions`](../pdfartifactwatermarkoptions). |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/pageindex) { get; set; } | Ottiene o imposta l'indice della pagina a cui aggiungere la filigrana. |

### Osservazioni

**Learn more:**

* [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### Esempi

Aggiungi una filigrana di artefatto immagine a un documento PDF.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf", loadOptions))
{
    using (ImageWatermark watermark = new ImageWatermark(@"D:\icon.png"))
    {
        watermark.HorizontalAlignment = HorizontalAlignment.Right;
        watermark.VerticalAlignment = VerticalAlignment.Bottom;

        PdfArtifactWatermarkOptions options = new PdfArtifactWatermarkOptions();
        options.PageIndex = -1; // default - all pages

        watermarker.Add(watermark, options);
        watermarker.Save();
    }
}
```

### Vedi anche

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
