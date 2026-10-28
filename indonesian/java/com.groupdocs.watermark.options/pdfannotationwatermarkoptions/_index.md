---
title: "PdfAnnotationWatermarkOptions"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili opsi penambahan watermark saat menambahkan watermark anotasi ke dokumen PDF."
type: docs
weight: 28
url: /id/java/com.groupdocs.watermark.options/pdfannotationwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfAnnotationWatermarkOptions extends PdfWatermarkOptions
```

Mewakili opsi penambahan watermark saat menambahkan watermark anotasi ke dokumen PDF.

**Learn more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

Contoh berikut menunjukkan cara menambahkan watermark anotasi gambar ke dokumen PDF.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.pdf", loadOptions);
>
>    ImageWatermark watermark = new ImageWatermark("D:\\icon.png");
>
>    PdfAnnotationWatermarkOptions options = new PdfAnnotationWatermarkOptions();
>    options.setPageIndex(-1); // default - all pages
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.pdf");
>    watermark.close();
>    watermarker.close();
>  
> ```
> ````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [PdfAnnotationWatermarkOptions()](#PdfAnnotationWatermarkOptions--) | Menginisialisasi instance baru dari kelas `[PdfAnnotationWatermarkOptions](../../com.groupdocs.watermark.options/pdfannotationwatermarkoptions)`. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | Mendapatkan indeks halaman untuk menambahkan watermark. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | Mengatur indeks halaman untuk menambahkan watermark. |
|
|  | [getPrintOnly()](#getPrintOnly--) | Dapatkan nilai yang menunjukkan apakah anotasi akan dicetak, tetapi tidak ditampilkan dalam aplikasi penampil PDF. |
|
|  | [setPrintOnly(boolean value)](#setPrintOnly-boolean-) | Atur nilai yang menunjukkan apakah anotasi akan dicetak, tetapi tidak ditampilkan dalam aplikasi penampil PDF. |
|
### PdfAnnotationWatermarkOptions() {#PdfAnnotationWatermarkOptions--}
```
public PdfAnnotationWatermarkOptions()
```


Menginisialisasi instance baru dari kelas `[PdfAnnotationWatermarkOptions](../../com.groupdocs.watermark.options/pdfannotationwatermarkoptions)`.


### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


Mendapatkan indeks halaman untuk menambahkan watermark.


**Returns:**
int - Indeks halaman untuk menambahkan watermark.

<br />

*** ** * ** ***

-1 means all pages.

<br />


### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


Mengatur indeks halaman untuk menambahkan watermark.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | int | Indeks halaman untuk menambahkan watermark. |

<br />

*** ** * ** ***

-1 means all pages.

<br />

|

### getPrintOnly() {#getPrintOnly--}
```
public final boolean getPrintOnly()
```


Dapatkan nilai yang menunjukkan apakah anotasi akan dicetak, tetapi tidak ditampilkan dalam aplikasi penampil PDF.


**Returns:**
boolean - Nilai yang menunjukkan apakah anotasi akan dicetak, tetapi tidak ditampilkan dalam aplikasi penampil PDF.

### setPrintOnly(boolean value) {#setPrintOnly-boolean-}
```
public final void setPrintOnly(boolean value)
```


Atur nilai yang menunjukkan apakah anotasi akan dicetak, tetapi tidak ditampilkan dalam aplikasi penampil PDF.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | boolean | Nilai yang menunjukkan apakah anotasi akan dicetak, tetapi tidak ditampilkan dalam aplikasi penampil PDF. |
|

