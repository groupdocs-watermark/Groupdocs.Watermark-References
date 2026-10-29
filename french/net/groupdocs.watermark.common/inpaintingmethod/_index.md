---
title: "InpaintingMethod"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Spécifie l'algorithme utilisé pour le remplissage d'image."
type: docs
weight: 80
url: /fr/net/groupdocs.watermark.common/inpaintingmethod/
---
## InpaintingMethod enumeration

Spécifie l'algorithme utilisé pour le remplissage d'image.

```csharp
public enum InpaintingMethod
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| PatchBased | `0` | Inpainting basé sur des patchs (style Criminisi). Trouve des patchs de texture similaires dans la région connue et les copie dans le masque. |
| Telea | `1` | Algorithme Telea. Une méthode de marche rapide qui propage les valeurs de pixels depuis la frontière de la région vers l'intérieur. |

### Voir aussi

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
