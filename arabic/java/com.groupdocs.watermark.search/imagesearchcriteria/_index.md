---
title: "ImageSearchCriteria"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يوفر فئة أساسية لمعايير البحث عن الصور."
type: docs
weight: 32
url: /ar/java/com.groupdocs.watermark.search/imagesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria)
```
public abstract class ImageSearchCriteria extends PageSearchCriteria
```

يوفر فئة أساسية لمعايير البحث عن الصور.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getMaxDifference()](#getMaxDifference--) | يحصل على الحد الأقصى المسموح به للاختلاف بين الصور. |
|
|  | [setMaxDifference(double value)](#setMaxDifference-double-) | يضبط الحد الأقصى المسموح به للاختلاف بين الصور. |
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


يحصل على الحد الأقصى المسموح به للاختلاف بين الصور.


**Returns:**
double - يجب أن تكون القيمة بين 0 و 1. 0 يعني أنه سيتم العثور فقط على الصور المتطابقة.

### setMaxDifference(double value) {#setMaxDifference-double-}
```
public final void setMaxDifference(double value)
```


يضبط الحد الأقصى المسموح به للاختلاف بين الصور.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | يجب أن تكون القيمة بين 0 و 1. 0 يعني أنه سيتم العثور فقط على الصور المتطابقة. |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

### resetCache() {#resetCache--}
```
public final void resetCache()
```




