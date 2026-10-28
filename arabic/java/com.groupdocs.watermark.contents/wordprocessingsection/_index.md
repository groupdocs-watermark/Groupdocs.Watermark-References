---
title: "WordProcessingSection"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل قسمًا من مستند Word."
type: docs
weight: 139
url: /ar/java/com.groupdocs.watermark.contents/wordprocessingsection/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class WordProcessingSection extends ContentPart
```

يمثل قسمًا من مستند Word.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPageSetup()](#getPageSetup--) | يحصل على إعداد صفحة الطباعة لهذا `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)`. |
|
|  | [getHeadersFooters()](#getHeadersFooters--) | يحصل على مجموعة جميع رؤوس وتذييلات هذا `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)`. |
|
|  | [getShapes()](#getShapes--) | يحصل على مجموعة جميع الأشكال الموجودة في هذا `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)`. |
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


يحصل على إعداد صفحة الطباعة لهذا `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)`.


**Returns:**
[WordProcessingPageSetup](../../com.groupdocs.watermark.contents/wordprocessingpagesetup) - The printing page setup for this `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)`.

### getHeadersFooters() {#getHeadersFooters--}
```
public final WordProcessingHeaderFooterCollection getHeadersFooters()
```


يحصل على مجموعة جميع رؤوس وتذييلات هذا `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)`.


**Returns:**
[WordProcessingHeaderFooterCollection](../../com.groupdocs.watermark.contents/wordprocessingheaderfootercollection) - The collection of all headers and footers of this `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)`.

### getShapes() {#getShapes--}
```
public final WordProcessingShapeCollection getShapes()
```


يحصل على مجموعة جميع الأشكال الموجودة في هذا `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)`.


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
| معامل | نوع | الوصف |
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
