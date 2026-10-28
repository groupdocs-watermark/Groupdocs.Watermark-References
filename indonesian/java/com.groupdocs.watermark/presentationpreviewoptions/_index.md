---
title: "PresentationPreviewOptions"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Menyediakan opsi untuk mengatur persyaratan dan delegasi aliran untuk pembuatan pratinjau dokumen Presentasi."
type: docs
weight: 12
url: /id/java/com.groupdocs.watermark/presentationpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class PresentationPreviewOptions extends PreviewOptions
```

Menyediakan opsi untuk mengatur persyaratan dan delegasi aliran untuk pembuatan pratinjau dokumen Presentasi.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [PresentationPreviewOptions(ICreatePageStream createPageStream)](#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Menginisialisasi instance baru dari kelas `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` yang menyebabkan aliran output ditutup. |
|
|  | [PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Menginisialisasi instance baru dari kelas `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` yang menyebabkan aliran output dikembalikan ke klien untuk penggunaan lebih lanjut. |
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
|  | [setResolution(long value)](#setResolution-long-) | Mengatur resolusi untuk gambar yang dihasilkan, dalam titik per inci. |
|
### PresentationPreviewOptions(ICreatePageStream createPageStream) {#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PresentationPreviewOptions(ICreatePageStream createPageStream)
```


Menginisialisasi instance baru dari kelas `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` yang menyebabkan aliran output ditutup.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Membuat aliran untuk pratinjau halaman tertentu. |
|

### PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Menginisialisasi instance baru dari kelas `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` yang menyebabkan aliran output dikembalikan ke klien untuk penggunaan lebih lanjut.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Membuat aliran untuk pratinjau halaman tertentu. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Memberitahukan bahwa pembuatan pratinjau halaman selesai dan mendapatkan aliran keluaran. |
|

### DefaultResolution {#DefaultResolution}
```
public static final long DefaultResolution
```


Resolusi default dalam titik per inci.


### getResolution() {#getResolution--}
```
public final long getResolution()
```


Mendapatkan resolusi untuk gambar yang dihasilkan, dalam titik per inci.


**Returns:**
long - Resolusi untuk gambar yang dihasilkan, dalam titik per inci.

### setResolution(long value) {#setResolution-long-}
```
public final void setResolution(long value)
```


Mengatur resolusi untuk gambar yang dihasilkan, dalam titik per inci.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | long | Resolusi untuk gambar yang dihasilkan, dalam titik per inci. |
|

