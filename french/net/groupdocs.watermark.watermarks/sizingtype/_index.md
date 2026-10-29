---
title: "SizingType"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Spécifie comment la taille du filigrane doit être calculée."
type: docs
weight: 3300
url: /fr/net/groupdocs.watermark.watermarks/sizingtype/
---
## SizingType enumeration

Spécifie comment la taille du filigrane doit être calculée.

```csharp
public enum SizingType
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Auto | `0` | Le filigrane doit être dimensionné automatiquement en fonction de son contenu. |
| Absolute | `1` | Le filigrane doit être dimensionné à une largeur exacte [`Width`](../../groupdocs.watermark/watermark/width) et une hauteur exacte [`Height`](../../groupdocs.watermark/watermark/height). |
| ScaleToParentDimensions | `2` | Le filigrane doit être mis à l'échelle par rapport aux dimensions du parent en utilisant le [`ScaleFactor`](../../groupdocs.watermark/watermark/scalefactor) spécifié. |
| ScaleToParentArea | `3` | Le filigrane doit être mis à l'échelle par rapport à la zone du parent en utilisant le [`ScaleFactor`](../../groupdocs.watermark/watermark/scalefactor) spécifié. |

### Voir aussi

* namespace [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
