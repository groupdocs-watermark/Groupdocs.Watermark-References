---
title: "MultiframeImageWatermarkOptions"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili opsi penambahan watermark saat menambahkan watermark ke gambar multi-frame."
type: docs
weight: 26
url: /id/java/com.groupdocs.watermark.options/multiframeimagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions)
```
public class MultiframeImageWatermarkOptions extends WatermarkOptions
```

Mewakili opsi penambahan watermark saat menambahkan watermark ke gambar multi-frame.

**Learn more:**

* [Add watermarks to images](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images)

Contoh berikut menunjukkan cara menambahkan watermark ke bingkai tertentu dari gambar multi-bingkai.
>
> ````
> ```
>
>    ImageLoadOptions loadOptions = new ImageLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\test.gif", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));
>
>    MultiframeImageWatermarkOptions options = new MultiframeImageWatermarkOptions();
>    options.setFrameIndex(0);
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.gif");
>    watermarker.close();
>  
> ```
> ````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [MultiframeImageWatermarkOptions()](#MultiframeImageWatermarkOptions--) | Menginisialisasi instansi baru dari kelas `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)`. |
|
|  | [MultiframeImageWatermarkOptions(int frameIndex)](#MultiframeImageWatermarkOptions-int-) | Menginisialisasi instansi baru dari kelas `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` dengan indeks bingkai yang ditentukan. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getFrameIndex()](#getFrameIndex--) | Mendapatkan indeks bingkai untuk menambahkan watermark. |
|
|  | [setFrameIndex(int value)](#setFrameIndex-int-) | Mengatur indeks bingkai untuk menambahkan watermark. |
|
### MultiframeImageWatermarkOptions() {#MultiframeImageWatermarkOptions--}
```
public MultiframeImageWatermarkOptions()
```


Menginisialisasi instansi baru dari kelas `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)`.


### MultiframeImageWatermarkOptions(int frameIndex) {#MultiframeImageWatermarkOptions-int-}
```
public MultiframeImageWatermarkOptions(int frameIndex)
```


Menginisialisasi instansi baru dari kelas `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` dengan indeks bingkai yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | frameIndex | int | Indeks bingkai untuk menambahkan watermark. |
|

### getFrameIndex() {#getFrameIndex--}
```
public final int getFrameIndex()
```


Mendapatkan indeks bingkai untuk menambahkan watermark.


**Returns:**
int - Indeks bingkai untuk menambahkan watermark.

<br />

*** ** * ** ***

-1 means all frames.

<br />


### setFrameIndex(int value) {#setFrameIndex-int-}
```
public final void setFrameIndex(int value)
```


Mengatur indeks bingkai untuk menambahkan watermark.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | int | Indeks bingkai untuk menambahkan watermark. |

<br />

*** ** * ** ***

-1 means all frames.

<br />

|

