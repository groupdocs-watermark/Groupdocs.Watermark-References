---
title: "WordProcessingTextFormattedTextFragmentCollection"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "Word दस्तावेज़ के मुख्य पाठ में स्वरूपित पाठ खंडों का संग्रह दर्शाता है।"
type: docs
weight: 146
url: /hi/java/com.groupdocs.watermark.contents/wordprocessingtextformattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase, [com.groupdocs.watermark.search.FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection), [com.groupdocs.watermark.contents.WordProcessingFormattedTextFragmentCollection](../../com.groupdocs.watermark.contents/wordprocessingformattedtextfragmentcollection)
```
public class WordProcessingTextFormattedTextFragmentCollection extends WordProcessingFormattedTextFragmentCollection
```

Word दस्तावेज़ के मुख्य पाठ में स्वरूपित पाठ खंडों का संग्रह दर्शाता है।

यह संग्रह `[WordProcessingTextFormattedTextFragment](../../com.groupdocs.watermark.contents/wordprocessingtextformattedtextfragment)` प्रकार के आइटम्स रखता है।

## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
| [WordProcessingTextFormattedTextFragmentCollection(ReplacingArgs replacingArgs, WordProcessingTextPossibleWatermark parentWatermark)](#WordProcessingTextFormattedTextFragmentCollection-com.aspose.words.ReplacingArgs-com.groupdocs.watermark.search.WordProcessingTextPossibleWatermark-) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [setText(String text)](#setText-java.lang.String-) |  |
| [removeFromDocument(FormattedTextFragment item)](#removeFromDocument-com.groupdocs.watermark.search.FormattedTextFragment-) |  |
| [createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) |  |
### WordProcessingTextFormattedTextFragmentCollection(ReplacingArgs replacingArgs, WordProcessingTextPossibleWatermark parentWatermark) {#WordProcessingTextFormattedTextFragmentCollection-com.aspose.words.ReplacingArgs-com.groupdocs.watermark.search.WordProcessingTextPossibleWatermark-}
```
public WordProcessingTextFormattedTextFragmentCollection(ReplacingArgs replacingArgs, WordProcessingTextPossibleWatermark parentWatermark)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| replacingArgs | com.aspose.words.ReplacingArgs |  |
| parentWatermark | [WordProcessingTextPossibleWatermark](../../com.groupdocs.watermark.search/wordprocessingtextpossiblewatermark) |  |

### setText(String text) {#setText-java.lang.String-}
```
public void setText(String text)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पाठ | java.lang.String |  |

### removeFromDocument(FormattedTextFragment item) {#removeFromDocument-com.groupdocs.watermark.search.FormattedTextFragment-}
```
public void removeFromDocument(FormattedTextFragment item)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment) |  |

### createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public FormattedTextFragment createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| सूचकांक | int |  |
| पाठ | java.lang.String |  |
| font | [Font](../../com.groupdocs.watermark.watermarks/font) |  |
| foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |
| backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |

**Returns:**
[FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)
