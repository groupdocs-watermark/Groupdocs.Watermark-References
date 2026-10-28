---
title: "AndSearchCriteria"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示 AND 复合搜索条件。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.watermark.search/andsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IBinaryOperation](../../com.groupdocs.watermark.internal/ibinaryoperation)
```
public class AndSearchCriteria extends SearchCriteria implements IBinaryOperation
```

表示 AND 复合搜索条件。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getRight()](#getRight--) | 获取右侧搜索条件。 |
|
|  | [getLeft()](#getLeft--) | 获取左侧搜索条件。 |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### getRight() {#getRight--}
```
public final SearchCriteria getRight()
```


获取右侧搜索条件。


**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - The right search criteria.

### getLeft() {#getLeft--}
```
public final SearchCriteria getLeft()
```


获取左侧搜索条件。


**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - The left search criteria.

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

