---
title: "ContentPart"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta qualsiasi parte logica di una pagina di contenuto, cornice o intestazione o di un contenuto intero dove è possibile posizionare la filigrana."
type: docs
weight: 13
url: /it/java/com.groupdocs.watermark.contents/contentpart/
---
**Inheritance:**
java.lang.Object
```
public abstract class ContentPart
```

Rappresenta qualsiasi parte logica di un contenuto (pagina, cornice, intestazione o
un contenuto intero) dove è possibile posizionare la filigrana.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getParts()](#getParts--) |  |
| [setParts(IReadOnlyList<? extends ContentPart> value)](#setParts-com.groupdocs.watermark.internal.IReadOnlyList---extends-com.groupdocs.watermark.contents.ContentPart--) |  |
| [getSearchWatermarksInParts()](#getSearchWatermarksInParts--) |  |
| [getStrategyManager()](#getStrategyManager--) |  |
|  | [findImages(ImageSearchCriteria searchCriteria)](#findImages-com.groupdocs.watermark.search.ImageSearchCriteria-) | Trova le immagini secondo i criteri di ricerca specificati. |
|
|  | [findImages()](#findImages--) | Trova tutte le immagini nel contenuto. |
|
|  | [search(SearchCriteria searchCriteria)](#search-com.groupdocs.watermark.search.SearchCriteria-) | Trova le possibili filigrane secondo i criteri di ricerca specificati. |
|
|  | [search()](#search--) | Trova tutte le possibili filigrane nel contenuto. |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | com.groupdocs.watermark.internal.IReadOnlyList<? extends com.groupdocs.watermark.contents.ContentPart> |  |

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


Trova le immagini secondo i criteri di ricerca specificati.

La ricerca viene eseguita negli oggetti specificati in
`[Watermarker.getSearchableObjects()](../../com.groupdocs.watermark/watermarker#getSearchableObjects--)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | searchCriteria | [ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria) | I criteri di ricerca da utilizzare. |
|

**Returns:**
[WatermarkableImageCollection](../../com.groupdocs.watermark.contents/watermarkableimagecollection) - The collection of the found images.

### findImages() {#findImages--}
```
public final WatermarkableImageCollection findImages()
```


Trova tutte le immagini nel contenuto.

La ricerca viene eseguita negli oggetti specificati in
`[Watermarker.getSearchableObjects()](../../com.groupdocs.watermark/watermarker#getSearchableObjects--)`.


**Returns:**
[WatermarkableImageCollection](../../com.groupdocs.watermark.contents/watermarkableimagecollection) - The collection of the found images.

### search(SearchCriteria searchCriteria) {#search-com.groupdocs.watermark.search.SearchCriteria-}
```
public final PossibleWatermarkCollection search(SearchCriteria searchCriteria)
```


Trova le possibili filigrane secondo i criteri di ricerca specificati.

La ricerca viene eseguita negli oggetti specificati in
`[Watermarker.getSearchableObjects()](../../com.groupdocs.watermark/watermarker#getSearchableObjects--)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | searchCriteria | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | I criteri di ricerca da utilizzare. |
|

**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection) - The collection of the possible watermarks.

### search() {#search--}
```
public final PossibleWatermarkCollection search()
```


Trova tutte le possibili filigrane nel contenuto.

La ricerca viene eseguita negli oggetti specificati in
`[Watermarker.getSearchableObjects()](../../com.groupdocs.watermark/watermarker#getSearchableObjects--)`.


**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection) - The collection of the possible watermarks.

### addWatermark(Watermark watermark) {#addWatermark-com.groupdocs.watermark.Watermark-}
```
public void addWatermark(Watermark watermark)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
