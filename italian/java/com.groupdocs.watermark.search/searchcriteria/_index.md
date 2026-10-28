---
title: "SearchCriteria"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Classe che può essere utilizzata per costruire i criteri durante la ricerca di watermark."
type: docs
weight: 53
url: /it/java/com.groupdocs.watermark.search/searchcriteria/
---
**Inheritance:**
java.lang.Object
```
public abstract class SearchCriteria
```

Classe che può essere utilizzata per costruire i criteri durante la ricerca di watermark.

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [and(SearchCriteria other)](#and-com.groupdocs.watermark.search.SearchCriteria-) | Combina questo `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` con altri criteri usando l'operatore logico AND. |
|
|  | [or(SearchCriteria other)](#or-com.groupdocs.watermark.search.SearchCriteria-) | Combina questo `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` con altri criteri usando l'operatore logico OR. |
|
|  | [not()](#not--) | Nega questo `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)`. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### and(SearchCriteria other) {#and-com.groupdocs.watermark.search.SearchCriteria-}
```
public final SearchCriteria and(SearchCriteria other)
```


Combina questo `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` con altri criteri usando l'operatore logico AND.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | Criteri di ricerca da combinare. |
|

**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.

### or(SearchCriteria other) {#or-com.groupdocs.watermark.search.SearchCriteria-}
```
public final SearchCriteria or(SearchCriteria other)
```


Combina questo `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` con altri criteri usando l'operatore logico OR.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | Criteri di ricerca da combinare. |
|

**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.

### not() {#not--}
```
public final SearchCriteria not()
```


Nega questo `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)`.


**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public abstract boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public abstract void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

