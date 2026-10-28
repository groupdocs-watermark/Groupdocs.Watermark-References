---
title: "SizeSearchCriteria"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili kriteria yang memungkinkan penyaringan berdasarkan ukuran watermark."
type: docs
weight: 57
url: /id/java/com.groupdocs.watermark.search/sizesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class SizeSearchCriteria extends SearchCriteria
```

Mewakili kriteria yang memungkinkan penyaringan berdasarkan ukuran watermark.

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
|  | [SizeSearchCriteria(int dimension, double min, double max)](#SizeSearchCriteria-int-double-double-) | Menginisialisasi instance baru dari kelas `[SizeSearchCriteria](../../com.groupdocs.watermark.search/sizesearchcriteria)` dengan dimensi yang ditentukan, nilai awal, dan nilai akhir. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getMinimum()](#getMinimum--) | Mendapatkan nilai awal. |
|
|  | [getMaximum()](#getMaximum--) | Mendapatkan nilai akhir. |
|
|  | [getDimension()](#getDimension--) | Mendapatkan dimensi watermark untuk pencarian. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### SizeSearchCriteria(int dimension, double min, double max) {#SizeSearchCriteria-int-double-double-}
```
public SizeSearchCriteria(int dimension, double min, double max)
```


Menginisialisasi instance baru dari kelas `[SizeSearchCriteria](../../com.groupdocs.watermark.search/sizesearchcriteria)` dengan dimensi yang ditentukan, nilai awal, dan nilai akhir.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | dimension | int | Dimensi `[Dimension](../../com.groupdocs.watermark.common/dimension)` dari watermark untuk pencarian. |
|
|  | min | double | Nilai awal. |
|
|  | max | double | Nilai akhir. |
|

### getMinimum() {#getMinimum--}
```
public final double getMinimum()
```


Mendapatkan nilai awal.


**Returns:**
double - Nilai awal.

### getMaximum() {#getMaximum--}
```
public final double getMaximum()
```


Mendapatkan nilai akhir.


**Returns:**
double - Nilai akhir.

### getDimension() {#getDimension--}
```
public final int getDimension()
```


Mendapatkan dimensi watermark untuk pencarian.


**Returns:**
int - Dimensi watermark untuk pencarian.

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

