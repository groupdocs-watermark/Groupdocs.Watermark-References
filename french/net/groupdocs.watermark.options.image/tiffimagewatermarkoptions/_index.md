---
title: "TiffImageWatermarkOptions"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente les options d'ajout de filigrane lors de l'ajout d'un filigrane à une image TIFF."
type: docs
weight: 1900
url: /fr/net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/
---
## TiffImageWatermarkOptions class

Représente les options d'ajout de filigrane lors de l'ajout d'un filigrane à une image TIFF.

```csharp
public sealed class TiffImageWatermarkOptions : MultiframeImageWatermarkOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TiffImageWatermarkOptions](tiffimagewatermarkoptions#constructor)() | Initialise une nouvelle instance de la classe [`TiffImageWatermarkOptions`](../tiffimagewatermarkoptions). |
| [TiffImageWatermarkOptions](tiffimagewatermarkoptions#constructor_1)(int) | Initialise une nouvelle instance de la classe [`TiffImageWatermarkOptions`](../tiffimagewatermarkoptions) avec un indice spécifié de la trame. |

## Propriétés

| Nom | Description |
| --- | --- |
| [FrameIndex](../../groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frameindex) { get; set; } | Obtient ou définit l'indice du cadre où ajouter le filigrane. |

### Remarques

**Learn more:**

* [Add watermarks to images](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### Exemples

Ajoutez un filigrane à une trame particulière d'une image TIFF.

```csharp
TiffImageLoadOptions loadOptions = new TiffImageLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\test.tiff", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));

    TiffImageWatermarkOptions options = new TiffImageWatermarkOptions();
    options.FrameIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Voir aussi

* class [MultiframeImageWatermarkOptions](../multiframeimagewatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Image](../../groupdocs.watermark.options.image)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
