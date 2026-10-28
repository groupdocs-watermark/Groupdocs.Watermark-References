---
title: "IsTextSearchCriteria"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل معايير البحث لتصفية العلامات المائية للنص فقط."
type: docs
weight: 35
url: /ar/java/com.groupdocs.watermark.search/istextsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public final class IsTextSearchCriteria extends SearchCriteria
```

يمثل معايير البحث لتصفية العلامات المائية للنص فقط.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [IsTextSearchCriteria()](#IsTextSearchCriteria--) | ينشئ مثيلًا جديدًا للفئة `[IsTextSearchCriteria](../../com.groupdocs.watermark.search/istextsearchcriteria)`. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### IsTextSearchCriteria() {#IsTextSearchCriteria--}
```
public IsTextSearchCriteria()
```


ينشئ مثيلًا جديدًا للفئة `[IsTextSearchCriteria](../../com.groupdocs.watermark.search/istextsearchcriteria)`.


### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

