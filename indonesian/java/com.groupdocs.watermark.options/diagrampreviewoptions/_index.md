---
title: "DiagramPreviewOptions"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Menyediakan opsi untuk mengatur persyaratan dan delegasi aliran untuk pembuatan pratinjau dokumen Diagram."
type: docs
weight: 12
url: /id/java/com.groupdocs.watermark.options/diagrampreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class DiagramPreviewOptions extends PreviewOptions
```

Menyediakan opsi untuk mengatur persyaratan dan delegasi aliran untuk pembuatan pratinjau dokumen Diagram.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [DiagramPreviewOptions(ICreatePageStream createPageStream)](#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Menginisialisasi instance baru dari kelas `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` yang menyebabkan aliran keluaran ditutup. |
|
|  | [DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Menginisialisasi instance baru dari `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` kelas yang menyebabkan aliran keluaran dikembalikan ke klien untuk penggunaan lebih lanjut. |
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
|  | [getHighQualityRendering()](#getHighQualityRendering--) | Mendapatkan flag untuk rendering berkualitas tinggi. |
|
|  | [setHighQualityRendering(boolean value)](#setHighQualityRendering-boolean-) | Mengatur flag untuk rendering berkualitas tinggi. |
|
### DiagramPreviewOptions(ICreatePageStream createPageStream) {#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public DiagramPreviewOptions(ICreatePageStream createPageStream)
```


Menginisialisasi instance baru dari kelas `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` yang menyebabkan aliran keluaran ditutup.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Membuat aliran untuk pratinjau halaman tertentu. |
|

### DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Menginisialisasi instance baru dari `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` kelas yang menyebabkan aliran keluaran dikembalikan ke klien untuk penggunaan lebih lanjut.


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

Nilai default adalah 300.

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

Nilai default adalah 300.

<br />

|

### getHighQualityRendering() {#getHighQualityRendering--}
```
public final boolean getHighQualityRendering()
```


Mendapatkan flag untuk rendering berkualitas tinggi.


**Returns:**
boolean - Flag untuk rendering berkualitas tinggi.

<br />

*** ** * ** ***

Rendering berkualitas tinggi menggunakan lebih banyak sumber daya. Nilai default adalah false.

<br />


### setHighQualityRendering(boolean value) {#setHighQualityRendering-boolean-}
```
public final void setHighQualityRendering(boolean value)
```


Mengatur flag untuk rendering berkualitas tinggi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | boolean | Flag untuk rendering berkualitas tinggi. |

<br />

*** ** * ** ***

Rendering berkualitas tinggi menggunakan lebih banyak sumber daya. Nilai default adalah false.

<br />

|

