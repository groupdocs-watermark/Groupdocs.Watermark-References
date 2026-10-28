---
title: "PresentationImageFillFormat"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili pengaturan format isian gambar dalam dokumen PowerPoint."
type: docs
weight: 85
url: /id/java/com.groupdocs.watermark.contents/presentationimagefillformat/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.contents.OfficeImageFillFormat
```
public class PresentationImageFillFormat extends OfficeImageFillFormat<PresentationWatermarkableImage>
```

Mewakili pengaturan format isian gambar dalam dokumen PowerPoint.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | Mendapatkan nilai yang menunjukkan apakah gambar ditile di latar belakang. |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | Mengatur nilai yang menunjukkan apakah gambar ditile di latar belakang. |
|
|  | [getTransparency()](#getTransparency--) | Mendapatkan transparansi gambar latar belakang sebagai nilai dari 0.0 (opaque) hingga 1.0 |
(sepenuhnya transparan).
|
|  | [setTransparency(double value)](#setTransparency-double-) | Mengatur transparansi gambar latar belakang sebagai nilai dari 0.0 (opaque) hingga 1.0 |
(sepenuhnya transparan).
|
|  | [getBackgroundImage()](#getBackgroundImage--) | Mendapatkan gambar latar belakang. |
|
|  | [setBackgroundImage(PresentationWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-) | Mengatur gambar latar belakang. |
|
### getTileAsTexture() {#getTileAsTexture--}
```
public boolean getTileAsTexture()
```


Mendapatkan nilai yang menunjukkan apakah gambar ditile di latar belakang.


**Returns:**
boolean - True jika gambar ditata berulang di latar belakang; jika tidak, false (gambar diregangkan). Nilai default adalah false.

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public void setTileAsTexture(boolean value)
```


Mengatur nilai yang menunjukkan apakah gambar ditile di latar belakang.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | boolean | True jika gambar ditata berulang di latar belakang; jika tidak, false (gambar diregangkan). Nilai default adalah false. |
|

### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


Mendapatkan transparansi gambar latar belakang sebagai nilai dari 0.0 (opaque) hingga 1.0
(sepenuhnya transparan).


**Returns:**
double - Transparansi gambar latar belakang sebagai nilai dari 0.0 (tidak tembus) hingga 1.0 (sepenuhnya transparan).

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


Mengatur transparansi gambar latar belakang sebagai nilai dari 0.0 (opaque) hingga 1.0
(sepenuhnya transparan).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Transparansi gambar latar belakang sebagai nilai dari 0.0 (tidak tembus) hingga 1.0 (sepenuhnya transparan). |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public PresentationWatermarkableImage getBackgroundImage()
```


Mendapatkan gambar latar belakang.


**Returns:**
[PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) - The background image. Returns null if the image is not set.

### setBackgroundImage(PresentationWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-}
```
public void setBackgroundImage(PresentationWatermarkableImage value)
```


Mengatur gambar latar belakang.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) | Gambar latar belakang. Mengembalikan null jika gambar belum diatur. |
|

