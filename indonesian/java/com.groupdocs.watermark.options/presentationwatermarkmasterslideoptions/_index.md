---
title: "PresentationWatermarkMasterSlideOptions"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili opsi saat menambahkan watermark ke slide master dokumen Presentasi."
type: docs
weight: 43
url: /id/java/com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)
```
public final class PresentationWatermarkMasterSlideOptions extends PresentationWatermarkBaseSlideOptions
```

Mewakili opsi saat menambahkan watermark ke slide master dokumen Presentasi.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

Lihat contoh penggunaan di `[PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)`.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [PresentationWatermarkMasterSlideOptions()](#PresentationWatermarkMasterSlideOptions--) | Menginisialisasi instance baru dari kelas `[PresentationWatermarkMasterSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions)`. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getMasterSlideIndex()](#getMasterSlideIndex--) | Mendapatkan indeks slide master untuk menambahkan watermark. |
|
|  | [setMasterSlideIndex(int value)](#setMasterSlideIndex-int-) | Mengatur indeks slide master untuk menambahkan watermark. |
|
### PresentationWatermarkMasterSlideOptions() {#PresentationWatermarkMasterSlideOptions--}
```
public PresentationWatermarkMasterSlideOptions()
```


Menginisialisasi instance baru dari kelas `[PresentationWatermarkMasterSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions)`.


### getMasterSlideIndex() {#getMasterSlideIndex--}
```
public final int getMasterSlideIndex()
```


Mendapatkan indeks slide master untuk menambahkan watermark.


**Returns:**
int - Indeks slide master untuk menambahkan watermark.

<br />

*** ** * ** ***

-1 means all slides.

<br />


### setMasterSlideIndex(int value) {#setMasterSlideIndex-int-}
```
public final void setMasterSlideIndex(int value)
```


Mengatur indeks slide master untuk menambahkan watermark.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | int | Indeks slide master untuk menambahkan watermark. |

<br />

*** ** * ** ***

-1 means all slides.

<br />

|

