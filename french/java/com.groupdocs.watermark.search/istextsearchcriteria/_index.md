---
title: "IsTextSearchCriteria"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente les critères de recherche pour filtrer uniquement les filigranes de texte."
type: docs
weight: 35
url: /fr/java/com.groupdocs.watermark.search/istextsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public final class IsTextSearchCriteria extends SearchCriteria
```

Représente les critères de recherche pour filtrer uniquement les filigranes de texte.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [IsTextSearchCriteria()](#IsTextSearchCriteria--) | Initialise une nouvelle instance de la classe `[IsTextSearchCriteria](../../com.groupdocs.watermark.search/istextsearchcriteria)`. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### IsTextSearchCriteria() {#IsTextSearchCriteria--}
```
public IsTextSearchCriteria()
```


Initialise une nouvelle instance de la classe `[IsTextSearchCriteria](../../com.groupdocs.watermark.search/istextsearchcriteria)`.


### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

