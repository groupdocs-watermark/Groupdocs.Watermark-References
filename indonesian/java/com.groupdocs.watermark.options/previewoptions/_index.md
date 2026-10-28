---
title: "PreviewOptions"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Menyediakan opsi untuk mengatur persyaratan dan delegasi aliran untuk pembuatan pratinjau."
type: docs
weight: 47
url: /id/java/com.groupdocs.watermark.options/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Menyediakan opsi untuk mengatur persyaratan dan delegasi aliran untuk pembuatan pratinjau.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [PreviewOptions(ICreatePageStream createPageStream)](#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Menginisialisasi instance baru dari kelas `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` yang menyebabkan aliran output ditutup. |
|
|  | [PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Menginisialisasi instance baru dari kelas `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` yang menyebabkan aliran output dikembalikan ke klien untuk penggunaan lebih lanjut. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getWidth()](#getWidth--) | Mendapatkan lebar pratinjau halaman. |
|
|  | [setWidth(int value)](#setWidth-int-) | Mengatur lebar pratinjau halaman. |
|
|  | [getHeight()](#getHeight--) | Mendapatkan tinggi pratinjau halaman. |
|
|  | [setHeight(int value)](#setHeight-int-) | Mengatur tinggi pratinjau halaman. |
|
|  | [getPageNumbers()](#getPageNumbers--) | Mendapatkan array nomor halaman untuk menghasilkan pratinjau. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Mengatur array nomor halaman untuk menghasilkan pratinjau. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Mendapatkan format gambar pratinjau. |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | Mengatur format gambar pratinjau. |
|
|  | [getCreatePageStream()](#getCreatePageStream--) | Mendapatkan instance dari kelas pembuatan aliran halaman. |
|
|  | [setCreatePageStream(ICreatePageStream value)](#setCreatePageStream-com.groupdocs.watermark.options.ICreatePageStream-) | Mengatur instance dari kelas pembuatan aliran halaman. |
|
|  | [getReleasePageStream()](#getReleasePageStream--) | Mendapatkan instance dari kelas penyelesaian pratinjau halaman. |
|
|  | [setReleasePageStream(IReleasePageStream value)](#setReleasePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Mengatur instance dari kelas penyelesaian pratinjau halaman. |
|
### PreviewOptions(ICreatePageStream createPageStream) {#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PreviewOptions(ICreatePageStream createPageStream)
```


Menginisialisasi instance baru dari kelas `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` yang menyebabkan aliran output ditutup.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Membuat aliran untuk pratinjau halaman tertentu. |
|

### PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Menginisialisasi instance baru dari kelas `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` yang menyebabkan aliran output dikembalikan ke klien untuk penggunaan lebih lanjut.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Membuat aliran untuk pratinjau halaman tertentu. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Memberitahukan bahwa pembuatan pratinjau halaman selesai dan mendapatkan aliran keluaran. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Mendapatkan lebar pratinjau halaman.


**Returns:**
int - Lebar pratinjau halaman.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Mengatur lebar pratinjau halaman.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | int | Lebar pratinjau halaman. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Mendapatkan tinggi pratinjau halaman.


**Returns:**
int - Tinggi pratinjau halaman.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Mengatur tinggi pratinjau halaman.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | int | Tinggi pratinjau halaman. |
|

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Mendapatkan array nomor halaman untuk menghasilkan pratinjau.


**Returns:**
int[] - Array nomor halaman untuk menghasilkan pratinjau.

### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Mengatur array nomor halaman untuk menghasilkan pratinjau.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | int[] | Array nomor halaman untuk menghasilkan pratinjau. |
|

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Mendapatkan format gambar pratinjau.


**Returns:**
int - Format gambar pratinjau.

### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Mengatur format gambar pratinjau.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | int | Format gambar pratinjau. |
|

### getCreatePageStream() {#getCreatePageStream--}
```
public final ICreatePageStream getCreatePageStream()
```


Mendapatkan instance dari kelas pembuatan aliran halaman.


**Returns:**
[ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) - The instance of the page stream creation class.

### setCreatePageStream(ICreatePageStream value) {#setCreatePageStream-com.groupdocs.watermark.options.ICreatePageStream-}
```
public final void setCreatePageStream(ICreatePageStream value)
```


Mengatur instance dari kelas pembuatan aliran halaman.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Instansi dari kelas pembuatan aliran halaman. |
|

### getReleasePageStream() {#getReleasePageStream--}
```
public final IReleasePageStream getReleasePageStream()
```


Mendapatkan instance dari kelas penyelesaian pratinjau halaman.


**Returns:**
[IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) - The instance of the page preview completion delegate.

### setReleasePageStream(IReleasePageStream value) {#setReleasePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public final void setReleasePageStream(IReleasePageStream value)
```


Mengatur instance dari kelas penyelesaian pratinjau halaman.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Instansi dari delegasi penyelesaian pratinjau halaman. |
|

