---
title: "PresentationBackgroundPossibleWatermark"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili watermark latar belakang yang mungkin ada dalam dokumen PowerPoint."
type: docs
weight: 47
url: /id/java/com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)
```
public class PresentationBackgroundPossibleWatermark extends PossibleWatermark
```

Mewakili watermark latar belakang yang mungkin ada dalam dokumen PowerPoint.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PresentationBackgroundPossibleWatermark(PresentationBaseSlide slide)](#PresentationBackgroundPossibleWatermark-com.groupdocs.watermark.contents.PresentationBaseSlide-) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getParent()](#getParent--) | Mendapatkan induk dari `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` ini. |
|
|  | [getWidth()](#getWidth--) | Mendapatkan lebar dari `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` ini dalam poin. |
|
|  | [getHeight()](#getHeight--) | Mendapatkan tinggi dari `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` ini dalam poin. |
|
|  | [getX()](#getX--) | Mendapatkan offset horizontal dari `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` ini dari batas kiri slide dalam poin. |
|
|  | [getY()](#getY--) | Mendapatkan offset vertikal dari `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` ini dari batas atas slide dalam poin. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Mendapatkan sudut rotasi dari `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` ini dalam derajat. |
|
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | Mendapatkan `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` dari `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` ini. |
|
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### PresentationBackgroundPossibleWatermark(PresentationBaseSlide slide) {#PresentationBackgroundPossibleWatermark-com.groupdocs.watermark.contents.PresentationBaseSlide-}
```
public PresentationBackgroundPossibleWatermark(PresentationBaseSlide slide)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| slide | [PresentationBaseSlide](../../com.groupdocs.watermark.contents/presentationbaseslide) |  |

### getParent() {#getParent--}
```
public ContentPart getParent()
```


Mendapatkan induk dari `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` ini.


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Mendapatkan lebar dari `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` ini dalam poin.


**Returns:**
double - Lebar dari `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` ini dalam poin.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Mendapatkan tinggi dari `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` ini dalam poin.


**Returns:**
double - Tinggi dari `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` ini dalam poin.

### getX() {#getX--}
```
public double getX()
```


Mendapatkan offset horizontal dari `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` ini dari batas kiri slide dalam poin.


**Returns:**
double - Koordinat x dari `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` ini.

### getY() {#getY--}
```
public double getY()
```


Mendapatkan offset vertikal dari `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` ini dari batas atas slide dalam poin.


**Returns:**
double - Koordinat y dari `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` ini.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Mendapatkan sudut rotasi dari `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` ini dalam derajat.


**Returns:**
double - Sudut rotasi dari `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` ini dalam derajat.

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


Mendapatkan `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` dari `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` ini.


**Returns:**
int - `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` dari `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)` ini.

### getImageInternally() {#getImageInternally--}
```
public WatermarkableImage getImageInternally()
```




**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### remove() {#remove--}
```
public void remove()
```




