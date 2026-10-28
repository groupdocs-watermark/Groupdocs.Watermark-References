---
title: "PossibleWatermark"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili watermark yang mungkin ditemukan dalam dokumen."
type: docs
weight: 45
url: /id/java/com.groupdocs.watermark.search/possiblewatermark/
---
**Inheritance:**
java.lang.Object
```
public abstract class PossibleWatermark
```

Mewakili watermark yang mungkin ditemukan dalam dokumen.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PossibleWatermark()](#PossibleWatermark--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getParent()](#getParent--) | Mendapatkan induk dari `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` ini. |
|
| [getPageNumber()](#getPageNumber--) |  |
|  | [getWidth()](#getWidth--) | Mendapatkan lebar dari `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` ini. |
|
|  | [getHeight()](#getHeight--) | Mendapatkan tinggi dari `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` ini. |
|
|  | [getX()](#getX--) | Mendapatkan koordinat x dari `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` ini. |
|
|  | [getY()](#getY--) | Mendapatkan koordinat y dari `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` ini. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Mendapatkan sudut rotasi dari `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` ini dalam derajat. |
|
|  | [getText()](#getText--) | Mendapatkan teks dari `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` ini. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Mengatur teks dari `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` ini. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Mendapatkan koleksi fragmen teks terformat dari `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` ini. |
|
|  | [getImageData()](#getImageData--) | Mendapatkan atau mengatur gambar dari `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` ini. |
|
| [setImageData(byte[] value)](#setImageData-byte---) |  |
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | Mendapatkan satuan ukuran `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` dari `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` ini. |
|
| [getCollection()](#getCollection--) |  |
| [setCollection(PossibleWatermarkCollection value)](#setCollection-com.groupdocs.watermark.search.PossibleWatermarkCollection-) |  |
| [getImageSize()](#getImageSize--) |  |
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### PossibleWatermark() {#PossibleWatermark--}
```
public PossibleWatermark()
```




### getParent() {#getParent--}
```
public abstract ContentPart getParent()
```


Mendapatkan induk dari `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` ini.


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```




**Returns:**
java.lang.Integer
### getWidth() {#getWidth--}
```
public double getWidth()
```


Mendapatkan lebar dari `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` ini.


**Returns:**
double - Lebar dari `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` ini.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Mendapatkan tinggi dari `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` ini.


**Returns:**
double - Tinggi dari `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` ini.

### getX() {#getX--}
```
public double getX()
```


Mendapatkan koordinat x dari `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` ini.


**Returns:**
double - Koordinat x dari `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` ini.

### getY() {#getY--}
```
public double getY()
```


Mendapatkan koordinat y dari `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` ini.


**Returns:**
double - Koordinat y dari `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` ini.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Mendapatkan sudut rotasi dari `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` ini dalam derajat.


**Returns:**
double - Sudut rotasi dari `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` ini.

### getText() {#getText--}
```
public String getText()
```


Mendapatkan teks dari `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` ini.


**Returns:**
java.lang.String - Teks dari `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` ini.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Mengatur teks dari `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` ini.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | java.lang.String | Teks dari `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` ini. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


Mendapatkan koleksi fragmen teks terformat dari `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` ini.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Mendapatkan atau mengatur gambar dari `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` ini.


**Returns:**
byte[] - Gambar dari `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` ini atau null jika watermark tidak memiliki gambar.

### setImageData(byte[] value) {#setImageData-byte---}
```
public final void setImageData(byte[] value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte[] |  |

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


Mendapatkan satuan ukuran `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` dari `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` ini.


**Returns:**
int - Satuan ukuran `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` dari `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` ini.

### getCollection() {#getCollection--}
```
public final PossibleWatermarkCollection getCollection()
```




**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection)
### setCollection(PossibleWatermarkCollection value) {#setCollection-com.groupdocs.watermark.search.PossibleWatermarkCollection-}
```
public final void setCollection(PossibleWatermarkCollection value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection) |  |

### getImageSize() {#getImageSize--}
```
public final Size getImageSize()
```




**Returns:**
[Size](../../com.groupdocs.watermark.internal/size)
### getImageInternally() {#getImageInternally--}
```
public WatermarkableImage getImageInternally()
```




**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### remove() {#remove--}
```
public abstract void remove()
```




