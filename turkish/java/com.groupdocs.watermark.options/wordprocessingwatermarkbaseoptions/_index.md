---
title: "WordProcessingWatermarkBaseOptions"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Bir Word belgesine filigran ekleme seçenekleri için temel sınıf."
type: docs
weight: 73
url: /tr/java/com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions)
```
public abstract class WordProcessingWatermarkBaseOptions extends WordProcessingWatermarkOptions
```

Bir Word belgesine filigran ekleme seçenekleri için temel sınıf.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isLocked()](#isLocked--) | Word'de şeklin düzenlenmesinin yasak olup olmadığını gösteren bir değeri alır. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Word'de şeklin düzenlenmesinin yasak olup olmadığını gösteren bir değeri ayarlar. |
|
|  | [getLockType()](#getLockType--) | Filigran kilitleme tipini alır. |
|
|  | [setLockType(int value)](#setLockType-int-) | Filigran kilitleme tipini ayarlar. |
|
|  | [getPassword()](#getPassword--) | Filigranı kilitlemek için kullanılan bir şifreyi alır. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Filigranı kilitlemek için kullanılan bir şifreyi ayarlar. |
|
|  | [getName()](#getName--) | Bir şeklin adını alır. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Bir şeklin adını ayarlar. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Bir şekille ilişkilendirilecek açıklayıcı (alternatif) metni alır. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Bir şekille ilişkilendirilecek açıklayıcı (alternatif) metni ayarlar. |
|
| [getEffects()](#getEffects--) |  |
| [setEffects(IWordProcessingWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-) |  |
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Word'de şeklin düzenlenmesinin yasak olup olmadığını gösteren bir değeri alır.


**Returns:**
boolean - Değer true ise şekil düzenleme yasaklanır. Varsayılan olarak, değer false olduğunda şekil Word'de düzenlenebilir.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Word'de şeklin düzenlenmesinin yasak olup olmadığını gösteren bir değeri ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | Değer true ise şekil düzenleme yasaklanır. Varsayılan olarak, değer false olduğunda şekil Word'de düzenlenebilir. |
|

### getLockType() {#getLockType--}
```
public final int getLockType()
```


Filigran kilitleme tipini alır.


**Returns:**
int - Damganın `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)` kilitleme türü.

### setLockType(int value) {#setLockType-int-}
```
public final void setLockType(int value)
```


Filigran kilitleme tipini ayarlar.

`[WordProcessingLockType.AllowOnlyFormFields](../../com.groupdocs.watermark.options/wordprocessinglocktype#AllowOnlyFormFields)` değeri şununla birlikte kullanılamaz
`[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` tipinde bir nesne.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | int | Damganın `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)` kilitleme türü. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Filigranı kilitlemek için kullanılan bir şifreyi alır.


**Returns:**
java.lang.String - Damgayı kilitlemek için kullanılan bir şifre.

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Filigranı kilitlemek için kullanılan bir şifreyi ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Damgayı kilitlemek için kullanılan bir şifre. |
|

### getName() {#getName--}
```
public final String getName()
```


Bir şeklin adını alır.


**Returns:**
java.lang.String - Şekil adı.

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Bir şeklin adını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Şekil adı. |
|

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Bir şekille ilişkilendirilecek açıklayıcı (alternatif) metni alır.


**Returns:**
java.lang.String - Şekille ilişkilendirilecek açıklayıcı (alternatif) metin.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Bir şekille ilişkilendirilecek açıklayıcı (alternatif) metni ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Şekille ilişkilendirilecek açıklayıcı (alternatif) metin. |
|

### getEffects() {#getEffects--}
```
public final IWordProcessingWatermarkEffects getEffects()
```




**Returns:**
[IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects)
### setEffects(IWordProcessingWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-}
```
public final void setEffects(IWordProcessingWatermarkEffects value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects) |  |

