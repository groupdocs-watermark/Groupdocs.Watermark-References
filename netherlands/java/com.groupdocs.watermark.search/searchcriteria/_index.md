---
title: "SearchCriteria"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Klasse die kan worden gebruikt om criteria samen te stellen bij het zoeken naar watermerken."
type: docs
weight: 53
url: /nl/java/com.groupdocs.watermark.search/searchcriteria/
---
**Inheritance:**
java.lang.Object
```
public abstract class SearchCriteria
```

Klasse die kan worden gebruikt om criteria samen te stellen bij het zoeken naar watermerken.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [and(SearchCriteria other)](#and-com.groupdocs.watermark.search.SearchCriteria-) | Combineert dit `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` met andere criteria met behulp van de logische AND-operator. |
|
|  | [or(SearchCriteria other)](#or-com.groupdocs.watermark.search.SearchCriteria-) | Combineert dit `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` met andere criteria met behulp van de logische OR-operator. |
|
|  | [not()](#not--) | Negateert dit `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)`. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### and(SearchCriteria other) {#and-com.groupdocs.watermark.search.SearchCriteria-}
```
public final SearchCriteria and(SearchCriteria other)
```


Combineert dit `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` met andere criteria met behulp van de logische AND-operator.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | Zoekcriteria om mee te combineren. |
|

**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.

### or(SearchCriteria other) {#or-com.groupdocs.watermark.search.SearchCriteria-}
```
public final SearchCriteria or(SearchCriteria other)
```


Combineert dit `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` met andere criteria met behulp van de logische OR-operator.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | Zoekcriteria om mee te combineren. |
|

**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.

### not() {#not--}
```
public final SearchCriteria not()
```


Negateert dit `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)`.


**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public abstract boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public abstract void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

