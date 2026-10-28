---
title: "WordProcessingTextFormattedTextFragmentCollection"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili kumpulan fragmen teks terformat dalam teks utama dokumen Word."
type: docs
weight: 146
url: /id/java/com.groupdocs.watermark.contents/wordprocessingtextformattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase, [com.groupdocs.watermark.search.FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection), [com.groupdocs.watermark.contents.WordProcessingFormattedTextFragmentCollection](../../com.groupdocs.watermark.contents/wordprocessingformattedtextfragmentcollection)
```
public class WordProcessingTextFormattedTextFragmentCollection extends WordProcessingFormattedTextFragmentCollection
```

Mewakili kumpulan fragmen teks terformat dalam teks utama dokumen Word.

Koleksi ini berisi item berjenis `[WordProcessingTextFormattedTextFragment](../../com.groupdocs.watermark.contents/wordprocessingtextformattedtextfragment)`.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [WordProcessingTextFormattedTextFragmentCollection(ReplacingArgs replacingArgs, WordProcessingTextPossibleWatermark parentWatermark)](#WordProcessingTextFormattedTextFragmentCollection-com.aspose.words.ReplacingArgs-com.groupdocs.watermark.search.WordProcessingTextPossibleWatermark-) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [setText(String text)](#setText-java.lang.String-) |  |
| [removeFromDocument(FormattedTextFragment item)](#removeFromDocument-com.groupdocs.watermark.search.FormattedTextFragment-) |  |
| [createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) |  |
### WordProcessingTextFormattedTextFragmentCollection(ReplacingArgs replacingArgs, WordProcessingTextPossibleWatermark parentWatermark) {#WordProcessingTextFormattedTextFragmentCollection-com.aspose.words.ReplacingArgs-com.groupdocs.watermark.search.WordProcessingTextPossibleWatermark-}
```
public WordProcessingTextFormattedTextFragmentCollection(ReplacingArgs replacingArgs, WordProcessingTextPossibleWatermark parentWatermark)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| replacingArgs | com.aspose.words.ReplacingArgs |  |
| parentWatermark | [WordProcessingTextPossibleWatermark](../../com.groupdocs.watermark.search/wordprocessingtextpossiblewatermark) |  |

### setText(String text) {#setText-java.lang.String-}
```
public void setText(String text)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| teks | java.lang.String |  |

### removeFromDocument(FormattedTextFragment item) {#removeFromDocument-com.groupdocs.watermark.search.FormattedTextFragment-}
```
public void removeFromDocument(FormattedTextFragment item)
```


<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment) |  |

### createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public FormattedTextFragment createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | int |  |
| teks | java.lang.String |  |
| font | [Font](../../com.groupdocs.watermark.watermarks/font) |  |
| foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |
| backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |

**Returns:**
[FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)
