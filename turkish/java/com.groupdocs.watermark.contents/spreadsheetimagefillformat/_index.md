---
title: "SpreadsheetImageFillFormat"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Excel belgesindeki resim doldurma biçim ayarlarını temsil eder."
type: docs
weight: 114
url: /tr/java/com.groupdocs.watermark.contents/spreadsheetimagefillformat/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.contents.OfficeImageFillFormat
```
public class SpreadsheetImageFillFormat extends OfficeImageFillFormat<SpreadsheetWatermarkableImage>
```

Excel belgesindeki resim doldurma biçim ayarlarını temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | Görüntünün arka plan boyunca döşenip döşenmediğini gösteren bir değeri alır. |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | Görüntünün arka plan boyunca döşenip döşenmediğini gösteren bir değeri ayarlar. |
|
|  | [getTransparency()](#getTransparency--) | Arka plan görüntüsünün şeffaflığını 0.0 (opak) değerinden başlayan bir değer olarak alır |
1.0 (tamamen şeffaf) değerine kadar.
|
|  | [setTransparency(double value)](#setTransparency-double-) | Arka plan görüntüsünün şeffaflığını 0.0 (opak) değerinden başlayan bir değer olarak ayarlar |
1.0 (tamamen şeffaf) değerine kadar.
|
|  | [getBackgroundImage()](#getBackgroundImage--) | Arka plan görüntüsünü alır. |
|
|  | [setBackgroundImage(SpreadsheetWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | Arka plan görüntüsünü ayarlar. |
|
### getTileAsTexture() {#getTileAsTexture--}
```
public boolean getTileAsTexture()
```


Görüntünün arka plan boyunca döşenip döşenmediğini gösteren bir değeri alır.


**Returns:**
boolean - Görüntü arka plan boyunca döşenmişse true; aksi takdirde false (görüntü gerilmiş olur).

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public void setTileAsTexture(boolean value)
```


Görüntünün arka plan boyunca döşenip döşenmediğini gösteren bir değeri ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | Görüntü arka plan boyunca döşenmişse true; aksi takdirde false (görüntü gerilmiş olur). |
|

### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


Arka plan görüntüsünün şeffaflığını 0.0 (opak) değerinden başlayan bir değer olarak alır
1.0 (tamamen şeffaf) değerine kadar.


**Returns:**
double - Arka plan görüntüsünün şeffaflığı 0.0 (opak) ile 1.0 (tamamen şeffaf) arasında bir değer olarak.

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


Arka plan görüntüsünün şeffaflığını 0.0 (opak) değerinden başlayan bir değer olarak ayarlar
1.0 (tamamen şeffaf) değerine kadar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | double | Arka plan görüntüsünün şeffaflığı 0.0 (opak) ile 1.0 (tamamen şeffaf) arasında bir değer. |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public SpreadsheetWatermarkableImage getBackgroundImage()
```


Arka plan görüntüsünü alır.


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The background image. Returns null if the image is not set.

### setBackgroundImage(SpreadsheetWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public void setBackgroundImage(SpreadsheetWatermarkableImage value)
```


Arka plan görüntüsünü ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | Arka plan görüntüsü. Görüntü ayarlanmamışsa null döndürür. |
|

