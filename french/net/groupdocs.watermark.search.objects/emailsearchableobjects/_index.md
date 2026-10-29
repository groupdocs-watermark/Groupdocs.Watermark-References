---
title: "EmailSearchableObjects"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Spécifie les indicateurs représentant les objets de message électronique qui doivent être inclus dans une recherche de filigrane."
type: docs
weight: 2520
url: /fr/net/groupdocs.watermark.search.objects/emailsearchableobjects/
---
## EmailSearchableObjects enumeration

Spécifie les indicateurs représentant les objets de message électronique qui doivent être inclus dans une recherche de filigrane.

```csharp
[Flags]
public enum EmailSearchableObjects
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| None | `0` | Spécifie aucun objet de recherche. |
| Subject | `1` | Rechercher dans l'objet du message. |
| PlainTextBody | `2` | Rechercher dans le corps du message en texte brut. |
| HtmlBody | `4` | Rechercher dans le corps HTML du message. |
| AttachedImages | `8` | Rechercher dans les images jointes. |
| EmbeddedImages | `10` | Rechercher dans les images intégrées. |
| All | `1F` | Rechercher dans tous les objets d'e-mail. |

### Voir aussi

* namespace [GroupDocs.Watermark.Search.Objects](../../groupdocs.watermark.search.objects)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
