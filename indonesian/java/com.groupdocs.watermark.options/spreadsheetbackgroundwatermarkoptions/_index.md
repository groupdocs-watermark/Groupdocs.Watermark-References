---
title: "SpreadsheetBackgroundWatermarkOptions"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili opsi saat menambahkan watermark sebagai latar belakang ke lembar kerja Spreadsheet."
type: docs
weight: 49
url: /id/java/com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)
```
public final class SpreadsheetBackgroundWatermarkOptions extends SpreadsheetWatermarkOptions
```

Mewakili opsi saat menambahkan watermark sebagai latar belakang ke lembar kerja Spreadsheet.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

Contoh berikut menunjukkan cara menambahkan watermark teks ke lembar kerja dokumen Excel sebagai latar belakang.
>
> ````
> ```
>
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\Documents\\test.xlsx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36));
>
>    SpreadsheetBackgroundWatermarkOptions options = new SpreadsheetBackgroundWatermarkOptions();
>    options.setWorksheetIndex(-1); // default
>    options.setBackgroundWidth(800);
>    options.setBackgroundHeight(600);
>    
>    watermarker.save("C:\\Documents\\watermarked_test.xlsx");
>    watermarker.close();
>  
> ```
> ````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [SpreadsheetBackgroundWatermarkOptions()](#SpreadsheetBackgroundWatermarkOptions--) | Menginisialisasi instance baru dari kelas `[SpreadsheetBackgroundWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions)`. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Dapatkan indeks lembar kerja tempat menambahkan watermark. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Mengatur indeks lembar kerja untuk menambahkan watermark. |
|
|  | [getBackgroundWidth()](#getBackgroundWidth--) | Dapatkan lebar yang diinginkan dari gambar latar belakang dalam piksel. |
|
|  | [setBackgroundWidth(int value)](#setBackgroundWidth-int-) | Mengatur lebar yang diinginkan dari gambar latar belakang dalam piksel. |
|
|  | [getBackgroundHeight()](#getBackgroundHeight--) | Mendapatkan atau mengatur tinggi yang diinginkan dari gambar latar belakang dalam piksel. |
|
|  | [setBackgroundHeight(int value)](#setBackgroundHeight-int-) | Mendapatkan atau mengatur tinggi yang diinginkan dari gambar latar belakang dalam piksel. |
|
### SpreadsheetBackgroundWatermarkOptions() {#SpreadsheetBackgroundWatermarkOptions--}
```
public SpreadsheetBackgroundWatermarkOptions()
```


Menginisialisasi instance baru dari kelas `[SpreadsheetBackgroundWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions)`.


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


Dapatkan indeks lembar kerja tempat menambahkan watermark.

-1 means every worksheet.


**Returns:**
int - Indeks lembar kerja untuk menambahkan watermark.

### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Mengatur indeks lembar kerja untuk menambahkan watermark.

-1 means every worksheet.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | int | Indeks lembar kerja untuk menambahkan watermark. |
|

### getBackgroundWidth() {#getBackgroundWidth--}
```
public final int getBackgroundWidth()
```


Dapatkan lebar yang diinginkan dari gambar latar belakang dalam piksel.


**Returns:**
int - Lebar yang diinginkan dari gambar latar belakang dalam piksel.

### setBackgroundWidth(int value) {#setBackgroundWidth-int-}
```
public final void setBackgroundWidth(int value)
```


Mengatur lebar yang diinginkan dari gambar latar belakang dalam piksel.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | int | Lebar yang diinginkan dari gambar latar belakang dalam piksel. |
|

### getBackgroundHeight() {#getBackgroundHeight--}
```
public final int getBackgroundHeight()
```


Mendapatkan atau mengatur tinggi yang diinginkan dari gambar latar belakang dalam piksel.


**Returns:**
int - Tinggi yang diinginkan dari gambar latar belakang dalam piksel.

### setBackgroundHeight(int value) {#setBackgroundHeight-int-}
```
public final void setBackgroundHeight(int value)
```


Mendapatkan atau mengatur tinggi yang diinginkan dari gambar latar belakang dalam piksel.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | int | Tinggi yang diinginkan dari gambar latar belakang dalam piksel. |
|

