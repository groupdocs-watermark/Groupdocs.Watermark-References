---
title: SearchCriteria
second_title: GroupDocs.Watermark for Java API Reference
description: Class that can be used to construct criteria when searching for watermarks.
type: docs
weight: 53
url: /java/com.groupdocs.watermark.search/searchcriteria/
---
**Inheritance:**
java.lang.Object
```
public abstract class SearchCriteria
```

Class that can be used to construct criteria when searching for watermarks.
## Methods

| Method | Description |
| --- | --- |
| [and(SearchCriteria other)](#and-com.groupdocs.watermark.search.SearchCriteria-) | Combines this `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` with other criteria using logical AND operator. |
| [or(SearchCriteria other)](#or-com.groupdocs.watermark.search.SearchCriteria-) | Combines this `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` with other criteria using logical OR operator. |
| [not()](#not--) | Negates this `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)`. |
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### and(SearchCriteria other) {#and-com.groupdocs.watermark.search.SearchCriteria-}
```
public final SearchCriteria and(SearchCriteria other)
```


Combines this `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` with other criteria using logical AND operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | Search criteria to combine with. |

**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.
### or(SearchCriteria other) {#or-com.groupdocs.watermark.search.SearchCriteria-}
```
public final SearchCriteria or(SearchCriteria other)
```


Combines this `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` with other criteria using logical OR operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | Search criteria to combine with. |

**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.
### not() {#not--}
```
public final SearchCriteria not()
```


Negates this `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)`.

**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.
### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public abstract boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public abstract void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | com.groupdocs.watermark.internal.ICriteriaVisitor |  |

