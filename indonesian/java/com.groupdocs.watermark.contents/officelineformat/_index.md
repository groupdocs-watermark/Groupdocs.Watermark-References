---
title: "OfficeLineFormat"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili format garis bentuk."
type: docs
weight: 47
url: /id/java/com.groupdocs.watermark.contents/officelineformat/
---
**Inheritance:**
java.lang.Object
```
public final class OfficeLineFormat
```

Mewakili format garis bentuk.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [OfficeLineFormat()](#OfficeLineFormat--) | Menginisialisasi instance baru dari kelas `[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat)`. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getWeight()](#getWeight--) | Mendapatkan ketebalan kuas yang menggambar jalur bentuk. |
|
|  | [setWeight(double value)](#setWeight-double-) | Mengatur ketebalan kuas yang menggambar jalur bentuk. |
|
|  | [getColor()](#getColor--) | Mendapatkan warna garis. |
|
|  | [setColor(Color value)](#setColor-com.groupdocs.watermark.watermarks.Color-) | Mengatur warna garis. |
|
|  | [getOpacity()](#getOpacity--) | Mendapatkan opasitas garis. |
|
|  | [setOpacity(double value)](#setOpacity-double-) | Mengatur opasitas garis. |
|
|  | [getEnabled()](#getEnabled--) | Mendapatkan nilai yang menunjukkan apakah bentuk akan digambar. |
|
|  | [setEnabled(boolean value)](#setEnabled-boolean-) | Mengatur nilai yang menunjukkan apakah bentuk akan digambar. |
|
|  | [getDashStyle()](#getDashStyle--) | Mendapatkan pola titik dan garis untuk garis. |
|
|  | [setDashStyle(int value)](#setDashStyle-int-) | Mengatur pola titik dan garis untuk garis. |
|
|  | [getLineStyle()](#getLineStyle--) | Mendapatkan gaya garis. |
|
|  | [setLineStyle(int value)](#setLineStyle-int-) | Mengatur gaya garis. |
|
|  | [getTransparency()](#getTransparency--) | <br /> |

|
|  | [getColorConsideringOpacity()](#getColorConsideringOpacity--) | <br /> |

|
### OfficeLineFormat() {#OfficeLineFormat--}
```
public OfficeLineFormat()
```


Menginisialisasi instance baru dari kelas `[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat)`.


### getWeight() {#getWeight--}
```
public final double getWeight()
```


Mendapatkan ketebalan kuas yang menggambar jalur bentuk.


**Returns:**
double - Ketebalan garis dalam poin. Nilai defaultnya adalah 0.75.

### setWeight(double value) {#setWeight-double-}
```
public final void setWeight(double value)
```


Mengatur ketebalan kuas yang menggambar jalur bentuk.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Ketebalan garis dalam poin. Nilai defaultnya adalah 0.75. |
|

### getColor() {#getColor--}
```
public final Color getColor()
```


Mendapatkan warna garis.

Nilai defaultnya adalah `[Color.getBlack()](../../com.groupdocs.watermark.watermarks/color#getBlack--)`.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The color of the line.

### setColor(Color value) {#setColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setColor(Color value)
```


Mengatur warna garis.

Nilai defaultnya adalah `[Color.getBlack()](../../com.groupdocs.watermark.watermarks/color#getBlack--)`.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | Warna garis. |
|

### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Mendapatkan opasitas garis.


**Returns:**
double - Nilai harus berada di antara 0 dan 1. Nilai default adalah 1.

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


Mengatur opasitas garis.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Nilai harus berada di antara 0 dan 1. Nilai default adalah 1. |
|

### getEnabled() {#getEnabled--}
```
public final boolean getEnabled()
```


Mendapatkan nilai yang menunjukkan apakah bentuk akan digambar.


**Returns:**
boolean - Nilai default adalah false.

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Mengatur nilai yang menunjukkan apakah bentuk akan digambar.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | boolean | Nilai default adalah false. |
|

### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


Mendapatkan pola titik dan garis untuk garis.

<br />



**Returns:**
int
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


Mengatur pola titik dan garis untuk garis.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getLineStyle() {#getLineStyle--}
```
public final int getLineStyle()
```


Mendapatkan gaya garis.

Nilai default adalah `[OfficeLineStyle.Single](../../com.groupdocs.watermark.contents/officelinestyle#Single)`.


**Returns:**
int - Gaya garis.

### setLineStyle(int value) {#setLineStyle-int-}
```
public final void setLineStyle(int value)
```


Mengatur gaya garis.

Nilai default adalah `[OfficeLineStyle.Single](../../com.groupdocs.watermark.contents/officelinestyle#Single)`.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | int | Gaya garis. |
|

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


<br />



**Returns:**
double
### getColorConsideringOpacity() {#getColorConsideringOpacity--}
```
public final Color getColorConsideringOpacity()
```


<br />



**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color)
