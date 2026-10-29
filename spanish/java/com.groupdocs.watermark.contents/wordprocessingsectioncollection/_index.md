---
title: "WordProcessingSectionCollection"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa una colección de secciones en un documento Word."
type: docs
weight: 140
url: /es/java/com.groupdocs.watermark.contents/wordprocessingsectioncollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public class WordProcessingSectionCollection extends ReadOnlyListBase<WordProcessingSection>
```

Representa una colección de secciones en un documento Word.

Esta colección contiene los elementos del tipo `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)`.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [WordProcessingSectionCollection(WordProcessingContent parent, SectionCollection sourceCollection, IStrategyManager strategyManager)](#WordProcessingSectionCollection-com.groupdocs.watermark.contents.WordProcessingContent-com.aspose.words.SectionCollection-com.groupdocs.watermark.internal.IStrategyManager-) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [findSection(Section section)](#findSection-com.aspose.words.Section-) |  |
### WordProcessingSectionCollection(WordProcessingContent parent, SectionCollection sourceCollection, IStrategyManager strategyManager) {#WordProcessingSectionCollection-com.groupdocs.watermark.contents.WordProcessingContent-com.aspose.words.SectionCollection-com.groupdocs.watermark.internal.IStrategyManager-}
```
public WordProcessingSectionCollection(WordProcessingContent parent, SectionCollection sourceCollection, IStrategyManager strategyManager)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parent | [WordProcessingContent](../../com.groupdocs.watermark.contents/wordprocessingcontent) |  |
| sourceCollection | com.aspose.words.SectionCollection |  |
| strategyManager | [IStrategyManager](../../com.groupdocs.watermark.internal/istrategymanager) |  |

### findSection(Section section) {#findSection-com.aspose.words.Section-}
```
public final WordProcessingSection findSection(Section section)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| section | com.aspose.words.Section |  |

**Returns:**
[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)
