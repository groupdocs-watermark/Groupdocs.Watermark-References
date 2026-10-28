---
title: "SearchCriteria"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "워터마크 검색 시 기준을 구성하는 데 사용할 수 있는 클래스입니다."
type: docs
weight: 53
url: /ko/java/com.groupdocs.watermark.search/searchcriteria/
---
**Inheritance:**
java.lang.Object
```
public abstract class SearchCriteria
```

워터마크 검색 시 기준을 구성하는 데 사용할 수 있는 클래스입니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [and(SearchCriteria other)](#and-com.groupdocs.watermark.search.SearchCriteria-) | 논리 AND 연산자를 사용하여 이 `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)`를 다른 기준과 결합합니다. |
|
|  | [or(SearchCriteria other)](#or-com.groupdocs.watermark.search.SearchCriteria-) | 논리 OR 연산자를 사용하여 이 `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)`를 다른 기준과 결합합니다. |
|
|  | [not()](#not--) | 이 `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)`를 부정합니다. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### and(SearchCriteria other) {#and-com.groupdocs.watermark.search.SearchCriteria-}
```
public final SearchCriteria and(SearchCriteria other)
```


논리 AND 연산자를 사용하여 이 `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)`를 다른 기준과 결합합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | other | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | 결합할 검색 기준. |
|

**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.

### or(SearchCriteria other) {#or-com.groupdocs.watermark.search.SearchCriteria-}
```
public final SearchCriteria or(SearchCriteria other)
```


논리 OR 연산자를 사용하여 이 `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)`를 다른 기준과 결합합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | other | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | 결합할 검색 기준. |
|

**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.

### not() {#not--}
```
public final SearchCriteria not()
```


이 `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)`를 부정합니다.


**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public abstract boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public abstract void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

