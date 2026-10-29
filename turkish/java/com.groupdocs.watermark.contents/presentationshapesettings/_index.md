---
title: "PresentationShapeSettings"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "PowerPoint belgesi için bir şekil filigranına uygulanabilecek ayarları temsil eder."
type: docs
weight: 95
url: /tr/java/com.groupdocs.watermark.contents/presentationshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class PresentationShapeSettings extends OfficeShapeSettings
```

PowerPoint belgesi için bir şekil filigranına uygulanabilecek ayarları temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [PresentationShapeSettings()](#PresentationShapeSettings--) | `[PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings)` sınıfının yeni bir örneğini başlatır. |
|
## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [UnreadableCharacter](#UnreadableCharacter) | <br /> |

|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isLocked()](#isLocked--) | PowerPoint'te şeklin düzenlenmesinin yasak olup olmadığını gösteren bir değeri alır. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | PowerPoint'te şeklin düzenlenmesinin yasak olup olmadığını gösteren bir değeri ayarlar. |
|
|  | [getProtectWithUnreadableCharacters()](#getProtectWithUnreadableCharacters--) | Metin filigran karakterlerinin okunamayan karakterlerle karıştırılıp karıştırılmadığını gösteren bir değeri alır. |
|
|  | [setProtectWithUnreadableCharacters(boolean value)](#setProtectWithUnreadableCharacters-boolean-) | Metin filigran karakterlerinin okunamayan karakterlerle karıştırılıp karıştırılmadığını gösteren bir değeri ayarlar. |
|
### PresentationShapeSettings() {#PresentationShapeSettings--}
```
public PresentationShapeSettings()
```


`[PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings)` sınıfının yeni bir örneğini başlatır.


### UnreadableCharacter {#UnreadableCharacter}
```
public static final char UnreadableCharacter
```


<br />



### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


PowerPoint'te şeklin düzenlenmesinin yasak olup olmadığını gösteren bir değeri alır.


**Returns:**
boolean - şekil düzenlemesi yasaksa `true`, şekil PowerPoint'te düzenlenebiliyorsa `false`.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


PowerPoint'te şeklin düzenlenmesinin yasak olup olmadığını gösteren bir değeri ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | `true` if shape editing should be forbidden, `false` if the shape can be edited in PowerPoint. |
|

### getProtectWithUnreadableCharacters() {#getProtectWithUnreadableCharacters--}
```
public final boolean getProtectWithUnreadableCharacters()
```


Metin filigran karakterlerinin okunamayan karakterlerle karıştırılıp karıştırılmadığını gösteren bir değeri alır.

Bu koruma yalnızca `#isLocked().isLocked()` `true` döndürdüğünde uygulanır.


**Returns:**
boolean - Metin filigran karakterlerinin okunamayan karakterlerle karıştırılıp karıştırılmadığını belirten bir değer.

### setProtectWithUnreadableCharacters(boolean value) {#setProtectWithUnreadableCharacters-boolean-}
```
public final void setProtectWithUnreadableCharacters(boolean value)
```


Metin filigran karakterlerinin okunamayan karakterlerle karıştırılıp karıştırılmadığını gösteren bir değeri ayarlar.

Bu koruma yalnızca `#isLocked().isLocked()` `true` döndürdüğünde uygulanır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | Metin filigran karakterlerinin okunamayan karakterlerle karıştırılıp karıştırılmadığını belirten bir değer. |
|

