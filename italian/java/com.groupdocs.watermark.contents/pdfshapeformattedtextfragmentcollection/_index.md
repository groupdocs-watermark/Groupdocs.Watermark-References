---
title: "PdfShapeFormattedTextFragmentCollection"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta una raccolta di frammenti di testo formattato in un documento PDF XObject, Artefatto o Annotazione."
type: docs
weight: 70
url: /it/java/com.groupdocs.watermark.contents/pdfshapeformattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase, [com.groupdocs.watermark.search.FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection), [com.groupdocs.watermark.contents.PdfFormattedTextFragmentCollection](../../com.groupdocs.watermark.contents/pdfformattedtextfragmentcollection)
```
public class PdfShapeFormattedTextFragmentCollection extends PdfFormattedTextFragmentCollection
```

Rappresenta una raccolta di frammenti di testo formattato in un XObject, Artifact o Annotation di un documento PDF.

Questa raccolta contiene gli elementi del tipo `[PdfFormattedTextFragment](../../com.groupdocs.watermark.contents/pdfformattedtextfragment)`.

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [setText(String text)](#setText-java.lang.String-) | <br /> |

|
|  | [createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) | <br /> |

|
### setText(String text) {#setText-java.lang.String-}
```
public void setText(String text)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| testo | java.lang.String |  |

### createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public FormattedTextFragment createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indice | int |  |
| testo | java.lang.String |  |
| font | [Font](../../com.groupdocs.watermark.watermarks/font) |  |
| foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |
| backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |

**Returns:**
[FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)
