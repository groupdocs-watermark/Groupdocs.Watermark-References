---
title: "Aggiungi"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Aggiunge un watermark al documento caricato."
type: docs
weight: 30
url: /it/net/groupdocs.watermark/watermarker/add/
---
## Add(Watermark) {#add}

Aggiunge un watermark al documento caricato.

```csharp
public AddWatermarkResult Add(Watermark watermark)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| filigrana | Watermark | La filigrana da aggiungere al documento. |

### Osservazioni

Maggiori informazioni su come aggiungere filigrane: [Aggiungere filigrane](https://docs.groupdocs.com/display/watermarknet/Adding+watermarks).

### Esempi

Aggiungi filigrana immagine e testo a un documento di qualsiasi tipo supportato.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.pdf"))
{
    TextWatermark textWatermark = new TextWatermark("DRAFT", new Font("Arial", 19));
    textWatermark.HorizontalAlignment = HorizontalAlignment.Center;
    textWatermark.VerticalAlignment = VerticalAlignment.Top;
    textWatermark.ConsiderParentMargins = true;
    textWatermark.ForegroundColor = Color.Red;
    textWatermark.IsBackground = true;
    textWatermark.Opacity = 0.5;
    watermarker.Add(textWatermark);

    using (ImageWatermark imageWatermark = new ImageWatermark(@"D:\draft.png"))
    {
        imageWatermark.HorizontalAlignment = HorizontalAlignment.Center;
        imageWatermark.VerticalAlignment = VerticalAlignment.Bottom;
        imageWatermark.ConsiderParentMargins = true;
        imageWatermark.IsBackground = true;
        imageWatermark.Opacity = 0.5;
        watermarker.Add(imageWatermark);
    }

    watermarker.Save(@"D:\output.pdf");
}
```

### Vedi anche

* class [AddWatermarkResult](../../../groupdocs.watermark.watermarks.results/addwatermarkresult)
* class [Watermark](../../watermark)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Add(Watermark, WatermarkOptions) {#add_1}

Aggiunge un watermark al documento caricato utilizzando le opzioni di watermark.

```csharp
public AddWatermarkResult Add(Watermark watermark, WatermarkOptions options)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| filigrana | Watermark | La filigrana da aggiungere al documento. |
| opzioni | WatermarkOptions | Opzioni aggiuntive da utilizzare quando si aggiunge la filigrana. |

### Osservazioni

Scopri di più su come aggiungere filigrane [Aggiungere filigrane](https://docs.groupdocs.com/display/watermarknet/Adding+watermarks).

### Esempi

Aggiungi una filigrana immagine a una pagina specifica di un documento pdf.

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

* class [AddWatermarkResult](../../../groupdocs.watermark.watermarks.results/addwatermarkresult)
* class [Watermark](../../watermark)
* class [WatermarkOptions](../../../groupdocs.watermark.options/watermarkoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
