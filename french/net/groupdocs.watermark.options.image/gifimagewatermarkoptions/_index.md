---
title: "GifImageWatermarkOptions"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente les options d'ajout de filigrane lors de l'ajout d'un filigrane à une image GIF."
type: docs
weight: 1830
url: /fr/net/groupdocs.watermark.options.image/gifimagewatermarkoptions/
---
## GifImageWatermarkOptions class

Représente les options d'ajout de filigrane lors de l'ajout d'un filigrane à une image GIF.

```csharp
public sealed class GifImageWatermarkOptions : MultiframeImageWatermarkOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [GifImageWatermarkOptions](gifimagewatermarkoptions#constructor)() | Initialise une nouvelle instance de la classe [`GifImageWatermarkOptions`](../gifimagewatermarkoptions). |
| [GifImageWatermarkOptions](gifimagewatermarkoptions#constructor_1)(int) | Initialise une nouvelle instance de la classe [`GifImageWatermarkOptions`](../gifimagewatermarkoptions) avec un indice spécifié d'une trame. |

## Propriétés

| Nom | Description |
| --- | --- |
| [FrameIndex](../../groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frameindex) { get; set; } | Obtient ou définit l'indice du cadre où ajouter le filigrane. |

### Remarques

**Learn more:**

* [Add watermarks to images](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### Exemples

Ajoutez un filigrane à une trame particulière d'une image GIF.

```csharp
GifImageLoadOptions loadOptions = new GifImageLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\test.gif", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));

    GifImageWatermarkOptions options = new GifImageWatermarkOptions();
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
