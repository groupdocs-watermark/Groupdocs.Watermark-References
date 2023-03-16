---
title: PdfArtifactWatermarkOptions
second_title: Référence de l'API GroupDocs.Watermark pour .NET
description: Représente les options dajout de filigrane lors de lajout dun filigrane dartefact à un document pdf.
type: docs
weight: 1870
url: /fr/net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/
---
## PdfArtifactWatermarkOptions class

Représente les options d'ajout de filigrane lors de l'ajout d'un filigrane d'artefact à un document pdf.

```csharp
public sealed class PdfArtifactWatermarkOptions : PdfWatermarkOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PdfArtifactWatermarkOptions](pdfartifactwatermarkoptions)() | Initialise une nouvelle instance du[`PdfArtifactWatermarkOptions`](../pdfartifactwatermarkoptions) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/pageindex) { get; set; } | Obtient ou définit l'index de page auquel ajouter un filigrane. |

### Remarques

**Apprendre encore plus:**

* [Ajouter des filigranes aux documents PDF](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### Exemples

Ajouter un filigrane d'artefact d'image à un document PDF.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf", loadOptions))
{
    using (ImageWatermark watermark = new ImageWatermark(@"D:\icon.png"))
    {
        watermark.HorizontalAlignment = HorizontalAlignment.Right;
        watermark.VerticalAlignment = VerticalAlignment.Bottom;

        PdfArtifactWatermarkOptions options = new PdfArtifactWatermarkOptions();
        options.PageIndex = -1; // par défaut - toutes les pages

        watermarker.Add(watermark, options);
        watermarker.Save();
    }
}
```

### Voir également

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* espace de noms [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* Assemblée [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->