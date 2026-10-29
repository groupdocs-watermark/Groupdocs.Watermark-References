---
title: "ColorRange"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Renk aralığını temsil eder."
type: docs
weight: 12
url: /tr/java/com.groupdocs.watermark.search/colorrange/
---
**Inheritance:**
java.lang.Object
```
public class ColorRange
```

Renk aralığını temsil eder. Aralıkları RGB renginin HSB temsili kullanılarak belirtir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [ColorRange()](#ColorRange--) | Yeni bir `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` sınıf örneği başlatır. |
|
|  | [ColorRange(Color exactColor)](#ColorRange-com.groupdocs.watermark.watermarks.Color-) | Belirtilen kesin renk ile yeni bir `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` sınıf örneği başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getMinHue()](#getMinHue--) | Başlangıç ton değerini derece cinsinden alır. |
|
|  | [setMinHue(float value)](#setMinHue-float-) | Başlangıç ton değerini derece cinsinden ayarlar. |
|
|  | [getMaxHue()](#getMaxHue--) | Bitiş ton değerini derece cinsinden alır. |
|
|  | [setMaxHue(float value)](#setMaxHue-float-) | Bitiş ton değerini derece cinsinden ayarlar. |
|
|  | [getMinSaturation()](#getMinSaturation--) | Başlangıç doygunluk değerini alır. |
|
|  | [setMinSaturation(float value)](#setMinSaturation-float-) | Başlangıç doygunluk değerini ayarlar. |
|
|  | [getMaxSaturation()](#getMaxSaturation--) | Bitiş doygunluk değerini alır. |
|
|  | [setMaxSaturation(float value)](#setMaxSaturation-float-) | Bitiş doygunluk değerini ayarlar. |
|
|  | [getMinBrightness()](#getMinBrightness--) | Başlangıç parlaklık değerini alır. |
|
|  | [setMinBrightness(float value)](#setMinBrightness-float-) | Başlangıç parlaklık değerini ayarlar. |
|
|  | [getMaxBrightness()](#getMaxBrightness--) | Bitiş parlaklık değerini alır. |
|
|  | [setMaxBrightness(float value)](#setMaxBrightness-float-) | Bitiş parlaklık değerini ayarlar. |
|
|  | [isEmpty()](#isEmpty--) | Yalnızca boş rengin aralıkta olup olmadığını gösteren bir değeri alır. |
|
|  | [setEmpty(boolean value)](#setEmpty-boolean-) | Yalnızca boş rengin aralıkta olup olmadığını gösteren bir değeri ayarlar. |
|
### ColorRange() {#ColorRange--}
```
public ColorRange()
```


Yeni bir `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` sınıf örneği başlatır.


### ColorRange(Color exactColor) {#ColorRange-com.groupdocs.watermark.watermarks.Color-}
```
public ColorRange(Color exactColor)
```


Belirtilen kesin renk ile yeni bir `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` sınıf örneği başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | exactColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Aralığın oluşturulduğu kesin renk. |
|

### getMinHue() {#getMinHue--}
```
public final float getMinHue()
```


Başlangıç ton değerini derece cinsinden alır.


**Returns:**
float - Başlangıç renk tonu değeri, derece cinsinden.

### setMinHue(float value) {#setMinHue-float-}
```
public final void setMinHue(float value)
```


Başlangıç ton değerini derece cinsinden ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | float | Başlangıç renk tonu değeri, derece cinsinden. |
|

### getMaxHue() {#getMaxHue--}
```
public final float getMaxHue()
```


Bitiş ton değerini derece cinsinden alır.


**Returns:**
float - Bitiş renk tonu değeri, derece cinsinden.

### setMaxHue(float value) {#setMaxHue-float-}
```
public final void setMaxHue(float value)
```


Bitiş ton değerini derece cinsinden ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | float | Bitiş renk tonu değeri, derece cinsinden. |
|

### getMinSaturation() {#getMinSaturation--}
```
public final float getMinSaturation()
```


Başlangıç doygunluk değerini alır.


**Returns:**
float - Doygunluk 0.0 ile 1.0 arasında değişir, 0.0 gri tonlamadır ve 1.0 en yüksek doygunluktur.

### setMinSaturation(float value) {#setMinSaturation-float-}
```
public final void setMinSaturation(float value)
```


Başlangıç doygunluk değerini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | float | Doygunluk 0.0 ile 1.0 arasında değişir, 0.0 gri tonlamadır ve 1.0 en yüksek doygunluktur. |
|

### getMaxSaturation() {#getMaxSaturation--}
```
public final float getMaxSaturation()
```


Bitiş doygunluk değerini alır.


**Returns:**
float - Doygunluk 0.0 ile 1.0 arasında değişir, 0.0 gri tonlamadır ve 1.0 en yüksek doygunluktur.

### setMaxSaturation(float value) {#setMaxSaturation-float-}
```
public final void setMaxSaturation(float value)
```


Bitiş doygunluk değerini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | float | Doygunluk 0.0 ile 1.0 arasında değişir, 0.0 gri tonlamadır ve 1.0 en yüksek doygunluktur. |
|

### getMinBrightness() {#getMinBrightness--}
```
public final float getMinBrightness()
```


Başlangıç parlaklık değerini alır.


**Returns:**
float - Parlaklık 0.0 ile 1.0 arasında değişir, 0.0 siyahı ve 1.0 beyazı temsil eder.

### setMinBrightness(float value) {#setMinBrightness-float-}
```
public final void setMinBrightness(float value)
```


Başlangıç parlaklık değerini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | float | Parlaklık 0.0 ile 1.0 arasında değişir, 0.0 siyahı ve 1.0 beyazı temsil eder. |
|

### getMaxBrightness() {#getMaxBrightness--}
```
public final float getMaxBrightness()
```


Bitiş parlaklık değerini alır.


**Returns:**
float - Parlaklık 0.0 ile 1.0 arasında değişir, 0.0 siyahı ve 1.0 beyazı temsil eder.

### setMaxBrightness(float value) {#setMaxBrightness-float-}
```
public final void setMaxBrightness(float value)
```


Bitiş parlaklık değerini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | float | Parlaklık 0.0 ile 1.0 arasında değişir, 0.0 siyahı ve 1.0 beyazı temsil eder. |
|

### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Yalnızca boş rengin aralıkta olup olmadığını gösteren bir değeri alır.


**Returns:**
boolean - Yalnızca boş renk aralıkta ise true (HSB aralıkları yok sayılır); aksi takdirde false.

### setEmpty(boolean value) {#setEmpty-boolean-}
```
public final void setEmpty(boolean value)
```


Yalnızca boş rengin aralıkta olup olmadığını gösteren bir değeri ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | Yalnızca boş renk aralıkta ise true (HSB aralıkları yok sayılır); aksi takdirde false. |
|

