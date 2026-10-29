---
title: "PdfAnnotationWatermarkOptions"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente les options d'ajout de filigrane lors de l'ajout d'un filigrane d'annotation à un document PDF."
type: docs
weight: 1930
url: /fr/net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/
---
## PdfAnnotationWatermarkOptions class

Représente les options d'ajout de filigrane lors de l'ajout d'un filigrane d'annotation à un document PDF.

```csharp
public sealed class PdfAnnotationWatermarkOptions : PdfWatermarkOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfAnnotationWatermarkOptions](pdfannotationwatermarkoptions)() | Initialise une nouvelle instance de la classe [`PdfAnnotationWatermarkOptions`](../pdfannotationwatermarkoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/pageindex) { get; set; } | Obtient ou définit l'index de page auquel ajouter le filigrane. |
| [PrintOnly](../../groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/printonly) { get; set; } | Obtient ou définit la valeur indiquant si l'annotation sera imprimée, mais ne sera pas affichée dans l'application de visualisation PDF. |

### Remarques

**Learn more:**

* [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### Exemples

Ajoute un filigrane d'annotation d'image à un document PDF.

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

### Voir aussi

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
