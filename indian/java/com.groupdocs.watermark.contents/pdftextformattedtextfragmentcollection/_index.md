---
title: "PdfTextFormattedTextFragmentCollection"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "PDF सामग्री के मुख्य टेक्स्ट में स्वरूपित टेक्स्ट भागों के संग्रह का प्रतिनिधित्व करता है।"
type: docs
weight: 71
url: /hi/java/com.groupdocs.watermark.contents/pdftextformattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase, [com.groupdocs.watermark.search.FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection), [com.groupdocs.watermark.contents.PdfFormattedTextFragmentCollection](../../com.groupdocs.watermark.contents/pdfformattedtextfragmentcollection)
```
public class PdfTextFormattedTextFragmentCollection extends PdfFormattedTextFragmentCollection
```

PDF सामग्री के मुख्य टेक्स्ट में स्वरूपित टेक्स्ट भागों के संग्रह का प्रतिनिधित्व करता है।

यह संग्रह `[PdfFormattedTextFragment](../../com.groupdocs.watermark.contents/pdfformattedtextfragment)` प्रकार की वस्तुओं को शामिल करता है।

## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [PdfTextFormattedTextFragmentCollection(TextFragment textFragment)](#PdfTextFormattedTextFragmentCollection-com.aspose.pdf.TextFragment-) | <br /> |

|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [setText(String text)](#setText-java.lang.String-) | <br /> |

|
|  | [removeFromDocument(FormattedTextFragment item)](#removeFromDocument-com.groupdocs.watermark.search.FormattedTextFragment-) | <br /> |

|
|  | [createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) | <br /> |

|
### PdfTextFormattedTextFragmentCollection(TextFragment textFragment) {#PdfTextFormattedTextFragmentCollection-com.aspose.pdf.TextFragment-}
```
public PdfTextFormattedTextFragmentCollection(TextFragment textFragment)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| textFragment | com.aspose.pdf.TextFragment |  |

### setText(String text) {#setText-java.lang.String-}
```
public void setText(String text)
```


<br />



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


<br />



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
