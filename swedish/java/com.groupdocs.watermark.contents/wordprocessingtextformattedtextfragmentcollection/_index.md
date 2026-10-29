---
title: "WordProcessingTextFormattedTextFragmentCollection"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar en samling formaterade textfragment i huvudtexten i ett Word-dokument."
type: docs
weight: 146
url: /sv/java/com.groupdocs.watermark.contents/wordprocessingtextformattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase, [com.groupdocs.watermark.search.FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection), [com.groupdocs.watermark.contents.WordProcessingFormattedTextFragmentCollection](../../com.groupdocs.watermark.contents/wordprocessingformattedtextfragmentcollection)
```
public class WordProcessingTextFormattedTextFragmentCollection extends WordProcessingFormattedTextFragmentCollection
```

Representerar en samling formaterade textfragment i huvudtexten i ett Word-dokument.

Denna samling innehåller objekt av typen `[WordProcessingTextFormattedTextFragment](../../com.groupdocs.watermark.contents/wordprocessingtextformattedtextfragment)`.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WordProcessingTextFormattedTextFragmentCollection(ReplacingArgs replacingArgs, WordProcessingTextPossibleWatermark parentWatermark)](#WordProcessingTextFormattedTextFragmentCollection-com.aspose.words.ReplacingArgs-com.groupdocs.watermark.search.WordProcessingTextPossibleWatermark-) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [setText(String text)](#setText-java.lang.String-) |  |
| [removeFromDocument(FormattedTextFragment item)](#removeFromDocument-com.groupdocs.watermark.search.FormattedTextFragment-) |  |
| [createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) |  |
### WordProcessingTextFormattedTextFragmentCollection(ReplacingArgs replacingArgs, WordProcessingTextPossibleWatermark parentWatermark) {#WordProcessingTextFormattedTextFragmentCollection-com.aspose.words.ReplacingArgs-com.groupdocs.watermark.search.WordProcessingTextPossibleWatermark-}
```
public WordProcessingTextFormattedTextFragmentCollection(ReplacingArgs replacingArgs, WordProcessingTextPossibleWatermark parentWatermark)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| replacingArgs | com.aspose.words.ReplacingArgs |  |
| parentWatermark | [WordProcessingTextPossibleWatermark](../../com.groupdocs.watermark.search/wordprocessingtextpossiblewatermark) |  |

### setText(String text) {#setText-java.lang.String-}
```
public void setText(String text)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String |  |

### removeFromDocument(FormattedTextFragment item) {#removeFromDocument-com.groupdocs.watermark.search.FormattedTextFragment-}
```
public void removeFromDocument(FormattedTextFragment item)
```


<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment) |  |

### createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public FormattedTextFragment createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |
| text | java.lang.String |  |
| font | [Font](../../com.groupdocs.watermark.watermarks/font) |  |
| foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |
| backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |

**Returns:**
[FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)
