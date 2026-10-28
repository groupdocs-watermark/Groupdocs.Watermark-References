---
title: "DiagramPageWatermarkOptions"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili opsi penambahan watermark saat menambahkan watermark bentuk ke halaman tertentu dari dokumen Visio."
type: docs
weight: 11
url: /id/java/com.groupdocs.watermark.options/diagrampagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.DiagramWatermarkOptions](../../com.groupdocs.watermark.options/diagramwatermarkoptions)
```
public final class DiagramPageWatermarkOptions extends DiagramWatermarkOptions
```

Mewakili opsi penambahan watermark saat menambahkan watermark bentuk ke halaman tertentu dari dokumen Visio.

**Learn more:**

* [Add watermarks to diagram documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+diagram+documents)

Contoh berikut menunjukkan cara menambahkan watermark yang dilindungi ke halaman pertama dokumen Visio.
>
> ````
> ```
>
>    DiagramLoadOptions loadOptions = new DiagramLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.vsdx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));
>
>    DiagramPageWatermarkOptions options = new DiagramPageWatermarkOptions();
>    options.setLocked(true);
>    options.setPageIndex(0);
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.vsdx");
>    watermarker.close();
>  
> ```
> ````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [DiagramPageWatermarkOptions()](#DiagramPageWatermarkOptions--) | Menginisialisasi instance baru dari kelas `[DiagramPageWatermarkOptions](../../com.groupdocs.watermark.options/diagrampagewatermarkoptions)`. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | Mendapatkan indeks halaman untuk menambahkan watermark. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | Mengatur indeks halaman untuk menambahkan watermark. |
|
### DiagramPageWatermarkOptions() {#DiagramPageWatermarkOptions--}
```
public DiagramPageWatermarkOptions()
```


Menginisialisasi instance baru dari kelas `[DiagramPageWatermarkOptions](../../com.groupdocs.watermark.options/diagrampagewatermarkoptions)`.


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

