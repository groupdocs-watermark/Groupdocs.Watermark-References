---
title: "PdfArtifactWatermarkOptions"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili opsi penambahan watermark saat menambahkan watermark artefak ke dokumen PDF."
type: docs
weight: 29
url: /id/java/com.groupdocs.watermark.options/pdfartifactwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfArtifactWatermarkOptions extends PdfWatermarkOptions
```

Mewakili opsi penambahan watermark saat menambahkan watermark artefak ke dokumen PDF.

**Leran more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

Contoh berikut menunjukkan cara menambahkan watermark artefak gambar ke dokumen PDF.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.pdf", loadOptions);
>
>    ImageWatermark watermark = new ImageWatermark("D:\\icon.png");
>
>    PdfArtifactWatermarkOptions options = new PdfArtifactWatermarkOptions();
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
|  | [PdfArtifactWatermarkOptions()](#PdfArtifactWatermarkOptions--) | Menginisialisasi instance baru dari kelas `[PdfArtifactWatermarkOptions](../../com.groupdocs.watermark.options/pdfartifactwatermarkoptions)`. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | Mendapatkan indeks halaman untuk menambahkan watermark. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | Mengatur indeks halaman untuk menambahkan watermark. |
|
### PdfArtifactWatermarkOptions() {#PdfArtifactWatermarkOptions--}
```
public PdfArtifactWatermarkOptions()
```


Menginisialisasi instance baru dari kelas `[PdfArtifactWatermarkOptions](../../com.groupdocs.watermark.options/pdfartifactwatermarkoptions)`.


### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


Mendapatkan indeks halaman untuk menambahkan watermark.


**Returns:**
int - Indeks halaman untuk menambahkan watermark.

### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


Mengatur indeks halaman untuk menambahkan watermark.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | int | Indeks halaman untuk menambahkan watermark. |
|

