---
title: "NotSearchCriteria"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "DEĞİL (NOT) birleşik arama kriterlerini temsil eder."
type: docs
weight: 36
url: /tr/java/com.groupdocs.watermark.search/notsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class NotSearchCriteria extends SearchCriteria
```

DEĞİL (NOT) birleşik arama kriterlerini temsil eder.

## Yöntemler

| Yöntem | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

