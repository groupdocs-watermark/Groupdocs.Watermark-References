---
title: "Search"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Recherche toutes les filigranes possibles dans le document."
type: docs
weight: 110
url: /fr/net/groupdocs.watermark/watermarker/search/
---
## Search() {#search}

Recherche toutes les filigranes possibles dans le document.

```csharp
public PossibleWatermarkCollection Search()
```

### Valeur de retour

La collection des filigranes possibles.

### Remarques

La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../searchableobjects).

En savoir plus sur la recherche de filigranes [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Exemples

Compter les filigranes possibles dans un document de tout type pris en charge.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    PossibleWatermarkCollection watermarks = watermarker.Search();
    Console.WrileLine(watermarks.Count);
}
```

### Voir aussi

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Search(SearchCriteria) {#search_1}

Recherche les filigranes possibles selon les critères de recherche spécifiés.

```csharp
public PossibleWatermarkCollection Search(SearchCriteria searchCriteria)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| searchCriteria | SearchCriteria | Les critères de recherche à utiliser. |

### Valeur de retour

La collection des filigranes possibles.

### Remarques

La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../searchableobjects).

En savoir plus sur la recherche de filigranes [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Exemples

Trouver et supprimer tous les filigranes possibles contenant un texte ou une image particuliers d'un document de tout type pris en charge.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria(@"D:\logo.png");
    Regex regex = new Regex(@"^Company\sName$", RegexOptions.IgnoreCase);
    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(regex);
    PossibleWatermarkCollection watermarks = watermarker.Search(textSearchCriteria.Or(imageSearchCriteria));
    watermarks.Clear();
    watermarker.Save(@"D:\output.doc");
}
```

### Voir aussi

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [SearchCriteria](../../../groupdocs.watermark.search.searchcriteria/searchcriteria)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
