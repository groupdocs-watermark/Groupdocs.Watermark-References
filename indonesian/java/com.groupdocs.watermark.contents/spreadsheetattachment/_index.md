---
title: "SpreadsheetAttachment"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili file yang dilampirkan pada dokumen Excel."
type: docs
weight: 101
url: /id/java/com.groupdocs.watermark.contents/spreadsheetattachment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.ITwoDObject](../../com.groupdocs.watermark.search/itwodobject)
```
public class SpreadsheetAttachment extends Attachment implements ITwoDObject
```

Mewakili file yang dilampirkan pada dokumen Excel.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getContent()](#getContent--) | Mendapatkan konten file terlampir. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | Mengatur konten file terlampir. |
|
|  | [getPreviewImageContent()](#getPreviewImageContent--) | Mendapatkan gambar pratinjau file terlampir sebagai array byte. |
|
|  | [setPreviewImageContent(byte[] value)](#setPreviewImageContent-byte---) | Mengatur gambar pratinjau file terlampir sebagai array byte. |
|
|  | [isLink()](#isLink--) | Mendapatkan nilai yang menunjukkan apakah konten hanya berisi tautan ke file. |
|
|  | [getSourceFullName()](#getSourceFullName--) | Mendapatkan nama lengkap file terlampir. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Mendapatkan teks deskriptif (alternatif) yang terkait dengan file terlampir. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Mengatur teks deskriptif (alternatif) yang terkait dengan file terlampir. |
|
|  | [getAsposeOleObject()](#getAsposeOleObject--) | <br /> |

|
|  | [getX()](#getX--) | Mendapatkan offset horizontal bingkai lampiran dari batas kiri lembar kerja dalam poin. |
|
|  | [setX(double value)](#setX-double-) | Mengatur offset horizontal bingkai lampiran dari batas kiri lembar kerja dalam poin. |
|
|  | [getY()](#getY--) | Mendapatkan offset vertikal bingkai lampiran dari batas atas lembar kerja dalam poin. |
|
|  | [setY(double value)](#setY-double-) | Mengatur offset vertikal bingkai lampiran dari batas atas lembar kerja dalam poin. |
|
|  | [getWidth()](#getWidth--) | Mendapatkan lebar bingkai lampiran dalam poin. |
|
|  | [setWidth(double value)](#setWidth-double-) | Mengatur lebar bingkai lampiran dalam poin. |
|
|  | [getHeight()](#getHeight--) | Mendapatkan tinggi bingkai lampiran dalam poin. |
|
|  | [setHeight(double value)](#setHeight-double-) | Mengatur tinggi bingkai lampiran dalam poin. |
|
|  | [checkImageType()](#checkImageType--) | <br /> |

|
### getContent() {#getContent--}
```
public byte[] getContent()
```


Mendapatkan konten file terlampir.


**Returns:**
byte[] - Konten file terlampir.

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


Mengatur konten file terlampir.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | byte[] | Konten file terlampir. |
|

### getPreviewImageContent() {#getPreviewImageContent--}
```
public final byte[] getPreviewImageContent()
```


Mendapatkan gambar pratinjau file terlampir sebagai array byte.


**Returns:**
byte[] - Gambar pratinjau file terlampir sebagai array byte.

### setPreviewImageContent(byte[] value) {#setPreviewImageContent-byte---}
```
public final void setPreviewImageContent(byte[] value)
```


Mengatur gambar pratinjau file terlampir sebagai array byte.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | byte[] | Gambar pratinjau file terlampir sebagai array byte. |
|

### isLink() {#isLink--}
```
public final boolean isLink()
```


Mendapatkan nilai yang menunjukkan apakah konten hanya berisi tautan ke file.


**Returns:**
boolean - Benar jika file terlampir direferensikan oleh tautan (konten tidak berisi konten file terlampir); jika tidak, salah.

### getSourceFullName() {#getSourceFullName--}
```
public final String getSourceFullName()
```


Mendapatkan nama lengkap file terlampir.


**Returns:**
java.lang.String - Nama lengkap file terlampir.

<br />

*** ** * ** ***

Ekstensi digunakan untuk menentukan aplikasi yang tepat untuk membuka file.

<br />


### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Mendapatkan teks deskriptif (alternatif) yang terkait dengan file terlampir.


**Returns:**
java.lang.String - Teks deskriptif (alternatif) yang terkait dengan file terlampir.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Mengatur teks deskriptif (alternatif) yang terkait dengan file terlampir.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | java.lang.String | Teks deskriptif (alternatif) yang terkait dengan file terlampir. |
|

### getAsposeOleObject() {#getAsposeOleObject--}
```
public final OleObject getAsposeOleObject()
```


<br />



**Returns:**
com.aspose.cells.OleObject
### getX() {#getX--}
```
public final double getX()
```


Mendapatkan offset horizontal bingkai lampiran dari batas kiri lembar kerja dalam poin.


**Returns:**
double - Koordinat x bingkai lampiran.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Mengatur offset horizontal bingkai lampiran dari batas kiri lembar kerja dalam poin.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Koordinat x bingkai lampiran. |
|

### getY() {#getY--}
```
public final double getY()
```


Mendapatkan offset vertikal bingkai lampiran dari batas atas lembar kerja dalam poin.


**Returns:**
double - Koordinat y bingkai lampiran.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Mengatur offset vertikal bingkai lampiran dari batas atas lembar kerja dalam poin.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Koordinat y dari bingkai lampiran. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Mendapatkan lebar bingkai lampiran dalam poin.


**Returns:**
double - Lebar bingkai lampiran dalam poin.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Mengatur lebar bingkai lampiran dalam poin.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Lebar bingkai lampiran dalam poin. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Mendapatkan tinggi bingkai lampiran dalam poin.


**Returns:**
double - Tinggi bingkai lampiran dalam poin.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Mengatur tinggi bingkai lampiran dalam poin.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Tinggi bingkai lampiran dalam poin. |
|

### checkImageType() {#checkImageType--}
```
public final void checkImageType()
```


<br />



