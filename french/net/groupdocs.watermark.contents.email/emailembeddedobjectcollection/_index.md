---
title: "EmailEmbeddedObjectCollection"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente une collection d'objets intégrés dans un message électronique."
type: docs
weight: 380
url: /fr/net/groupdocs.watermark.contents.email/emailembeddedobjectcollection/
---
## EmailEmbeddedObjectCollection class

Représente une collection d'objets intégrés dans un message électronique.

```csharp
public class EmailEmbeddedObjectCollection : RemoveOnlyListBase<EmailEmbeddedObject>
```

## Propriétés

| Nom | Description |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Obtient le nombre d'éléments contenus dans la collection. |
| override [IsReadOnly](../../groupdocs.watermark.common/removeonlylistbase-1/isreadonly) { get; } | Obtient une valeur indiquant si la collection est en lecture seule. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Obtient l'élément à l'index spécifié dans la collection. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.email/emailembeddedobjectcollection/add)(byte[], string) | Ajoute une ressource intégrée à [`EmailContent`](../emailcontent). |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() |  |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(EmailEmbeddedObject) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(EmailEmbeddedObject) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(EmailEmbeddedObject) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### Remarques

Cette collection contient les éléments de type [`EmailEmbeddedObject`](../emailembeddedobject).

### Voir aussi

* class [RemoveOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/removeonlylistbase-1)
* class [EmailEmbeddedObject](../emailembeddedobject)
* namespace [GroupDocs.Watermark.Contents.Email](../../groupdocs.watermark.contents.email)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
