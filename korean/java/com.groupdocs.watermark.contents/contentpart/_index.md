---
title: "ContentPart"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "워터마크를 배치할 수 있는 콘텐츠 페이지 프레임 머리글 또는 전체 콘텐츠의 논리적 부분을 나타냅니다."
type: docs
weight: 13
url: /ko/java/com.groupdocs.watermark.contents/contentpart/
---
**Inheritance:**
java.lang.Object
```
public abstract class ContentPart
```

콘텐츠(페이지, 프레임, 머리글 또는
전체 콘텐츠) 중 워터마크를 배치할 수 있는 논리적 부분을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getParts()](#getParts--) |  |
| [setParts(IReadOnlyList<? extends ContentPart> value)](#setParts-com.groupdocs.watermark.internal.IReadOnlyList---extends-com.groupdocs.watermark.contents.ContentPart--) |  |
| [getSearchWatermarksInParts()](#getSearchWatermarksInParts--) |  |
| [getStrategyManager()](#getStrategyManager--) |  |
|  | [findImages(ImageSearchCriteria searchCriteria)](#findImages-com.groupdocs.watermark.search.ImageSearchCriteria-) | 지정된 검색 기준에 따라 이미지를 찾습니다. |
|
|  | [findImages()](#findImages--) | 콘텐츠 내 모든 이미지를 찾습니다. |
|
|  | [search(SearchCriteria searchCriteria)](#search-com.groupdocs.watermark.search.SearchCriteria-) | 지정된 검색 기준에 따라 가능한 워터마크를 찾습니다. |
|
|  | [search()](#search--) | 콘텐츠에서 가능한 모든 워터마크를 찾습니다. |
|
| [addWatermark(Watermark watermark)](#addWatermark-com.groupdocs.watermark.Watermark-) |  |
| [afterWatermarkAdding()](#afterWatermarkAdding--) |  |
| [checkWatermarkingLicenseRestrictions(Watermark watermark)](#checkWatermarkingLicenseRestrictions-com.groupdocs.watermark.Watermark-) |  |
| [getTopParent()](#getTopParent--) |  |
| [tryGetWatermarkerSettings()](#tryGetWatermarkerSettings--) |  |
### getParts() {#getParts--}
```
public final IReadOnlyList<? extends ContentPart> getParts()
```




**Returns:**
[IReadOnlyList](../../com.groupdocs.watermark.internal/ireadonlylist)
### setParts(IReadOnlyList<? extends ContentPart> value) {#setParts-com.groupdocs.watermark.internal.IReadOnlyList---extends-com.groupdocs.watermark.contents.ContentPart--}
```
public final void setParts(IReadOnlyList<? extends ContentPart> value)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | com.groupdocs.watermark.internal.IReadOnlyList<? extends com.groupdocs.watermark.contents.ContentPart> |  |

### getSearchWatermarksInParts() {#getSearchWatermarksInParts--}
```
public boolean getSearchWatermarksInParts()
```




**Returns:**
boolean
### getStrategyManager() {#getStrategyManager--}
```
public final IStrategyManager getStrategyManager()
```




**Returns:**
[IStrategyManager](../../com.groupdocs.watermark.internal/istrategymanager)
### findImages(ImageSearchCriteria searchCriteria) {#findImages-com.groupdocs.watermark.search.ImageSearchCriteria-}
```
public final WatermarkableImageCollection findImages(ImageSearchCriteria searchCriteria)
```


지정된 검색 기준에 따라 이미지를 찾습니다.

검색은 지정된 객체에서 수행됩니다.
`[Watermarker.getSearchableObjects()](../../com.groupdocs.watermark/watermarker#getSearchableObjects--)`.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | searchCriteria | [ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria) | 사용할 검색 기준. |
|

**Returns:**
[WatermarkableImageCollection](../../com.groupdocs.watermark.contents/watermarkableimagecollection) - The collection of the found images.

### findImages() {#findImages--}
```
public final WatermarkableImageCollection findImages()
```


콘텐츠 내 모든 이미지를 찾습니다.

검색은 지정된 객체에서 수행됩니다.
`[Watermarker.getSearchableObjects()](../../com.groupdocs.watermark/watermarker#getSearchableObjects--)`.


**Returns:**
[WatermarkableImageCollection](../../com.groupdocs.watermark.contents/watermarkableimagecollection) - The collection of the found images.

### search(SearchCriteria searchCriteria) {#search-com.groupdocs.watermark.search.SearchCriteria-}
```
public final PossibleWatermarkCollection search(SearchCriteria searchCriteria)
```


지정된 검색 기준에 따라 가능한 워터마크를 찾습니다.

검색은 지정된 객체에서 수행됩니다.
`[Watermarker.getSearchableObjects()](../../com.groupdocs.watermark/watermarker#getSearchableObjects--)`.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | searchCriteria | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | 사용할 검색 기준. |
|

**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection) - The collection of the possible watermarks.

### search() {#search--}
```
public final PossibleWatermarkCollection search()
```


콘텐츠에서 가능한 모든 워터마크를 찾습니다.

검색은 지정된 객체에서 수행됩니다.
`[Watermarker.getSearchableObjects()](../../com.groupdocs.watermark/watermarker#getSearchableObjects--)`.


**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection) - The collection of the possible watermarks.

### addWatermark(Watermark watermark) {#addWatermark-com.groupdocs.watermark.Watermark-}
```
public void addWatermark(Watermark watermark)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### afterWatermarkAdding() {#afterWatermarkAdding--}
```
public void afterWatermarkAdding()
```




### checkWatermarkingLicenseRestrictions(Watermark watermark) {#checkWatermarkingLicenseRestrictions-com.groupdocs.watermark.Watermark-}
```
public void checkWatermarkingLicenseRestrictions(Watermark watermark)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### getTopParent() {#getTopParent--}
```
public final Content getTopParent()
```




**Returns:**
[Content](../../com.groupdocs.watermark.contents/content)
### tryGetWatermarkerSettings() {#tryGetWatermarkerSettings--}
```
public final WatermarkerSettings tryGetWatermarkerSettings()
```




**Returns:**
[WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings)
