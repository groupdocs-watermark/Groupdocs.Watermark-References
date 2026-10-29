---
title: "WordProcessingHeaderFooter"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Bir Word belgesindeki üstbilgi/altbilgiyi temsil eder."
type: docs
weight: 131
url: /tr/java/com.groupdocs.watermark.contents/wordprocessingheaderfooter/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class WordProcessingHeaderFooter extends ContentPart
```

Bir Word belgesindeki üstbilgi/altbilgiyi temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WordProcessingHeaderFooter(int headerFooterHeaderFooterType, WordProcessingSection parent, IStrategyManager strategyManager, WordProcessingHeaderFooterWrapper wrapper)](#WordProcessingHeaderFooter-int-com.groupdocs.watermark.contents.WordProcessingSection-com.groupdocs.watermark.internal.IStrategyManager-com.groupdocs.watermark.internal.WordProcessingHeaderFooterWrapper-) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getWrapper()](#getWrapper--) |  |
|  | [getHeaderFooterType()](#getHeaderFooterType--) | Bu `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` tipini alır. |
|
|  | [getSection()](#getSection--) | Bu `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` öğesinin üst bölümünü alır. |
|
|  | [isLinkedToPrevious()](#isLinkedToPrevious--) | Bu üstbilgi/altbilginin önceki bölümdeki karşılık gelen üstbilgi/altbilgiye bağlanıp bağlanmadığını gösteren bir değeri alır. |
|
|  | [setLinkedToPrevious(boolean value)](#setLinkedToPrevious-boolean-) | Bu üstbilgi/altbilgi önceki bölümdeki karşılık gelen üstbilgi/altbilgiye bağlanıp bağlanmadığını gösteren bir değeri ayarlar. |
|
| [isVisible()](#isVisible--) |  |
| [addWatermark(Watermark watermark, IWordProcessingWatermarkEffects effects, WordProcessingShapeSettings shapeSettings)](#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-com.groupdocs.watermark.options.WordProcessingShapeSettings-) |  |
### WordProcessingHeaderFooter(int headerFooterHeaderFooterType, WordProcessingSection parent, IStrategyManager strategyManager, WordProcessingHeaderFooterWrapper wrapper) {#WordProcessingHeaderFooter-int-com.groupdocs.watermark.contents.WordProcessingSection-com.groupdocs.watermark.internal.IStrategyManager-com.groupdocs.watermark.internal.WordProcessingHeaderFooterWrapper-}
```
public WordProcessingHeaderFooter(int headerFooterHeaderFooterType, WordProcessingSection parent, IStrategyManager strategyManager, WordProcessingHeaderFooterWrapper wrapper)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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


Bu `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` tipini alır.


**Returns:**
int - Bu `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` tipinin türü.

### getSection() {#getSection--}
```
public final WordProcessingSection getSection()
```


Bu `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` öğesinin üst bölümünü alır.


**Returns:**
[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection) - The parent section of this `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`.

### isLinkedToPrevious() {#isLinkedToPrevious--}
```
public final boolean isLinkedToPrevious()
```


Bu üstbilgi/altbilginin önceki bölümdeki karşılık gelen üstbilgi/altbilgiye bağlanıp bağlanmadığını gösteren bir değeri alır.

Varsayılan true'dur.


**Returns:**
boolean - Bu üstbilgi/altbilgi önceki bölümdeki karşılık gelen üstbilgi/altbilgiye bağlıysa `true`; aksi takdirde `false`.

### setLinkedToPrevious(boolean value) {#setLinkedToPrevious-boolean-}
```
public final void setLinkedToPrevious(boolean value)
```


Bu üstbilgi/altbilgi önceki bölümdeki karşılık gelen üstbilgi/altbilgiye bağlanıp bağlanmadığını gösteren bir değeri ayarlar.

Not, bir üstbilgi veya altbilgi bağladığınızda, içeriği temizlenir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | `true` bu üstbilgi/altbilgi önceki bölümdeki karşılık gelen üstbilgi/altbilgiye bağlanması gerekiyorsa; `false` aksi takdirde. |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| effects | [IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects) |  |
| shapeSettings | [WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings) |  |

