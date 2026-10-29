---
title: "OfficeLineFormat"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Bir şekil çizgi biçimini temsil eder."
type: docs
weight: 47
url: /tr/java/com.groupdocs.watermark.contents/officelineformat/
---
**Inheritance:**
java.lang.Object
```
public final class OfficeLineFormat
```

Bir şekil çizgi biçimini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [OfficeLineFormat()](#OfficeLineFormat--) | Yeni bir `[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat)` sınıfı örneği başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getWeight()](#getWeight--) | Bir şeklin yolunu çizen fırça kalınlığını alır. |
|
|  | [setWeight(double value)](#setWeight-double-) | Bir şeklin yolunu çizen fırça kalınlığını ayarlar. |
|
|  | [getColor()](#getColor--) | Çizginin rengini alır. |
|
|  | [setColor(Color value)](#setColor-com.groupdocs.watermark.watermarks.Color-) | Çizginin rengini ayarlar. |
|
|  | [getOpacity()](#getOpacity--) | Çizgi opaklığını alır. |
|
|  | [setOpacity(double value)](#setOpacity-double-) | Çizgi opaklığını ayarlar. |
|
|  | [getEnabled()](#getEnabled--) | Bir şeklin çizilip çizilmeyeceğini gösteren değeri alır. |
|
|  | [setEnabled(boolean value)](#setEnabled-boolean-) | Bir şeklin çizilip çizilmeyeceğini gösteren değeri ayarlar. |
|
|  | [getDashStyle()](#getDashStyle--) | Çizgi için nokta ve tire desenini alır. |
|
|  | [setDashStyle(int value)](#setDashStyle-int-) | Çizgi için nokta ve tire desenini ayarlar. |
|
|  | [getLineStyle()](#getLineStyle--) | Çizgi stilini alır. |
|
|  | [setLineStyle(int value)](#setLineStyle-int-) | Çizgi stilini ayarlar. |
|
|  | [getTransparency()](#getTransparency--) | <br /> |

|
|  | [getColorConsideringOpacity()](#getColorConsideringOpacity--) | <br /> |

|
### OfficeLineFormat() {#OfficeLineFormat--}
```
public OfficeLineFormat()
```


Yeni bir `[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat)` sınıfı örneği başlatır.


### getWeight() {#getWeight--}
```
public final double getWeight()
```


Bir şeklin yolunu çizen fırça kalınlığını alır.


**Returns:**
double - Çizgi kalınlığı puan cinsindendir. Varsayılan değer 0.75.

### setWeight(double value) {#setWeight-double-}
```
public final void setWeight(double value)
```


Bir şeklin yolunu çizen fırça kalınlığını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | double | Çizgi kalınlığı puan cinsindendir. Varsayılan değer 0.75. |
|

### getColor() {#getColor--}
```
public final Color getColor()
```


Çizginin rengini alır.

Varsayılan değer `[Color.getBlack()](../../com.groupdocs.watermark.watermarks/color#getBlack--)`'dir.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The color of the line.

### setColor(Color value) {#setColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setColor(Color value)
```


Çizginin rengini ayarlar.

Varsayılan değer `[Color.getBlack()](../../com.groupdocs.watermark.watermarks/color#getBlack--)`'dir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | Çizginin rengi. |
|

### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Çizgi opaklığını alır.


**Returns:**
double - Değer 0 ile 1 arasında olmalıdır. Varsayılan değer 1.

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


Çizgi opaklığını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | double | Değer 0 ile 1 arasında olmalıdır. Varsayılan değer 1. |
|

### getEnabled() {#getEnabled--}
```
public final boolean getEnabled()
```


Bir şeklin çizilip çizilmeyeceğini gösteren değeri alır.


**Returns:**
boolean - Varsayılan değer false'tur.

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Bir şeklin çizilip çizilmeyeceğini gösteren değeri ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | Varsayılan değer false'tur. |
|

### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


Çizgi için nokta ve tire desenini alır.

<br />



**Returns:**
int
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


Çizgi için nokta ve tire desenini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getLineStyle() {#getLineStyle--}
```
public final int getLineStyle()
```


Çizgi stilini alır.

Varsayılan değer `[OfficeLineStyle.Single](../../com.groupdocs.watermark.contents/officelinestyle#Single)`'dir.


**Returns:**
int - Çizgi stili.

### setLineStyle(int value) {#setLineStyle-int-}
```
public final void setLineStyle(int value)
```


Çizgi stilini ayarlar.

Varsayılan değer `[OfficeLineStyle.Single](../../com.groupdocs.watermark.contents/officelinestyle#Single)`'dir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Çizgi stili. |
|

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


<br />



**Returns:**
double
### getColorConsideringOpacity() {#getColorConsideringOpacity--}
```
public final Color getColorConsideringOpacity()
```


<br />



**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color)
