---
title: "OrSearchCriteria"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili kriteria pencarian komposit OR."
type: docs
weight: 37
url: /id/java/com.groupdocs.watermark.search/orsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IBinaryOperation](../../com.groupdocs.watermark.internal/ibinaryoperation)
```
public class OrSearchCriteria extends SearchCriteria implements IBinaryOperation
```

Mewakili kriteria pencarian komposit OR.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getLeft()](#getLeft--) | Mendapatkan kriteria pencarian kiri. |
|
|  | [getRight()](#getRight--) | Mendapatkan kriteria pencarian kanan. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### getLeft() {#getLeft--}
```
public final SearchCriteria getLeft()
```


Mendapatkan kriteria pencarian kiri.


**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - The left search criteria.

### getRight() {#getRight--}
```
public final SearchCriteria getRight()
```


Mendapatkan kriteria pencarian kanan.


**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - The right search criteria.

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

