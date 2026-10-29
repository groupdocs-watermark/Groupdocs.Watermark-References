---
title: "ImageInpaintingPossibleWatermark"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente une région d'image spécifiée manuellement qui doit être remplie par inpainting à l'aide des pixels environnants."
type: docs
weight: 2900
url: /fr/net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/
---
## ImageInpaintingPossibleWatermark class

Représente une région d'image spécifiée manuellement qui doit être repeinte (remplie à l'aide des pixels environnants).

```csharp
public class ImageInpaintingPossibleWatermark : PossibleWatermark
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ImageInpaintingPossibleWatermark](imageinpaintingpossiblewatermark)() | Initialise une nouvelle instance de la classe [`ImageInpaintingPossibleWatermark`](../imageinpaintingpossiblewatermark). |

## Propriétés

| Nom | Description |
| --- | --- |
| virtual [FormattedTextFragments](../../groupdocs.watermark.search/possiblewatermark/formattedtextfragments) { get; } | Obtient la collection de fragments de texte formatés de ce [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [Height](../../groupdocs.watermark.search/possiblewatermark/height) { get; } | Obtient la hauteur de ce [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| [ImageData](../../groupdocs.watermark.search/possiblewatermark/imagedata) { get; set; } | Obtient ou définit l'image de ce [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| [Method](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/method) { get; set; } | Obtient ou définit l'algorithme d'inpainting. La valeur par défaut est PatchBased. |
| virtual [PageNumber](../../groupdocs.watermark.search/possiblewatermark/pagenumber) { get; } | Obtient la page sur laquelle le filigrane est placé. |
| override [Parent](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/parent) { get; } | Obtient le parent de ce [`ImageInpaintingPossibleWatermark`](../imageinpaintingpossiblewatermark). Retourne toujours `null` car la région est spécifiée manuellement. |
| [PatchSize](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/patchsize) { get; set; } | Obtient ou définit la taille du patch utilisée par l'algorithme (impair, 5-11). La valeur par défaut est 7. Pour Telea, cela est utilisé comme HalfPatchSize. |
| [Polygons](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/polygons) { get; set; } | Obtient ou définit les régions polygonales à inpaint, en pixels d'image. Chaque polygone est un tableau de sommets. Soit [`Rectangles`](./rectangles) soit [`Polygons`](./polygons) doit être spécifié, mais pas les deux. |
| [Rectangles](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/rectangles) { get; set; } | Obtient ou définit les zones rectangulaires à inpaint, en pixels d'image. Soit [`Rectangles`](./rectangles) soit [`Polygons`](./polygons) doit être spécifié, mais pas les deux. |
| virtual [RotateAngle](../../groupdocs.watermark.search/possiblewatermark/rotateangle) { get; } | Obtient l'angle de rotation de ce [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) en degrés. |
| virtual [Text](../../groupdocs.watermark.search/possiblewatermark/text) { get; set; } | Obtient ou définit le texte de ce [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [UnitOfMeasurement](../../groupdocs.watermark.search/possiblewatermark/unitofmeasurement) { get; } | Obtient l'unité de mesure de ce [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [Width](../../groupdocs.watermark.search/possiblewatermark/width) { get; } | Obtient la largeur de ce [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [X](../../groupdocs.watermark.search/possiblewatermark/x) { get; } | Obtient la coordonnée x de ce [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [Y](../../groupdocs.watermark.search/possiblewatermark/y) { get; } | Obtient la coordonnée y de ce [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |

### Voir aussi

* class [PossibleWatermark](../../groupdocs.watermark.search/possiblewatermark)
* namespace [GroupDocs.Watermark.Search.Watermarks](../../groupdocs.watermark.search.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
