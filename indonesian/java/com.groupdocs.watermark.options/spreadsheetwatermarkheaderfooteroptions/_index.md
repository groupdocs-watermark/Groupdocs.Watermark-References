---
title: "SpreadsheetWatermarkHeaderFooterOptions"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili opsi saat menambahkan watermark ke header/footer Spreadsheet."
type: docs
weight: 57
url: /id/java/com.groupdocs.watermark.options/spreadsheetwatermarkheaderfooteroptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)
```
public final class SpreadsheetWatermarkHeaderFooterOptions extends SpreadsheetWatermarkOptions
```

Mewakili opsi saat menambahkan watermark ke header/footer Spreadsheet.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

Contoh berikut menunjukkan cara menambahkan watermark teks ke header lembar kerja Excel.
>
> ````
> ```
>
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.xls", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    SpreadsheetWatermarkHeaderFooterOptions options = new SpreadsheetWatermarkHeaderFooterOptions();
>    options.setWorksheetIndex(0);
>    
>    watermarker.save("D:\\watermarked_test.xlsx");
>    watermarker.close();
>  
> ```
> ````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [SpreadsheetWatermarkHeaderFooterOptions()](#SpreadsheetWatermarkHeaderFooterOptions--) | Menginisialisasi instance baru dari kelas `[SpreadsheetWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkheaderfooteroptions)`. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Mendapatkan indeks lembar kerja untuk menambahkan watermark. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Mengatur indeks lembar kerja untuk menambahkan watermark. |
|
### SpreadsheetWatermarkHeaderFooterOptions() {#SpreadsheetWatermarkHeaderFooterOptions--}
```
public SpreadsheetWatermarkHeaderFooterOptions()
```


Menginisialisasi instance baru dari kelas `[SpreadsheetWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkheaderfooteroptions)`.


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


Mendapatkan indeks lembar kerja untuk menambahkan watermark.


**Returns:**
int - Indeks lembar kerja untuk menambahkan watermark.

<br />

*** ** * ** ***

-1 means every worksheet.

<br />


### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Mengatur indeks lembar kerja untuk menambahkan watermark.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | int | Indeks lembar kerja untuk menambahkan watermark. |

<br />

*** ** * ** ***

-1 means every worksheet.

<br />

|

