---
title: "RotateAngleSearchCriteria"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili kriteria yang memungkinkan penyaringan berdasarkan sudut rotasi watermark."
type: docs
weight: 52
url: /id/java/com.groupdocs.watermark.search/rotateanglesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class RotateAngleSearchCriteria extends SearchCriteria
```

Mewakili kriteria yang memungkinkan penyaringan berdasarkan sudut rotasi watermark.

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
|  | [RotateAngleSearchCriteria(double minAngle, double maxAngle)](#RotateAngleSearchCriteria-double-double-) | Menginisialisasi instance baru dari kelas `[RotateAngleSearchCriteria](../../com.groupdocs.watermark.search/rotateanglesearchcriteria)` dengan sudut awal dan sudut akhir. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getMinimumAngle()](#getMinimumAngle--) | Mendapatkan sudut awal dalam derajat. |
|
|  | [getMaximumAngle()](#getMaximumAngle--) | Mendapatkan sudut akhir dalam derajat. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### RotateAngleSearchCriteria(double minAngle, double maxAngle) {#RotateAngleSearchCriteria-double-double-}
```
public RotateAngleSearchCriteria(double minAngle, double maxAngle)
```


Menginisialisasi instance baru dari kelas `[RotateAngleSearchCriteria](../../com.groupdocs.watermark.search/rotateanglesearchcriteria)` dengan sudut awal dan sudut akhir.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | minAngle | double | Sudut awal dalam derajat. |
|
|  | maxAngle | double | Sudut akhir dalam derajat. |
|

### getMinimumAngle() {#getMinimumAngle--}
```
public final double getMinimumAngle()
```


Mendapatkan sudut awal dalam derajat.


**Returns:**
double - Sudut awal.

### getMaximumAngle() {#getMaximumAngle--}
```
public final double getMaximumAngle()
```


Mendapatkan sudut akhir dalam derajat.


**Returns:**
double - Sudut akhir.

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

