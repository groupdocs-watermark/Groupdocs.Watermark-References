---
title: "PdfShapeFormattedTextFragmentCollection"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "PDF belgesi XObject Artifact veya Annotation içinde biçimlendirilmiş metin parçacıklarından oluşan bir koleksiyonu temsil eder."
type: docs
weight: 70
url: /tr/java/com.groupdocs.watermark.contents/pdfshapeformattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase, [com.groupdocs.watermark.search.FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection), [com.groupdocs.watermark.contents.PdfFormattedTextFragmentCollection](../../com.groupdocs.watermark.contents/pdfformattedtextfragmentcollection)
```
public class PdfShapeFormattedTextFragmentCollection extends PdfFormattedTextFragmentCollection
```

PDF belgesi XObject, Artifact veya Annotation içinde biçimlendirilmiş metin fragmentlerinin bir koleksiyonunu temsil eder.

Bu koleksiyon, [PdfFormattedTextFragment](../../com.groupdocs.watermark.contents/pdfformattedtextfragment) türündeki öğeleri içerir.

## Yöntemler

| Yöntem | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metin | java.lang.String |  |

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
