---
title: "SearchCriteria"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "الفئة التي يمكن استخدامها لإنشاء معايير عند البحث عن العلامات المائية."
type: docs
weight: 53
url: /ar/java/com.groupdocs.watermark.search/searchcriteria/
---
**Inheritance:**
java.lang.Object
```
public abstract class SearchCriteria
```

الفئة التي يمكن استخدامها لإنشاء معايير عند البحث عن العلامات المائية.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [and(SearchCriteria other)](#and-com.groupdocs.watermark.search.SearchCriteria-) | يجمع هذا `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` مع معايير أخرى باستخدام عامل AND المنطقي. |
|
|  | [or(SearchCriteria other)](#or-com.groupdocs.watermark.search.SearchCriteria-) | يجمع هذا `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` مع معايير أخرى باستخدام عامل OR المنطقي. |
|
|  | [not()](#not--) | ينفي هذا `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)`. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### and(SearchCriteria other) {#and-com.groupdocs.watermark.search.SearchCriteria-}
```
public final SearchCriteria and(SearchCriteria other)
```


يجمع هذا `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` مع معايير أخرى باستخدام عامل AND المنطقي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | معايير البحث للدمج معها. |
|

**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.

### or(SearchCriteria other) {#or-com.groupdocs.watermark.search.SearchCriteria-}
```
public final SearchCriteria or(SearchCriteria other)
```


يجمع هذا `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` مع معايير أخرى باستخدام عامل OR المنطقي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | معايير البحث للدمج معها. |
|

**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.

### not() {#not--}
```
public final SearchCriteria not()
```


ينفي هذا `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)`.


**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public abstract boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public abstract void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

