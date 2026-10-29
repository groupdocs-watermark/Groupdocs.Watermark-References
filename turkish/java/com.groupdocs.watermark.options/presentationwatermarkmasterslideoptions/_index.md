---
title: "PresentationWatermarkMasterSlideOptions"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Sunum belgesi ana slaytına filigran eklenirken seçenekleri temsil eder."
type: docs
weight: 43
url: /tr/java/com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)
```
public final class PresentationWatermarkMasterSlideOptions extends PresentationWatermarkBaseSlideOptions
```

Sunum belgesi ana slaytına filigran eklenirken seçenekleri temsil eder.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

`[PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)` içindeki kullanım örneklerine bakın.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [PresentationWatermarkMasterSlideOptions()](#PresentationWatermarkMasterSlideOptions--) | Yeni bir `[PresentationWatermarkMasterSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions)` sınıfı örneği başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getMasterSlideIndex()](#getMasterSlideIndex--) | Filigranın ekleneceği ana slaytın dizinini alır. |
|
|  | [setMasterSlideIndex(int value)](#setMasterSlideIndex-int-) | Filigranın ekleneceği ana slaytın dizinini ayarlar. |
|
### PresentationWatermarkMasterSlideOptions() {#PresentationWatermarkMasterSlideOptions--}
```
public PresentationWatermarkMasterSlideOptions()
```


Yeni bir `[PresentationWatermarkMasterSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions)` sınıfı örneği başlatır.


### getMasterSlideIndex() {#getMasterSlideIndex--}
```
public final int getMasterSlideIndex()
```


Filigranın ekleneceği ana slaytın dizinini alır.


**Returns:**
int - Filigranın ekleneceği ana slaytın dizini.

<br />

*** ** * ** ***

-1 means all slides.

<br />


### setMasterSlideIndex(int value) {#setMasterSlideIndex-int-}
```
public final void setMasterSlideIndex(int value)
```


Filigranın ekleneceği ana slaytın dizinini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Filigranın ekleneceği ana slaytın dizini. |

<br />

*** ** * ** ***

-1 means all slides.

<br />

|

