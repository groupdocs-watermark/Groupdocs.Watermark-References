---
title: "SpreadsheetWatermarkShapeOptions"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili opsi saat menambahkan watermark bentuk ke lembar kerja Spreadsheet."
type: docs
weight: 60
url: /id/java/com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkBaseOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions)
```
public final class SpreadsheetWatermarkShapeOptions extends SpreadsheetWatermarkBaseOptions
```

Mewakili opsi saat menambahkan watermark bentuk ke lembar kerja Spreadsheet.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

Contoh berikut menunjukkan cara menambahkan watermark ke lembar kerja tertentu dari dokumen Excel.
>
> ````
> ```
>
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.xls", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    SpreadsheetWatermarkShapeOptions options = new SpreadsheetWatermarkShapeOptions();
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
|  | [SpreadsheetWatermarkShapeOptions()](#SpreadsheetWatermarkShapeOptions--) | Menginisialisasi instansi baru dari kelas `[SpreadsheetWatermarkShapeOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions)`. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Mendapatkan indeks lembar kerja untuk menambahkan watermark. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Mengatur indeks lembar kerja untuk menambahkan watermark. |
|
|  | [getEffects()](#getEffects--) | Mendapatkan nilai `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` atau `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` untuk efek yang harus diterapkan pada watermark. |
|
|  | [setEffects(ISpreadsheetWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-) | Mendapatkan atau mengatur nilai `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` atau `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` untuk efek yang harus diterapkan pada watermark. |
|
### SpreadsheetWatermarkShapeOptions() {#SpreadsheetWatermarkShapeOptions--}
```
public SpreadsheetWatermarkShapeOptions()
```


Menginisialisasi instansi baru dari kelas `[SpreadsheetWatermarkShapeOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions)`.


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

### getEffects() {#getEffects--}
```
public final ISpreadsheetWatermarkEffects getEffects()
```


Mendapatkan nilai `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` atau `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` untuk efek yang harus diterapkan pada watermark.


**Returns:**
[ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) - The `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` or `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` for effects that should be applied to the watermark.

### setEffects(ISpreadsheetWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-}
```
public final void setEffects(ISpreadsheetWatermarkEffects value)
```


Mendapatkan atau mengatur nilai `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` atau `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` untuk efek yang harus diterapkan pada watermark.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) | `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` atau `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` untuk efek yang harus diterapkan pada watermark. |
|

