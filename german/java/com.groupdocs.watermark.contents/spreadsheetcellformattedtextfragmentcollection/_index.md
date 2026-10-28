---
title: "SpreadsheetCellFormattedTextFragmentCollection"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt eine Sammlung von formatierten Textfragmenten in einer Excel-Dokumentzelle dar."
type: docs
weight: 105
url: /de/java/com.groupdocs.watermark.contents/spreadsheetcellformattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase, [com.groupdocs.watermark.search.FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
```
public class SpreadsheetCellFormattedTextFragmentCollection extends FormattedTextFragmentCollection
```

Stellt eine Sammlung von formatierten Textfragmenten in einer Excel-Dokumentzelle dar.

Diese Sammlung enthält Elemente des Typs `[SpreadsheetCellFormattedTextFragment](../../com.groupdocs.watermark.contents/spreadsheetcellformattedtextfragment)`.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [SpreadsheetCellFormattedTextFragmentCollection(Cell cell)](#SpreadsheetCellFormattedTextFragmentCollection-com.aspose.cells.Cell-) | <br /> |

|
## Methoden

| Methode | Beschreibung |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Zelle | com.aspose.cells.Cell |  |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment) |  |

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
### setText(String text) {#setText-java.lang.String-}
```
public void setText(String text)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Text | java.lang.String |  |

