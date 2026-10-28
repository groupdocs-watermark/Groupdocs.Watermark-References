---
title: "ImageSearchCriteria"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Fornisce una classe base per i criteri di ricerca di immagini."
type: docs
weight: 32
url: /it/java/com.groupdocs.watermark.search/imagesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria)
```
public abstract class ImageSearchCriteria extends PageSearchCriteria
```

Fornisce una classe base per i criteri di ricerca di immagini.

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getMaxDifference()](#getMaxDifference--) | Ottiene la differenza massima consentita tra le immagini. |
|
|  | [setMaxDifference(double value)](#setMaxDifference-double-) | Imposta la differenza massima consentita tra le immagini. |
|
| [getStream()](#getStream--) |  |
| [getTrueImages()](#getTrueImages--) |  |
| [getFalseImages()](#getFalseImages--) |  |
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
| [resetCache()](#resetCache--) |  |
### getMaxDifference() {#getMaxDifference--}
```
public final double getMaxDifference()
```


Ottiene la differenza massima consentita tra le immagini.


**Returns:**
double - Il valore deve essere compreso tra 0 e 1. 0 significa che verranno trovate solo immagini identiche.

### setMaxDifference(double value) {#setMaxDifference-double-}
```
public final void setMaxDifference(double value)
```


Imposta la differenza massima consentita tra le immagini.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | double | Il valore deve essere compreso tra 0 e 1. 0 significa che verranno trovate solo immagini identiche. |
|

### getStream() {#getStream--}
```
public final StreamContainer getStream()
```




**Returns:**
[StreamContainer](../../com.groupdocs.watermark.internal/streamcontainer)
### getTrueImages() {#getTrueImages--}
```
public final System.Collections.Generic.List<WatermarkableImage> getTrueImages()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.groupdocs.watermark.contents.WatermarkableImage>
### getFalseImages() {#getFalseImages--}
```
public final System.Collections.Generic.List<WatermarkableImage> getFalseImages()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.groupdocs.watermark.contents.WatermarkableImage>
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

### resetCache() {#resetCache--}
```
public final void resetCache()
```




