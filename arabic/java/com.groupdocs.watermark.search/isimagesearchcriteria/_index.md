---
title: "IsImageSearchCriteria"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل معايير البحث لتصفية العلامات المائية للصور فقط."
type: docs
weight: 34
url: /ar/java/com.groupdocs.watermark.search/isimagesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public final class IsImageSearchCriteria extends SearchCriteria
```

يمثل معايير البحث لتصفية العلامات المائية للصور فقط.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [IsImageSearchCriteria()](#IsImageSearchCriteria--) | ينشئ مثيلاً جديداً من الفئة `[IsImageSearchCriteria](../../com.groupdocs.watermark.search/isimagesearchcriteria)`. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### IsImageSearchCriteria() {#IsImageSearchCriteria--}
```
public IsImageSearchCriteria()
```


ينشئ مثيلاً جديداً من الفئة `[IsImageSearchCriteria](../../com.groupdocs.watermark.search/isimagesearchcriteria)`.


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

