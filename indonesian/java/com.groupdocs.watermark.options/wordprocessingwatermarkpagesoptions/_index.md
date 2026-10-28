---
title: "WordProcessingWatermarkPagesOptions"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili opsi saat menambahkan watermark ke halaman dokumen Word."
type: docs
weight: 76
url: /id/java/com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkPagesOptions extends WordProcessingWatermarkBaseOptions
```

Mewakili opsi saat menambahkan watermark ke halaman dokumen Word.

**Learn more:**

* [Add watermarks to word processing documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+word+processing+documents)

Contoh berikut menunjukkan cara menambahkan watermark ke halaman tertentu dari dokumen Word.
>
> ````
> ```
>
>    WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.doc", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    WordProcessingWatermarkPagesOptions options = new WordProcessingWatermarkPagesOptions();
>    options.setPageNumbers(new int[] { 1 });
>    
>    watermarker.save("D:\\watermarked_test.doc");
>    watermarker.close();
>  
> ```
> ````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [WordProcessingWatermarkPagesOptions()](#WordProcessingWatermarkPagesOptions--) | Menginisialisasi instance baru dari kelas `[WordProcessingWatermarkPagesOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions)`. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getPageNumbers()](#getPageNumbers--) | Mendapatkan nomor halaman untuk menambahkan watermark. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Mengatur nomor halaman untuk menambahkan watermark. |
|
### WordProcessingWatermarkPagesOptions() {#WordProcessingWatermarkPagesOptions--}
```
public WordProcessingWatermarkPagesOptions()
```


Menginisialisasi instance baru dari kelas `[WordProcessingWatermarkPagesOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions)`.


### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Mendapatkan nomor halaman untuk menambahkan watermark.


**Returns:**
int[] - Nomor halaman untuk menambahkan watermark.

<br />

*** ** * ** ***

Semua nomor harus lebih besar dari atau sama dengan 1. Properti ini hanya digunakan saat menambahkan watermark ke dokumen. Jika nilai ini  null  atau kosong, watermark akan ditambahkan ke semua halaman.

<br />


### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Mengatur nomor halaman untuk menambahkan watermark.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | int[] | Nomor halaman untuk menambahkan watermark. |

<br />

*** ** * ** ***

Semua nomor harus lebih besar dari atau sama dengan 1. Properti ini hanya digunakan saat menambahkan watermark ke dokumen. Jika nilai ini  null  atau kosong, watermark akan ditambahkan ke semua halaman.

<br />

|

