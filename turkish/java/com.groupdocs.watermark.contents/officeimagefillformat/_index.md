---
title: "OfficeImageFillFormat"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Desteklenen herhangi bir ofis içeriğindeki görüntü doldurma biçimi ayarlarını temsil eder."
type: docs
weight: 46
url: /tr/java/com.groupdocs.watermark.contents/officeimagefillformat/
---
**Inheritance:**
java.lang.Object
```
public abstract class OfficeImageFillFormat<TWatermarkableImage>
```

Desteklenen herhangi bir ofis içeriğindeki görüntü doldurma biçimi ayarlarını temsil eder.


TWatermarkableImage
: Arka plan olarak kullanılan watermarkable görüntünün tam türü.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [OfficeImageFillFormat()](#OfficeImageFillFormat--) | <br /> |

|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | Görüntünün arka plan boyunca döşenip döşenmediğini gösteren bir değeri alır. |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | Görüntünün arka plan boyunca döşenip döşenmediğini gösteren bir değeri ayarlar. |
|
|  | [getTransparency()](#getTransparency--) | Arka plan görüntüsünün şeffaflığını 0.0 (opak) ile 1.0 (tamamen şeffaf) arasında bir değer olarak alır. |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Arka plan görüntüsünün şeffaflığını 0.0 (opak) ile 1.0 (tamamen şeffaf) arasında bir değer olarak ayarlar. |
|
|  | [getBackgroundImage()](#getBackgroundImage--) | Arka plan görüntüsünü alır. |
|
|  | [setBackgroundImage(TWatermarkableImage value)](#setBackgroundImage-TWatermarkableImage-) | Arka plan görüntüsünü ayarlar. |
|
|  | [checkIfBackgroundImageIsSet()](#checkIfBackgroundImageIsSet--) | <br /> |

|
### OfficeImageFillFormat() {#OfficeImageFillFormat--}
```
public OfficeImageFillFormat()
```


<br />



### getTileAsTexture() {#getTileAsTexture--}
```
public abstract boolean getTileAsTexture()
```


Görüntünün arka plan boyunca döşenip döşenmediğini gösteren bir değeri alır.


**Returns:**
boolean - Görüntü arka plan boyunca döşenmişse true; aksi takdirde false (görüntü gerilmiş olur).

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public abstract void setTileAsTexture(boolean value)
```


Görüntünün arka plan boyunca döşenip döşenmediğini gösteren bir değeri ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | Görüntü arka plan boyunca döşenmişse true; aksi takdirde false (görüntü gerilmiş olur). |
|

### getTransparency() {#getTransparency--}
```
public abstract double getTransparency()
```


Arka plan görüntüsünün şeffaflığını 0.0 (opak) ile 1.0 (tamamen şeffaf) arasında bir değer olarak alır.


**Returns:**
double - Arka plan görüntüsünün şeffaflığı 0.0 (opak) ile 1.0 (tamamen şeffaf) arasında bir değer olarak.

### setTransparency(double value) {#setTransparency-double-}
```
public abstract void setTransparency(double value)
```


Arka plan görüntüsünün şeffaflığını 0.0 (opak) ile 1.0 (tamamen şeffaf) arasında bir değer olarak ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | double | Arka plan görüntüsünün şeffaflığı 0.0 (opak) ile 1.0 (tamamen şeffaf) arasında bir değer. |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public abstract TWatermarkableImage getBackgroundImage()
```


Arka plan görüntüsünü alır.


**Returns:**
TWatermarkableImage - Arka plan görüntüsü. Görüntü ayarlanmamışsa null döner.

### setBackgroundImage(TWatermarkableImage value) {#setBackgroundImage-TWatermarkableImage-}
```
public abstract void setBackgroundImage(TWatermarkableImage value)
```


Arka plan görüntüsünü ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | TWatermarkableImage | Arka plan görüntüsü. Görüntü ayarlanmamışsa null döndürür. |
|

### checkIfBackgroundImageIsSet() {#checkIfBackgroundImageIsSet--}
```
public final void checkIfBackgroundImageIsSet()
```


<br />



