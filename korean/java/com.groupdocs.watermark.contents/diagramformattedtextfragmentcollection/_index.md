---
title: "DiagramFormattedTextFragmentCollection"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "Visio 문서의 서식이 지정된 텍스트 조각 컬렉션을 나타냅니다."
type: docs
weight: 17
url: /ko/java/com.groupdocs.watermark.contents/diagramformattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase, [com.groupdocs.watermark.search.FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
```
public class DiagramFormattedTextFragmentCollection extends FormattedTextFragmentCollection
```

Visio 문서의 서식이 지정된 텍스트 조각 컬렉션을 나타냅니다.

이 컬렉션은 `[DiagramFormattedTextFragment](../../com.groupdocs.watermark.contents/diagramformattedtextfragment)` 유형의 항목을 포함합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [removeFromDocument(FormattedTextFragment item)](#removeFromDocument-com.groupdocs.watermark.search.FormattedTextFragment-) | <br /> |

|
|  | [createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) | <br /> |

|
### removeFromDocument(FormattedTextFragment item) {#removeFromDocument-com.groupdocs.watermark.search.FormattedTextFragment-}
```
public void removeFromDocument(FormattedTextFragment item)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| item | [FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment) |  |

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
