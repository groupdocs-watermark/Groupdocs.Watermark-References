---
title: "WordProcessingTextFormattedTextFragmentCollection"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente une collection de fragments de texte formaté dans le texte principal d'un document Word."
type: docs
weight: 146
url: /fr/java/com.groupdocs.watermark.contents/wordprocessingtextformattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase, [com.groupdocs.watermark.search.FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection), [com.groupdocs.watermark.contents.WordProcessingFormattedTextFragmentCollection](../../com.groupdocs.watermark.contents/wordprocessingformattedtextfragmentcollection)
```
public class WordProcessingTextFormattedTextFragmentCollection extends WordProcessingFormattedTextFragmentCollection
```

Représente une collection de fragments de texte formaté dans le texte principal d'un document Word.

Cette collection contient les éléments de type `[WordProcessingTextFormattedTextFragment](../../com.groupdocs.watermark.contents/wordprocessingtextformattedtextfragment)`.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WordProcessingTextFormattedTextFragmentCollection(ReplacingArgs replacingArgs, WordProcessingTextPossibleWatermark parentWatermark)](#WordProcessingTextFormattedTextFragmentCollection-com.aspose.words.ReplacingArgs-com.groupdocs.watermark.search.WordProcessingTextPossibleWatermark-) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [setText(String text)](#setText-java.lang.String-) |  |
| [removeFromDocument(FormattedTextFragment item)](#removeFromDocument-com.groupdocs.watermark.search.FormattedTextFragment-) |  |
| [createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) |  |
### WordProcessingTextFormattedTextFragmentCollection(ReplacingArgs replacingArgs, WordProcessingTextPossibleWatermark parentWatermark) {#WordProcessingTextFormattedTextFragmentCollection-com.aspose.words.ReplacingArgs-com.groupdocs.watermark.search.WordProcessingTextPossibleWatermark-}
```
public WordProcessingTextFormattedTextFragmentCollection(ReplacingArgs replacingArgs, WordProcessingTextPossibleWatermark parentWatermark)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| replacingArgs | com.aspose.words.ReplacingArgs |  |
| parentWatermark | [WordProcessingTextPossibleWatermark](../../com.groupdocs.watermark.search/wordprocessingtextpossiblewatermark) |  |

### setText(String text) {#setText-java.lang.String-}
```
public void setText(String text)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| texte | java.lang.String |  |

### removeFromDocument(FormattedTextFragment item) {#removeFromDocument-com.groupdocs.watermark.search.FormattedTextFragment-}
```
public void removeFromDocument(FormattedTextFragment item)
```


<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment) |  |

### createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public FormattedTextFragment createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| indice | int |  |
| texte | java.lang.String |  |
| font | [Font](../../com.groupdocs.watermark.watermarks/font) |  |
| foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |
| backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |

**Returns:**
[FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)
