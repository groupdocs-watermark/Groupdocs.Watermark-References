---
title: "OfficeImageFillFormat"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili pengaturan format isi gambar dalam konten office yang didukung."
type: docs
weight: 46
url: /id/java/com.groupdocs.watermark.contents/officeimagefillformat/
---
**Inheritance:**
java.lang.Object
```
public abstract class OfficeImageFillFormat<TWatermarkableImage>
```

Mewakili pengaturan format isi gambar dalam konten office yang didukung.


TWatermarkableImage
: Tipe tepat dari gambar yang dapat diberi watermark yang digunakan sebagai latar belakang.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [OfficeImageFillFormat()](#OfficeImageFillFormat--) | <br /> |

|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | Mendapatkan nilai yang menunjukkan apakah gambar ditile di latar belakang. |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | Mengatur nilai yang menunjukkan apakah gambar ditile di latar belakang. |
|
|  | [getTransparency()](#getTransparency--) | Mendapatkan transparansi gambar latar belakang sebagai nilai dari 0.0 (tidak tembus pandang) hingga 1.0 (sepenuhnya transparan). |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Mengatur transparansi gambar latar belakang sebagai nilai dari 0.0 (tidak tembus pandang) hingga 1.0 (sepenuhnya transparan). |
|
|  | [getBackgroundImage()](#getBackgroundImage--) | Mendapatkan gambar latar belakang. |
|
|  | [setBackgroundImage(TWatermarkableImage value)](#setBackgroundImage-TWatermarkableImage-) | Mengatur gambar latar belakang. |
|
|  | [checkIfBackgroundImageIsSet()](#checkIfBackgroundImageIsSet--) | <br /> |

|
### OfficeImageFillFormat() {#OfficeImageFillFormat--}
```
public OfficeImageFillFormat()
```


<br />



### getTileAsTexture() {#getTileAsTexture--}
```
public abstract boolean getTileAsTexture()
```


Mendapatkan nilai yang menunjukkan apakah gambar ditile di latar belakang.


**Returns:**
boolean - True jika gambar ditata berulang di latar belakang; jika tidak, false (gambar diregangkan).

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public abstract void setTileAsTexture(boolean value)
```


Mengatur nilai yang menunjukkan apakah gambar ditile di latar belakang.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | boolean | True jika gambar ditata berulang di latar belakang; jika tidak, false (gambar diregangkan). |
|

### getTransparency() {#getTransparency--}
```
public abstract double getTransparency()
```


Mendapatkan transparansi gambar latar belakang sebagai nilai dari 0.0 (tidak tembus pandang) hingga 1.0 (sepenuhnya transparan).


**Returns:**
double - Transparansi gambar latar belakang sebagai nilai dari 0.0 (tidak tembus) hingga 1.0 (sepenuhnya transparan).

### setTransparency(double value) {#setTransparency-double-}
```
public abstract void setTransparency(double value)
```


Mengatur transparansi gambar latar belakang sebagai nilai dari 0.0 (tidak tembus pandang) hingga 1.0 (sepenuhnya transparan).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Transparansi gambar latar belakang sebagai nilai dari 0.0 (tidak tembus) hingga 1.0 (sepenuhnya transparan). |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public abstract TWatermarkableImage getBackgroundImage()
```


Mendapatkan gambar latar belakang.


**Returns:**
TWatermarkableImage - Gambar latar belakang. Mengembalikan null jika gambar tidak diatur.

### setBackgroundImage(TWatermarkableImage value) {#setBackgroundImage-TWatermarkableImage-}
```
public abstract void setBackgroundImage(TWatermarkableImage value)
```


Mengatur gambar latar belakang.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | TWatermarkableImage | Gambar latar belakang. Mengembalikan null jika gambar belum diatur. |
|

### checkIfBackgroundImageIsSet() {#checkIfBackgroundImageIsSet--}
```
public final void checkIfBackgroundImageIsSet()
```


<br />



