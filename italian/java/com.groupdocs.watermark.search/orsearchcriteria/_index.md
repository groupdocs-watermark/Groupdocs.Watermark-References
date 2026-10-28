---
title: "OrSearchCriteria"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta i criteri di ricerca compositi OR."
type: docs
weight: 37
url: /it/java/com.groupdocs.watermark.search/orsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IBinaryOperation](../../com.groupdocs.watermark.internal/ibinaryoperation)
```
public class OrSearchCriteria extends SearchCriteria implements IBinaryOperation
```

Rappresenta i criteri di ricerca compositi OR.

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getLeft()](#getLeft--) | Ottiene il criterio di ricerca a sinistra. |
|
|  | [getRight()](#getRight--) | Ottiene il criterio di ricerca a destra. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### getLeft() {#getLeft--}
```
public final SearchCriteria getLeft()
```


Ottiene il criterio di ricerca a sinistra.


**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - The left search criteria.

### getRight() {#getRight--}
```
public final SearchCriteria getRight()
```


Ottiene il criterio di ricerca a destra.


**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - The right search criteria.

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

