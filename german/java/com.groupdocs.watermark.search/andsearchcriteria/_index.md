---
title: "AndSearchCriteria"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt AND‑zusammengesetzte Suchkriterien dar."
type: docs
weight: 10
url: /de/java/com.groupdocs.watermark.search/andsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IBinaryOperation](../../com.groupdocs.watermark.internal/ibinaryoperation)
```
public class AndSearchCriteria extends SearchCriteria implements IBinaryOperation
```

Stellt AND‑zusammengesetzte Suchkriterien dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getRight()](#getRight--) | Gibt das rechte Suchkriterium zurück. |
|
|  | [getLeft()](#getLeft--) | Gibt das linke Suchkriterium zurück. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### getRight() {#getRight--}
```
public final SearchCriteria getRight()
```


Gibt das rechte Suchkriterium zurück.


**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - The right search criteria.

### getLeft() {#getLeft--}
```
public final SearchCriteria getLeft()
```


Gibt das linke Suchkriterium zurück.


**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - The left search criteria.

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

