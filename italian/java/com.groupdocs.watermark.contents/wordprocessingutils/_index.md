---
title: "WordProcessingUtils"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: 
type: docs
weight: 147
url: /it/java/com.groupdocs.watermark.contents/wordprocessingutils/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingUtils
```

<br />


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WordProcessingUtils()](#WordProcessingUtils--) |  |
## Metodi

| Metodo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tipo | java.lang.Class<T> |  |
| nodo | com.aspose.words.Node |  |

**Returns:**
T
### buildSettings(Watermark watermark, WordProcessingShapeSettings shapeSettings, IWordProcessingWatermarkEffects effects, WordProcessingPlacementSettings placementSettings, Content parent) {#buildSettings-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WordProcessingShapeSettings-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-com.groupdocs.watermark.internal.WordProcessingPlacementSettings-com.groupdocs.watermark.contents.Content-}
```
public static DocumentSpecificSettingsCollection buildSettings(Watermark watermark, WordProcessingShapeSettings shapeSettings, IWordProcessingWatermarkEffects effects, WordProcessingPlacementSettings placementSettings, Content parent)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings) |  |
| effects | [IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects) |  |
| placementSettings | [WordProcessingPlacementSettings](../../com.groupdocs.watermark.internal/wordprocessingplacementsettings) |  |
| parent | [Content](../../com.groupdocs.watermark.contents/content) |  |

**Returns:**
[DocumentSpecificSettingsCollection](../../com.groupdocs.watermark.internal/documentspecificsettingscollection)
