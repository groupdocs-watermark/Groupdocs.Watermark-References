---
title: "LoadOptions"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili opsi pemuatan dokumen saat memuat sebuah dokumen."
type: docs
weight: 24
url: /id/java/com.groupdocs.watermark.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Mewakili opsi pemuatan dokumen saat memuat sebuah dokumen.

**Learn more:**

* [Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents)
* [Load from local disk](../https://docs.groupdocs.com/display/watermarkjava/Load+from+local+disk)
* [Load from stream](../https://docs.groupdocs.com/display/watermarkjava/Load+from+stream)
* [Load document of specific format](../https://docs.groupdocs.com/display/watermarkjava/Load+document+of+specific+format)
* [Load password-protected document](../https://docs.groupdocs.com/display/watermarkjava/Load+password-protected+document)

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Menginisialisasi instance baru dari kelas `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)`. |
|
|  | [LoadOptions(String password)](#LoadOptions-java.lang.String-) | Menginisialisasi instance baru dari kelas `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` dengan kata sandi yang ditentukan. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getPassword()](#getPassword--) | Mendapatkan kata sandi untuk membuka dokumen terenkripsi. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Mengatur kata sandi untuk membuka dokumen terenkripsi. |
|
|  | [getFormatFamily()](#getFormatFamily--) | Dapatkan keluarga format dokumen, yang menunjukkan tipe-nya (mis., Image, Pdf, Spreadsheet, dll.). |
|
|  | [setFormatFamily(int formatFamily)](#setFormatFamily-int-) | Atur keluarga format dokumen, yang menunjukkan tipe-nya (mis., Image, Pdf, Spreadsheet, dll.). |
|
|  | [getFileType()](#getFileType--) | Dapatkan tipe file, yang menunjukkan jenisnya (mis., docx, pdf, xlsx, dll.). |
|
|  | [setFileType(FileType fileType)](#setFileType-com.groupdocs.watermark.common.FileType-) | Atur tipe file, yang menunjukkan jenisnya (mis., docx, pdf, xlsx, dll.). |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Menginisialisasi instance baru dari kelas `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)`.


### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


Menginisialisasi instance baru dari kelas `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` dengan kata sandi yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | kata sandi | java.lang.String | Kata sandi untuk membuka konten yang terenkripsi. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Mendapatkan kata sandi untuk membuka dokumen terenkripsi.


**Returns:**
java.lang.String - Kata sandi untuk membuka dokumen terenkripsi.

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Mengatur kata sandi untuk membuka dokumen terenkripsi.

Kata sandi dapat bernilai null atau string kosong. Nilai default adalah null.
Jika konten tidak terenkripsi, atur ini menjadi null atau string kosong.

Contoh berikut menunjukkan cara memuat dokumen yang dilindungi dengan kata sandi.
>
> ````
> ```
>
>    LoadOptions loadOptions = new LoadOptions();
>    loadOptions.setPassword("pwd123");
>  
>    Watermarker watermarker = new Watermarker("D:\\doc.vsdx", loadOptions);
>    // ...
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | java.lang.String | Kata sandi untuk membuka dokumen terenkripsi. |
|

### getFormatFamily() {#getFormatFamily--}
```
public int getFormatFamily()
```


Dapatkan keluarga format dokumen, yang menunjukkan tipe-nya (mis., Image, Pdf, Spreadsheet, dll.).


**Returns:**
int - formatFamily Tipe file.

### setFormatFamily(int formatFamily) {#setFormatFamily-int-}
```
public void setFormatFamily(int formatFamily)
```


Atur keluarga format dokumen, yang menunjukkan tipe-nya (mis., Image, Pdf, Spreadsheet, dll.).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | formatFamily | int | Tipe file. |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


Dapatkan tipe file, yang menunjukkan jenisnya (mis., docx, pdf, xlsx, dll.).


**Returns:**
[FileType](../../com.groupdocs.watermark.common/filetype) - fileType The file type.

### setFileType(FileType fileType) {#setFileType-com.groupdocs.watermark.common.FileType-}
```
public void setFileType(FileType fileType)
```


Atur tipe file, yang menunjukkan jenisnya (mis., docx, pdf, xlsx, dll.).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.watermark.common/filetype) | Tipe file. |
|

