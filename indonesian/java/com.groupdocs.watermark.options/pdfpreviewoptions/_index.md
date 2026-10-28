---
title: "PdfPreviewOptions"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Memberikan opsi untuk mengatur persyaratan dan delegasi aliran untuk pembuatan pratinjau dokumen PDF."
type: docs
weight: 31
url: /id/java/com.groupdocs.watermark.options/pdfpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class PdfPreviewOptions extends PreviewOptions
```

Memberikan opsi untuk mengatur persyaratan dan delegasi aliran untuk pembuatan pratinjau dokumen PDF.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [PdfPreviewOptions(ICreatePageStream createPageStream)](#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Menginisialisasi instance baru dari kelas `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` yang menyebabkan aliran keluaran ditutup. |
|
|  | [PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Menginisialisasi instance baru dari kelas `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` yang menyebabkan aliran keluaran dikembalikan ke klien untuk penggunaan lebih lanjut. |
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
### PdfPreviewOptions(ICreatePageStream createPageStream) {#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PdfPreviewOptions(ICreatePageStream createPageStream)
```


Menginisialisasi instance baru dari kelas `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` yang menyebabkan aliran keluaran ditutup.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Membuat aliran untuk pratinjau halaman tertentu. |
|

### PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Menginisialisasi instance baru dari kelas `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` yang menyebabkan aliran keluaran dikembalikan ke klien untuk penggunaan lebih lanjut.


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

Nilai default adalah 150.

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

Nilai default adalah 150.

<br />

|

