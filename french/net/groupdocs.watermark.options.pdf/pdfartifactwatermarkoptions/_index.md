---
title: "PdfArtifactWatermarkOptions"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente les options d'ajout de filigrane lors de l'ajout d'un filigrane d'artefact à un document PDF."
type: docs
weight: 1940
url: /fr/net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/
---
## PdfArtifactWatermarkOptions class

Représente les options d'ajout de filigrane lors de l'ajout d'un filigrane d'artefact à un document PDF.

```csharp
public sealed class PdfArtifactWatermarkOptions : PdfWatermarkOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfArtifactWatermarkOptions](pdfartifactwatermarkoptions)() | Initialise une nouvelle instance de la classe [`PdfArtifactWatermarkOptions`](../pdfartifactwatermarkoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/pageindex) { get; set; } | Obtient ou définit l'index de page auquel ajouter le filigrane. |

### Remarques

**Learn more:**

* [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### Exemples

Ajoute un filigrane d'artefact d'image à un document PDF.

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

### Voir aussi

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
