---
title: "SizingType"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Menentukan bagaimana ukuran watermark harus dihitung."
type: docs
weight: 16
url: /id/java/com.groupdocs.watermark.watermarks/sizingtype/
---
**Inheritance:**
java.lang.Object
```
public final class SizingType
```

Menentukan bagaimana ukuran watermark harus dihitung.

## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Auto](#Auto) | Watermark harus diukur secara otomatis sesuai dengan kontennya. |
|
|  | [Absolute](#Absolute) | Watermark harus diukur ke lebar yang tepat `[Watermark.getWidth()](../../com.groupdocs.watermark/watermark#getWidth--)` |
dan `[Watermark.getHeight()](../../com.groupdocs.watermark/watermark#getHeight--)`.
|
|  | [ScaleToParentDimensions](#ScaleToParentDimensions) | Watermark harus diskalakan relatif terhadap dimensi induk menggunakan |
yang ditentukan `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`.
|
|  | [ScaleToParentArea](#ScaleToParentArea) | Watermark harus diskalakan relatif terhadap area induk menggunakan `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)` yang ditentukan. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [toString(int value)](#toString-int-) | Mengembalikan representasi string dari nilai `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`. |
|
|  | [parse(String value)](#parse-java.lang.String-) | Mengurai string menjadi nilai enumerasi `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`. |
|
### Auto {#Auto}
```
public static final int Auto
```


Watermark harus diukur secara otomatis sesuai dengan kontennya.


### Absolute {#Absolute}
```
public static final int Absolute
```


Watermark harus diukur ke lebar yang tepat `[Watermark.getWidth()](../../com.groupdocs.watermark/watermark#getWidth--)`
dan `[Watermark.getHeight()](../../com.groupdocs.watermark/watermark#getHeight--)`.


### ScaleToParentDimensions {#ScaleToParentDimensions}
```
public static final int ScaleToParentDimensions
```


Watermark harus diskalakan relatif terhadap dimensi induk menggunakan
yang ditentukan `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`.


### ScaleToParentArea {#ScaleToParentArea}
```
public static final int ScaleToParentArea
```


Watermark harus diskalakan relatif terhadap area induk menggunakan `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)` yang ditentukan.


### toString(int value) {#toString-int-}
```
public static final String toString(int value)
```


Mengembalikan representasi string dari nilai `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | int | Nilai yang akan dikonversi. |
|

**Returns:**
java.lang.String - Representasi string dari nilai `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`.

### parse(String value) {#parse-java.lang.String-}
```
public static final int parse(String value)
```


Mengurai string menjadi nilai enumerasi `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | java.lang.String | String yang akan diurai. |
|

**Returns:**
int - Nilai enumerasi `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`.

