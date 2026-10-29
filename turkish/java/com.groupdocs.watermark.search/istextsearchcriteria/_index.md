---
title: "IsTextSearchCriteria"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Yalnızca metin filigranlarını filtrelemek için arama kriterlerini temsil eder."
type: docs
weight: 35
url: /tr/java/com.groupdocs.watermark.search/istextsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public final class IsTextSearchCriteria extends SearchCriteria
```

Yalnızca metin filigranlarını filtrelemek için arama kriterlerini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [IsTextSearchCriteria()](#IsTextSearchCriteria--) | Yeni bir `[IsTextSearchCriteria](../../com.groupdocs.watermark.search/istextsearchcriteria)` sınıf örneği başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### IsTextSearchCriteria() {#IsTextSearchCriteria--}
```
public IsTextSearchCriteria()
```


Yeni bir `[IsTextSearchCriteria](../../com.groupdocs.watermark.search/istextsearchcriteria)` sınıf örneği başlatır.


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

