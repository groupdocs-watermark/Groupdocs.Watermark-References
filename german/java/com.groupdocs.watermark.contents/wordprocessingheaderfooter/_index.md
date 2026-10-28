---
title: "WordProcessingHeaderFooter"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt eine Kopf- bzw. Fußzeile in einem Word-Dokument dar."
type: docs
weight: 131
url: /de/java/com.groupdocs.watermark.contents/wordprocessingheaderfooter/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class WordProcessingHeaderFooter extends ContentPart
```

Stellt eine Kopf- bzw. Fußzeile in einem Word-Dokument dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WordProcessingHeaderFooter(int headerFooterHeaderFooterType, WordProcessingSection parent, IStrategyManager strategyManager, WordProcessingHeaderFooterWrapper wrapper)](#WordProcessingHeaderFooter-int-com.groupdocs.watermark.contents.WordProcessingSection-com.groupdocs.watermark.internal.IStrategyManager-com.groupdocs.watermark.internal.WordProcessingHeaderFooterWrapper-) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getWrapper()](#getWrapper--) |  |
|  | [getHeaderFooterType()](#getHeaderFooterType--) | Ermittelt den Typ dieses `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`. |
|
|  | [getSection()](#getSection--) | Ermittelt den übergeordneten Abschnitt dieses `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`. |
|
|  | [isLinkedToPrevious()](#isLinkedToPrevious--) | Ermittelt einen Wert, der angibt, ob diese Kopf-/Fußzeile mit der entsprechenden Kopf-/Fußzeile im vorherigen Abschnitt verknüpft ist. |
|
|  | [setLinkedToPrevious(boolean value)](#setLinkedToPrevious-boolean-) | Setzt einen Wert, der angibt, ob diese Kopf-/Fußzeile mit der entsprechenden Kopf-/Fußzeile im vorherigen Abschnitt verknüpft ist. |
|
| [isVisible()](#isVisible--) |  |
| [addWatermark(Watermark watermark, IWordProcessingWatermarkEffects effects, WordProcessingShapeSettings shapeSettings)](#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-com.groupdocs.watermark.options.WordProcessingShapeSettings-) |  |
### WordProcessingHeaderFooter(int headerFooterHeaderFooterType, WordProcessingSection parent, IStrategyManager strategyManager, WordProcessingHeaderFooterWrapper wrapper) {#WordProcessingHeaderFooter-int-com.groupdocs.watermark.contents.WordProcessingSection-com.groupdocs.watermark.internal.IStrategyManager-com.groupdocs.watermark.internal.WordProcessingHeaderFooterWrapper-}
```
public WordProcessingHeaderFooter(int headerFooterHeaderFooterType, WordProcessingSection parent, IStrategyManager strategyManager, WordProcessingHeaderFooterWrapper wrapper)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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


Ermittelt den Typ dieses `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`.


**Returns:**
int - Der Typ dieses `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`.

### getSection() {#getSection--}
```
public final WordProcessingSection getSection()
```


Ermittelt den übergeordneten Abschnitt dieses `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`.


**Returns:**
[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection) - The parent section of this `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`.

### isLinkedToPrevious() {#isLinkedToPrevious--}
```
public final boolean isLinkedToPrevious()
```


Ermittelt einen Wert, der angibt, ob diese Kopf-/Fußzeile mit der entsprechenden Kopf-/Fußzeile im vorherigen Abschnitt verknüpft ist.

Standard ist true.


**Returns:**
boolean - `true`, wenn diese Kopf-/Fußzeile mit der entsprechenden Kopf-/Fußzeile im vorherigen Abschnitt verknüpft ist; `false` andernfalls.

### setLinkedToPrevious(boolean value) {#setLinkedToPrevious-boolean-}
```
public final void setLinkedToPrevious(boolean value)
```


Setzt einen Wert, der angibt, ob diese Kopf-/Fußzeile mit der entsprechenden Kopf-/Fußzeile im vorherigen Abschnitt verknüpft ist.

Hinweis: Wenn Sie eine Kopf- oder Fußzeile verknüpfen, wird ihr Inhalt gelöscht.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | `true`, wenn diese Kopf-/Fußzeile mit der entsprechenden Kopf-/Fußzeile im vorherigen Abschnitt verknüpft werden muss; `false` andernfalls. |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| effects | [IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects) |  |
| shapeSettings | [WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings) |  |

