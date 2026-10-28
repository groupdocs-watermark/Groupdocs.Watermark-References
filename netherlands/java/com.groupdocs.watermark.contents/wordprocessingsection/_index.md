---
title: "WordProcessingSection"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt een sectie van een Word-document voor."
type: docs
weight: 139
url: /nl/java/com.groupdocs.watermark.contents/wordprocessingsection/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class WordProcessingSection extends ContentPart
```

Stelt een sectie van een Word-document voor.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPageSetup()](#getPageSetup--) | Haalt de afdrukpagina-instelling op voor deze `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)`. |
|
|  | [getHeadersFooters()](#getHeadersFooters--) | Haalt de verzameling van alle kopteksten en voetteksten van deze `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)` op. |
|
|  | [getShapes()](#getShapes--) | Haalt de verzameling van alle vormen die in deze `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)` zijn opgenomen op. |
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


Haalt de afdrukpagina-instelling op voor deze `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)`.


**Returns:**
[WordProcessingPageSetup](../../com.groupdocs.watermark.contents/wordprocessingpagesetup) - The printing page setup for this `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)`.

### getHeadersFooters() {#getHeadersFooters--}
```
public final WordProcessingHeaderFooterCollection getHeadersFooters()
```


Haalt de verzameling van alle kopteksten en voetteksten van deze `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)` op.


**Returns:**
[WordProcessingHeaderFooterCollection](../../com.groupdocs.watermark.contents/wordprocessingheaderfootercollection) - The collection of all headers and footers of this `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)`.

### getShapes() {#getShapes--}
```
public final WordProcessingShapeCollection getShapes()
```


Haalt de verzameling van alle vormen die in deze `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)` zijn opgenomen op.


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
| Parameter | Type | Beschrijving |
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
