---
title: PdfXObjectWatermarkOptions
second_title: Référence de l'API GroupDocs.Watermark pour .NET
description: Représente les options dajout de filigrane lors de lajout dun filigrane XObject à un document pdf.
type: docs
weight: 1920
url: /fr/net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/
---
## PdfXObjectWatermarkOptions class

Représente les options d'ajout de filigrane lors de l'ajout d'un filigrane XObject à un document pdf.

```csharp
public sealed class PdfXObjectWatermarkOptions : PdfWatermarkOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PdfXObjectWatermarkOptions](pdfxobjectwatermarkoptions)() | Initialise une nouvelle instance du[`PdfXObjectWatermarkOptions`](../pdfxobjectwatermarkoptions) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/pageindex) { get; set; } | Obtient ou définit l'index de page auquel ajouter un filigrane. |

### Remarques

**Apprendre encore plus:**

* [Ajouter des filigranes aux documents PDF](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### Exemples

Ajouter un filigrane à une page particulière d'un document pdf.

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

### Voir également

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* espace de noms [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* Assemblée [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->