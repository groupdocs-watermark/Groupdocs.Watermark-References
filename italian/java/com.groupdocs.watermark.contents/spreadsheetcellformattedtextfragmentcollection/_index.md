---
title: "SpreadsheetCellFormattedTextFragmentCollection"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta una raccolta di frammenti di testo formattato nella cella di un documento Excel."
type: docs
weight: 105
url: /it/java/com.groupdocs.watermark.contents/spreadsheetcellformattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase, [com.groupdocs.watermark.search.FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
```
public class SpreadsheetCellFormattedTextFragmentCollection extends FormattedTextFragmentCollection
```

Rappresenta una raccolta di frammenti di testo formattato nella cella di un documento Excel.

Questa collezione contiene gli elementi di tipo `[SpreadsheetCellFormattedTextFragment](../../com.groupdocs.watermark.contents/spreadsheetcellformattedtextfragment)`.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [SpreadsheetCellFormattedTextFragmentCollection(Cell cell)](#SpreadsheetCellFormattedTextFragmentCollection-com.aspose.cells.Cell-) | <br /> |

|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getText()](#getText--) | <br /> |

|
|  | [removeFromDocument(FormattedTextFragment item)](#removeFromDocument-com.groupdocs.watermark.search.FormattedTextFragment-) | <br /> |

|
|  | [createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) | <br /> |

|
|  | [setText(String text)](#setText-java.lang.String-) | <br /> |

|
### SpreadsheetCellFormattedTextFragmentCollection(Cell cell) {#SpreadsheetCellFormattedTextFragmentCollection-com.aspose.cells.Cell-}
```
public SpreadsheetCellFormattedTextFragmentCollection(Cell cell)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cella | com.aspose.cells.Cell |  |

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
### setText(String text) {#setText-java.lang.String-}
```
public void setText(String text)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| testo | java.lang.String |  |

