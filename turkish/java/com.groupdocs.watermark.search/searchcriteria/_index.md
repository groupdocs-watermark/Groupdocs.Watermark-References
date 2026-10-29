---
title: "SearchCriteria"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Filigran ararken kriter oluşturmak için kullanılabilecek sınıf."
type: docs
weight: 53
url: /tr/java/com.groupdocs.watermark.search/searchcriteria/
---
**Inheritance:**
java.lang.Object
```
public abstract class SearchCriteria
```

Filigran ararken kriter oluşturmak için kullanılabilecek sınıf.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [and(SearchCriteria other)](#and-com.groupdocs.watermark.search.SearchCriteria-) | Bu `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` öğesini diğer kriterlerle mantıksal VE operatörü kullanarak birleştirir. |
|
|  | [or(SearchCriteria other)](#or-com.groupdocs.watermark.search.SearchCriteria-) | Bu `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` öğesini diğer kriterlerle mantıksal VEYA operatörü kullanarak birleştirir. |
|
|  | [not()](#not--) | Bu `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` öğesini olumsuzlaştırır. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### and(SearchCriteria other) {#and-com.groupdocs.watermark.search.SearchCriteria-}
```
public final SearchCriteria and(SearchCriteria other)
```


Bu `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` öğesini diğer kriterlerle mantıksal VE operatörü kullanarak birleştirir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | Birleştirilecek arama kriteri. |
|

**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.

### or(SearchCriteria other) {#or-com.groupdocs.watermark.search.SearchCriteria-}
```
public final SearchCriteria or(SearchCriteria other)
```


Bu `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` öğesini diğer kriterlerle mantıksal VEYA operatörü kullanarak birleştirir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | Birleştirilecek arama kriteri. |
|

**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.

### not() {#not--}
```
public final SearchCriteria not()
```


Bu `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` öğesini olumsuzlaştırır.


**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public abstract boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public abstract void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

