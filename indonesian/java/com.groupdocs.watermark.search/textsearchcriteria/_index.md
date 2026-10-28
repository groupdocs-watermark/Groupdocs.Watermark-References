---
title: "TextSearchCriteria"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili kriteria yang memungkinkan penyaringan berdasarkan teks watermark."
type: docs
weight: 67
url: /id/java/com.groupdocs.watermark.search/textsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria)
```
public class TextSearchCriteria extends PageSearchCriteria
```

Mewakili kriteria yang memungkinkan penyaringan berdasarkan teks watermark.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

Contoh berikut menunjukkan cara menemukan dan menghapus watermark menggunakan kriteria pencarian.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("C:\\test.some_ext");
>    SizeSearchCriteria widthRange = new SizeSearchCriteria(Dimension.Width, 50, 100);
>    RotateAngleSearchCriteria rotateAngle = new RotateAngleSearchCriteria(0, 45);
>    TextSearchCriteria textCriteria = new TextSearchCriteria(Pattern.compile("^Test watermark$"));
>
>    PossibleWatermarkCollection watermarks = watermarker.search(textCriteria.and(widthRange.or(rotateAngle)));
>    watermarks.clear();
>
>    watermarker.save("C:\\modified_test.some_ext");
>    watermarker.close();
>  
> ```
> ````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [TextSearchCriteria(Pattern pattern)](#TextSearchCriteria-java.util.regex.Pattern-) | Menginisialisasi instance baru dari kelas `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` dengan ekspresi reguler yang ditentukan. |
|
| [TextSearchCriteria(System.Text.RegularExpressions.Regex pattern)](#TextSearchCriteria-com.aspose.ms.System.Text.RegularExpressions.Regex-) |  |
|  | [TextSearchCriteria(String searchString, boolean isMatchCase)](#TextSearchCriteria-java.lang.String-boolean-) | Menginisialisasi instance baru dari kelas `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` dengan string pencarian dan flag untuk perbandingan. |
|
|  | [TextSearchCriteria(String searchString)](#TextSearchCriteria-java.lang.String-) | Menginisialisasi instance baru dari kelas `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` dengan string pencarian. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getPattern()](#getPattern--) | Mendapatkan pola pencarian. |
|
| [getPatternInternal()](#getPatternInternal--) |  |
|  | [getSkipUnreadableCharacters()](#getSkipUnreadableCharacters--) | Mendapatkan nilai yang menunjukkan bahwa karakter yang tidak dapat dibaca akan dilewati selama perbandingan string. |
|
|  | [setSkipUnreadableCharacters(boolean value)](#setSkipUnreadableCharacters-boolean-) | Mengatur nilai yang menunjukkan bahwa karakter yang tidak dapat dibaca akan dilewati selama perbandingan string. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### TextSearchCriteria(Pattern pattern) {#TextSearchCriteria-java.util.regex.Pattern-}
```
public TextSearchCriteria(Pattern pattern)
```


Menginisialisasi instance baru dari kelas `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` dengan ekspresi reguler yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | pattern | java.util.regex.Pattern | Ekspresi reguler untuk dicocokkan. |
|

### TextSearchCriteria(System.Text.RegularExpressions.Regex pattern) {#TextSearchCriteria-com.aspose.ms.System.Text.RegularExpressions.Regex-}
```
public TextSearchCriteria(System.Text.RegularExpressions.Regex pattern)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pattern | com.aspose.ms.System.Text.RegularExpressions.Regex |  |

### TextSearchCriteria(String searchString, boolean isMatchCase) {#TextSearchCriteria-java.lang.String-boolean-}
```
public TextSearchCriteria(String searchString, boolean isMatchCase)
```


Menginisialisasi instance baru dari kelas `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` dengan string pencarian dan flag untuk perbandingan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | searchString | java.lang.String | String tepat untuk dicari. |
|
|  | isMatchCase | boolean | `false` untuk mengabaikan huruf besar/kecil selama perbandingan; jika tidak, `true`. |
|

### TextSearchCriteria(String searchString) {#TextSearchCriteria-java.lang.String-}
```
public TextSearchCriteria(String searchString)
```


Menginisialisasi instance baru dari kelas `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` dengan string pencarian.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | searchString | java.lang.String | String tepat untuk dicari. |
|

### getPattern() {#getPattern--}
```
public final Pattern getPattern()
```


Mendapatkan pola pencarian.


**Returns:**
java.util.regex.Pattern - Pola ekspresi reguler untuk dicocokkan.

### getPatternInternal() {#getPatternInternal--}
```
public final System.Text.RegularExpressions.Regex getPatternInternal()
```




**Returns:**
com.aspose.ms.System.Text.RegularExpressions.Regex
### getSkipUnreadableCharacters() {#getSkipUnreadableCharacters--}
```
public final boolean getSkipUnreadableCharacters()
```


Mendapatkan nilai yang menunjukkan bahwa karakter yang tidak dapat dibaca akan dilewati selama perbandingan string.


**Returns:**
boolean - Nilai yang menunjukkan bahwa karakter yang tidak dapat dibaca akan dilewati selama perbandingan string.

### setSkipUnreadableCharacters(boolean value) {#setSkipUnreadableCharacters-boolean-}
```
public final void setSkipUnreadableCharacters(boolean value)
```


Mengatur nilai yang menunjukkan bahwa karakter yang tidak dapat dibaca akan dilewati selama perbandingan string.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | boolean | Nilai yang menunjukkan bahwa karakter yang tidak dapat dibaca akan dilewati selama perbandingan string. |
|

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

