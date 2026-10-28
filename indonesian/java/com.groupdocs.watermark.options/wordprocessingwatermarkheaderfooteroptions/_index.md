---
title: "WordProcessingWatermarkHeaderFooterOptions"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili opsi saat menambahkan watermark ke header/footer bagian Word."
type: docs
weight: 74
url: /id/java/com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkHeaderFooterOptions extends WordProcessingWatermarkBaseOptions
```

Mewakili opsi saat menambahkan watermark ke header/footer bagian Word.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [WordProcessingWatermarkHeaderFooterOptions()](#WordProcessingWatermarkHeaderFooterOptions--) | Menginisialisasi instance baru dari kelas `[WordProcessingWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions)`. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getSectionIndex()](#getSectionIndex--) | Mendapatkan indeks bagian untuk menambahkan watermark. |
|
|  | [setSectionIndex(int value)](#setSectionIndex-int-) | Mengatur indeks bagian untuk menambahkan watermark. |
|
|  | [getHeaderFooterType()](#getHeaderFooterType--) | Mendapatkan nilai yang mengidentifikasi jenis header atau footer untuk menambahkan watermark. |
|
|  | [setHeaderFooterType(int value)](#setHeaderFooterType-int-) | Mengatur nilai yang mengidentifikasi jenis header atau footer untuk menambahkan watermark. |
|
### WordProcessingWatermarkHeaderFooterOptions() {#WordProcessingWatermarkHeaderFooterOptions--}
```
public WordProcessingWatermarkHeaderFooterOptions()
```


Menginisialisasi instance baru dari kelas `[WordProcessingWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions)`.


### getSectionIndex() {#getSectionIndex--}
```
public final int getSectionIndex()
```


Mendapatkan indeks bagian untuk menambahkan watermark.


**Returns:**
int - Indeks bagian untuk menambahkan watermark.

<br />

*** ** * ** ***

-1 means all sections.

<br />


### setSectionIndex(int value) {#setSectionIndex-int-}
```
public final void setSectionIndex(int value)
```


Mengatur indeks bagian untuk menambahkan watermark.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | int | Indeks bagian untuk menambahkan watermark. |

<br />

*** ** * ** ***

-1 means all sections.

<br />

|

### getHeaderFooterType() {#getHeaderFooterType--}
```
public final int getHeaderFooterType()
```


Mendapatkan nilai yang mengidentifikasi jenis header atau footer untuk menambahkan watermark.


**Returns:**
int - Nilai bertipe `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` yang mengidentifikasi jenis header atau footer untuk menambahkan watermark.

### setHeaderFooterType(int value) {#setHeaderFooterType-int-}
```
public final void setHeaderFooterType(int value)
```


Mengatur nilai yang mengidentifikasi jenis header atau footer untuk menambahkan watermark.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | int | Nilai bertipe `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` yang mengidentifikasi jenis header atau footer untuk menambahkan watermark. |
|

