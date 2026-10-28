---
title: "PdfShapeFormattedTextFragmentCollection"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt eine Sammlung formatierter Textfragmente in einem PDF-Dokument‑XObject‑Artefakt oder einer Anmerkung dar."
type: docs
weight: 70
url: /de/java/com.groupdocs.watermark.contents/pdfshapeformattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase, [com.groupdocs.watermark.search.FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection), [com.groupdocs.watermark.contents.PdfFormattedTextFragmentCollection](../../com.groupdocs.watermark.contents/pdfformattedtextfragmentcollection)
```
public class PdfShapeFormattedTextFragmentCollection extends PdfFormattedTextFragmentCollection
```

Stellt eine Sammlung von Fragmenten formatierten Textes in einem PDF-Dokument-XObject, Artefakt oder Anmerkung dar.

Diese Sammlung enthält Elemente des Typs `[PdfFormattedTextFragment](../../com.groupdocs.watermark.contents/pdfformattedtextfragment)`.

## Methoden

| Methode | Beschreibung |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Text | java.lang.String |  |

### createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public FormattedTextFragment createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Index | int |  |
| Text | java.lang.String |  |
| font | [Font](../../com.groupdocs.watermark.watermarks/font) |  |
| foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |
| backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |

**Returns:**
[FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)
