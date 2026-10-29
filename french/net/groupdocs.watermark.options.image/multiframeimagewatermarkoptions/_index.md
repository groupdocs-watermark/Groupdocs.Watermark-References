---
title: "MultiframeImageWatermarkOptions"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente les options d'ajout de filigrane lors de l'ajout d'un filigrane à une image multiframe."
type: docs
weight: 1870
url: /fr/net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/
---
## MultiframeImageWatermarkOptions class

Représente les options d'ajout de filigrane lors de l'ajout d'un filigrane à une image multi-cadres.

```csharp
public class MultiframeImageWatermarkOptions : WatermarkOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [MultiframeImageWatermarkOptions](multiframeimagewatermarkoptions#constructor)() | Initialise une nouvelle instance de la classe [`MultiframeImageWatermarkOptions`](../multiframeimagewatermarkoptions). |
| [MultiframeImageWatermarkOptions](multiframeimagewatermarkoptions#constructor_1)(int) | Initialise une nouvelle instance de la classe [`MultiframeImageWatermarkOptions`](../multiframeimagewatermarkoptions) avec un indice spécifié du cadre. |

## Propriétés

| Nom | Description |
| --- | --- |
| [FrameIndex](../../groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frameindex) { get; set; } | Obtient ou définit l'indice du cadre où ajouter le filigrane. |

### Remarques

**Learn more:**

* [Add watermarks to images](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### Exemples

Ajoute un filigrane à un cadre particulier d'une image multi-cadre.

```csharp
ImageLoadOptions loadOptions = new ImageLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\test.gif", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));

    MultiframeImageWatermarkOptions options = new MultiframeImageWatermarkOptions();
    options.FrameIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Voir aussi

* class [WatermarkOptions](../../groupdocs.watermark.options/watermarkoptions)
* namespace [GroupDocs.Watermark.Options.Image](../../groupdocs.watermark.options.image)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
