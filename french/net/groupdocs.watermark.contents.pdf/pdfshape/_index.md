---
title: "PdfShape"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Fournit la classe de base pour les artefacts et annotations XObjects."
type: docs
weight: 770
url: /fr/net/groupdocs.watermark.contents.pdf/pdfshape/
---
## PdfShape class

Fournit une classe de base pour les XObjects, les Artefacts et les Annotations.

```csharp
public abstract class PdfShape : ShapeSearchAdapter, IRotatableTwoDObject
```

## Propriétés

| Nom | Description |
| --- | --- |
| [FormattedTextFragments](../../groupdocs.watermark.contents.pdf/pdfshape/formattedtextfragments) { get; } | Obtient la collection de fragments de texte formatés de ce [`PdfShape`](../pdfshape). |
| abstract [Height](../../groupdocs.watermark.contents.pdf/pdfshape/height) { get; } | Obtient la hauteur de l'objet. |
| [Image](../../groupdocs.watermark.contents.pdf/pdfshape/image) { get; set; } | Obtient ou définit l'image de ce [`PdfShape`](../pdfshape). |
| abstract [RotateAngle](../../groupdocs.watermark.contents.pdf/pdfshape/rotateangle) { get; } | Obtient l'angle de rotation de l'objet en degrés. |
| virtual [Text](../../groupdocs.watermark.contents.pdf/pdfshape/text) { get; set; } | Obtient ou définit le texte de ce [`PdfShape`](../pdfshape). |
| abstract [Width](../../groupdocs.watermark.contents.pdf/pdfshape/width) { get; } | Obtient la largeur de l'objet. |
| abstract [X](../../groupdocs.watermark.contents.pdf/pdfshape/x) { get; } | Obtient la coordonnée x de l'objet. |
| abstract [Y](../../groupdocs.watermark.contents.pdf/pdfshape/y) { get; } | Obtient la coordonnée y de l'objet. |

### Voir aussi

* class [ShapeSearchAdapter](../../groupdocs.watermark.search/shapesearchadapter)
* interface [IRotatableTwoDObject](../../groupdocs.watermark.search/irotatabletwodobject)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
