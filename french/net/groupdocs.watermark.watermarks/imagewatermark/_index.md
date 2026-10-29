---
title: "ImageWatermark"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente un filigrane image."
type: docs
weight: 3190
url: /fr/net/groupdocs.watermark.watermarks/imagewatermark/
---
## ImageWatermark class

Représente un filigrane image.

```csharp
public sealed class ImageWatermark : Watermark, IDisposable
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ImageWatermark](imagewatermark#constructor)(Stream) | Initialise une nouvelle instance de la classe [`ImageWatermark`](../imagewatermark) avec un flux spécifié. |
| [ImageWatermark](imagewatermark#constructor_1)(string) | Initialise une nouvelle instance de la classe [`ImageWatermark`](../imagewatermark) avec un chemin de fichier spécifié. |

## Propriétés

| Nom | Description |
| --- | --- |
| [ConsiderParentMargins](../../groupdocs.watermark/watermark/considerparentmargins) { get; set; } | Obtient ou définit une valeur indiquant si la taille et les coordonnées du filigrane sont calculées en tenant compte des marges du parent. |
| [Height](../../groupdocs.watermark/watermark/height) { get; set; } | Obtient ou définit la hauteur souhaitée de ce [`Watermark`](../../groupdocs.watermark/watermark). |
| [HorizontalAlignment](../../groupdocs.watermark/watermark/horizontalalignment) { get; set; } | Obtient ou définit l'alignement horizontal de ce [`Watermark`](../../groupdocs.watermark/watermark). |
| [IsBackground](../../groupdocs.watermark/watermark/isbackground) { get; set; } | Obtient ou définit une valeur indiquant si le filigrane doit être placé en arrière-plan. |
| [Margins](../../groupdocs.watermark/watermark/margins) { get; set; } | Obtient ou définit les paramètres de marge de ce [`Watermark`](../../groupdocs.watermark/watermark). |
| [Opacity](../../groupdocs.watermark/watermark/opacity) { get; set; } | Obtient ou définit l'opacité de ce [`Watermark`](../../groupdocs.watermark/watermark). |
| [PagesSetup](../../groupdocs.watermark/watermark/pagessetup) { get; set; } | Obtient ou définit les paramètres de configuration des pages de ce [`Watermark`](../../groupdocs.watermark/watermark). |
| [RotateAngle](../../groupdocs.watermark/watermark/rotateangle) { get; set; } | Obtient ou définit l'angle de rotation de ce [`Watermark`](../../groupdocs.watermark/watermark) en degrés. |
| [SaveResultInMetadata](../../groupdocs.watermark/watermark/saveresultinmetadata) { get; set; } | Obtient ou définit une valeur indiquant s'il faut enregistrer les informations sur les filigranes ajoutés dans les métadonnées du document. |
| [ScaleFactor](../../groupdocs.watermark/watermark/scalefactor) { get; set; } | Obtient ou définit une valeur qui définit comment la taille du filigrane dépend de la taille du parent. |
| [SizingType](../../groupdocs.watermark/watermark/sizingtype) { get; set; } | Obtient ou définit une valeur spécifiant la façon dont le filigrane doit être dimensionné. |
| [TileOptions](../../groupdocs.watermark/watermark/tileoptions) { get; set; } | Obtient ou définit les options pour définir le filigrane répété. |
| [VerticalAlignment](../../groupdocs.watermark/watermark/verticalalignment) { get; set; } | Obtient ou définit l'alignement vertical de ce [`Watermark`](../../groupdocs.watermark/watermark). |
| [Width](../../groupdocs.watermark/watermark/width) { get; set; } | Obtient ou définit la largeur souhaitée de ce [`Watermark`](../../groupdocs.watermark/watermark). |
| [X](../../groupdocs.watermark/watermark/x) { get; set; } | Obtient ou définit la coordonnée x de ce [`Watermark`](../../groupdocs.watermark/watermark). |
| [Y](../../groupdocs.watermark/watermark/y) { get; set; } | Obtient ou définit la coordonnée y de ce [`Watermark`](../../groupdocs.watermark/watermark). |

## Méthodes

| Nom | Description |
| --- | --- |
| [Dispose](../../groupdocs.watermark.watermarks/imagewatermark/dispose)() | Libère l'instance actuelle. |

### Remarques

**Learn more:**

* [Adding image watermarks](https://docs.groupdocs.com/display/watermarknet/Adding+image+watermarks)

### Exemples

Ajouter un filigrane d'image à un document de tout type pris en charge.

```csharp
foreach (string filePath in Directory.GetFiles(@"C:\Documents"))
{
    using (Watermarker watermarker = new Watermarker(filePath))
    {
        using (ImageWatermark watermark = new ImageWatermark(@"C:\watermark.png"))
        {
            watermark.HorizontalAlignment = HorizontalAlignment.Center;
            watermark.VerticalAlignment = VerticalAlignment.Center;
            watermarker.Add(watermark);
        }

        watermarker.Save();
    }
}
```

### Voir aussi

* class [Watermark](../../groupdocs.watermark/watermark)
* namespace [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
