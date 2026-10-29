---
title: "RemoveOnlyListBaseT"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Fournit la classe de base abstraite pour une liste en suppression uniquement fortement typée."
type: docs
weight: 130
url: /fr/net/groupdocs.watermark.common/removeonlylistbase-1/
---
## RemoveOnlyListBase&lt;T&gt; class

Fournit la classe de base abstraite pour une liste en suppression uniquement fortement typée.

```csharp
public abstract class RemoveOnlyListBase<T> : ReadOnlyListBase<T>
```

| Paramètre | Description |
| --- | --- |
| T | Le type de l'élément. |

## Propriétés

| Nom | Description |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Obtient le nombre d'éléments contenus dans la collection. |
| override [IsReadOnly](../../groupdocs.watermark.common/removeonlylistbase-1/isreadonly) { get; } | Obtient une valeur indiquant si la collection est en lecture seule. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Obtient l'élément à l'index spécifié dans la collection. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() | Supprime tous les éléments de la collection. |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(T) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(T) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(T) | Supprime la première occurrence d'un objet spécifique de la collection. |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) | Supprime l'élément à l'index spécifié. |

### Voir aussi

* class [ReadOnlyListBase&lt;T&gt;](../readonlylistbase-1)
* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
