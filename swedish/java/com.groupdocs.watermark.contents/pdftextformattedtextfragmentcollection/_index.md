---
title: "PdfTextFormattedTextFragmentCollection"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar en samling av formaterade textfragment i huvudtexten för ett pdf-innehåll."
type: docs
weight: 71
url: /sv/java/com.groupdocs.watermark.contents/pdftextformattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase, [com.groupdocs.watermark.search.FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection), [com.groupdocs.watermark.contents.PdfFormattedTextFragmentCollection](../../com.groupdocs.watermark.contents/pdfformattedtextfragmentcollection)
```
public class PdfTextFormattedTextFragmentCollection extends PdfFormattedTextFragmentCollection
```

Representerar en samling av formaterade textfragment i huvudtexten för ett pdf-innehåll.

Denna samling innehåller objekt av typen `[PdfFormattedTextFragment](../../com.groupdocs.watermark.contents/pdfformattedtextfragment)`.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [PdfTextFormattedTextFragmentCollection(TextFragment textFragment)](#PdfTextFormattedTextFragmentCollection-com.aspose.pdf.TextFragment-) | <br /> |

|
## Metoder

| Metod | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| textFragment | com.aspose.pdf.TextFragment |  |

### setText(String text) {#setText-java.lang.String-}
```
public void setText(String text)
```


<br />



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


<br />



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
