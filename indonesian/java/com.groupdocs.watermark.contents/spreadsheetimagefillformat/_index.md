---
title: "SpreadsheetImageFillFormat"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili pengaturan format isi gambar dalam dokumen Excel."
type: docs
weight: 114
url: /id/java/com.groupdocs.watermark.contents/spreadsheetimagefillformat/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.contents.OfficeImageFillFormat
```
public class SpreadsheetImageFillFormat extends OfficeImageFillFormat<SpreadsheetWatermarkableImage>
```

Mewakili pengaturan format isi gambar dalam dokumen Excel.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | Mendapatkan nilai yang menunjukkan apakah gambar ditile di latar belakang. |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | Mengatur nilai yang menunjukkan apakah gambar ditile di latar belakang. |
|
|  | [getTransparency()](#getTransparency--) | Mendapatkan transparansi gambar latar belakang sebagai nilai dari 0.0 (tidak tembus) |
hingga 1.0 (sepenuhnya transparan).
|
|  | [setTransparency(double value)](#setTransparency-double-) | Mengatur transparansi gambar latar belakang sebagai nilai dari 0.0 (tidak tembus) |
hingga 1.0 (sepenuhnya transparan).
|
|  | [getBackgroundImage()](#getBackgroundImage--) | Mendapatkan gambar latar belakang. |
|
|  | [setBackgroundImage(SpreadsheetWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | Mengatur gambar latar belakang. |
|
### getTileAsTexture() {#getTileAsTexture--}
```
public boolean getTileAsTexture()
```


Mendapatkan nilai yang menunjukkan apakah gambar ditile di latar belakang.


**Returns:**
boolean - True jika gambar ditata berulang di latar belakang; jika tidak, false (gambar diregangkan).

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public void setTileAsTexture(boolean value)
```


Mengatur nilai yang menunjukkan apakah gambar ditile di latar belakang.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | boolean | True jika gambar ditata berulang di latar belakang; jika tidak, false (gambar diregangkan). |
|

### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


Mendapatkan transparansi gambar latar belakang sebagai nilai dari 0.0 (tidak tembus)
hingga 1.0 (sepenuhnya transparan).


**Returns:**
double - Transparansi gambar latar belakang sebagai nilai dari 0.0 (tidak tembus) hingga 1.0 (sepenuhnya transparan).

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


Mengatur transparansi gambar latar belakang sebagai nilai dari 0.0 (tidak tembus)
hingga 1.0 (sepenuhnya transparan).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Transparansi gambar latar belakang sebagai nilai dari 0.0 (tidak tembus) hingga 1.0 (sepenuhnya transparan). |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public SpreadsheetWatermarkableImage getBackgroundImage()
```


Mendapatkan gambar latar belakang.


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The background image. Returns null if the image is not set.

### setBackgroundImage(SpreadsheetWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public void setBackgroundImage(SpreadsheetWatermarkableImage value)
```


Mengatur gambar latar belakang.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | Gambar latar belakang. Mengembalikan null jika gambar belum diatur. |
|

