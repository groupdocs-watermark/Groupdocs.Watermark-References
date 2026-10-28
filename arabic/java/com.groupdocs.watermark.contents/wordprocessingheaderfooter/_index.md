---
title: "WordProcessingHeaderFooter"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل رأس/تذييل في مستند Word."
type: docs
weight: 131
url: /ar/java/com.groupdocs.watermark.contents/wordprocessingheaderfooter/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class WordProcessingHeaderFooter extends ContentPart
```

يمثل رأس/تذييل في مستند Word.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [WordProcessingHeaderFooter(int headerFooterHeaderFooterType, WordProcessingSection parent, IStrategyManager strategyManager, WordProcessingHeaderFooterWrapper wrapper)](#WordProcessingHeaderFooter-int-com.groupdocs.watermark.contents.WordProcessingSection-com.groupdocs.watermark.internal.IStrategyManager-com.groupdocs.watermark.internal.WordProcessingHeaderFooterWrapper-) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getWrapper()](#getWrapper--) |  |
|  | [getHeaderFooterType()](#getHeaderFooterType--) | يحصل على نوع هذا `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`. |
|
|  | [getSection()](#getSection--) | يحصل على القسم الأب لهذا `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`. |
|
|  | [isLinkedToPrevious()](#isLinkedToPrevious--) | يحصل على قيمة تشير إلى ما إذا كان هذا الترويسة/التذييل مرتبطًا بالترويسة/التذييل المقابل في القسم السابق. |
|
|  | [setLinkedToPrevious(boolean value)](#setLinkedToPrevious-boolean-) | يضبط قيمة تشير إلى ما إذا كان هذا الترويسة/التذييل مرتبطًا بالترويسة/التذييل المقابل في القسم السابق. |
|
| [isVisible()](#isVisible--) |  |
| [addWatermark(Watermark watermark, IWordProcessingWatermarkEffects effects, WordProcessingShapeSettings shapeSettings)](#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-com.groupdocs.watermark.options.WordProcessingShapeSettings-) |  |
### WordProcessingHeaderFooter(int headerFooterHeaderFooterType, WordProcessingSection parent, IStrategyManager strategyManager, WordProcessingHeaderFooterWrapper wrapper) {#WordProcessingHeaderFooter-int-com.groupdocs.watermark.contents.WordProcessingSection-com.groupdocs.watermark.internal.IStrategyManager-com.groupdocs.watermark.internal.WordProcessingHeaderFooterWrapper-}
```
public WordProcessingHeaderFooter(int headerFooterHeaderFooterType, WordProcessingSection parent, IStrategyManager strategyManager, WordProcessingHeaderFooterWrapper wrapper)
```




**Parameters:**
| معامل | نوع | الوصف |
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


يحصل على نوع هذا `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`.


**Returns:**
int - نوع هذا `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`.

### getSection() {#getSection--}
```
public final WordProcessingSection getSection()
```


يحصل على القسم الأب لهذا `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`.


**Returns:**
[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection) - The parent section of this `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`.

### isLinkedToPrevious() {#isLinkedToPrevious--}
```
public final boolean isLinkedToPrevious()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الترويسة/التذييل مرتبطًا بالترويسة/التذييل المقابل في القسم السابق.

القيمة الافتراضية هي true.


**Returns:**
boolean - `true` إذا كان هذا الترويسة/التذييل مرتبطًا بالترويسة/التذييل المقابل في القسم السابق؛ `false` خلاف ذلك.

### setLinkedToPrevious(boolean value) {#setLinkedToPrevious-boolean-}
```
public final void setLinkedToPrevious(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان هذا الترويسة/التذييل مرتبطًا بالترويسة/التذييل المقابل في القسم السابق.

ملاحظة، عند ربطك لترويسة أو تذييل، يتم مسح محتوياته.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | boolean | `true` إذا كان يجب ربط هذا الترويسة/التذييل بالترويسة/التذييل المقابل في القسم السابق؛ `false` خلاف ذلك. |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| effects | [IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects) |  |
| shapeSettings | [WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings) |  |

