---
title: "WordProcessingWordArtShapeFormattedTextFragmentCollection"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt een verzameling opgemaakte tekstfragmenten in een WordArt-vorm van een Word-document voor."
type: docs
weight: 151
url: /nl/java/com.groupdocs.watermark.contents/wordprocessingwordartshapeformattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase, [com.groupdocs.watermark.search.FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection), [com.groupdocs.watermark.contents.WordProcessingFormattedTextFragmentCollection](../../com.groupdocs.watermark.contents/wordprocessingformattedtextfragmentcollection)
```
public class WordProcessingWordArtShapeFormattedTextFragmentCollection extends WordProcessingFormattedTextFragmentCollection
```

Stelt een verzameling opgemaakte tekstfragmenten in een WordArt-vorm van een Word-document voor.

Deze collectie bevat de items van het type `[WordProcessingWordArtShapeFormattedTextFragment](../../com.groupdocs.watermark.contents/wordprocessingwordartshapeformattedtextfragment)`.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getText()](#getText--) |  |
| [removeFromDocument(FormattedTextFragment item)](#removeFromDocument-com.groupdocs.watermark.search.FormattedTextFragment-) |  |
| [createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) |  |
| [setText(String text)](#setText-java.lang.String-) |  |
### getText() {#getText--}
```
public String getText()
```




**Returns:**
java.lang.String
### removeFromDocument(FormattedTextFragment item) {#removeFromDocument-com.groupdocs.watermark.search.FormattedTextFragment-}
```
public void removeFromDocument(FormattedTextFragment item)
```


<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment) |  |

### createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public FormattedTextFragment createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |
| tekst | java.lang.String |  |
| font | [Font](../../com.groupdocs.watermark.watermarks/font) |  |
| foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |
| backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |

**Returns:**
[FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)
### setText(String text) {#setText-java.lang.String-}
```
public void setText(String text)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tekst | java.lang.String |  |

