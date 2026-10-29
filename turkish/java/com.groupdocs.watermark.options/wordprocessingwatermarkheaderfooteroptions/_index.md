---
title: "WordProcessingWatermarkHeaderFooterOptions"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Filigranı bir Word bölüm başlığı/altbilgisine eklerken seçenekleri temsil eder."
type: docs
weight: 74
url: /tr/java/com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkHeaderFooterOptions extends WordProcessingWatermarkBaseOptions
```

Filigranı bir Word bölüm başlığı/altbilgisine eklerken seçenekleri temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [WordProcessingWatermarkHeaderFooterOptions()](#WordProcessingWatermarkHeaderFooterOptions--) | Yeni bir `[WordProcessingWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions)` sınıfı örneği başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getSectionIndex()](#getSectionIndex--) | Filigranı eklemek için bölümün dizinini alır. |
|
|  | [setSectionIndex(int value)](#setSectionIndex-int-) | Filigranı eklemek için bölümün dizinini ayarlar. |
|
|  | [getHeaderFooterType()](#getHeaderFooterType--) | Filigranı eklemek için başlık veya altbilgi türünü tanımlayan değeri alır. |
|
|  | [setHeaderFooterType(int value)](#setHeaderFooterType-int-) | Filigranı eklemek için başlık veya altbilgi türünü tanımlayan değeri ayarlar. |
|
### WordProcessingWatermarkHeaderFooterOptions() {#WordProcessingWatermarkHeaderFooterOptions--}
```
public WordProcessingWatermarkHeaderFooterOptions()
```


Yeni bir `[WordProcessingWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions)` sınıfı örneği başlatır.


### getSectionIndex() {#getSectionIndex--}
```
public final int getSectionIndex()
```


Filigranı eklemek için bölümün dizinini alır.


**Returns:**
int - Filigranı eklemek için bir bölümün dizini.

<br />

*** ** * ** ***

-1 means all sections.

<br />


### setSectionIndex(int value) {#setSectionIndex-int-}
```
public final void setSectionIndex(int value)
```


Filigranı eklemek için bölümün dizinini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Filigranı eklemek için bir bölümün dizini. |

<br />

*** ** * ** ***

-1 means all sections.

<br />

|

### getHeaderFooterType() {#getHeaderFooterType--}
```
public final int getHeaderFooterType()
```


Filigranı eklemek için başlık veya altbilgi türünü tanımlayan değeri alır.


**Returns:**
int - Filigranı eklemek için başlık veya altbilgi türünü tanımlayan `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` tipindeki değer.

### setHeaderFooterType(int value) {#setHeaderFooterType-int-}
```
public final void setHeaderFooterType(int value)
```


Filigranı eklemek için başlık veya altbilgi türünü tanımlayan değeri ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | int | Filigranı eklemek için başlık veya altbilgi türünü tanımlayan `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` tipindeki değer. |
|

