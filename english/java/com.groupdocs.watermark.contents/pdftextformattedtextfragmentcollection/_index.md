---
title: PdfTextFormattedTextFragmentCollection
second_title: GroupDocs.Watermark for Java API Reference
description: Represents a collection of formatted text fragments in a pdf content main text.
type: docs
weight: 71
url: /java/com.groupdocs.watermark.contents/pdftextformattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase, [com.groupdocs.watermark.search.FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection), [com.groupdocs.watermark.contents.PdfFormattedTextFragmentCollection](../../com.groupdocs.watermark.contents/pdfformattedtextfragmentcollection)
```
public class PdfTextFormattedTextFragmentCollection extends PdfFormattedTextFragmentCollection
```

Represents a collection of formatted text fragments in a pdf content main text.

This collection contains the items of `[PdfFormattedTextFragment](../../com.groupdocs.watermark.contents/pdfformattedtextfragment)` type.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfTextFormattedTextFragmentCollection(TextFragment textFragment)](#PdfTextFormattedTextFragmentCollection-com.aspose.pdf.TextFragment-) |  |
## Methods

| Method | Description |
| --- | --- |
| [setText(String text)](#setText-java.lang.String-) |  |
| [removeFromDocument(FormattedTextFragment item)](#removeFromDocument-com.groupdocs.watermark.search.FormattedTextFragment-) |  |
| [createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) |  |
### PdfTextFormattedTextFragmentCollection(TextFragment textFragment) {#PdfTextFormattedTextFragmentCollection-com.aspose.pdf.TextFragment-}
```
public PdfTextFormattedTextFragmentCollection(TextFragment textFragment)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| textFragment | com.aspose.pdf.TextFragment |  |

### setText(String text) {#setText-java.lang.String-}
```
public void setText(String text)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |

### removeFromDocument(FormattedTextFragment item) {#removeFromDocument-com.groupdocs.watermark.search.FormattedTextFragment-}
```
public void removeFromDocument(FormattedTextFragment item)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment) |  |

### createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public FormattedTextFragment createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |
| text | java.lang.String |  |
| font | [Font](../../com.groupdocs.watermark.watermarks/font) |  |
| foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |
| backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |

**Returns:**
[FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)
