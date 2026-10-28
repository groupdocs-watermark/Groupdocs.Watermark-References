---
title: "Watermark"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili watermark yang akan ditambahkan ke dokumen."
type: docs
weight: 13
url: /id/java/com.groupdocs.watermark/watermark/
---
**Inheritance:**
java.lang.Object
```
public abstract class Watermark
```

Mewakili watermark yang akan ditambahkan ke dokumen.

**Learn more**

* More details about watermark properties:
  [Adding text watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+text+watermarks).

* More advanced watermarking topics: [Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks)

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Watermark()](#Watermark--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getOpacity()](#getOpacity--) | Mendapatkan atau mengatur opasitas `[Watermark](../../com.groupdocs.watermark/watermark)` ini. |
|
|  | [setOpacity(double value)](#setOpacity-double-) | Mendapatkan atau mengatur opasitas `[Watermark](../../com.groupdocs.watermark/watermark)` ini. |
|
|  | [getY()](#getY--) | Mendapatkan koordinat y `[Watermark](../../com.groupdocs.watermark/watermark)` ini. |
|
|  | [setY(double value)](#setY-double-) | Mengatur koordinat y `[Watermark](../../com.groupdocs.watermark/watermark)` ini. |
|
|  | [getX()](#getX--) | Mendapatkan koordinat x `[Watermark](../../com.groupdocs.watermark/watermark)` ini. |
|
|  | [setX(double value)](#setX-double-) | Mengatur koordinat x `[Watermark](../../com.groupdocs.watermark/watermark)` ini. |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | Mendapatkan perataan vertikal `[Watermark](../../com.groupdocs.watermark/watermark)` ini. |
|
|  | [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Mengatur perataan vertikal `[Watermark](../../com.groupdocs.watermark/watermark)` ini. |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | Mendapatkan perataan horizontal `[Watermark](../../com.groupdocs.watermark/watermark)` ini. |
|
|  | [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Mengatur perataan horizontal `[Watermark](../../com.groupdocs.watermark/watermark)` ini. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Mendapatkan sudut rotasi `[Watermark](../../com.groupdocs.watermark/watermark)` ini dalam derajat. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Mengatur sudut rotasi `[Watermark](../../com.groupdocs.watermark/watermark)` ini dalam derajat. |
|
|  | [isBackground()](#isBackground--) | Mendapatkan nilai yang menunjukkan apakah watermark harus ditempatkan di latar belakang. |
|
|  | [setBackground(boolean value)](#setBackground-boolean-) | Mengatur nilai yang menunjukkan apakah watermark harus ditempatkan di latar belakang. |
|
|  | [getMargins()](#getMargins--) | Mendapatkan pengaturan margin `[Watermark](../../com.groupdocs.watermark/watermark)` ini. |
|
|  | [setMargins(Margins value)](#setMargins-com.groupdocs.watermark.watermarks.Margins-) | Mengatur pengaturan margin `[Watermark](../../com.groupdocs.watermark/watermark)` ini. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Mendapatkan pengaturan penyiapan halaman `[Watermark](../../com.groupdocs.watermark/watermark)` ini. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.watermark.PagesSetup-) | Mengatur pengaturan penyiapan halaman dari `[Watermark](../../com.groupdocs.watermark/watermark)` ini. |
|
|  | [getHeight()](#getHeight--) | Mendapatkan tinggi yang diinginkan dari `[Watermark](../../com.groupdocs.watermark/watermark)` ini. |
|
|  | [setHeight(double value)](#setHeight-double-) | Mengatur tinggi yang diinginkan untuk `[Watermark](../../com.groupdocs.watermark/watermark)` ini. |
|
|  | [getWidth()](#getWidth--) | Mendapatkan lebar yang diinginkan dari `[Watermark](../../com.groupdocs.watermark/watermark)` ini. |
|
|  | [setWidth(double value)](#setWidth-double-) | Mengatur lebar yang diinginkan untuk `[Watermark](../../com.groupdocs.watermark/watermark)` ini. |
|
|  | [getScaleFactor()](#getScaleFactor--) | Mendapatkan nilai yang menentukan bagaimana ukuran watermark bergantung pada ukuran induk. |
|
|  | [setScaleFactor(double value)](#setScaleFactor-double-) | Mengatur nilai yang menentukan bagaimana ukuran watermark bergantung pada ukuran induk. |
|
|  | [getSizingType()](#getSizingType--) | Mendapatkan nilai yang menentukan cara ukuran watermark. |
|
|  | [setSizingType(int value)](#setSizingType-int-) | Mengatur nilai yang menentukan cara ukuran watermark. |
|
|  | [getConsiderParentMargins()](#getConsiderParentMargins--) | Mendapatkan nilai yang menunjukkan apakah ukuran dan koordinat watermark dihitung |
dengan mempertimbangkan margin induk.
|
|  | [setConsiderParentMargins(boolean value)](#setConsiderParentMargins-boolean-) | Mengatur nilai yang menunjukkan apakah ukuran dan koordinat watermark dihitung |
dengan mempertimbangkan margin induk.
|
| [isImageWatermark()](#isImageWatermark--) |  |
| [isTextWatermark()](#isTextWatermark--) |  |
| [getTransparency()](#getTransparency--) |  |
| [getSize()](#getSize--) |  |
| [getTileOptions()](#getTileOptions--) |  |
| [setTileOptions(TileOptions tileOptions)](#setTileOptions-com.groupdocs.watermark.watermarks.TileOptions-) |  |
| [copyPropertiesValues(Watermark source, Watermark destination)](#copyPropertiesValues-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.Watermark-) |  |
| [deepClone()](#deepClone--) |  |
| [hasSameValues(Watermark watermark)](#hasSameValues-com.groupdocs.watermark.Watermark-) |  |
| [createGeometry(ContentPartGeometry parent)](#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-) |  |
### Watermark() {#Watermark--}
```
public Watermark()
```




### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Mendapatkan atau mengatur opasitas `[Watermark](../../com.groupdocs.watermark/watermark)` ini.

Nilai opacity harus berada di antara 0 dan 1. Nilai default adalah 1.


**Returns:**
double - Opacity dari `[Watermark](../../com.groupdocs.watermark/watermark)` ini.

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


Mendapatkan atau mengatur opasitas `[Watermark](../../com.groupdocs.watermark/watermark)` ini.

Nilai opacity harus berada di antara 0 dan 1. Nilai default adalah 1.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Opacity dari `[Watermark](../../com.groupdocs.watermark/watermark)` ini. |
|

### getY() {#getY--}
```
public final double getY()
```


Mendapatkan koordinat y `[Watermark](../../com.groupdocs.watermark/watermark)` ini.


**Returns:**
double - Koordinat y dari `[Watermark](../../com.groupdocs.watermark/watermark)` ini.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Mengatur koordinat y `[Watermark](../../com.groupdocs.watermark/watermark)` ini.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Koordinat y dari `[Watermark](../../com.groupdocs.watermark/watermark)` ini. |
|

### getX() {#getX--}
```
public final double getX()
```


Mendapatkan koordinat x `[Watermark](../../com.groupdocs.watermark/watermark)` ini.


**Returns:**
double - Koordinat x dari `[Watermark](../../com.groupdocs.watermark/watermark)` ini.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Mengatur koordinat x `[Watermark](../../com.groupdocs.watermark/watermark)` ini.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Koordinat x dari `[Watermark](../../com.groupdocs.watermark/watermark)` ini. |
|

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Mendapatkan perataan vertikal `[Watermark](../../com.groupdocs.watermark/watermark)` ini.

Nilai default adalah `[VerticalAlignment.None](../../com.groupdocs.watermark.common/verticalalignment#None)`.


**Returns:**
int - `[VerticalAlignment](../../com.groupdocs.watermark.common/verticalalignment)` dari `[Watermark](../../com.groupdocs.watermark/watermark)` ini.

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


Mengatur perataan vertikal `[Watermark](../../com.groupdocs.watermark/watermark)` ini.

Nilai default adalah `[VerticalAlignment.None](../../com.groupdocs.watermark.common/verticalalignment#None)`.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | int | `[VerticalAlignment](../../com.groupdocs.watermark.common/verticalalignment)` dari `[Watermark](../../com.groupdocs.watermark/watermark)` ini. |
|

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


Mendapatkan perataan horizontal `[Watermark](../../com.groupdocs.watermark/watermark)` ini.

Nilai default adalah `[HorizontalAlignment.None](../../com.groupdocs.watermark.common/horizontalalignment#None)`.


**Returns:**
int - `[HorizontalAlignment](../../com.groupdocs.watermark.common/horizontalalignment)` dari `[Watermark](../../com.groupdocs.watermark/watermark)` ini.

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public final void setHorizontalAlignment(int value)
```


Mengatur perataan horizontal `[Watermark](../../com.groupdocs.watermark/watermark)` ini.

Nilai default adalah `[HorizontalAlignment.None](../../com.groupdocs.watermark.common/horizontalalignment#None)`.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | int | `[HorizontalAlignment](../../com.groupdocs.watermark.common/horizontalalignment)` dari `[Watermark](../../com.groupdocs.watermark/watermark)` ini. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Mendapatkan sudut rotasi `[Watermark](../../com.groupdocs.watermark/watermark)` ini dalam derajat.


**Returns:**
double - Sudut rotasi dari `[Watermark](../../com.groupdocs.watermark/watermark)` dalam derajat.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Mengatur sudut rotasi `[Watermark](../../com.groupdocs.watermark/watermark)` ini dalam derajat.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Sudut rotasi dari `[Watermark](../../com.groupdocs.watermark/watermark)` dalam derajat. |
|

### isBackground() {#isBackground--}
```
public final boolean isBackground()
```


Mendapatkan nilai yang menunjukkan apakah watermark harus ditempatkan di latar belakang.


**Returns:**
boolean - Jika nilai bernilai true, watermark akan ditempatkan di bagian bawah. Secara default, nilai bernilai false, watermark akan ditempatkan di bagian atas.

### setBackground(boolean value) {#setBackground-boolean-}
```
public final void setBackground(boolean value)
```


Mengatur nilai yang menunjukkan apakah watermark harus ditempatkan di latar belakang.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | boolean | Jika nilai bernilai true, watermark akan ditempatkan di bagian bawah. Secara default, nilai bernilai false, watermark akan ditempatkan di bagian atas. |
|

### getMargins() {#getMargins--}
```
public final Margins getMargins()
```


Mendapatkan pengaturan margin `[Watermark](../../com.groupdocs.watermark/watermark)` ini.


**Returns:**
[Margins](../../com.groupdocs.watermark.watermarks/margins) - The margin settings of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setMargins(Margins value) {#setMargins-com.groupdocs.watermark.watermarks.Margins-}
```
public final void setMargins(Margins value)
```


Mengatur pengaturan margin `[Watermark](../../com.groupdocs.watermark/watermark)` ini.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [Margins](../../com.groupdocs.watermark.watermarks/margins) | Pengaturan margin dari `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


Mendapatkan pengaturan penyiapan halaman `[Watermark](../../com.groupdocs.watermark/watermark)` ini.


**Returns:**
[PagesSetup](../../com.groupdocs.watermark/pagessetup) - The pages setup settings of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.watermark.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


Mengatur pengaturan penyiapan halaman dari `[Watermark](../../com.groupdocs.watermark/watermark)` ini.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | Pengaturan penyiapan halaman dari `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Mendapatkan tinggi yang diinginkan dari `[Watermark](../../com.groupdocs.watermark/watermark)` ini.


**Returns:**
double - Tinggi yang diinginkan dari `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Mengatur tinggi yang diinginkan untuk `[Watermark](../../com.groupdocs.watermark/watermark)` ini.

Mengatur properti ini juga akan mengubah nilai `#getSizingType().getSizingType()`
properti menjadi `[SizingType.Absolute](../../com.groupdocs.watermark.watermarks/sizingtype#Absolute)`.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Tinggi yang diinginkan dari `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Mendapatkan lebar yang diinginkan dari `[Watermark](../../com.groupdocs.watermark/watermark)` ini.


**Returns:**
double - Lebar yang diinginkan dari `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Mengatur lebar yang diinginkan untuk `[Watermark](../../com.groupdocs.watermark/watermark)` ini.

Mengatur properti ini juga akan mengubah nilai `#getSizingType().getSizingType()`
properti menjadi `[SizingType.Absolute](../../com.groupdocs.watermark.watermarks/sizingtype#Absolute)`.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Lebar yang diinginkan dari `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getScaleFactor() {#getScaleFactor--}
```
public final double getScaleFactor()
```


Mendapatkan nilai yang menentukan bagaimana ukuran watermark bergantung pada ukuran induk.

Nilai harus berada di antara 0 dan 1.


**Returns:**
double - Faktor skala dari `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setScaleFactor(double value) {#setScaleFactor-double-}
```
public final void setScaleFactor(double value)
```


Mengatur nilai yang menentukan bagaimana ukuran watermark bergantung pada ukuran induk.

Nilai harus berada di antara 0 dan 1.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Faktor skala dari `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getSizingType() {#getSizingType--}
```
public final int getSizingType()
```


Mendapatkan nilai yang menentukan cara ukuran watermark.


**Returns:**
int - Tipe ukuran.

### setSizingType(int value) {#setSizingType-int-}
```
public final void setSizingType(int value)
```


Mengatur nilai yang menentukan cara ukuran watermark.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | int | Tipe ukuran. |
|

### getConsiderParentMargins() {#getConsiderParentMargins--}
```
public final boolean getConsiderParentMargins()
```


Mendapatkan nilai yang menunjukkan apakah ukuran dan koordinat watermark dihitung
dengan mempertimbangkan margin induk.


**Returns:**
boolean - Jika nilai bernilai true, ukuran watermark dan koordinat dihitung dengan mempertimbangkan margin induk. Secara default, nilai bernilai false, margin induk diabaikan.

### setConsiderParentMargins(boolean value) {#setConsiderParentMargins-boolean-}
```
public final void setConsiderParentMargins(boolean value)
```


Mengatur nilai yang menunjukkan apakah ukuran dan koordinat watermark dihitung
dengan mempertimbangkan margin induk.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | boolean | Jika nilai bernilai true, ukuran watermark dan koordinat dihitung dengan mempertimbangkan margin induk. Secara default, nilai bernilai false, margin induk diabaikan. |
|

### isImageWatermark() {#isImageWatermark--}
```
public abstract boolean isImageWatermark()
```




**Returns:**
boolean
### isTextWatermark() {#isTextWatermark--}
```
public abstract boolean isTextWatermark()
```




**Returns:**
boolean
### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```




**Returns:**
double
### getSize() {#getSize--}
```
public abstract SizeD getSize()
```




**Returns:**
[SizeD](../../com.groupdocs.watermark.internal/sized)
### getTileOptions() {#getTileOptions--}
```
public TileOptions getTileOptions()
```




**Returns:**
[TileOptions](../../com.groupdocs.watermark.watermarks/tileoptions)
### setTileOptions(TileOptions tileOptions) {#setTileOptions-com.groupdocs.watermark.watermarks.TileOptions-}
```
public void setTileOptions(TileOptions tileOptions)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tileOptions | [TileOptions](../../com.groupdocs.watermark.watermarks/tileoptions) |  |

### copyPropertiesValues(Watermark source, Watermark destination) {#copyPropertiesValues-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.Watermark-}
```
public static void copyPropertiesValues(Watermark source, Watermark destination)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| destination | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### deepClone() {#deepClone--}
```
public abstract Watermark deepClone()
```




**Returns:**
[Watermark](../../com.groupdocs.watermark/watermark)
### hasSameValues(Watermark watermark) {#hasSameValues-com.groupdocs.watermark.Watermark-}
```
public boolean hasSameValues(Watermark watermark)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

**Returns:**
boolean
### createGeometry(ContentPartGeometry parent) {#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-}
```
public abstract WatermarkGeometry createGeometry(ContentPartGeometry parent)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| parent | [ContentPartGeometry](../../com.groupdocs.watermark.internal/contentpartgeometry) |  |

**Returns:**
[WatermarkGeometry](../../com.groupdocs.watermark.internal/watermarkgeometry)
