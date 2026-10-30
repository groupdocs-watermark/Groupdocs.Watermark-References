---
title: "PdfXObjectWatermarkOptions"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta le opzioni di aggiunta della filigrana quando si aggiunge una filigrana XObject a un documento pdf."
type: docs
weight: 1990
url: /it/net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/
---
## PdfXObjectWatermarkOptions class

Rappresenta le opzioni di aggiunta della filigrana quando si aggiunge una filigrana XObject a un documento pdf.

```csharp
public sealed class PdfXObjectWatermarkOptions : PdfWatermarkOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfXObjectWatermarkOptions](pdfxobjectwatermarkoptions)() | Inizializza una nuova istanza della classe [`PdfXObjectWatermarkOptions`](../pdfxobjectwatermarkoptions). |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/pageindex) { get; set; } | Ottiene o imposta l'indice della pagina a cui aggiungere la filigrana. |

### Osservazioni

**Learn more:**

* [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### Esempi

Aggiungi una filigrana a una pagina specifica di un documento PDF.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\doc.pdf", loadOptions))
using (ImageWatermark watermark = new ImageWatermark(@"C:\watermark.png"))
{
    PdfXObjectWatermarkOptions options = new PdfXObjectWatermarkOptions();
    options.PageIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Vedi anche

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
