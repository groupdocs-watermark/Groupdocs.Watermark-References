---
title: "SearchCriteria"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "可用于在搜索水印时构建条件的类。"
type: docs
weight: 53
url: /zh/java/com.groupdocs.watermark.search/searchcriteria/
---
**Inheritance:**
java.lang.Object
```
public abstract class SearchCriteria
```

可用于在搜索水印时构建条件的类。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [and(SearchCriteria other)](#and-com.groupdocs.watermark.search.SearchCriteria-) | 将此 `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` 与其他条件使用逻辑 AND 运算符组合。 |
|
|  | [or(SearchCriteria other)](#or-com.groupdocs.watermark.search.SearchCriteria-) | 将此 `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` 与其他条件使用逻辑 OR 运算符组合。 |
|
|  | [not()](#not--) | 否定此 `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)`。 |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### and(SearchCriteria other) {#and-com.groupdocs.watermark.search.SearchCriteria-}
```
public final SearchCriteria and(SearchCriteria other)
```


将此 `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` 与其他条件使用逻辑 AND 运算符组合。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | 要组合的搜索条件。 |
|

**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.

### or(SearchCriteria other) {#or-com.groupdocs.watermark.search.SearchCriteria-}
```
public final SearchCriteria or(SearchCriteria other)
```


将此 `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` 与其他条件使用逻辑 OR 运算符组合。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | 要组合的搜索条件。 |
|

**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.

### not() {#not--}
```
public final SearchCriteria not()
```


否定此 `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)`。


**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public abstract boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public abstract void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

