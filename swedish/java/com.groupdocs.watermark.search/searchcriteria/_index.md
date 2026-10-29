---
title: "SearchCriteria"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Klass som kan användas för att konstruera kriterier vid sökning efter vattenstämplar."
type: docs
weight: 53
url: /sv/java/com.groupdocs.watermark.search/searchcriteria/
---
**Inheritance:**
java.lang.Object
```
public abstract class SearchCriteria
```

Klass som kan användas för att konstruera kriterier vid sökning efter vattenstämplar.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [and(SearchCriteria other)](#and-com.groupdocs.watermark.search.SearchCriteria-) | Kombinerar detta `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` med andra kriterier med hjälp av logisk OCH-operator. |
|
|  | [or(SearchCriteria other)](#or-com.groupdocs.watermark.search.SearchCriteria-) | Kombinerar detta `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` med andra kriterier med hjälp av logisk ELLER-operator. |
|
|  | [not()](#not--) | Negerar detta `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)`. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### and(SearchCriteria other) {#and-com.groupdocs.watermark.search.SearchCriteria-}
```
public final SearchCriteria and(SearchCriteria other)
```


Kombinerar detta `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` med andra kriterier med hjälp av logisk OCH-operator.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | Sök-kriterier att kombinera med. |
|

**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.

### or(SearchCriteria other) {#or-com.groupdocs.watermark.search.SearchCriteria-}
```
public final SearchCriteria or(SearchCriteria other)
```


Kombinerar detta `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` med andra kriterier med hjälp av logisk ELLER-operator.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | Sök-kriterier att kombinera med. |
|

**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.

### not() {#not--}
```
public final SearchCriteria not()
```


Negerar detta `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)`.


**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public abstract boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public abstract void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

