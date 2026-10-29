---
title: "OfficeImageEffects"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Ofis içeriği için bir görüntü filigranına uygulanabilecek efektleri temsil eder."
type: docs
weight: 45
url: /tr/java/com.groupdocs.watermark.contents/officeimageeffects/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IDocumentSpecificSettings](../../com.groupdocs.watermark.internal/idocumentspecificsettings)
```
public abstract class OfficeImageEffects implements IDocumentSpecificSettings
```

Ofis içeriği için bir görüntü filigranına uygulanabilecek efektleri temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getBorderLineFormat()](#getBorderLineFormat--) | Görüntü kenarı için satır biçimi ayarlarını alır. |
|
|  | [setBorderLineFormat(OfficeLineFormat value)](#setBorderLineFormat-com.groupdocs.watermark.contents.OfficeLineFormat-) | Görüntü kenarı için satır biçimi ayarlarını ayarlar. |
|
|  | [getGrayScale()](#getGrayScale--) | Bir resmin gri tonlamalı modda görüntülenip görüntülenmeyeceğini gösteren bir değeri alır. |
|
|  | [setGrayScale(boolean value)](#setGrayScale-boolean-) | Bir resmin gri tonlamalı modda görüntülenip görüntülenmeyeceğini gösteren bir değeri ayarlar. |
|
|  | [getChromaKey()](#getChromaKey--) | Şeffaf olarak işlenecek görüntünün renk değerini alır. |
|
|  | [setChromaKey(Color value)](#setChromaKey-com.groupdocs.watermark.watermarks.Color-) | Şeffaf olarak işlenecek görüntünün renk değerini ayarlar. |
|
|  | [getBrightness()](#getBrightness--) | Resmin parlaklığını alır. |
|
|  | [setBrightness(double value)](#setBrightness-double-) | Resmin parlaklığını ayarlar. |
|
|  | [getContrast()](#getContrast--) | Belirtilen resim için kontrastı alır. |
|
|  | [setContrast(double value)](#setContrast-double-) | Belirtilen resim için kontrastı ayarlar. |
|
### getBorderLineFormat() {#getBorderLineFormat--}
```
public final OfficeLineFormat getBorderLineFormat()
```


Görüntü kenarı için satır biçimi ayarlarını alır.


**Returns:**
[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat) - Instance of  OfficeLineFormat  class, representing shape line format.

### setBorderLineFormat(OfficeLineFormat value) {#setBorderLineFormat-com.groupdocs.watermark.contents.OfficeLineFormat-}
```
public final void setBorderLineFormat(OfficeLineFormat value)
```


Görüntü kenarı için satır biçimi ayarlarını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat) | OfficeLineFormat sınıfının bir örneği, şekil satır biçimini temsil eder. |
|

### getGrayScale() {#getGrayScale--}
```
public final boolean getGrayScale()
```


Bir resmin gri tonlamalı modda görüntülenip görüntülenmeyeceğini gösteren bir değeri alır.


**Returns:**
boolean - Varsayılan değer false'tur.

### setGrayScale(boolean value) {#setGrayScale-boolean-}
```
public final void setGrayScale(boolean value)
```


Bir resmin gri tonlamalı modda görüntülenip görüntülenmeyeceğini gösteren bir değeri ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | Varsayılan değer false'tur. |
|

### getChromaKey() {#getChromaKey--}
```
public final Color getChromaKey()
```


Şeffaf olarak işlenecek görüntünün renk değerini alır.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The default value is fully transparent color.

### setChromaKey(Color value) {#setChromaKey-com.groupdocs.watermark.watermarks.Color-}
```
public final void setChromaKey(Color value)
```


Şeffaf olarak işlenecek görüntünün renk değerini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | Varsayılan değer tamamen şeffaf renktir. |
|

### getBrightness() {#getBrightness--}
```
public final double getBrightness()
```


Resmin parlaklığını alır. Bu özelliğin değeri şu olmalıdır
0.0 (en karanlık) ile 1.0 (en parlak) arasında bir sayı olmalıdır.


**Returns:**
double - Varsayılan değer 0.5'tir.

### setBrightness(double value) {#setBrightness-double-}
```
public final void setBrightness(double value)
```


Resmin parlaklığını ayarlar. Bu özelliğin değeri şu olmalıdır
0.0 (en karanlık) ile 1.0 (en parlak) arasında bir sayı olmalıdır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | double | Varsayılan değer 0.5'tir. |
|

### getContrast() {#getContrast--}
```
public final double getContrast()
```


Belirtilen resmin kontrastını alır. Bu özelliğin değeri
0.0 (en düşük kontrast) ile 1.0 (en yüksek kontrast) arasında bir sayı olmalıdır.


**Returns:**
double - Varsayılan değer 0.5'tir.

### setContrast(double value) {#setContrast-double-}
```
public final void setContrast(double value)
```


Belirtilen resmin kontrastını ayarlar. Bu özelliğin değeri
0.0 (en düşük kontrast) ile 1.0 (en yüksek kontrast) arasında bir sayı olmalıdır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | double | Varsayılan değer 0.5'tir. |
|

