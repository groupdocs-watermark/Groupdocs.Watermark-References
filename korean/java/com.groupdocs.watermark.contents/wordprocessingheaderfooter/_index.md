---
title: "WordProcessingHeaderFooter"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "Word 문서의 머리글/바닥글을 나타냅니다."
type: docs
weight: 131
url: /ko/java/com.groupdocs.watermark.contents/wordprocessingheaderfooter/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class WordProcessingHeaderFooter extends ContentPart
```

Word 문서의 머리글/바닥글을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [WordProcessingHeaderFooter(int headerFooterHeaderFooterType, WordProcessingSection parent, IStrategyManager strategyManager, WordProcessingHeaderFooterWrapper wrapper)](#WordProcessingHeaderFooter-int-com.groupdocs.watermark.contents.WordProcessingSection-com.groupdocs.watermark.internal.IStrategyManager-com.groupdocs.watermark.internal.WordProcessingHeaderFooterWrapper-) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getWrapper()](#getWrapper--) |  |
|  | [getHeaderFooterType()](#getHeaderFooterType--) | 이 `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`의 유형을 가져옵니다. |
|
|  | [getSection()](#getSection--) | 이 `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`의 상위 섹션을 가져옵니다. |
|
|  | [isLinkedToPrevious()](#isLinkedToPrevious--) | 이 header/footer가 이전 섹션의 해당 header/footer에 연결되어 있는지 여부를 나타내는 값을 가져옵니다. |
|
|  | [setLinkedToPrevious(boolean value)](#setLinkedToPrevious-boolean-) | 이 header/footer가 이전 섹션의 해당 header/footer에 연결되어 있는지 여부를 나타내는 값을 설정합니다. |
|
| [isVisible()](#isVisible--) |  |
| [addWatermark(Watermark watermark, IWordProcessingWatermarkEffects effects, WordProcessingShapeSettings shapeSettings)](#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-com.groupdocs.watermark.options.WordProcessingShapeSettings-) |  |
### WordProcessingHeaderFooter(int headerFooterHeaderFooterType, WordProcessingSection parent, IStrategyManager strategyManager, WordProcessingHeaderFooterWrapper wrapper) {#WordProcessingHeaderFooter-int-com.groupdocs.watermark.contents.WordProcessingSection-com.groupdocs.watermark.internal.IStrategyManager-com.groupdocs.watermark.internal.WordProcessingHeaderFooterWrapper-}
```
public WordProcessingHeaderFooter(int headerFooterHeaderFooterType, WordProcessingSection parent, IStrategyManager strategyManager, WordProcessingHeaderFooterWrapper wrapper)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| headerFooterHeaderFooterType | int |  |
| parent | [WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection) |  |
| strategyManager | [IStrategyManager](../../com.groupdocs.watermark.internal/istrategymanager) |  |
| wrapper | [WordProcessingHeaderFooterWrapper](../../com.groupdocs.watermark.internal/wordprocessingheaderfooterwrapper) |  |

### getWrapper() {#getWrapper--}
```
public final WordProcessingHeaderFooterWrapper getWrapper()
```




**Returns:**
[WordProcessingHeaderFooterWrapper](../../com.groupdocs.watermark.internal/wordprocessingheaderfooterwrapper)
### getHeaderFooterType() {#getHeaderFooterType--}
```
public final int getHeaderFooterType()
```


이 `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`의 유형을 가져옵니다.


**Returns:**
int - 이 `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`의 유형.

### getSection() {#getSection--}
```
public final WordProcessingSection getSection()
```


이 `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`의 상위 섹션을 가져옵니다.


**Returns:**
[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection) - The parent section of this `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`.

### isLinkedToPrevious() {#isLinkedToPrevious--}
```
public final boolean isLinkedToPrevious()
```


이 header/footer가 이전 섹션의 해당 header/footer에 연결되어 있는지 여부를 나타내는 값을 가져옵니다.

기본값은 true입니다.


**Returns:**
boolean - 이전 섹션의 해당 header/footer에 이 header/footer가 연결된 경우 `true`; 그렇지 않으면 `false`.

### setLinkedToPrevious(boolean value) {#setLinkedToPrevious-boolean-}
```
public final void setLinkedToPrevious(boolean value)
```


이 header/footer가 이전 섹션의 해당 header/footer에 연결되어 있는지 여부를 나타내는 값을 설정합니다.

참고: 머리글이나 바닥글을 연결하면 해당 내용이 지워집니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | `true` - 이 header/footer가 이전 섹션의 해당 header/footer에 연결되어야 하는 경우; `false` - 그렇지 않은 경우. |
|

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```




**Returns:**
boolean
### addWatermark(Watermark watermark, IWordProcessingWatermarkEffects effects, WordProcessingShapeSettings shapeSettings) {#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-com.groupdocs.watermark.options.WordProcessingShapeSettings-}
```
public final void addWatermark(Watermark watermark, IWordProcessingWatermarkEffects effects, WordProcessingShapeSettings shapeSettings)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| effects | [IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects) |  |
| shapeSettings | [WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings) |  |

