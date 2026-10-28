---
title: "EmailPreviewOptions"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Menyediakan opsi untuk mengatur persyaratan dan delegasi aliran untuk pembuatan pratinjau dokumen Email."
type: docs
weight: 17
url: /id/java/com.groupdocs.watermark.options/emailpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class EmailPreviewOptions extends PreviewOptions
```

Menyediakan opsi untuk mengatur persyaratan dan delegasi aliran untuk pembuatan pratinjau dokumen Email.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [EmailPreviewOptions(ICreatePageStream createPageStream)](#EmailPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Menginisialisasi sebuah instance baru dari kelas `[EmailPreviewOptions](../../com.groupdocs.watermark.options/emailpreviewoptions)` yang menyebabkan aliran keluaran ditutup. |
|
|  | [EmailPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#EmailPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Menginisialisasi sebuah instance baru dari `[EmailPreviewOptions](../../com.groupdocs.watermark.options/emailpreviewoptions)` kelas yang menyebabkan aliran keluaran dikembalikan ke klien untuk penggunaan lebih lanjut. |
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
|  | [setResolution(float value)](#setResolution-float-) | Mengatur resolusi untuk gambar yang dihasilkan, dalam titik per inci. |
|
### EmailPreviewOptions(ICreatePageStream createPageStream) {#EmailPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public EmailPreviewOptions(ICreatePageStream createPageStream)
```


Menginisialisasi sebuah instance baru dari kelas `[EmailPreviewOptions](../../com.groupdocs.watermark.options/emailpreviewoptions)` yang menyebabkan aliran keluaran ditutup.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Membuat aliran untuk pratinjau halaman tertentu. |
|

### EmailPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#EmailPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public EmailPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Menginisialisasi sebuah instance baru dari `[EmailPreviewOptions](../../com.groupdocs.watermark.options/emailpreviewoptions)` kelas yang menyebabkan aliran keluaran dikembalikan ke klien untuk penggunaan lebih lanjut.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Membuat aliran untuk pratinjau halaman tertentu. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Memberitahukan bahwa pembuatan pratinjau halaman selesai dan mendapatkan aliran keluaran. |
|

### DefaultResolution {#DefaultResolution}
```
public static final float DefaultResolution
```


Resolusi default dalam titik per inci.


### getResolution() {#getResolution--}
```
public final float getResolution()
```


Mendapatkan resolusi untuk gambar yang dihasilkan, dalam titik per inci.


**Returns:**
float - Resolusi untuk gambar yang dihasilkan, dalam titik per inci.

<br />

*** ** * ** ***

Nilai default adalah 96.

<br />


### setResolution(float value) {#setResolution-float-}
```
public final void setResolution(float value)
```


Mengatur resolusi untuk gambar yang dihasilkan, dalam titik per inci.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | float | Resolusi untuk gambar yang dihasilkan, dalam titik per inci. |

<br />

*** ** * ** ***

Nilai default adalah 96.

<br />

|

