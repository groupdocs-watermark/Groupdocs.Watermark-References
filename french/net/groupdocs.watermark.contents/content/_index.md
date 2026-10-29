---
title: "Contenu"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente un contenu où un filigrane peut être placé."
type: docs
weight: 150
url: /fr/net/groupdocs.watermark.contents/content/
---
## Content class

Représente un contenu où un filigrane peut être placé.

```csharp
public abstract class Content : ContentPart, IDisposable
```

## Méthodes

| Nom | Description |
| --- | --- |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Libère l'instance actuelle. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Trouve toutes les images dans le contenu. La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Trouve les images selon les critères de recherche spécifiés. La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Trouve tous les filigranes possibles dans le contenu. La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Trouve les filigranes possibles selon les critères de recherche spécifiés. La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Voir aussi

* class [ContentPart](../contentpart)
* namespace [GroupDocs.Watermark.Contents](../../groupdocs.watermark.contents)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
