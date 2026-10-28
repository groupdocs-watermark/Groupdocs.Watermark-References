---
title: "MarginType"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Menentukan bagaimana nilai margin harus diinterpretasikan."
type: docs
weight: 14
url: /id/java/com.groupdocs.watermark.watermarks/margintype/
---
**Inheritance:**
java.lang.Object
```
public final class MarginType
```

Menentukan bagaimana nilai margin harus diinterpretasikan.

## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Absolute](#Absolute) | Nilai margin diukur dalam satuan konten. |
|
|  | [RelativeToParentDimensions](#RelativeToParentDimensions) | Nilai margin harus diinterpretasikan sebagai bagian dari dimensi induk yang sesuai. |
|
|  | [RelativeToParentMinDimension](#RelativeToParentMinDimension) | Nilai margin harus diinterpretasikan sebagai bagian dari dimensi minimum induk. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [toString(int value)](#toString-int-) | Mengembalikan representasi string dari nilai `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. |
|
|  | [parse(String value)](#parse-java.lang.String-) | Mengurai string menjadi nilai enumerasi `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. |
|
### Absolute {#Absolute}
```
public static final int Absolute
```


Nilai margin diukur dalam satuan konten.


### RelativeToParentDimensions {#RelativeToParentDimensions}
```
public static final int RelativeToParentDimensions
```


Nilai margin harus diinterpretasikan sebagai bagian dari dimensi induk yang sesuai.


Margin kiri dan kanan relatif terhadap lebar induk,
margin atas dan bawah relatif terhadap tinggi induk.
Jika tipe ini dipilih, nilai margin harus berada di antara 0.0 dan 1.0.


### RelativeToParentMinDimension {#RelativeToParentMinDimension}
```
public static final int RelativeToParentMinDimension
```


Nilai margin harus diinterpretasikan sebagai bagian dari dimensi minimum induk.


Jika tipe ini dipilih, nilai margin harus berada di antara 0.0 dan 1.0.


### toString(int value) {#toString-int-}
```
public static final String toString(int value)
```


Mengembalikan representasi string dari nilai `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | int | Nilai yang akan dikonversi. |
|

**Returns:**
java.lang.String - Representasi string dari nilai `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`.

### parse(String value) {#parse-java.lang.String-}
```
public static final int parse(String value)
```


Mengurai string menjadi nilai enumerasi `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | java.lang.String | String yang akan diurai. |
|

**Returns:**
int - Nilai enumerasi `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`.

