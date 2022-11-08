---
title: ImageSearchCriteria
second_title: GroupDocs.Watermark for Java API Reference
description: Provides base class for image search criteria.
type: docs
weight: 32
url: /java/com.groupdocs.watermark.search/imagesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public abstract class ImageSearchCriteria extends SearchCriteria
```

Provides base class for image search criteria.
## Methods

| Method | Description |
| --- | --- |
| [getMaxDifference()](#getMaxDifference--) | Gets maximum allowed difference between images. |
| [setMaxDifference(double value)](#setMaxDifference-double-) | Sets maximum allowed difference between images. |
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


Gets maximum allowed difference between images.

**Returns:**
double - The value should be between 0 and 1. 0 means that only identical images will be found.
### setMaxDifference(double value) {#setMaxDifference-double-}
```
public final void setMaxDifference(double value)
```


Sets maximum allowed difference between images.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The value should be between 0 and 1. 0 means that only identical images will be found. |

### getStream() {#getStream--}
```
public final StreamContainer getStream()
```




**Returns:**
com.groupdocs.watermark.internal.StreamContainer
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
| Parameter | Type | Description |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | com.groupdocs.watermark.internal.ICriteriaVisitor |  |

### resetCache() {#resetCache--}
```
public final void resetCache()
```




