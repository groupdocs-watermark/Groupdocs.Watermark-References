---
title: "PdfPermissions"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili izin pengguna untuk dokumen PDF."
type: docs
weight: 68
url: /id/java/com.groupdocs.watermark.contents/pdfpermissions/
---
**Inheritance:**
java.lang.Object
```
public final class PdfPermissions
```

Mewakili izin pengguna untuk dokumen pdf.

## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [PrintDocument](#PrintDocument) | Cetak konten. |
|
|  | [ModifyContent](#ModifyContent) | Ubah konten. |
|
|  | [ExtractContent](#ExtractContent) | Salin atau ekstrak teks dan grafik dari dokumen. |
|
|  | [ModifyTextAnnotations](#ModifyTextAnnotations) | Tambahkan atau ubah anotasi teks. |
|
|  | [FillForm](#FillForm) | Isi bidang formulir interaktif yang ada. |
|
|  | [ExtractContentWithDisabilities](#ExtractContentWithDisabilities) | Ekstrak teks dan grafik. |
|
|  | [AssembleDocument](#AssembleDocument) | Susun konten. |
|
|  | [PrintingQuality](#PrintingQuality) | Cetak konten ke representasi yang dapat menghasilkan salinan digital yang akurat dari dokumen PDF. |
|
### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```


Cetak konten.

Penangani keamanan revisi 2: Cetak konten.

Penangani keamanan revisi 3 atau lebih: Cetak konten
(mungkin tidak pada tingkat kualitas tertinggi, tergantung apakah
`#PrintingQuality.PrintingQuality` juga diatur).


### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```


Ubah konten.

Ubah isi dokumen dengan operasi lain
daripada yang dikendalikan oleh `#ModifyTextAnnotations.ModifyTextAnnotations`, `#FillForm.FillForm`.


### ExtractContent {#ExtractContent}
```
public static final int ExtractContent
```


Salin atau ekstrak teks dan grafik dari dokumen.

Penangani keamanan revisi 2: Salin atau ekstrak teks dan grafik dari konten,
termasuk mengekstrak teks dan grafik (untuk mendukung aksesibilitas bagi pengguna dengan
disabilitas atau untuk tujuan lain).

Penangani keamanan revisi 3 atau lebih: Salin atau ekstrak teks dan grafik dari
konten dengan operasi lain selain yang dikendalikan oleh
`#ExtractContentWithDisabilities.ExtractContentWithDisabilities`.


### ModifyTextAnnotations {#ModifyTextAnnotations}
```
public static final int ModifyTextAnnotations
```


Tambahkan atau ubah anotasi teks.

Tambahkan atau ubah anotasi teks, isi bidang formulir interaktif,
dan, jika `#ModifyContent.ModifyContent` juga diatur,
buat atau ubah bidang formulir interaktif (termasuk bidang tanda tangan).


### FillForm {#FillForm}
```
public static final int FillForm
```


Isi bidang formulir interaktif yang ada.

Penangani keamanan pada revisi 3 atau lebih: Isi bidang formulir interaktif yang ada
(termasuk bidang tanda tangan), bahkan jika `#ModifyTextAnnotations.ModifyTextAnnotations` tidak diatur.


### ExtractContentWithDisabilities {#ExtractContentWithDisabilities}
```
public static final int ExtractContentWithDisabilities
```


Ekstrak teks dan grafik.

Penangani keamanan pada revisi 3 atau lebih: Ekstrak teks dan grafik
(sebagai dukungan aksesibilitas bagi pengguna dengan disabilitas atau untuk tujuan lain).


### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```


Susun konten.

Penangani keamanan pada revisi 3 atau lebih: Susun konten (sisipkan, putar, atau hapus halaman
dan buat penanda atau gambar mini), bahkan jika `#ModifyContent.ModifyContent` tidak diatur.


### PrintingQuality {#PrintingQuality}
```
public static final int PrintingQuality
```


Cetak konten ke representasi yang dapat menghasilkan salinan digital yang akurat dari dokumen PDF.

Penangani keamanan pada revisi 3 atau lebih: Cetak konten ke representasi yang dapat menghasilkan
salinan digital dokumen PDF dapat dihasilkan. Ketika bit ini tidak diatur (dan `#PrintDocument.PrintDocument`
diatur), pencetakan dibatasi pada representasi tingkat rendah dari tampilan, mungkin dengan kualitas yang menurun.


