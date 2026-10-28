---
title: "PdfTextFormattedTextFragmentCollection"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示 PDF 内容主文本中格式化文本片段的集合。"
type: docs
weight: 71
url: /zh/java/com.groupdocs.watermark.contents/pdftextformattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase, [com.groupdocs.watermark.search.FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection), [com.groupdocs.watermark.contents.PdfFormattedTextFragmentCollection](../../com.groupdocs.watermark.contents/pdfformattedtextfragmentcollection)
```
public class PdfTextFormattedTextFragmentCollection extends PdfFormattedTextFragmentCollection
```

表示 PDF 内容主文本中格式化文本片段的集合。

此集合包含 `[PdfFormattedTextFragment](../../com.groupdocs.watermark.contents/pdfformattedtextfragment)` 类型的项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PdfTextFormattedTextFragmentCollection(TextFragment textFragment)](#PdfTextFormattedTextFragmentCollection-com.aspose.pdf.TextFragment-) | <br /> |

|
## 方法

| 方法 | 描述 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| textFragment | com.aspose.pdf.TextFragment |  |

### setText(String text) {#setText-java.lang.String-}
```
public void setText(String text)
```


<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文本 | java.lang.String |  |

### removeFromDocument(FormattedTextFragment item) {#removeFromDocument-com.groupdocs.watermark.search.FormattedTextFragment-}
```
public void removeFromDocument(FormattedTextFragment item)
```


<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment) |  |

### createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public FormattedTextFragment createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```


<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |
| 文本 | java.lang.String |  |
| font | [Font](../../com.groupdocs.watermark.watermarks/font) |  |
| foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |
| backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |

**Returns:**
[FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)
