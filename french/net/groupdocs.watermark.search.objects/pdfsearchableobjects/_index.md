---
title: "PdfSearchableObjects"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Spécifie les indicateurs représentant les objets de contenu PDF qui doivent être inclus dans une recherche de filigrane."
type: docs
weight: 2530
url: /fr/net/groupdocs.watermark.search.objects/pdfsearchableobjects/
---
## PdfSearchableObjects enumeration

Spécifie les indicateurs représentant les objets de contenu PDF qui doivent être inclus dans une recherche de filigrane.

```csharp
[Flags]
public enum PdfSearchableObjects
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| None | `0` | Spécifie aucun objet de recherche. |
| XObjects | `1` | Rechercher dans les XObjects. |
| Artifacts | `2` | Rechercher dans les artefacts. |
| Annotations | `4` | Rechercher dans les annotations. |
| Text | `8` | Rechercher dans le texte du contenu. |
| Hyperlinks | `10` | Rechercher dans les hyperliens. |
| AttachedImages | `20` | Rechercher dans les images jointes. |
| Vector | `40` | Rechercher dans les opérateurs. |
| All | `7F` | Rechercher dans tous les objets de contenu. |

### Voir aussi

* namespace [GroupDocs.Watermark.Search.Objects](../../groupdocs.watermark.search.objects)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
