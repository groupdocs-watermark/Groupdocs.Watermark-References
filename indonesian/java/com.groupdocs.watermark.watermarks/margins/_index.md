---
title: "Margins"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili pengaturan margin untuk setiap tepi objek."
type: docs
weight: 15
url: /id/java/com.groupdocs.watermark.watermarks/margins/
---
**Inheritance:**
java.lang.Object
```
public class Margins
```

Mewakili pengaturan margin untuk setiap tepi objek.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [Margins()](#Margins--) | Menginisialisasi instance baru dari kelas `[Margins](../../com.groupdocs.watermark.watermarks/margins)`. |
|
|  | [Margins(int marginType, double left, double right, double top, double bottom)](#Margins-int-double-double-double-double-) | Menginisialisasi instance baru dari kelas `[Margins](../../com.groupdocs.watermark.watermarks/margins)` dengan tipe, lokasi, dan ukuran yang ditentukan. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getMarginType()](#getMarginType--) | Mendapatkan `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. |
|
|  | [setMarginType(int value)](#setMarginType-int-) | Mengatur `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. |
|
|  | [getLeft()](#getLeft--) | Mendapatkan margin kiri. |
|
|  | [setLeft(double value)](#setLeft-double-) | Mengatur margin kiri. |
|
|  | [getRight()](#getRight--) | Mendapatkan margin kanan. |
|
|  | [setRight(double value)](#setRight-double-) | Mengatur margin kanan. |
|
|  | [getTop()](#getTop--) | Mendapatkan margin atas. |
|
|  | [setTop(double value)](#setTop-double-) | Mengatur margin atas. |
|
|  | [getBottom()](#getBottom--) | Mendapatkan margin bawah. |
|
|  | [setBottom(double value)](#setBottom-double-) | Mengatur margin bawah. |
|
### Margins() {#Margins--}
```
public Margins()
```


Menginisialisasi instance baru dari kelas `[Margins](../../com.groupdocs.watermark.watermarks/margins)`.


### Margins(int marginType, double left, double right, double top, double bottom) {#Margins-int-double-double-double-double-}
```
public Margins(int marginType, double left, double right, double top, double bottom)
```


Menginisialisasi instance baru dari kelas `[Margins](../../com.groupdocs.watermark.watermarks/margins)` dengan tipe, lokasi, dan ukuran yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | marginType | int | `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. Menentukan bagaimana nilai margin harus diinterpretasikan. |
|
|  | kiri | double | Nilai margin kiri. |
|
|  | kanan | double | Nilai margin kanan. |
|
|  | atas | double | Nilai margin atas. |
|
|  | bawah | double | Nilai margin bawah. |
|

### getMarginType() {#getMarginType--}
```
public final int getMarginType()
```


Mendapatkan `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. Menetapkan nilai baru ke properti ini secara otomatis mengembalikan semua margin ke nilai default mereka (nol).

Nilai default adalah `[MarginType.Absolute](../../com.groupdocs.watermark.watermarks/margintype#Absolute)`


**Returns:**
int - Nilai yang menentukan bagaimana margin harus diinterpretasikan.

### setMarginType(int value) {#setMarginType-int-}
```
public final void setMarginType(int value)
```


Mengatur `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. Menetapkan nilai baru ke properti ini secara otomatis mengembalikan semua margin ke nilai default mereka (nol).

Nilai default adalah `[MarginType.Absolute](../../com.groupdocs.watermark.watermarks/margintype#Absolute)`


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | int | Nilai yang menentukan bagaimana margin harus diinterpretasikan. |
|

### getLeft() {#getLeft--}
```
public final double getLeft()
```


Mendapatkan margin kiri.


**Returns:**
double - Offset horizontal dari batas kiri induk.

### setLeft(double value) {#setLeft-double-}
```
public final void setLeft(double value)
```


Mengatur margin kiri.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Offset horizontal dari batas kiri induk. |
|

### getRight() {#getRight--}
```
public final double getRight()
```


Mendapatkan margin kanan.


**Returns:**
double - Offset horizontal dari batas kanan induk.

### setRight(double value) {#setRight-double-}
```
public final void setRight(double value)
```


Mengatur margin kanan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Offset horizontal dari batas kanan induk. |
|

### getTop() {#getTop--}
```
public final double getTop()
```


Mendapatkan margin atas.


**Returns:**
double - Offset horizontal dari batas atas induk.

### setTop(double value) {#setTop-double-}
```
public final void setTop(double value)
```


Mengatur margin atas.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Offset horizontal dari batas atas induk. |
|

### getBottom() {#getBottom--}
```
public final double getBottom()
```


Mendapatkan margin bawah.


**Returns:**
double - Offset horizontal dari batas bawah induk.

### setBottom(double value) {#setBottom-double-}
```
public final void setBottom(double value)
```


Mengatur margin bawah.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Offset horizontal dari batas bawah induk. |
|

