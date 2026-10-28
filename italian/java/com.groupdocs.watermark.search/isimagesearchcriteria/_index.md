---
title: "IsImageSearchCriteria"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta i criteri di ricerca per filtrare solo le filigrane di immagini."
type: docs
weight: 34
url: /it/java/com.groupdocs.watermark.search/isimagesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public final class IsImageSearchCriteria extends SearchCriteria
```

Rappresenta i criteri di ricerca per filtrare solo le filigrane di immagini.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [IsImageSearchCriteria()](#IsImageSearchCriteria--) | Inizializza una nuova istanza della classe `[IsImageSearchCriteria](../../com.groupdocs.watermark.search/isimagesearchcriteria)`. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### IsImageSearchCriteria() {#IsImageSearchCriteria--}
```
public IsImageSearchCriteria()
```


Inizializza una nuova istanza della classe `[IsImageSearchCriteria](../../com.groupdocs.watermark.search/isimagesearchcriteria)`.


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

