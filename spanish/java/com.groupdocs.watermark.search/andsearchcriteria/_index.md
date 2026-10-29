---
title: "AndSearchCriteria"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa criterios de búsqueda compuestos AND."
type: docs
weight: 10
url: /es/java/com.groupdocs.watermark.search/andsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IBinaryOperation](../../com.groupdocs.watermark.internal/ibinaryoperation)
```
public class AndSearchCriteria extends SearchCriteria implements IBinaryOperation
```

Representa criterios de búsqueda compuestos AND.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getRight()](#getRight--) | Obtiene el criterio de búsqueda derecho. |
|
|  | [getLeft()](#getLeft--) | Obtiene el criterio de búsqueda izquierdo. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### getRight() {#getRight--}
```
public final SearchCriteria getRight()
```


Obtiene el criterio de búsqueda derecho.


**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - The right search criteria.

### getLeft() {#getLeft--}
```
public final SearchCriteria getLeft()
```


Obtiene el criterio de búsqueda izquierdo.


**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - The left search criteria.

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

