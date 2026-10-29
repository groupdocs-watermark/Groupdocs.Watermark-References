---
title: "ImageSearchCriteria"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Tillhandahåller basklass för bildsökkriterier."
type: docs
weight: 32
url: /sv/java/com.groupdocs.watermark.search/imagesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria)
```
public abstract class ImageSearchCriteria extends PageSearchCriteria
```

Tillhandahåller basklass för bildsökkriterier.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getMaxDifference()](#getMaxDifference--) | Hämtar maximalt tillåten skillnad mellan bilder. |
|
|  | [setMaxDifference(double value)](#setMaxDifference-double-) | Ställer in maximalt tillåten skillnad mellan bilder. |
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


Hämtar maximalt tillåten skillnad mellan bilder.


**Returns:**
double - Värdet bör vara mellan 0 och 1. 0 betyder att endast identiska bilder kommer att hittas.

### setMaxDifference(double value) {#setMaxDifference-double-}
```
public final void setMaxDifference(double value)
```


Ställer in maximalt tillåten skillnad mellan bilder.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | double | Värdet bör vara mellan 0 och 1. 0 betyder att endast identiska bilder kommer att hittas. |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

### resetCache() {#resetCache--}
```
public final void resetCache()
```




