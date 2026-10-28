---
title: "FontNotFoundException"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Pengecualian yang dilemparkan ketika font yang diminta tidak ditemukan."
type: docs
weight: 12
url: /id/java/com.groupdocs.watermark.exceptions/fontnotfoundexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, [com.groupdocs.watermark.exceptions.WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception)
```
public class FontNotFoundException extends WatermarkException
```

Pengecualian yang dilemparkan ketika font yang diminta tidak ditemukan.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [FontNotFoundException()](#FontNotFoundException--) | Menginisialisasi instance baru dari kelas `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)`. |
|
|  | [FontNotFoundException(String fontName)](#FontNotFoundException-java.lang.String-) | Menginisialisasi instance baru dari kelas `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` dengan nama font yang ditentukan. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getFontName()](#getFontName--) | Mendapatkan nama font yang diminta. |
|
### FontNotFoundException() {#FontNotFoundException--}
```
public FontNotFoundException()
```


Menginisialisasi instance baru dari kelas `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)`.


### FontNotFoundException(String fontName) {#FontNotFoundException-java.lang.String-}
```
public FontNotFoundException(String fontName)
```


Menginisialisasi instance baru dari kelas `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` dengan nama font yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | `fontName` | java.lang.String | Nama font yang diminta. |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Mendapatkan nama font yang diminta.


**Returns:**
java.lang.String - Nama font yang diminta.

