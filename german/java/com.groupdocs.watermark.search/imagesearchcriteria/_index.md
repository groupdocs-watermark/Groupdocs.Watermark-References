---
title: "ImageSearchCriteria"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt eine Basisklasse für Bildsuchkriterien bereit."
type: docs
weight: 32
url: /de/java/com.groupdocs.watermark.search/imagesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria)
```
public abstract class ImageSearchCriteria extends PageSearchCriteria
```

Stellt eine Basisklasse für Bildsuchkriterien bereit.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getMaxDifference()](#getMaxDifference--) | Ruft die maximal zulässige Differenz zwischen Bildern ab. |
|
|  | [setMaxDifference(double value)](#setMaxDifference-double-) | Legt die maximal zulässige Differenz zwischen Bildern fest. |
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


Ruft die maximal zulässige Differenz zwischen Bildern ab.


**Returns:**
double - Der Wert sollte zwischen 0 und 1 liegen. 0 bedeutet, dass nur identische Bilder gefunden werden.

### setMaxDifference(double value) {#setMaxDifference-double-}
```
public final void setMaxDifference(double value)
```


Legt die maximal zulässige Differenz zwischen Bildern fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | double | Der Wert sollte zwischen 0 und 1 liegen. 0 bedeutet, dass nur identische Bilder gefunden werden. |
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

### resetCache() {#resetCache--}
```
public final void resetCache()
```




