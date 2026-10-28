---
title: "PresentationBaseShape"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Menyediakan kelas dasar abstrak untuk bentuk dari semua jenis dalam dokumen PowerPoint."
type: docs
weight: 77
url: /id/java/com.groupdocs.watermark.contents/presentationbaseshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.ITwoDObject](../../com.groupdocs.watermark.search/itwodobject), [com.groupdocs.watermark.contents.IPresentationHyperlinkContainer](../../com.groupdocs.watermark.contents/ipresentationhyperlinkcontainer)
```
public abstract class PresentationBaseShape extends ShapeSearchAdapter implements ITwoDObject, IPresentationHyperlinkContainer
```

Menyediakan kelas dasar abstrak untuk bentuk dari semua jenis dalam dokumen PowerPoint.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getPresentation()](#getPresentation--) | Mendapatkan presentasi induk dari `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini. |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | Mendapatkan pengaturan format isi gambar dari `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini. |
|
|  | [getName()](#getName--) | Mendapatkan nama dari `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Mendapatkan teks deskriptif (alternatif) yang terkait dengan `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Mengatur teks deskriptif (alternatif) yang terkait dengan `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini. |
|
|  | [getId()](#getId--) | Mendapatkan pengidentifikasi dari `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini. |
|
|  | [getZOrderPosition()](#getZOrderPosition--) | Mendapatkan posisi `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini dalam urutan z. |
|
|  | [getHyperlink(int actionType)](#getHyperlink-int-) | Mendapatkan hyperlink yang terkait dengan `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini. |
|
|  | [setHyperlink(int actionType, String url)](#setHyperlink-int-java.lang.String-) | Mengatur hyperlink yang terkait dengan `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini. |
|
|  | [getX()](#getX--) | Mendapatkan offset horizontal `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini dari batas kiri presentasi dalam poin. |
|
|  | [setX(double value)](#setX-double-) | Mengatur offset horizontal `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini dari batas kiri presentasi dalam poin. |
|
|  | [getY()](#getY--) | Mendapatkan atau mengatur offset vertikal `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini dari batas atas presentasi dalam poin. |
|
|  | [setY(double value)](#setY-double-) | Mendapatkan atau mengatur offset vertikal `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini dari batas atas presentasi dalam poin. |
|
|  | [getWidth()](#getWidth--) | Mendapatkan lebar `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini dalam poin. |
|
|  | [setWidth(double value)](#setWidth-double-) | Mengatur lebar `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini dalam poin. |
|
|  | [getHeight()](#getHeight--) | Mendapatkan tinggi `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini dalam poin. |
|
|  | [setHeight(double value)](#setHeight-double-) | Mengatur tinggi `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini dalam poin. |
|
### getPresentation() {#getPresentation--}
```
public final PresentationBaseSlide getPresentation()
```


Mendapatkan presentasi induk dari `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini.


**Returns:**
[PresentationBaseSlide](../../com.groupdocs.watermark.contents/presentationbaseslide) - The parent presentation of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getImageFillFormat() {#getImageFillFormat--}
```
public final PresentationImageFillFormat getImageFillFormat()
```


Mendapatkan pengaturan format isi gambar dari `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini.


**Returns:**
[PresentationImageFillFormat](../../com.groupdocs.watermark.contents/presentationimagefillformat) - The image fill format settings of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getName() {#getName--}
```
public final String getName()
```


Mendapatkan nama dari `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini.


**Returns:**
java.lang.String - Nama dari `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Mendapatkan teks deskriptif (alternatif) yang terkait dengan `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini.


**Returns:**
java.lang.String - Teks deskriptif (alternatif) yang terkait dengan `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Mengatur teks deskriptif (alternatif) yang terkait dengan `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | java.lang.String | Teks deskriptif (alternatif) yang terkait dengan `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini. |
|

### getId() {#getId--}
```
public final long getId()
```


Mendapatkan pengidentifikasi dari `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini.


**Returns:**
long - Pengidentifikasi dari `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini.

### getZOrderPosition() {#getZOrderPosition--}
```
public final int getZOrderPosition()
```


Mendapatkan posisi `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini dalam urutan z.

Sebuah bentuk dengan urutan z yang lebih tinggi selalu berada di depan bentuk dengan urutan z yang lebih rendah.


**Returns:**
int - Posisi `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini dalam urutan z.

### getHyperlink(int actionType) {#getHyperlink-int-}
```
public final String getHyperlink(int actionType)
```


Mendapatkan hyperlink yang terkait dengan `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | actionType | int | Aksi yang mengaktifkan hyperlink. |
|

**Returns:**
java.lang.String - url dari hyperlink yang diaktifkan pada aksi yang ditentukan.

### setHyperlink(int actionType, String url) {#setHyperlink-int-java.lang.String-}
```
public final void setHyperlink(int actionType, String url)
```


Mengatur hyperlink yang terkait dengan `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | actionType | int | Aksi yang mengaktifkan hyperlink. |
|
|  | url | java.lang.String | URL hyperlink. |
|

### getX() {#getX--}
```
public final double getX()
```


Mendapatkan offset horizontal `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini dari batas kiri presentasi dalam poin.


**Returns:**
double - Koordinat x `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Mengatur offset horizontal `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini dari batas kiri presentasi dalam poin.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Koordinat x `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini. |
|

### getY() {#getY--}
```
public final double getY()
```


Mendapatkan atau mengatur offset vertikal `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini dari batas atas presentasi dalam poin.


**Returns:**
double - Koordinat y `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Mendapatkan atau mengatur offset vertikal `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini dari batas atas presentasi dalam poin.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Koordinat y dari `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Mendapatkan lebar `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini dalam poin.


**Returns:**
double - Lebar dari `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini dalam poin.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Mengatur lebar `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini dalam poin.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Lebar dari `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini dalam poin. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Mendapatkan tinggi `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini dalam poin.


**Returns:**
double - Tinggi dari `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini dalam poin.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Mengatur tinggi `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini dalam poin.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Tinggi dari `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ini dalam poin. |
|

