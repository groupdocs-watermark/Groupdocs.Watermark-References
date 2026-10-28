---
title: "ImageSearchCriteria"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "이미지 검색 기준에 대한 기본 클래스를 제공합니다."
type: docs
weight: 32
url: /ko/java/com.groupdocs.watermark.search/imagesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria)
```
public abstract class ImageSearchCriteria extends PageSearchCriteria
```

이미지 검색 기준에 대한 기본 클래스를 제공합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getMaxDifference()](#getMaxDifference--) | 이미지 간 허용되는 최대 차이를 가져옵니다. |
|
|  | [setMaxDifference(double value)](#setMaxDifference-double-) | 이미지 간 허용되는 최대 차이를 설정합니다. |
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


이미지 간 허용되는 최대 차이를 가져옵니다.


**Returns:**
double - 값은 0과 1 사이여야 합니다. 0은 동일한 이미지만 검색된다는 의미입니다.

### setMaxDifference(double value) {#setMaxDifference-double-}
```
public final void setMaxDifference(double value)
```


이미지 간 허용되는 최대 차이를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | double | 값은 0과 1 사이여야 합니다. 0은 동일한 이미지만 검색된다는 의미입니다. |
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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

### resetCache() {#resetCache--}
```
public final void resetCache()
```




