---
title: NotSearchCriteria
second_title: GroupDocs.Watermark for Java API Reference
description: Represents NOT composite search criteria.
type: docs
weight: 36
url: /java/com.groupdocs.watermark.search/notsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class NotSearchCriteria extends SearchCriteria
```

Represents NOT composite search criteria.
## Methods

| Method | Description |
| --- | --- |
| [getWrapped()](#getWrapped--) |  |
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### getWrapped() {#getWrapped--}
```
public final SearchCriteria getWrapped()
```




**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

