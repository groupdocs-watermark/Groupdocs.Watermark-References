---
title: "WordProcessingUtils"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: 
type: docs
weight: 147
url: /hi/java/com.groupdocs.watermark.contents/wordprocessingutils/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingUtils
```

<br />


## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
| [WordProcessingUtils()](#WordProcessingUtils--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [<T>getParent(Class<T> type, Node node)](#-T-getParent-java.lang.Class-T--com.aspose.words.Node-) |  |
| [buildSettings(Watermark watermark, WordProcessingShapeSettings shapeSettings, IWordProcessingWatermarkEffects effects, WordProcessingPlacementSettings placementSettings, Content parent)](#buildSettings-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WordProcessingShapeSettings-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-com.groupdocs.watermark.internal.WordProcessingPlacementSettings-com.groupdocs.watermark.contents.Content-) |  |
### WordProcessingUtils() {#WordProcessingUtils--}
```
public WordProcessingUtils()
```


### <T>getParent(Class<T> type, Node node) {#-T-getParent-java.lang.Class-T--com.aspose.words.Node-}
```
public static T <T>getParent(Class<T> type, Node node)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| प्रकार | java.lang.Class<T> |  |
| नोड | com.aspose.words.Node |  |

**Returns:**
T
### buildSettings(Watermark watermark, WordProcessingShapeSettings shapeSettings, IWordProcessingWatermarkEffects effects, WordProcessingPlacementSettings placementSettings, Content parent) {#buildSettings-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WordProcessingShapeSettings-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-com.groupdocs.watermark.internal.WordProcessingPlacementSettings-com.groupdocs.watermark.contents.Content-}
```
public static DocumentSpecificSettingsCollection buildSettings(Watermark watermark, WordProcessingShapeSettings shapeSettings, IWordProcessingWatermarkEffects effects, WordProcessingPlacementSettings placementSettings, Content parent)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings) |  |
| effects | [IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects) |  |
| placementSettings | [WordProcessingPlacementSettings](../../com.groupdocs.watermark.internal/wordprocessingplacementsettings) |  |
| parent | [Content](../../com.groupdocs.watermark.contents/content) |  |

**Returns:**
[DocumentSpecificSettingsCollection](../../com.groupdocs.watermark.internal/documentspecificsettingscollection)
