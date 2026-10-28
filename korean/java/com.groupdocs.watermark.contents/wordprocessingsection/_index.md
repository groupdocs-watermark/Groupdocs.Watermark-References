---
title: "WordProcessingSection"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "Word 문서 섹션을 나타냅니다."
type: docs
weight: 139
url: /ko/java/com.groupdocs.watermark.contents/wordprocessingsection/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class WordProcessingSection extends ContentPart
```

Word 문서 섹션을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPageSetup()](#getPageSetup--) | 이 `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)`의 인쇄 페이지 설정을 가져옵니다. |
|
|  | [getHeadersFooters()](#getHeadersFooters--) | 이 `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)`의 모든 머리글 및 바닥글 컬렉션을 가져옵니다. |
|
|  | [getShapes()](#getShapes--) | 이 `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)`에 포함된 모든 도형 컬렉션을 가져옵니다. |
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


이 `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)`의 인쇄 페이지 설정을 가져옵니다.


**Returns:**
[WordProcessingPageSetup](../../com.groupdocs.watermark.contents/wordprocessingpagesetup) - The printing page setup for this `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)`.

### getHeadersFooters() {#getHeadersFooters--}
```
public final WordProcessingHeaderFooterCollection getHeadersFooters()
```


이 `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)`의 모든 머리글 및 바닥글 컬렉션을 가져옵니다.


**Returns:**
[WordProcessingHeaderFooterCollection](../../com.groupdocs.watermark.contents/wordprocessingheaderfootercollection) - The collection of all headers and footers of this `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)`.

### getShapes() {#getShapes--}
```
public final WordProcessingShapeCollection getShapes()
```


이 `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)`에 포함된 모든 도형 컬렉션을 가져옵니다.


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
| 매개변수 | 유형 | 설명 |
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
