---
title: "SearchCriteria"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Kelas yang dapat digunakan untuk membangun kriteria saat mencari watermark."
type: docs
weight: 53
url: /id/java/com.groupdocs.watermark.search/searchcriteria/
---
**Inheritance:**
java.lang.Object
```
public abstract class SearchCriteria
```

Kelas yang dapat digunakan untuk membangun kriteria saat mencari watermark.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [and(SearchCriteria other)](#and-com.groupdocs.watermark.search.SearchCriteria-) | Menggabungkan `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` ini dengan kriteria lain menggunakan operator logika AND. |
|
|  | [or(SearchCriteria other)](#or-com.groupdocs.watermark.search.SearchCriteria-) | Menggabungkan `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` ini dengan kriteria lain menggunakan operator logika OR. |
|
|  | [not()](#not--) | Membalikkan `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` ini. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### and(SearchCriteria other) {#and-com.groupdocs.watermark.search.SearchCriteria-}
```
public final SearchCriteria and(SearchCriteria other)
```


Menggabungkan `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` ini dengan kriteria lain menggunakan operator logika AND.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | Kriteria pencarian untuk digabungkan. |
|

**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.

### or(SearchCriteria other) {#or-com.groupdocs.watermark.search.SearchCriteria-}
```
public final SearchCriteria or(SearchCriteria other)
```


Menggabungkan `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` ini dengan kriteria lain menggunakan operator logika OR.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | Kriteria pencarian untuk digabungkan. |
|

**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.

### not() {#not--}
```
public final SearchCriteria not()
```


Membalikkan `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` ini.


**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public abstract boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public abstract void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

