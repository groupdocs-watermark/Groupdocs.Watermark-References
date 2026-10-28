---
title: "PdfXObjectWatermarkOptions"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili opsi penambahan watermark saat menambahkan watermark XObject ke dokumen PDF."
type: docs
weight: 34
url: /id/java/com.groupdocs.watermark.options/pdfxobjectwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfXObjectWatermarkOptions extends PdfWatermarkOptions
```

Mewakili opsi penambahan watermark saat menambahkan watermark XObject ke dokumen PDF.

**Learn more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

Contoh berikut menunjukkan cara menambahkan watermark ke halaman tertentu dari dokumen pdf.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\doc.pdf", loadOptions);
>
>    ImageWatermark watermark = new ImageWatermark("C:\\watermark.png");
>
>    PdfXObjectWatermarkOptions options = new PdfXObjectWatermarkOptions();
>    options.setPageIndex(0);
>
>    watermarker.add(watermark, options);
>    watermarker.save("C:\\watermarked_doc.pdf");
>    watermark.close();
>    watermarker.close();
>  
> ```
> ````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [PdfXObjectWatermarkOptions()](#PdfXObjectWatermarkOptions--) | Menginisialisasi instance baru dari kelas `[PdfXObjectWatermarkOptions](../../com.groupdocs.watermark.options/pdfxobjectwatermarkoptions)`. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | Mendapatkan indeks halaman untuk menambahkan watermark. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | Mengatur indeks halaman untuk menambahkan watermark. |
|
### PdfXObjectWatermarkOptions() {#PdfXObjectWatermarkOptions--}
```
public PdfXObjectWatermarkOptions()
```


Menginisialisasi instance baru dari kelas `[PdfXObjectWatermarkOptions](../../com.groupdocs.watermark.options/pdfxobjectwatermarkoptions)`.


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

