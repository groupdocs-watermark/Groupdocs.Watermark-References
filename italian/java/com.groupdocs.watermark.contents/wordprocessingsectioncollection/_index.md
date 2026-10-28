---
title: "WordProcessingSectionCollection"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta una raccolta di sezioni in un documento Word."
type: docs
weight: 140
url: /it/java/com.groupdocs.watermark.contents/wordprocessingsectioncollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public class WordProcessingSectionCollection extends ReadOnlyListBase<WordProcessingSection>
```

Rappresenta una raccolta di sezioni in un documento Word.

Questa collezione contiene gli elementi di tipo `[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)`.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WordProcessingSectionCollection(WordProcessingContent parent, SectionCollection sourceCollection, IStrategyManager strategyManager)](#WordProcessingSectionCollection-com.groupdocs.watermark.contents.WordProcessingContent-com.aspose.words.SectionCollection-com.groupdocs.watermark.internal.IStrategyManager-) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [findSection(Section section)](#findSection-com.aspose.words.Section-) |  |
### WordProcessingSectionCollection(WordProcessingContent parent, SectionCollection sourceCollection, IStrategyManager strategyManager) {#WordProcessingSectionCollection-com.groupdocs.watermark.contents.WordProcessingContent-com.aspose.words.SectionCollection-com.groupdocs.watermark.internal.IStrategyManager-}
```
public WordProcessingSectionCollection(WordProcessingContent parent, SectionCollection sourceCollection, IStrategyManager strategyManager)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| parent | [WordProcessingContent](../../com.groupdocs.watermark.contents/wordprocessingcontent) |  |
| sourceCollection | com.aspose.words.SectionCollection |  |
| strategyManager | [IStrategyManager](../../com.groupdocs.watermark.internal/istrategymanager) |  |

### findSection(Section section) {#findSection-com.aspose.words.Section-}
```
public final WordProcessingSection findSection(Section section)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| section | com.aspose.words.Section |  |

**Returns:**
[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection)
