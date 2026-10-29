---
title: "WordProcessingUtils"
second_title: "GroupDocs.Watermark för Java API-referens"
description: 
type: docs
weight: 147
url: /sv/java/com.groupdocs.watermark.contents/wordprocessingutils/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingUtils
```

<br />


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WordProcessingUtils()](#WordProcessingUtils--) |  |
## Metoder

| Metod | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | java.lang.Class<T> |  |
| nod | com.aspose.words.Node |  |

**Returns:**
T
### buildSettings(Watermark watermark, WordProcessingShapeSettings shapeSettings, IWordProcessingWatermarkEffects effects, WordProcessingPlacementSettings placementSettings, Content parent) {#buildSettings-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WordProcessingShapeSettings-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-com.groupdocs.watermark.internal.WordProcessingPlacementSettings-com.groupdocs.watermark.contents.Content-}
```
public static DocumentSpecificSettingsCollection buildSettings(Watermark watermark, WordProcessingShapeSettings shapeSettings, IWordProcessingWatermarkEffects effects, WordProcessingPlacementSettings placementSettings, Content parent)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings) |  |
| effects | [IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects) |  |
| placementSettings | [WordProcessingPlacementSettings](../../com.groupdocs.watermark.internal/wordprocessingplacementsettings) |  |
| parent | [Content](../../com.groupdocs.watermark.contents/content) |  |

**Returns:**
[DocumentSpecificSettingsCollection](../../com.groupdocs.watermark.internal/documentspecificsettingscollection)
