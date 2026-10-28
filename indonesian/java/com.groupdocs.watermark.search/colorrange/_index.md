---
title: "ColorRange"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili rentang warna."
type: docs
weight: 12
url: /id/java/com.groupdocs.watermark.search/colorrange/
---
**Inheritance:**
java.lang.Object
```
public class ColorRange
```

Mewakili rentang warna. Menentukan rentang menggunakan representasi HSB dari warna RGB.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [ColorRange()](#ColorRange--) | Menginisialisasi instance baru dari kelas `[ColorRange](../../com.groupdocs.watermark.search/colorrange)`. |
|
|  | [ColorRange(Color exactColor)](#ColorRange-com.groupdocs.watermark.watermarks.Color-) | Menginisialisasi instance baru dari kelas `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` dengan warna tepat yang ditentukan. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getMinHue()](#getMinHue--) | Mendapatkan nilai hue awal, dalam derajat. |
|
|  | [setMinHue(float value)](#setMinHue-float-) | Mengatur nilai hue awal, dalam derajat. |
|
|  | [getMaxHue()](#getMaxHue--) | Mendapatkan nilai hue akhir, dalam derajat. |
|
|  | [setMaxHue(float value)](#setMaxHue-float-) | Mengatur nilai hue akhir, dalam derajat. |
|
|  | [getMinSaturation()](#getMinSaturation--) | Mendapatkan nilai saturasi awal. |
|
|  | [setMinSaturation(float value)](#setMinSaturation-float-) | Mengatur nilai saturasi awal. |
|
|  | [getMaxSaturation()](#getMaxSaturation--) | Mendapatkan nilai saturasi akhir. |
|
|  | [setMaxSaturation(float value)](#setMaxSaturation-float-) | Mengatur nilai saturasi akhir. |
|
|  | [getMinBrightness()](#getMinBrightness--) | Mendapatkan nilai kecerahan awal. |
|
|  | [setMinBrightness(float value)](#setMinBrightness-float-) | Mengatur nilai kecerahan awal. |
|
|  | [getMaxBrightness()](#getMaxBrightness--) | Mendapatkan nilai kecerahan akhir. |
|
|  | [setMaxBrightness(float value)](#setMaxBrightness-float-) | Mengatur nilai kecerahan akhir. |
|
|  | [isEmpty()](#isEmpty--) | Mendapatkan nilai yang menunjukkan apakah hanya warna kosong yang berada dalam rentang. |
|
|  | [setEmpty(boolean value)](#setEmpty-boolean-) | Mengatur nilai yang menunjukkan apakah hanya warna kosong yang berada dalam rentang. |
|
### ColorRange() {#ColorRange--}
```
public ColorRange()
```


Menginisialisasi instance baru dari kelas `[ColorRange](../../com.groupdocs.watermark.search/colorrange)`.


### ColorRange(Color exactColor) {#ColorRange-com.groupdocs.watermark.watermarks.Color-}
```
public ColorRange(Color exactColor)
```


Menginisialisasi instance baru dari kelas `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` dengan warna tepat yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | exactColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Warna tepat dari mana rentang dibuat. |
|

### getMinHue() {#getMinHue--}
```
public final float getMinHue()
```


Mendapatkan nilai hue awal, dalam derajat.


**Returns:**
float - Nilai hue awal, dalam derajat.

### setMinHue(float value) {#setMinHue-float-}
```
public final void setMinHue(float value)
```


Mengatur nilai hue awal, dalam derajat.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | float | Nilai hue awal, dalam derajat. |
|

### getMaxHue() {#getMaxHue--}
```
public final float getMaxHue()
```


Mendapatkan nilai hue akhir, dalam derajat.


**Returns:**
float - Nilai hue akhir, dalam derajat.

### setMaxHue(float value) {#setMaxHue-float-}
```
public final void setMaxHue(float value)
```


Mengatur nilai hue akhir, dalam derajat.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | float | Nilai hue akhir, dalam derajat. |
|

### getMinSaturation() {#getMinSaturation--}
```
public final float getMinSaturation()
```


Mendapatkan nilai saturasi awal.


**Returns:**
float - Saturasi berkisar dari 0.0 hingga 1.0, di mana 0.0 adalah skala abu-abu dan 1.0 adalah paling jenuh.

### setMinSaturation(float value) {#setMinSaturation-float-}
```
public final void setMinSaturation(float value)
```


Mengatur nilai saturasi awal.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | float | Saturasi berkisar dari 0.0 hingga 1.0, di mana 0.0 adalah skala abu-abu dan 1.0 adalah paling jenuh. |
|

### getMaxSaturation() {#getMaxSaturation--}
```
public final float getMaxSaturation()
```


Mendapatkan nilai saturasi akhir.


**Returns:**
float - Saturasi berkisar dari 0.0 hingga 1.0, di mana 0.0 adalah skala abu-abu dan 1.0 adalah paling jenuh.

### setMaxSaturation(float value) {#setMaxSaturation-float-}
```
public final void setMaxSaturation(float value)
```


Mengatur nilai saturasi akhir.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | float | Saturasi berkisar dari 0.0 hingga 1.0, di mana 0.0 adalah skala abu-abu dan 1.0 adalah paling jenuh. |
|

### getMinBrightness() {#getMinBrightness--}
```
public final float getMinBrightness()
```


Mendapatkan nilai kecerahan awal.


**Returns:**
float - Kecerahan berkisar dari 0.0 hingga 1.0, di mana 0.0 mewakili hitam dan 1.0 mewakili putih.

### setMinBrightness(float value) {#setMinBrightness-float-}
```
public final void setMinBrightness(float value)
```


Mengatur nilai kecerahan awal.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | float | Kecerahan berkisar dari 0.0 hingga 1.0, di mana 0.0 mewakili hitam dan 1.0 mewakili putih. |
|

### getMaxBrightness() {#getMaxBrightness--}
```
public final float getMaxBrightness()
```


Mendapatkan nilai kecerahan akhir.


**Returns:**
float - Kecerahan berkisar dari 0.0 hingga 1.0, di mana 0.0 mewakili hitam dan 1.0 mewakili putih.

### setMaxBrightness(float value) {#setMaxBrightness-float-}
```
public final void setMaxBrightness(float value)
```


Mengatur nilai kecerahan akhir.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | float | Kecerahan berkisar dari 0.0 hingga 1.0, di mana 0.0 mewakili hitam dan 1.0 mewakili putih. |
|

### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Mendapatkan nilai yang menunjukkan apakah hanya warna kosong yang berada dalam rentang.


**Returns:**
boolean - True jika hanya warna kosong yang berada dalam rentang (rentang HSB diabaikan); jika tidak, false.

### setEmpty(boolean value) {#setEmpty-boolean-}
```
public final void setEmpty(boolean value)
```


Mengatur nilai yang menunjukkan apakah hanya warna kosong yang berada dalam rentang.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | boolean | True jika hanya warna kosong yang berada dalam rentang (rentang HSB diabaikan); jika tidak, false. |
|

