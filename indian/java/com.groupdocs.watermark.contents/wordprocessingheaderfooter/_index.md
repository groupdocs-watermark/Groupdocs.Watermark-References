---
title: "WordProcessingHeaderFooter"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "Word दस्तावेज़ में हेडर/फ़ूटर को दर्शाता है।"
type: docs
weight: 131
url: /hi/java/com.groupdocs.watermark.contents/wordprocessingheaderfooter/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class WordProcessingHeaderFooter extends ContentPart
```

Word दस्तावेज़ में हेडर/फ़ूटर को दर्शाता है।

## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
| [WordProcessingHeaderFooter(int headerFooterHeaderFooterType, WordProcessingSection parent, IStrategyManager strategyManager, WordProcessingHeaderFooterWrapper wrapper)](#WordProcessingHeaderFooter-int-com.groupdocs.watermark.contents.WordProcessingSection-com.groupdocs.watermark.internal.IStrategyManager-com.groupdocs.watermark.internal.WordProcessingHeaderFooterWrapper-) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getWrapper()](#getWrapper--) |  |
|  | [getHeaderFooterType()](#getHeaderFooterType--) | इस `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` का प्रकार प्राप्त करता है। |
|
|  | [getSection()](#getSection--) | इस `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` का पैरेंट सेक्शन प्राप्त करता है। |
|
|  | [isLinkedToPrevious()](#isLinkedToPrevious--) | एक मान प्राप्त करता है जो दर्शाता है कि यह हेडर/फ़ूटर पिछले सेक्शन में संबंधित हेडर/फ़ूटर से जुड़ा है या नहीं। |
|
|  | [setLinkedToPrevious(boolean value)](#setLinkedToPrevious-boolean-) | एक मान सेट करता है जो दर्शाता है कि यह हेडर/फ़ूटर पिछले सेक्शन में संबंधित हेडर/फ़ूटर से जुड़ा है या नहीं। |
|
| [isVisible()](#isVisible--) |  |
| [addWatermark(Watermark watermark, IWordProcessingWatermarkEffects effects, WordProcessingShapeSettings shapeSettings)](#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-com.groupdocs.watermark.options.WordProcessingShapeSettings-) |  |
### WordProcessingHeaderFooter(int headerFooterHeaderFooterType, WordProcessingSection parent, IStrategyManager strategyManager, WordProcessingHeaderFooterWrapper wrapper) {#WordProcessingHeaderFooter-int-com.groupdocs.watermark.contents.WordProcessingSection-com.groupdocs.watermark.internal.IStrategyManager-com.groupdocs.watermark.internal.WordProcessingHeaderFooterWrapper-}
```
public WordProcessingHeaderFooter(int headerFooterHeaderFooterType, WordProcessingSection parent, IStrategyManager strategyManager, WordProcessingHeaderFooterWrapper wrapper)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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


इस `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` का प्रकार प्राप्त करता है।


**Returns:**
int - इस `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` का प्रकार।

### getSection() {#getSection--}
```
public final WordProcessingSection getSection()
```


इस `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` का पैरेंट सेक्शन प्राप्त करता है।


**Returns:**
[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection) - The parent section of this `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`.

### isLinkedToPrevious() {#isLinkedToPrevious--}
```
public final boolean isLinkedToPrevious()
```


एक मान प्राप्त करता है जो दर्शाता है कि यह हेडर/फ़ूटर पिछले सेक्शन में संबंधित हेडर/फ़ूटर से जुड़ा है या नहीं।

डिफ़ॉल्ट true है।


**Returns:**
boolean - `true` यदि यह हेडर/फ़ूटर पिछले सेक्शन में संबंधित हेडर/फ़ूटर से जुड़ा है; अन्यथा `false`।

### setLinkedToPrevious(boolean value) {#setLinkedToPrevious-boolean-}
```
public final void setLinkedToPrevious(boolean value)
```


एक मान सेट करता है जो दर्शाता है कि यह हेडर/फ़ूटर पिछले सेक्शन में संबंधित हेडर/फ़ूटर से जुड़ा है या नहीं।

ध्यान दें, जब आप किसी हेडर या फ़ूटर को लिंक करते हैं, तो उसकी सामग्री साफ़ हो जाती है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | `true` यदि इस हेडर/फ़ूटर को पिछले सेक्शन में संबंधित हेडर/फ़ूटर से लिंक करना है; अन्यथा `false`। |
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| effects | [IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects) |  |
| shapeSettings | [WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings) |  |

