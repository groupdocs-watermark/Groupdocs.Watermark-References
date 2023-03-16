---
title: TextWatermark
second_title: Référence de l'API GroupDocs.Watermark pour .NET
description: Représente un filigrane de texte.
type: docs
weight: 3160
url: /fr/net/groupdocs.watermark.watermarks/textwatermark/
---
## TextWatermark class

Représente un filigrane de texte.

```csharp
public class TextWatermark : Watermark
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [TextWatermark](textwatermark)(string, Font) | Initialise une nouvelle instance du[`TextWatermark`](../textwatermark)classe avec un texte spécifié et une police. |

## Propriétés

| Nom | La description |
| --- | --- |
| [BackgroundColor](../../groupdocs.watermark.watermarks/textwatermark/backgroundcolor) { get; set; } | Obtient ou définit la couleur d'arrière-plan du texte. |
| [ConsiderParentMargins](../../groupdocs.watermark/watermark/considerparentmargins) { get; set; } | Obtient ou définit une valeur indiquant si la taille et les coordonnées du filigrane sont calculées en tenant compte des marges parentes. |
| [Font](../../groupdocs.watermark.watermarks/textwatermark/font) { get; set; } | Obtient ou définit la police du texte. |
| [ForegroundColor](../../groupdocs.watermark.watermarks/textwatermark/foregroundcolor) { get; set; } | Obtient ou définit la couleur de premier plan du texte. |
| [Height](../../groupdocs.watermark/watermark/height) { get; set; } | Obtient ou définit la hauteur souhaitée de ce[`Watermark`](../../groupdocs.watermark/watermark) . |
| [HorizontalAlignment](../../groupdocs.watermark/watermark/horizontalalignment) { get; set; } | Obtient ou définit l'alignement horizontal de ce[`Watermark`](../../groupdocs.watermark/watermark) . |
| [IsBackground](../../groupdocs.watermark/watermark/isbackground) { get; set; } | Obtient ou définit une valeur indiquant si le filigrane doit être placé en arrière-plan. |
| [Margins](../../groupdocs.watermark/watermark/margins) { get; set; } | Obtient ou définit les paramètres de marge de ce[`Watermark`](../../groupdocs.watermark/watermark) . |
| [Opacity](../../groupdocs.watermark/watermark/opacity) { get; set; } | Obtient ou définit l'opacité de ce[`Watermark`](../../groupdocs.watermark/watermark) . |
| [Padding](../../groupdocs.watermark.watermarks/textwatermark/padding) { get; set; } | Obtient ou définit les paramètres de remplissage de ce[`TextWatermark`](../textwatermark) . Cette propriété s'applique uniquement aux fichiers image. |
| [RotateAngle](../../groupdocs.watermark/watermark/rotateangle) { get; set; } | Obtient ou définit l'angle de rotation de ce[`Watermark`](../../groupdocs.watermark/watermark) en degrés. |
| [ScaleFactor](../../groupdocs.watermark/watermark/scalefactor) { get; set; } | Obtient ou définit une valeur qui définit la façon dont la taille du filigrane dépend de la taille du parent. |
| [SizingType](../../groupdocs.watermark/watermark/sizingtype) { get; set; } | Obtient ou définit une valeur spécifiant la façon dont le filigrane doit être dimensionné. |
| [Text](../../groupdocs.watermark.watermarks/textwatermark/text) { get; set; } | Obtient ou définit le texte à utiliser comme filigrane. |
| [TextAlignment](../../groupdocs.watermark.watermarks/textwatermark/textalignment) { get; set; } | Obtient ou définit l'alignement du texte du filigrane. |
| [VerticalAlignment](../../groupdocs.watermark/watermark/verticalalignment) { get; set; } | Obtient ou définit l'alignement vertical de ce[`Watermark`](../../groupdocs.watermark/watermark) . |
| [Width](../../groupdocs.watermark/watermark/width) { get; set; } | Obtient ou définit la largeur souhaitée de ce[`Watermark`](../../groupdocs.watermark/watermark) . |
| [X](../../groupdocs.watermark/watermark/x) { get; set; } | Obtient ou définit la coordonnée x de ce[`Watermark`](../../groupdocs.watermark/watermark) . |
| [Y](../../groupdocs.watermark/watermark/y) { get; set; } | Obtient ou définit la coordonnée y de ce[`Watermark`](../../groupdocs.watermark/watermark) . |

### Remarques

**Apprendre encore plus:**

* [Ajouter des filigranes de texte](https://docs.groupdocs.com/display/watermarknet/Adding+text+watermarks)

### Exemples

Mettez à l'échelle le filigrane du texte en fonction de la taille du parent.

```csharp
foreach (string file in Directory.GetFiles("C:\\test"))
{
    using (Watermarker watermarker = new Watermarker(file))
    {
        TextWatermark watermark = new TextWatermark("test watermark", new Font("Arial", 36));
        watermark.HorizontalAlignment = HorizontalAlignment.Center;
        watermark.VerticalAlignment = VerticalAlignment.Center;
        watermark.SizingType = SizingType.ScaleToParentDimensions;
        watermark.RotateAngle = 45;
        watermark.ScaleFactor = 0.4;

        watermarker.Add(watermark);
        watermarker.Save();
    }
}
```

### Voir également

* class [Watermark](../../groupdocs.watermark/watermark)
* espace de noms [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* Assemblée [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
