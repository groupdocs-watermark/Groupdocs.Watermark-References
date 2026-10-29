---
title: "WordProcessingShapeSettings"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Word belgesi için şekil filigranına uygulanabilecek ayarları temsil eder."
type: docs
weight: 71
url: /tr/java/com.groupdocs.watermark.options/wordprocessingshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class WordProcessingShapeSettings extends OfficeShapeSettings
```

Word belgesi için şekil filigranına uygulanabilecek ayarları temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [WordProcessingShapeSettings()](#WordProcessingShapeSettings--) | Yeni bir `[WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings)` sınıf örneği oluşturur. |
|
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
|  | [getPageNumbers()](#getPageNumbers--) | Filigranı eklemek için sayfa numaralarını alır. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Filigranı eklemek için sayfa numaralarını ayarlar. |
|
### WordProcessingShapeSettings() {#WordProcessingShapeSettings--}
```
public WordProcessingShapeSettings()
```


Yeni bir `[WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings)` sınıf örneği oluşturur.


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
int - `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)` damga kilitleme türü.

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
|  | value | int | `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)` damga kilitleme türü. |
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

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Filigranı eklemek için sayfa numaralarını alır.


**Returns:**
int[] - Filigranı eklemek için sayfa numaraları.

<br />

*** ** * ** ***

Tüm sayılar 1'e eşit veya daha büyük olmalıdır. Bu özellik yalnızca damga bir belgeye eklendiğinde kullanılır. Bu değer null ise, damga tüm sayfalara eklenir.

<br />


### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Filigranı eklemek için sayfa numaralarını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int[] | Filigranı eklemek için sayfa numaraları. |

<br />

*** ** * ** ***

Tüm sayılar 1'e eşit veya daha büyük olmalıdır. Bu özellik yalnızca damga bir belgeye eklendiğinde kullanılır. Bu değer null ise, damga tüm sayfalara eklenir.

<br />

|

