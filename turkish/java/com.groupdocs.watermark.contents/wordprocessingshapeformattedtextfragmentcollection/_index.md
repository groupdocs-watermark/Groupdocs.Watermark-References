---
title: "WordProcessingShapeFormattedTextFragmentCollection"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Bir Word belgesi şekli içindeki biçimlendirilmiş metin parçacıklarının bir koleksiyonunu temsil eder."
type: docs
weight: 143
url: /tr/java/com.groupdocs.watermark.contents/wordprocessingshapeformattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase, [com.groupdocs.watermark.search.FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection), [com.groupdocs.watermark.contents.WordProcessingFormattedTextFragmentCollection](../../com.groupdocs.watermark.contents/wordprocessingformattedtextfragmentcollection)
```
public class WordProcessingShapeFormattedTextFragmentCollection extends WordProcessingFormattedTextFragmentCollection
```

Bir Word belgesi şekli içindeki biçimlendirilmiş metin parçacıklarının bir koleksiyonunu temsil eder.

Bu koleksiyon, `[WordProcessingTextFormattedTextFragment](../../com.groupdocs.watermark.contents/wordprocessingtextformattedtextfragment)` türündeki öğeleri içerir.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getText()](#getText--) |  |
| [setText(String text)](#setText-java.lang.String-) |  |
| [removeFromDocument(FormattedTextFragment item)](#removeFromDocument-com.groupdocs.watermark.search.FormattedTextFragment-) |  |
| [createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) |  |
### getText() {#getText--}
```
public String getText()
```




**Returns:**
java.lang.String
### setText(String text) {#setText-java.lang.String-}
```
public void setText(String text)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metin | java.lang.String |  |

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
