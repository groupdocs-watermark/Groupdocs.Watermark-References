---
title: "SpreadsheetShapeFormattedTextFragmentCollection"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta una raccolta di frammenti di testo formattato nella forma di testo di un documento Excel."
type: docs
weight: 120
url: /it/java/com.groupdocs.watermark.contents/spreadsheetshapeformattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase, [com.groupdocs.watermark.search.FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
```
public class SpreadsheetShapeFormattedTextFragmentCollection extends FormattedTextFragmentCollection
```

Rappresenta una raccolta di frammenti di testo formattato nella forma di testo di un documento Excel.

Questa collezione contiene gli elementi del tipo `[SpreadsheetShapeFormattedTextFragment](../../com.groupdocs.watermark.contents/spreadsheetshapeformattedtextfragment)`.

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getText()](#getText--) | <br /> |

|
|  | [removeFromDocument(FormattedTextFragment item)](#removeFromDocument-com.groupdocs.watermark.search.FormattedTextFragment-) | <br /> |

|
|  | [createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) | <br /> |

|
### getText() {#getText--}
```
public String getText()
```


<br />



**Returns:**
java.lang.String
### removeFromDocument(FormattedTextFragment item) {#removeFromDocument-com.groupdocs.watermark.search.FormattedTextFragment-}
```
public void removeFromDocument(FormattedTextFragment item)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment) |  |

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
