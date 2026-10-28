---
title: "SearchCriteria"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Klasse, die verwendet werden kann, um Kriterien beim Suchen nach Wasserzeichen zu erstellen."
type: docs
weight: 53
url: /de/java/com.groupdocs.watermark.search/searchcriteria/
---
**Inheritance:**
java.lang.Object
```
public abstract class SearchCriteria
```

Klasse, die verwendet werden kann, um Kriterien beim Suchen nach Wasserzeichen zu erstellen.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [and(SearchCriteria other)](#and-com.groupdocs.watermark.search.SearchCriteria-) | Kombiniert dieses `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` mit anderen Kriterien mittels logischem UND-Operator. |
|
|  | [or(SearchCriteria other)](#or-com.groupdocs.watermark.search.SearchCriteria-) | Kombiniert dieses `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` mit anderen Kriterien unter Verwendung des logischen ODER-Operators. |
|
|  | [not()](#not--) | Negiert dieses `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)`. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### and(SearchCriteria other) {#and-com.groupdocs.watermark.search.SearchCriteria-}
```
public final SearchCriteria and(SearchCriteria other)
```


Kombiniert dieses `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` mit anderen Kriterien mittels logischem UND-Operator.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | Suchkriterien, mit denen kombiniert werden soll. |
|

**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.

### or(SearchCriteria other) {#or-com.groupdocs.watermark.search.SearchCriteria-}
```
public final SearchCriteria or(SearchCriteria other)
```


Kombiniert dieses `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` mit anderen Kriterien unter Verwendung des logischen ODER-Operators.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | Suchkriterien, mit denen kombiniert werden soll. |
|

**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.

### not() {#not--}
```
public final SearchCriteria not()
```


Negiert dieses `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)`.


**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public abstract boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public abstract void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

