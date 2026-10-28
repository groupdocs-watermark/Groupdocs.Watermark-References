---
title: "TextFormattingSearchCriteria"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili kriteria yang memungkinkan penyaringan berdasarkan format teks."
type: docs
weight: 66
url: /id/java/com.groupdocs.watermark.search/textformattingsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class TextFormattingSearchCriteria extends SearchCriteria
```

Mewakili kriteria yang memungkinkan penyaringan berdasarkan format teks.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

Contoh berikut menunjukkan cara menghapus watermark yang mungkin dengan format tertentu
pemformatan teks (tanpa mempedulikan jenis dokumen).
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\test.doc");
>    TextFormattingSearchCriteria criteria = new TextFormattingSearchCriteria();
>
>    criteria.setForegroundColorRange(new ColorRange());
>    criteria.getForegroundColorRange().setMinHue(-5);
>    criteria.getForegroundColorRange().setMaxHue(10);
>    criteria.getForegroundColorRange().setMinBrightness(0.01f);
>    criteria.getForegroundColorRange().setMaxBrightness(0.99f);
>    criteria.setBackgroundColorRange(new ColorRange());
>    criteria.getBackgroundColorRange().setEmpty(true);
>    criteria.setFontName("Arial");
>    criteria.setMinFontSize(19);
>    criteria.setMaxFontSize(42);
>    criteria.setFontBold(true);
>
>    PossibleWatermarkCollection watermarks = watermarker.search(criteria);
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
|  | [TextFormattingSearchCriteria()](#TextFormattingSearchCriteria--) | Menginisialisasi instance baru dari kelas `[TextFormattingSearchCriteria](../../com.groupdocs.watermark.search/textformattingsearchcriteria)`. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getForegroundColorRange()](#getForegroundColorRange--) | Mendapatkan rentang warna yang digunakan untuk menyaring watermark berdasarkan warna latar depan teks. |
|
|  | [setForegroundColorRange(ColorRange value)](#setForegroundColorRange-com.groupdocs.watermark.search.ColorRange-) | Mengatur rentang warna yang digunakan untuk menyaring watermark berdasarkan warna latar depan teks. |
|
|  | [getBackgroundColorRange()](#getBackgroundColorRange--) | Mendapatkan rentang warna yang digunakan untuk menyaring watermark berdasarkan warna latar belakang teks. |
|
|  | [setBackgroundColorRange(ColorRange value)](#setBackgroundColorRange-com.groupdocs.watermark.search.ColorRange-) | Mengatur rentang warna yang digunakan untuk menyaring watermark berdasarkan warna latar belakang teks. |
|
|  | [getFontName()](#getFontName--) | Mendapatkan nama font yang digunakan dalam pemformatan teks watermark yang mungkin. |
|
|  | [setFontName(String value)](#setFontName-java.lang.String-) | Mengatur nama font yang digunakan dalam pemformatan teks watermark yang mungkin. |
|
|  | [getMinFontSize()](#getMinFontSize--) | Mendapatkan nilai awal ukuran font. |
|
|  | [setMinFontSize(float value)](#setMinFontSize-float-) | Mengatur nilai awal ukuran font. |
|
|  | [getMaxFontSize()](#getMaxFontSize--) | Mendapatkan nilai akhir ukuran font. |
|
|  | [setMaxFontSize(float value)](#setMaxFontSize-float-) | Mengatur nilai akhir ukuran font. |
|
|  | [getFontBold()](#getFontBold--) | Mendapatkan nilai yang menunjukkan apakah font yang digunakan dalam pemformatan teks watermark dicetak tebal. |
|
|  | [setFontBold(Boolean value)](#setFontBold-java.lang.Boolean-) | Mengatur nilai yang menunjukkan apakah font yang digunakan dalam pemformatan teks watermark dicetak tebal. |
|
|  | [getFontItalic()](#getFontItalic--) | Mendapatkan nilai yang menunjukkan apakah font yang digunakan dalam pemformatan teks watermark miring. |
|
|  | [setFontItalic(Boolean value)](#setFontItalic-java.lang.Boolean-) | Mengatur nilai yang menunjukkan apakah font yang digunakan dalam pemformatan teks watermark miring. |
|
|  | [getFontUnderline()](#getFontUnderline--) | Mendapatkan nilai yang menunjukkan apakah font yang digunakan dalam pemformatan teks watermark bergaris bawah. |
|
|  | [setFontUnderline(Boolean value)](#setFontUnderline-java.lang.Boolean-) | Mengatur nilai yang menunjukkan apakah font yang digunakan dalam pemformatan teks watermark bergaris bawah. |
|
|  | [getFontStrikeout()](#getFontStrikeout--) | Mendapatkan nilai yang menunjukkan apakah font yang digunakan dalam pemformatan teks watermark dicoret. |
|
|  | [setFontStrikeout(Boolean value)](#setFontStrikeout-java.lang.Boolean-) | Mengatur nilai yang menunjukkan apakah font yang digunakan dalam pemformatan teks watermark dicoret. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### TextFormattingSearchCriteria() {#TextFormattingSearchCriteria--}
```
public TextFormattingSearchCriteria()
```


Menginisialisasi instance baru dari kelas `[TextFormattingSearchCriteria](../../com.groupdocs.watermark.search/textformattingsearchcriteria)`.


### getForegroundColorRange() {#getForegroundColorRange--}
```
public final ColorRange getForegroundColorRange()
```


Mendapatkan rentang warna yang digunakan untuk menyaring watermark berdasarkan warna latar depan teks.


**Returns:**
[ColorRange](../../com.groupdocs.watermark.search/colorrange) - The range of colors which are used to filter watermarks by text foreground color.

### setForegroundColorRange(ColorRange value) {#setForegroundColorRange-com.groupdocs.watermark.search.ColorRange-}
```
public final void setForegroundColorRange(ColorRange value)
```


Mengatur rentang warna yang digunakan untuk menyaring watermark berdasarkan warna latar depan teks.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [ColorRange](../../com.groupdocs.watermark.search/colorrange) | Rentang warna yang digunakan untuk menyaring watermark berdasarkan warna latar depan teks. |
|

### getBackgroundColorRange() {#getBackgroundColorRange--}
```
public final ColorRange getBackgroundColorRange()
```


Mendapatkan rentang warna yang digunakan untuk menyaring watermark berdasarkan warna latar belakang teks.


**Returns:**
[ColorRange](../../com.groupdocs.watermark.search/colorrange) - The range of colors which are used to filter watermarks by text background color.

### setBackgroundColorRange(ColorRange value) {#setBackgroundColorRange-com.groupdocs.watermark.search.ColorRange-}
```
public final void setBackgroundColorRange(ColorRange value)
```


Mengatur rentang warna yang digunakan untuk menyaring watermark berdasarkan warna latar belakang teks.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [ColorRange](../../com.groupdocs.watermark.search/colorrange) | Rentang warna yang digunakan untuk menyaring watermark berdasarkan warna latar belakang teks. |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Mendapatkan nama font yang digunakan dalam pemformatan teks watermark yang mungkin.


**Returns:**
java.lang.String - Nilai default adalah null, yang berarti filter tidak diterapkan.

### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


Mengatur nama font yang digunakan dalam pemformatan teks watermark yang mungkin.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | java.lang.String | Nilai default adalah null, yang berarti filter tidak diterapkan. |
|

### getMinFontSize() {#getMinFontSize--}
```
public final float getMinFontSize()
```


Mendapatkan nilai awal ukuran font.


**Returns:**
float - Nilai awal ukuran font.

### setMinFontSize(float value) {#setMinFontSize-float-}
```
public final void setMinFontSize(float value)
```


Mengatur nilai awal ukuran font.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | float | Nilai awal ukuran font. |
|

### getMaxFontSize() {#getMaxFontSize--}
```
public final float getMaxFontSize()
```


Mendapatkan nilai akhir ukuran font.


**Returns:**
float - Nilai akhir ukuran font.

### setMaxFontSize(float value) {#setMaxFontSize-float-}
```
public final void setMaxFontSize(float value)
```


Mengatur nilai akhir ukuran font.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | float | Nilai akhir ukuran font. |
|

### getFontBold() {#getFontBold--}
```
public final Boolean getFontBold()
```


Mendapatkan nilai yang menunjukkan apakah font yang digunakan dalam pemformatan teks watermark dicetak tebal.


**Returns:**
java.lang.Boolean - Nilai default adalah null, yang berarti filter tidak diterapkan.

### setFontBold(Boolean value) {#setFontBold-java.lang.Boolean-}
```
public final void setFontBold(Boolean value)
```


Mengatur nilai yang menunjukkan apakah font yang digunakan dalam pemformatan teks watermark dicetak tebal.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | java.lang.Boolean | Nilai default adalah null, yang berarti filter tidak diterapkan. |
|

### getFontItalic() {#getFontItalic--}
```
public final Boolean getFontItalic()
```


Mendapatkan nilai yang menunjukkan apakah font yang digunakan dalam pemformatan teks watermark miring.


**Returns:**
java.lang.Boolean - Nilai default adalah null, yang berarti filter tidak diterapkan.

### setFontItalic(Boolean value) {#setFontItalic-java.lang.Boolean-}
```
public final void setFontItalic(Boolean value)
```


Mengatur nilai yang menunjukkan apakah font yang digunakan dalam pemformatan teks watermark miring.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | java.lang.Boolean | Nilai default adalah null, yang berarti filter tidak diterapkan. |
|

### getFontUnderline() {#getFontUnderline--}
```
public final Boolean getFontUnderline()
```


Mendapatkan nilai yang menunjukkan apakah font yang digunakan dalam pemformatan teks watermark bergaris bawah.


**Returns:**
java.lang.Boolean - Nilai default adalah null, yang berarti filter tidak diterapkan.

### setFontUnderline(Boolean value) {#setFontUnderline-java.lang.Boolean-}
```
public final void setFontUnderline(Boolean value)
```


Mengatur nilai yang menunjukkan apakah font yang digunakan dalam pemformatan teks watermark bergaris bawah.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | java.lang.Boolean | Nilai default adalah null, yang berarti filter tidak diterapkan. |
|

### getFontStrikeout() {#getFontStrikeout--}
```
public final Boolean getFontStrikeout()
```


Mendapatkan nilai yang menunjukkan apakah font yang digunakan dalam pemformatan teks watermark dicoret.


**Returns:**
java.lang.Boolean - Nilai default adalah null, yang berarti filter tidak diterapkan.

### setFontStrikeout(Boolean value) {#setFontStrikeout-java.lang.Boolean-}
```
public final void setFontStrikeout(Boolean value)
```


Mengatur nilai yang menunjukkan apakah font yang digunakan dalam pemformatan teks watermark dicoret.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | java.lang.Boolean | Nilai default adalah null, yang berarti filter tidak diterapkan. |
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

