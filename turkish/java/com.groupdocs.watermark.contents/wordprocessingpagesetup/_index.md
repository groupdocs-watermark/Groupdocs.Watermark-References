---
title: "WordProcessingPageSetup"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Bir Word belgesi bölümünün sayfa yazdırma özelliklerini temsil eder."
type: docs
weight: 134
url: /tr/java/com.groupdocs.watermark.contents/wordprocessingpagesetup/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingPageSetup
```

Bir Word belgesi bölümünün sayfa yazdırma özelliklerini temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getWidth()](#getWidth--) | Yazdırma sayfasının genişliğini puan cinsinden alır. |
|
|  | [getHeight()](#getHeight--) | Yazdırma sayfasının yüksekliğini puan cinsinden alır. |
|
|  | [getLeftMargin()](#getLeftMargin--) | Sol kenar boşluğunun boyutunu puan cinsinden alır. |
|
|  | [getTopMargin()](#getTopMargin--) | Üst kenar boşluğunun boyutunu puan cinsinden alır. |
|
|  | [getRightMargin()](#getRightMargin--) | Sağ kenar boşluğunun boyutunu puan cinsinden alır. |
|
|  | [getBottomMargin()](#getBottomMargin--) | Alt kenar boşluğunun boyutunu puan cinsinden alır. |
|
|  | [getDifferentFirstPageHeaderFooter()](#getDifferentFirstPageHeaderFooter--) | İlk sayfa için farklı bir üstbilgi/altbilgi kullanılıp kullanılmadığını gösteren bir değeri alır. |
|
|  | [setDifferentFirstPageHeaderFooter(boolean value)](#setDifferentFirstPageHeaderFooter-boolean-) | İlk sayfa için farklı bir üstbilgi/altbilgi kullanılıp kullanılmadığını gösteren bir değeri ayarlar. |
|
|  | [getOddAndEvenPagesHeaderFooter()](#getOddAndEvenPagesHeaderFooter--) | Tek ve çift numaralı sayfalar için farklı üstbilgi/altbilgilerin kullanılıp kullanılmadığını gösteren bir değeri alır |
sayfalar.
|
|  | [setOddAndEvenPagesHeaderFooter(boolean value)](#setOddAndEvenPagesHeaderFooter-boolean-) | Tek ve çift numaralı sayfalar için farklı üstbilgi/altbilgilerin kullanılıp kullanılmadığını gösteren bir değeri ayarlar |
sayfalar.
|
### getWidth() {#getWidth--}
```
public final double getWidth()
```


Yazdırma sayfasının genişliğini puan cinsinden alır.


**Returns:**
double - Yazdırma sayfasının genişliği puan cinsinden.

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Yazdırma sayfasının yüksekliğini puan cinsinden alır.


**Returns:**
double - Yazdırma sayfasının yüksekliği puan cinsinden.

### getLeftMargin() {#getLeftMargin--}
```
public final double getLeftMargin()
```


Sol kenar boşluğunun boyutunu puan cinsinden alır.


**Returns:**
double - Sol kenar boşluğunun boyutu puan cinsinden.

### getTopMargin() {#getTopMargin--}
```
public final double getTopMargin()
```


Üst kenar boşluğunun boyutunu puan cinsinden alır.


**Returns:**
double - Üst kenar boşluğunun boyutu puan cinsinden.

### getRightMargin() {#getRightMargin--}
```
public final double getRightMargin()
```


Sağ kenar boşluğunun boyutunu puan cinsinden alır.


**Returns:**
double - Sağ kenar boşluğunun boyutu puan cinsinden.

### getBottomMargin() {#getBottomMargin--}
```
public final double getBottomMargin()
```


Alt kenar boşluğunun boyutunu puan cinsinden alır.


**Returns:**
double - Alt kenar boşluğunun nokta cinsinden boyutu.

### getDifferentFirstPageHeaderFooter() {#getDifferentFirstPageHeaderFooter--}
```
public final boolean getDifferentFirstPageHeaderFooter()
```


İlk sayfa için farklı bir üstbilgi/altbilgi kullanılıp kullanılmadığını gösteren bir değeri alır.


**Returns:**
boolean - İlk sayfa için farklı bir üstbilgi/altbilgi kullanılıyorsa true; aksi takdirde false.

### setDifferentFirstPageHeaderFooter(boolean value) {#setDifferentFirstPageHeaderFooter-boolean-}
```
public final void setDifferentFirstPageHeaderFooter(boolean value)
```


İlk sayfa için farklı bir üstbilgi/altbilgi kullanılıp kullanılmadığını gösteren bir değeri ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | İlk sayfa için farklı bir üstbilgi/altbilgi kullanılıyorsa true; aksi takdirde false. |
|

### getOddAndEvenPagesHeaderFooter() {#getOddAndEvenPagesHeaderFooter--}
```
public final boolean getOddAndEvenPagesHeaderFooter()
```


Tek ve çift numaralı sayfalar için farklı üstbilgi/altbilgilerin kullanılıp kullanılmadığını gösteren bir değeri alır
sayfalar.
Not: Bu özelliği değiştirmek, içerikteki tüm bölümleri etkiler.


**Returns:**
boolean - Tek ve çift numaralı sayfalar için farklı üstbilgi/altbilgiler kullanılıyorsa true; aksi takdirde false.

### setOddAndEvenPagesHeaderFooter(boolean value) {#setOddAndEvenPagesHeaderFooter-boolean-}
```
public final void setOddAndEvenPagesHeaderFooter(boolean value)
```


Tek ve çift numaralı sayfalar için farklı üstbilgi/altbilgilerin kullanılıp kullanılmadığını gösteren bir değeri ayarlar
sayfalar.
Not: Bu özelliği değiştirmek, içerikteki tüm bölümleri etkiler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | Tek ve çift numaralı sayfalar için farklı üstbilgi/altbilgiler kullanılıyorsa true; aksi takdirde false. |
|

