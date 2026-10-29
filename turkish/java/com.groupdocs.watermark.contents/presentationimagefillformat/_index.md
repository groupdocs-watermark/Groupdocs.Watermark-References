---
title: "PresentationImageFillFormat"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "PowerPoint belgesindeki resim doldurma biçimi ayarlarını temsil eder."
type: docs
weight: 85
url: /tr/java/com.groupdocs.watermark.contents/presentationimagefillformat/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.contents.OfficeImageFillFormat
```
public class PresentationImageFillFormat extends OfficeImageFillFormat<PresentationWatermarkableImage>
```

PowerPoint belgesindeki resim doldurma biçimi ayarlarını temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | Görüntünün arka plan boyunca döşenip döşenmediğini gösteren bir değeri alır. |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | Görüntünün arka plan boyunca döşenip döşenmediğini gösteren bir değeri ayarlar. |
|
|  | [getTransparency()](#getTransparency--) | Arka plan görüntüsünün şeffaflığını 0.0 (opak) ile 1.0 (tam şeffaf) arasında bir değer olarak alır. |
(tamamen şeffaf).
|
|  | [setTransparency(double value)](#setTransparency-double-) | Arka plan görüntüsünün şeffaflığını 0.0 (opak) ile 1.0 (tam şeffaf) arasında bir değer olarak ayarlar. |
(tamamen şeffaf).
|
|  | [getBackgroundImage()](#getBackgroundImage--) | Arka plan görüntüsünü alır. |
|
|  | [setBackgroundImage(PresentationWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-) | Arka plan görüntüsünü ayarlar. |
|
### getTileAsTexture() {#getTileAsTexture--}
```
public boolean getTileAsTexture()
```


Görüntünün arka plan boyunca döşenip döşenmediğini gösteren bir değeri alır.


**Returns:**
boolean - Görüntü arka plan boyunca döşenmişse true; aksi takdirde false (görüntü uzatılmıştır). Varsayılan değer false.

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public void setTileAsTexture(boolean value)
```


Görüntünün arka plan boyunca döşenip döşenmediğini gösteren bir değeri ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | Görüntü arka plan boyunca döşenmişse true; aksi takdirde false (görüntü uzatılmıştır). Varsayılan değer false. |
|

### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


Arka plan görüntüsünün şeffaflığını 0.0 (opak) ile 1.0 (tam şeffaf) arasında bir değer olarak alır.
(tamamen şeffaf).


**Returns:**
double - Arka plan görüntüsünün şeffaflığı 0.0 (opak) ile 1.0 (tamamen şeffaf) arasında bir değer olarak.

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


Arka plan görüntüsünün şeffaflığını 0.0 (opak) ile 1.0 (tam şeffaf) arasında bir değer olarak ayarlar.
(tamamen şeffaf).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | double | Arka plan görüntüsünün şeffaflığı 0.0 (opak) ile 1.0 (tamamen şeffaf) arasında bir değer. |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public PresentationWatermarkableImage getBackgroundImage()
```


Arka plan görüntüsünü alır.


**Returns:**
[PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) - The background image. Returns null if the image is not set.

### setBackgroundImage(PresentationWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-}
```
public void setBackgroundImage(PresentationWatermarkableImage value)
```


Arka plan görüntüsünü ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) | Arka plan görüntüsü. Görüntü ayarlanmamışsa null döndürür. |
|

