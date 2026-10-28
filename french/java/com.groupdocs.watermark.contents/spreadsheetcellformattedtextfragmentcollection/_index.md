---
title: "SpreadsheetCellFormattedTextFragmentCollection"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente une collection de fragments de texte formaté dans une cellule de document Excel."
type: docs
weight: 105
url: /fr/java/com.groupdocs.watermark.contents/spreadsheetcellformattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase, [com.groupdocs.watermark.search.FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
```
public class SpreadsheetCellFormattedTextFragmentCollection extends FormattedTextFragmentCollection
```

Représente une collection de fragments de texte formaté dans une cellule de document Excel.

Cette collection contient les éléments du type `[SpreadsheetCellFormattedTextFragment](../../com.groupdocs.watermark.contents/spreadsheetcellformattedtextfragment)`.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [SpreadsheetCellFormattedTextFragmentCollection(Cell cell)](#SpreadsheetCellFormattedTextFragmentCollection-com.aspose.cells.Cell-) | <br /> |

|
## Méthodes

| Méthode | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| cellule | com.aspose.cells.Cell |  |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment) |  |

### createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public FormattedTextFragment createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```


<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| indice | int |  |
| texte | java.lang.String |  |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| texte | java.lang.String |  |

