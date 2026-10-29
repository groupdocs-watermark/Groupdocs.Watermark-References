---
title: "Margins"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Bir nesnenin her kenarı için kenar boşluğu ayarlarını temsil eder."
type: docs
weight: 15
url: /tr/java/com.groupdocs.watermark.watermarks/margins/
---
**Inheritance:**
java.lang.Object
```
public class Margins
```

Bir nesnenin her kenarı için kenar boşluğu ayarlarını temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [Margins()](#Margins--) | `[Margins](../../com.groupdocs.watermark.watermarks/margins)` sınıfının yeni bir örneğini başlatır. |
|
|  | [Margins(int marginType, double left, double right, double top, double bottom)](#Margins-int-double-double-double-double-) | Belirtilen tip, konum ve boyutla `[Margins](../../com.groupdocs.watermark.watermarks/margins)` sınıfının yeni bir örneğini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getMarginType()](#getMarginType--) | Alır `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. |
|
|  | [setMarginType(int value)](#setMarginType-int-) | Ayarlar `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. |
|
|  | [getLeft()](#getLeft--) | Sol kenar boşluğunu alır. |
|
|  | [setLeft(double value)](#setLeft-double-) | Sol kenar boşluğunu ayarlar. |
|
|  | [getRight()](#getRight--) | Sağ kenar boşluğunu alır. |
|
|  | [setRight(double value)](#setRight-double-) | Sağ kenar boşluğunu ayarlar. |
|
|  | [getTop()](#getTop--) | Üst kenar boşluğunu alır. |
|
|  | [setTop(double value)](#setTop-double-) | Üst kenar boşluğunu ayarlar. |
|
|  | [getBottom()](#getBottom--) | Alt kenar boşluğunu alır. |
|
|  | [setBottom(double value)](#setBottom-double-) | Alt kenar boşluğunu ayarlar. |
|
### Margins() {#Margins--}
```
public Margins()
```


`[Margins](../../com.groupdocs.watermark.watermarks/margins)` sınıfının yeni bir örneğini başlatır.


### Margins(int marginType, double left, double right, double top, double bottom) {#Margins-int-double-double-double-double-}
```
public Margins(int marginType, double left, double right, double top, double bottom)
```


Belirtilen tip, konum ve boyutla `[Margins](../../com.groupdocs.watermark.watermarks/margins)` sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | marginType | int | Bu `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. Kenar boşluğu değerlerinin nasıl yorumlanacağını belirtir. |
|
|  | sol | double | Sol kenar boşluğu değeri. |
|
|  | sağ | double | Sağ kenar boşluğu değeri. |
|
|  | üst | double | Üst kenar boşluğu değeri. |
|
|  | alt | double | Alt kenar boşluğu değeri. |
|

### getMarginType() {#getMarginType--}
```
public final int getMarginType()
```


Alır `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. Bu özelliğe yeni bir değer atandığında, tüm kenar boşlukları otomatik olarak varsayılan değerlerine (sıfır) döner.

Varsayılan değer `[MarginType.Absolute](../../com.groupdocs.watermark.watermarks/margintype#Absolute)`'dır.


**Returns:**
int - Kenar boşluklarının nasıl yorumlanacağını belirten değer.

### setMarginType(int value) {#setMarginType-int-}
```
public final void setMarginType(int value)
```


Ayarlar `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. Bu özelliğe yeni bir değer atandığında, tüm kenar boşlukları otomatik olarak varsayılan değerlerine (sıfır) döner.

Varsayılan değer `[MarginType.Absolute](../../com.groupdocs.watermark.watermarks/margintype#Absolute)`'dır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Kenar boşluklarının nasıl yorumlanacağını belirten değer. |
|

### getLeft() {#getLeft--}
```
public final double getLeft()
```


Sol kenar boşluğunu alır.


**Returns:**
double - Üst öğenin sol kenarından yatay offset.

### setLeft(double value) {#setLeft-double-}
```
public final void setLeft(double value)
```


Sol kenar boşluğunu ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | double | Üst öğenin sol kenarından yatay offset. |
|

### getRight() {#getRight--}
```
public final double getRight()
```


Sağ kenar boşluğunu alır.


**Returns:**
double - Üst öğenin sağ kenarından yatay offset.

### setRight(double value) {#setRight-double-}
```
public final void setRight(double value)
```


Sağ kenar boşluğunu ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | double | Üst öğenin sağ kenarından yatay offset. |
|

### getTop() {#getTop--}
```
public final double getTop()
```


Üst kenar boşluğunu alır.


**Returns:**
double - Üst öğenin üst kenarından yatay offset.

### setTop(double value) {#setTop-double-}
```
public final void setTop(double value)
```


Üst kenar boşluğunu ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | double | Üst öğenin üst kenarından yatay offset. |
|

### getBottom() {#getBottom--}
```
public final double getBottom()
```


Alt kenar boşluğunu alır.


**Returns:**
double - Üst öğenin alt kenarından yatay offset.

### setBottom(double value) {#setBottom-double-}
```
public final void setBottom(double value)
```


Alt kenar boşluğunu ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | double | Üst öğenin alt kenarından yatay offset. |
|

