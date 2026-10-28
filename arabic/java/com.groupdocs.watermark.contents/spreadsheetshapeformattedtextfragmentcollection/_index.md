---
title: "SpreadsheetShapeFormattedTextFragmentCollection"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل مجموعة من أجزاء النص المنسق في شكل نصي لمستند Excel."
type: docs
weight: 120
url: /ar/java/com.groupdocs.watermark.contents/spreadsheetshapeformattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase, [com.groupdocs.watermark.search.FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
```
public class SpreadsheetShapeFormattedTextFragmentCollection extends FormattedTextFragmentCollection
```

يمثل مجموعة من أجزاء النص المنسق في شكل نصي لمستند Excel.

هذه المجموعة تحتوي على عناصر من النوع `[SpreadsheetShapeFormattedTextFragment](../../com.groupdocs.watermark.contents/spreadsheetshapeformattedtextfragment)`.

## الطرق

| طريقة | الوصف |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment) |  |

### createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public FormattedTextFragment createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```


<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int |  |
| نص | java.lang.String |  |
| font | [Font](../../com.groupdocs.watermark.watermarks/font) |  |
| foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |
| backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |

**Returns:**
[FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)
