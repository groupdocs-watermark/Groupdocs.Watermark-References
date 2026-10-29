---
title: "WordProcessingSection"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Bir Word belgesi bölümünü temsil eder."
type: docs
weight: 139
url: /tr/java/com.groupdocs.watermark.contents/wordprocessingsection/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class WordProcessingSection extends ContentPart
```

Bir Word belgesi bölümünü temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPageSetup()](#getPageSetup--) | Bu `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)` için baskı sayfa ayarlarını alır. |
|
|  | [getHeadersFooters()](#getHeadersFooters--) | Bu `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)` öğesinin tüm başlık ve altbilgi koleksiyonunu alır. |
|
|  | [getShapes()](#getShapes--) | Bu `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)` içinde bulunan tüm şekillerin koleksiyonunu alır. |
|
| [getAsposeWordsSection()](#getAsposeWordsSection--) |  |
| [getSearchWatermarksInParts()](#getSearchWatermarksInParts--) |  |
| [getContent()](#getContent--) |  |
| [addWatermark(Watermark watermark, WordProcessingShapeSettings shapeSettings, IWordProcessingWatermarkEffects effects)](#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WordProcessingShapeSettings-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-) |  |
| [getSectionIndex()](#getSectionIndex--) |  |
### getPageSetup() {#getPageSetup--}
```
public final WordProcessingPageSetup getPageSetup()
```


Bu `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)` için baskı sayfa ayarlarını alır.


**Returns:**
[WordProcessingPageSetup](../../com.groupdocs.watermark.contents/wordprocessingpagesetup) - The printing page setup for this `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)`.

### getHeadersFooters() {#getHeadersFooters--}
```
public final WordProcessingHeaderFooterCollection getHeadersFooters()
```


Bu `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)` öğesinin tüm başlık ve altbilgi koleksiyonunu alır.


**Returns:**
[WordProcessingHeaderFooterCollection](../../com.groupdocs.watermark.contents/wordprocessingheaderfootercollection) - The collection of all headers and footers of this `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)`.

### getShapes() {#getShapes--}
```
public final WordProcessingShapeCollection getShapes()
```


Bu `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)` içinde bulunan tüm şekillerin koleksiyonunu alır.


**Returns:**
[WordProcessingShapeCollection](../../com.groupdocs.watermark.contents/wordprocessingshapecollection) - The collection of all shapes contained in this `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)`.

### getAsposeWordsSection() {#getAsposeWordsSection--}
```
public final Section getAsposeWordsSection()
```




**Returns:**
com.aspose.words.Section
### getSearchWatermarksInParts() {#getSearchWatermarksInParts--}
```
public boolean getSearchWatermarksInParts()
```




**Returns:**
boolean
### getContent() {#getContent--}
```
public final WordProcessingContent getContent()
```




**Returns:**
[WordProcessingContent](../../com.groupdocs.watermark.contents/wordprocessingcontent)
### addWatermark(Watermark watermark, WordProcessingShapeSettings shapeSettings, IWordProcessingWatermarkEffects effects) {#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WordProcessingShapeSettings-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-}
```
public final void addWatermark(Watermark watermark, WordProcessingShapeSettings shapeSettings, IWordProcessingWatermarkEffects effects)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings) |  |
| effects | [IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects) |  |

### getSectionIndex() {#getSectionIndex--}
```
public final int getSectionIndex()
```




**Returns:**
int
