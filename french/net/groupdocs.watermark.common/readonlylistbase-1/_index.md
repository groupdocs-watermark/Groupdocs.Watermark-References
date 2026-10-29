---
title: "ReadOnlyListBaseT"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Fournit la classe de base abstraite pour une liste en lecture seule fortement typée."
type: docs
weight: 110
url: /fr/net/groupdocs.watermark.common/readonlylistbase-1/
---
## ReadOnlyListBase&lt;T&gt; class

Fournit la classe de base abstraite pour une liste en lecture seule fortement typée.

```csharp
public abstract class ReadOnlyListBase<T> : IList, IList<T>
```

| Paramètre | Description |
| --- | --- |
| T | Le type de l'élément. |

## Propriétés

| Nom | Description |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Obtient le nombre d'éléments contenus dans la collection. |
| virtual [IsReadOnly](../../groupdocs.watermark.common/readonlylistbase-1/isreadonly) { get; } | Obtient une valeur indiquant si la collection est en lecture seule. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Obtient l'élément à l'index spécifié dans la collection. |

## Méthodes

| Nom | Description |
| --- | --- |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(T) | Détermine si la collection contient un élément spécifique. |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() | Renvoie un énumérateur qui parcourt une collection. |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(T) | Détermine l'index d'un élément spécifique dans la collection. |

### Voir aussi

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
