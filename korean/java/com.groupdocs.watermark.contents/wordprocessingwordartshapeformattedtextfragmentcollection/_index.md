---
title: "WordProcessingWordArtShapeFormattedTextFragmentCollection"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "Word 문서 WordArt 도형 내 서식이 적용된 텍스트 조각 컬렉션을 나타냅니다."
type: docs
weight: 151
url: /ko/java/com.groupdocs.watermark.contents/wordprocessingwordartshapeformattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase, [com.groupdocs.watermark.search.FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection), [com.groupdocs.watermark.contents.WordProcessingFormattedTextFragmentCollection](../../com.groupdocs.watermark.contents/wordprocessingformattedtextfragmentcollection)
```
public class WordProcessingWordArtShapeFormattedTextFragmentCollection extends WordProcessingFormattedTextFragmentCollection
```

Word 문서 WordArt 도형 내 서식이 적용된 텍스트 조각 컬렉션을 나타냅니다.

이 컬렉션은 `[WordProcessingWordArtShapeFormattedTextFragment](../../com.groupdocs.watermark.contents/wordprocessingwordartshapeformattedtextfragment)` 유형의 항목을 포함합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getText()](#getText--) |  |
| [removeFromDocument(FormattedTextFragment item)](#removeFromDocument-com.groupdocs.watermark.search.FormattedTextFragment-) |  |
| [createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) |  |
| [setText(String text)](#setText-java.lang.String-) |  |
### getText() {#getText--}
```
public String getText()
```




**Returns:**
java.lang.String
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
### setText(String text) {#setText-java.lang.String-}
```
public void setText(String text)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 텍스트 | java.lang.String |  |

