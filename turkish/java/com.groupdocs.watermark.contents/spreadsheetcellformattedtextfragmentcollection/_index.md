---
title: "SpreadsheetCellFormattedTextFragmentCollection"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Excel belgesi hücresindeki biçimlendirilmiş metin bölümlerinin bir koleksiyonunu temsil eder."
type: docs
weight: 105
url: /tr/java/com.groupdocs.watermark.contents/spreadsheetcellformattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase, [com.groupdocs.watermark.search.FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
```
public class SpreadsheetCellFormattedTextFragmentCollection extends FormattedTextFragmentCollection
```

Excel belgesi hücresindeki biçimlendirilmiş metin bölümlerinin bir koleksiyonunu temsil eder.

Bu koleksiyon, `[SpreadsheetCellFormattedTextFragment](../../com.groupdocs.watermark.contents/spreadsheetcellformattedtextfragment)` türündeki öğeleri içerir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [SpreadsheetCellFormattedTextFragmentCollection(Cell cell)](#SpreadsheetCellFormattedTextFragmentCollection-com.aspose.cells.Cell-) | <br /> |

|
## Yöntemler

| Yöntem | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hücre | com.aspose.cells.Cell |  |

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment) |  |

### createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public FormattedTextFragment createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```


<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |
| metin | java.lang.String |  |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metin | java.lang.String |  |

