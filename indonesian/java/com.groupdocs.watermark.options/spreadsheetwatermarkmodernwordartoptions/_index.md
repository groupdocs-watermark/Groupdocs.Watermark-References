---
title: "SpreadsheetWatermarkModernWordArtOptions"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili opsi saat menambahkan watermark seni kata modern ke lembar kerja Spreadsheet."
type: docs
weight: 58
url: /id/java/com.groupdocs.watermark.options/spreadsheetwatermarkmodernwordartoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkBaseOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions)
```
public final class SpreadsheetWatermarkModernWordArtOptions extends SpreadsheetWatermarkBaseOptions
```

Mewakili opsi saat menambahkan watermark seni kata modern ke lembar kerja Spreadsheet.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

Contoh berikut menunjukkan cara menambahkan watermark WordArt modern ke dokumen Excel.
>
> ````
> ```
>
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.xls", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    SpreadsheetWatermarkModernWordArtOptions options = new SpreadsheetWatermarkModernWordArtOptions();
>    options.setWorksheetIndex(-1); // default
>    options.setLocked(false); // default
>    
>    watermarker.save("D:\\watermarked_test.xlsx");
>    watermarker.close();
>  
> ```
> ````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [SpreadsheetWatermarkModernWordArtOptions()](#SpreadsheetWatermarkModernWordArtOptions--) | Menginisialisasi sebuah instance baru dari kelas `[SpreadsheetWatermarkModernWordArtOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkmodernwordartoptions)`. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Mendapatkan indeks lembar kerja untuk menambahkan watermark. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Mengatur indeks lembar kerja untuk menambahkan watermark. |
|
### SpreadsheetWatermarkModernWordArtOptions() {#SpreadsheetWatermarkModernWordArtOptions--}
```
public SpreadsheetWatermarkModernWordArtOptions()
```


Menginisialisasi sebuah instance baru dari kelas `[SpreadsheetWatermarkModernWordArtOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkmodernwordartoptions)`.


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

