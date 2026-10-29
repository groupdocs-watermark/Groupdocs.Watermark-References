---
title: "ContentPart"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Bir içerik sayfa çerçevesi başlığı veya bir bütün içerik içinde filigranın yerleştirilebileceği herhangi bir mantıksal bölümü temsil eder."
type: docs
weight: 13
url: /tr/java/com.groupdocs.watermark.contents/contentpart/
---
**Inheritance:**
java.lang.Object
```
public abstract class ContentPart
```

Bir içeriğin (sayfa, çerçeve, başlık veya
bir bütün içerik) içinde filigranın yerleştirilebileceği herhangi bir mantıksal bölümü temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getParts()](#getParts--) |  |
| [setParts(IReadOnlyList<? extends ContentPart> value)](#setParts-com.groupdocs.watermark.internal.IReadOnlyList---extends-com.groupdocs.watermark.contents.ContentPart--) |  |
| [getSearchWatermarksInParts()](#getSearchWatermarksInParts--) |  |
| [getStrategyManager()](#getStrategyManager--) |  |
|  | [findImages(ImageSearchCriteria searchCriteria)](#findImages-com.groupdocs.watermark.search.ImageSearchCriteria-) | Belirtilen arama kriterlerine göre görüntüleri bulur. |
|
|  | [findImages()](#findImages--) | İçerikteki tüm görüntüleri bulur. |
|
|  | [search(SearchCriteria searchCriteria)](#search-com.groupdocs.watermark.search.SearchCriteria-) | Belirtilen arama kriterlerine göre olası filigranları bulur. |
|
|  | [search()](#search--) | İçerikteki tüm olası filigranları bulur. |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | com.groupdocs.watermark.internal.IReadOnlyList<? extends com.groupdocs.watermark.contents.ContentPart> |  |

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


Belirtilen arama kriterlerine göre görüntüleri bulur.

Arama, belirtilen nesneler içinde gerçekleştirilir
`[Watermarker.getSearchableObjects()](../../com.groupdocs.watermark/watermarker#getSearchableObjects--)`.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | searchCriteria | [ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria) | Kullanılacak arama kriterleri. |
|

**Returns:**
[WatermarkableImageCollection](../../com.groupdocs.watermark.contents/watermarkableimagecollection) - The collection of the found images.

### findImages() {#findImages--}
```
public final WatermarkableImageCollection findImages()
```


İçerikteki tüm görüntüleri bulur.

Arama, belirtilen nesneler içinde gerçekleştirilir
`[Watermarker.getSearchableObjects()](../../com.groupdocs.watermark/watermarker#getSearchableObjects--)`.


**Returns:**
[WatermarkableImageCollection](../../com.groupdocs.watermark.contents/watermarkableimagecollection) - The collection of the found images.

### search(SearchCriteria searchCriteria) {#search-com.groupdocs.watermark.search.SearchCriteria-}
```
public final PossibleWatermarkCollection search(SearchCriteria searchCriteria)
```


Belirtilen arama kriterlerine göre olası filigranları bulur.

Arama, belirtilen nesneler içinde gerçekleştirilir
`[Watermarker.getSearchableObjects()](../../com.groupdocs.watermark/watermarker#getSearchableObjects--)`.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | searchCriteria | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | Kullanılacak arama kriterleri. |
|

**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection) - The collection of the possible watermarks.

### search() {#search--}
```
public final PossibleWatermarkCollection search()
```


İçerikteki tüm olası filigranları bulur.

Arama, belirtilen nesneler içinde gerçekleştirilir
`[Watermarker.getSearchableObjects()](../../com.groupdocs.watermark/watermarker#getSearchableObjects--)`.


**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection) - The collection of the possible watermarks.

### addWatermark(Watermark watermark) {#addWatermark-com.groupdocs.watermark.Watermark-}
```
public void addWatermark(Watermark watermark)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
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
