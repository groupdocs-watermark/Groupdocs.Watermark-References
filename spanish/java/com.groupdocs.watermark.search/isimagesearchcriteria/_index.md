---
title: "IsImageSearchCriteria"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa criterios de búsqueda para filtrar solo marcas de agua de imágenes."
type: docs
weight: 34
url: /es/java/com.groupdocs.watermark.search/isimagesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public final class IsImageSearchCriteria extends SearchCriteria
```

Representa criterios de búsqueda para filtrar solo marcas de agua de imágenes.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [IsImageSearchCriteria()](#IsImageSearchCriteria--) | Inicializa una nueva instancia de la clase `[IsImageSearchCriteria](../../com.groupdocs.watermark.search/isimagesearchcriteria)`. |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### IsImageSearchCriteria() {#IsImageSearchCriteria--}
```
public IsImageSearchCriteria()
```


Inicializa una nueva instancia de la clase `[IsImageSearchCriteria](../../com.groupdocs.watermark.search/isimagesearchcriteria)`.


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

