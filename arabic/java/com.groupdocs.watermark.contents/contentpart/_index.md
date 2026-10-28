---
title: "ContentPart"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل أي جزء منطقي من رأس إطار صفحة المحتوى أو محتوى كامل حيث يمكن وضع العلامة المائية."
type: docs
weight: 13
url: /ar/java/com.groupdocs.watermark.contents/contentpart/
---
**Inheritance:**
java.lang.Object
```
public abstract class ContentPart
```

يمثل أي جزء منطقي من محتوى (صفحة، إطار، رأس أو
محتوى كامل) حيث يمكن وضع العلامة المائية.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getParts()](#getParts--) |  |
| [setParts(IReadOnlyList<? extends ContentPart> value)](#setParts-com.groupdocs.watermark.internal.IReadOnlyList---extends-com.groupdocs.watermark.contents.ContentPart--) |  |
| [getSearchWatermarksInParts()](#getSearchWatermarksInParts--) |  |
| [getStrategyManager()](#getStrategyManager--) |  |
|  | [findImages(ImageSearchCriteria searchCriteria)](#findImages-com.groupdocs.watermark.search.ImageSearchCriteria-) | يجد الصور وفقًا لمعايير البحث المحددة. |
|
|  | [findImages()](#findImages--) | يجد جميع الصور في المحتوى. |
|
|  | [search(SearchCriteria searchCriteria)](#search-com.groupdocs.watermark.search.SearchCriteria-) | يجد العلامات المائية المحتملة وفقًا لمعايير البحث المحددة. |
|
|  | [search()](#search--) | يجد جميع العلامات المائية المحتملة في المحتوى. |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | com.groupdocs.watermark.internal.IReadOnlyList<? extends com.groupdocs.watermark.contents.ContentPart> |  |

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


يجد الصور وفقًا لمعايير البحث المحددة.

يتم إجراء البحث في الكائنات المحددة في
`[Watermarker.getSearchableObjects()](../../com.groupdocs.watermark/watermarker#getSearchableObjects--)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | searchCriteria | [ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria) | معايير البحث للاستخدام. |
|

**Returns:**
[WatermarkableImageCollection](../../com.groupdocs.watermark.contents/watermarkableimagecollection) - The collection of the found images.

### findImages() {#findImages--}
```
public final WatermarkableImageCollection findImages()
```


يجد جميع الصور في المحتوى.

يتم إجراء البحث في الكائنات المحددة في
`[Watermarker.getSearchableObjects()](../../com.groupdocs.watermark/watermarker#getSearchableObjects--)`.


**Returns:**
[WatermarkableImageCollection](../../com.groupdocs.watermark.contents/watermarkableimagecollection) - The collection of the found images.

### search(SearchCriteria searchCriteria) {#search-com.groupdocs.watermark.search.SearchCriteria-}
```
public final PossibleWatermarkCollection search(SearchCriteria searchCriteria)
```


يجد العلامات المائية المحتملة وفقًا لمعايير البحث المحددة.

يتم إجراء البحث في الكائنات المحددة في
`[Watermarker.getSearchableObjects()](../../com.groupdocs.watermark/watermarker#getSearchableObjects--)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | searchCriteria | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | معايير البحث للاستخدام. |
|

**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection) - The collection of the possible watermarks.

### search() {#search--}
```
public final PossibleWatermarkCollection search()
```


يجد جميع العلامات المائية المحتملة في المحتوى.

يتم إجراء البحث في الكائنات المحددة في
`[Watermarker.getSearchableObjects()](../../com.groupdocs.watermark/watermarker#getSearchableObjects--)`.


**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection) - The collection of the possible watermarks.

### addWatermark(Watermark watermark) {#addWatermark-com.groupdocs.watermark.Watermark-}
```
public void addWatermark(Watermark watermark)
```




**Parameters:**
| معامل | نوع | الوصف |
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
| معامل | نوع | الوصف |
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
