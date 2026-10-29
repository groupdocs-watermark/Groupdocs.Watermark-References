---
title: "FromExtension"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Mappe l'extension de fichier au type de fichier."
type: docs
weight: 590
url: /fr/net/groupdocs.watermark.common/filetype/fromextension/
---
## FileType.FromExtension method

Mappe l'extension de fichier au type de fichier.

```csharp
public static FileType FromExtension(string extension)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| extension | String | L'extension de fichier (y compris le point "."). |

### Valeur de retour

Lorsque le type de fichier est pris en charge, le renvoie ; sinon, renvoie le type de fichier par défaut [`Unknown`](../unknown).

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancée lorsque *extension* est null ou chaîne vide. |

### Voir aussi

* class [FileType](../../filetype)
* namespace [GroupDocs.Watermark.Common](../../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
