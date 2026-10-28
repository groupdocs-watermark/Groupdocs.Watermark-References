---
title: "PdfShapeFormattedTextFragmentCollection"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "pdf 문서 XObject 아티팩트 또는 주석에 포함된 형식화된 텍스트 조각 컬렉션을 나타냅니다."
type: docs
weight: 70
url: /ko/java/com.groupdocs.watermark.contents/pdfshapeformattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase, [com.groupdocs.watermark.search.FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection), [com.groupdocs.watermark.contents.PdfFormattedTextFragmentCollection](../../com.groupdocs.watermark.contents/pdfformattedtextfragmentcollection)
```
public class PdfShapeFormattedTextFragmentCollection extends PdfFormattedTextFragmentCollection
```

pdf 문서 XObject, Artifact 또는 Annotation의 서식이 지정된 텍스트 조각 컬렉션을 나타냅니다.

이 컬렉션에는 `[PdfFormattedTextFragment](../../com.groupdocs.watermark.contents/pdfformattedtextfragment)` 유형의 항목이 포함됩니다.

## 메서드

| 메서드 | 설명 |
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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 텍스트 | java.lang.String |  |

### createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public FormattedTextFragment createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 인덱스 | int |  |
| 텍스트 | java.lang.String |  |
| font | [Font](../../com.groupdocs.watermark.watermarks/font) |  |
| foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |
| backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |

**Returns:**
[FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)
