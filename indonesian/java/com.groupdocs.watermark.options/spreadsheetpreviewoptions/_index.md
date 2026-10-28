---
title: "SpreadsheetPreviewOptions"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Menyediakan opsi untuk mengatur persyaratan dan delegasi aliran untuk pembuatan pratinjau dokumen Spreadsheet."
type: docs
weight: 52
url: /id/java/com.groupdocs.watermark.options/spreadsheetpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class SpreadsheetPreviewOptions extends PreviewOptions
```

Menyediakan opsi untuk mengatur persyaratan dan delegasi aliran untuk pembuatan pratinjau dokumen Spreadsheet.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [SpreadsheetPreviewOptions(ICreatePageStream createPageStream)](#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Menginisialisasi instance baru dari kelas `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` yang menyebabkan aliran keluaran ditutup. |
|
|  | [SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Menginisialisasi instance baru dari kelas `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` yang menyebabkan aliran keluaran dikembalikan ke klien untuk penggunaan lebih lanjut. |
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [DefaultResolution](#DefaultResolution) | Resolusi default dalam titik per inci. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getResolution()](#getResolution--) | Mendapatkan resolusi untuk gambar yang dihasilkan, dalam titik per inci. |
|
|  | [setResolution(int value)](#setResolution-int-) | Mengatur resolusi untuk gambar yang dihasilkan, dalam titik per inci. |
|
|  | [getOnlyDataArea()](#getOnlyDataArea--) | Mendapatkan flag untuk merender area data saja tanpa header, footer, margin. |
|
|  | [setOnlyDataArea(boolean value)](#setOnlyDataArea-boolean-) | Mengatur flag untuk merender area data saja tanpa header, footer, margin. |
|
### SpreadsheetPreviewOptions(ICreatePageStream createPageStream) {#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public SpreadsheetPreviewOptions(ICreatePageStream createPageStream)
```


Menginisialisasi instance baru dari kelas `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` yang menyebabkan aliran keluaran ditutup.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Membuat aliran untuk pratinjau halaman tertentu. |
|

### SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Menginisialisasi instance baru dari kelas `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` yang menyebabkan aliran keluaran dikembalikan ke klien untuk penggunaan lebih lanjut.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Membuat aliran untuk pratinjau halaman tertentu. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Memberitahukan bahwa pembuatan pratinjau halaman selesai dan mendapatkan aliran keluaran. |
|

### DefaultResolution {#DefaultResolution}
```
public static final int DefaultResolution
```


Resolusi default dalam titik per inci.


### getResolution() {#getResolution--}
```
public final int getResolution()
```


Mendapatkan resolusi untuk gambar yang dihasilkan, dalam titik per inci.


**Returns:**
int - Resolusi untuk gambar yang dihasilkan, dalam titik per inci.

<br />

*** ** * ** ***

Nilai default adalah 96.

<br />


### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


Mengatur resolusi untuk gambar yang dihasilkan, dalam titik per inci.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | int | Resolusi untuk gambar yang dihasilkan, dalam titik per inci. |

<br />

*** ** * ** ***

Nilai default adalah 96.

<br />

|

### getOnlyDataArea() {#getOnlyDataArea--}
```
public final boolean getOnlyDataArea()
```


Mendapatkan flag untuk merender area data saja tanpa header, footer, margin.


**Returns:**
boolean - Flag untuk merender area data saja tanpa header, footer, margin.

<br />

*** ** * ** ***

Flag ini menyebabkan seluruh lembar kerja dirender pada satu halaman. Nilai default adalah false.

<br />


### setOnlyDataArea(boolean value) {#setOnlyDataArea-boolean-}
```
public final void setOnlyDataArea(boolean value)
```


Mengatur flag untuk merender area data saja tanpa header, footer, margin.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | boolean | Flag untuk merender area data saja tanpa header, footer, margin. |

<br />

*** ** * ** ***

Flag ini menyebabkan seluruh lembar kerja dirender pada satu halaman. Nilai default adalah false.

<br />

|

