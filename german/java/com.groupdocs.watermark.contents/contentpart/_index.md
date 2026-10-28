---
title: "ContentPart"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt einen beliebigen logischen Teil einer Inhaltsseiten‑Rahmen‑Kopfzeile oder eines gesamten Inhalts dar, in dem ein Wasserzeichen platziert werden kann."
type: docs
weight: 13
url: /de/java/com.groupdocs.watermark.contents/contentpart/
---
**Inheritance:**
java.lang.Object
```
public abstract class ContentPart
```

Stellt einen beliebigen logischen Teil eines Inhalts (Seite, Rahmen, Kopfzeile oder
einen gesamten Inhalt) dar, in dem ein Wasserzeichen platziert werden kann.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getParts()](#getParts--) |  |
| [setParts(IReadOnlyList<? extends ContentPart> value)](#setParts-com.groupdocs.watermark.internal.IReadOnlyList---extends-com.groupdocs.watermark.contents.ContentPart--) |  |
| [getSearchWatermarksInParts()](#getSearchWatermarksInParts--) |  |
| [getStrategyManager()](#getStrategyManager--) |  |
|  | [findImages(ImageSearchCriteria searchCriteria)](#findImages-com.groupdocs.watermark.search.ImageSearchCriteria-) | Findet Bilder gemäß den angegebenen Suchkriterien. |
|
|  | [findImages()](#findImages--) | Findet alle Bilder im Inhalt. |
|
|  | [search(SearchCriteria searchCriteria)](#search-com.groupdocs.watermark.search.SearchCriteria-) | Findet mögliche Wasserzeichen gemäß den angegebenen Suchkriterien. |
|
|  | [search()](#search--) | Findet alle möglichen Wasserzeichen im Inhalt. |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | com.groupdocs.watermark.internal.IReadOnlyList<? extends com.groupdocs.watermark.contents.ContentPart> |  |

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


Findet Bilder gemäß den angegebenen Suchkriterien.

Die Suche wird in den angegebenen Objekten durchgeführt
`[Watermarker.getSearchableObjects()](../../com.groupdocs.watermark/watermarker#getSearchableObjects--)`.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | searchCriteria | [ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria) | Die zu verwendenden Suchkriterien. |
|

**Returns:**
[WatermarkableImageCollection](../../com.groupdocs.watermark.contents/watermarkableimagecollection) - The collection of the found images.

### findImages() {#findImages--}
```
public final WatermarkableImageCollection findImages()
```


Findet alle Bilder im Inhalt.

Die Suche wird in den angegebenen Objekten durchgeführt
`[Watermarker.getSearchableObjects()](../../com.groupdocs.watermark/watermarker#getSearchableObjects--)`.


**Returns:**
[WatermarkableImageCollection](../../com.groupdocs.watermark.contents/watermarkableimagecollection) - The collection of the found images.

### search(SearchCriteria searchCriteria) {#search-com.groupdocs.watermark.search.SearchCriteria-}
```
public final PossibleWatermarkCollection search(SearchCriteria searchCriteria)
```


Findet mögliche Wasserzeichen gemäß den angegebenen Suchkriterien.

Die Suche wird in den angegebenen Objekten durchgeführt
`[Watermarker.getSearchableObjects()](../../com.groupdocs.watermark/watermarker#getSearchableObjects--)`.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | searchCriteria | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | Die zu verwendenden Suchkriterien. |
|

**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection) - The collection of the possible watermarks.

### search() {#search--}
```
public final PossibleWatermarkCollection search()
```


Findet alle möglichen Wasserzeichen im Inhalt.

Die Suche wird in den angegebenen Objekten durchgeführt
`[Watermarker.getSearchableObjects()](../../com.groupdocs.watermark/watermarker#getSearchableObjects--)`.


**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection) - The collection of the possible watermarks.

### addWatermark(Watermark watermark) {#addWatermark-com.groupdocs.watermark.Watermark-}
```
public void addWatermark(Watermark watermark)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
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
