---
title: "PresentationWatermarkBaseSlideOptions"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Sunum belgesine filigran ekleme seçenekleri için temel sınıf."
type: docs
weight: 39
url: /tr/java/com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions)
```
public abstract class PresentationWatermarkBaseSlideOptions extends PresentationWatermarkOptions
```

Sunum belgesine filigran ekleme seçenekleri için temel sınıf.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

Aşağıdaki örnek, bir Power Point sunumunun farklı hizmet slaytlarına filigran eklemenin nasıl yapılacağını gösterir.
>
> ````
> ```
>
>    PresentationLoadOptions loadOptions = new PresentationLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.pptx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 8));
>
>    // Add watermark to all master slides
>    PresentationWatermarkMasterSlideOptions masterSlideOptions = new PresentationWatermarkMasterSlideOptions();
>    masterSlideOptions.setMasterSlideIndex(-1); // default
>    watermarker.add(watermark, masterSlideOptions);
>    
>    // Add watermark to all layout slides
>    PresentationWatermarkLayoutSlideOptions layoutSlideOptions = new PresentationWatermarkLayoutSlideOptions();
>    layoutSlideOptions.setLayoutSlideIndex(-1); // default
>    watermarker.add(watermark, layoutSlideOptions);
>    
>    // Add watermark to all notes slides
>    PresentationWatermarkNoteSlideOptions noteSlideOptions = new PresentationWatermarkNoteSlideOptions();
>    noteSlideOptions.setSlideIndex(-1); // default
>    watermarker.add(watermark, noteSlideOptions);
>    
>    // Add watermark to handout master
>    PresentationWatermarkMasterHandoutSlideOptions masterHandoutSlideOptions = new PresentationWatermarkMasterHandoutSlideOptions();
>    watermarker.add(watermark, masterHandoutSlideOptions);
>    
>    // Add watermark to notes master
>    PresentationWatermarkMasterNotesSlideOptions masterNotesSlideOptions = new PresentationWatermarkMasterNotesSlideOptions();
>    watermarker.add(watermark, masterNotesSlideOptions);
>    
>    watermarker.save("D:\\watermarked_test.pptx");
>    watermarker.close();
>  
> ```
> ````


## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isLocked()](#isLocked--) | PowerPoint'te şeklin düzenlenmesinin yasak olup olmadığını gösteren bir değeri alır. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | PowerPoint'te şeklin düzenlenmesinin yasak olup olmadığını gösteren bir değeri ayarlar. |
|
|  | [getProtectWithUnreadableCharacters()](#getProtectWithUnreadableCharacters--) | Metin filigranı karakterlerinin okunamayan karakterlerle karıştırılıp karıştırılmadığını gösteren bir değeri alır veya ayarlar. |
|
|  | [setProtectWithUnreadableCharacters(boolean value)](#setProtectWithUnreadableCharacters-boolean-) | Metin filigranı karakterlerinin okunamayan karakterlerle karıştırılıp karıştırılmadığını gösteren bir değeri alır veya ayarlar. |
|
|  | [getName()](#getName--) | Bir şeklin adını alır. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Bir şeklin adını ayarlar. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Bir şekille ilişkilendirilecek açıklayıcı (alternatif) metni alır. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Bir şekille ilişkilendirilecek açıklayıcı (alternatif) metni ayarlar. |
|
|  | [getEffects()](#getEffects--) | Filigrana uygulanması gereken etkiler için `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` veya `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` değerini alır. |
|
|  | [setEffects(IPresentationWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.IPresentationWatermarkEffects-) | Filigrana uygulanması gereken etkiler için `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` veya `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` değerini ayarlar. |
|
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


PowerPoint'te şeklin düzenlenmesinin yasak olup olmadığını gösteren bir değeri alır.


**Returns:**
boolean - Değer true ise, şekil düzenlemesi yasaklanacaktır. Varsayılan olarak, değer false olduğunda, şekil PowerPoint'te düzenlenebilir.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


PowerPoint'te şeklin düzenlenmesinin yasak olup olmadığını gösteren bir değeri ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | Değer true ise, şekil düzenlemesi yasaklanacaktır. Varsayılan olarak, değer false olduğunda, şekil PowerPoint'te düzenlenebilir. |
|

### getProtectWithUnreadableCharacters() {#getProtectWithUnreadableCharacters--}
```
public final boolean getProtectWithUnreadableCharacters()
```


Metin filigranı karakterlerinin okunamayan karakterlerle karıştırılıp karıştırılmadığını gösteren bir değeri alır veya ayarlar.

Bu koruma yalnızca `#isLocked().isLocked()` `true` döndürdüğünde uygulanır.


**Returns:**
boolean - Metin filigran karakterlerinin okunamayan karakterlerle karıştırılıp karıştırılmadığını belirten bir değer.

### setProtectWithUnreadableCharacters(boolean value) {#setProtectWithUnreadableCharacters-boolean-}
```
public final void setProtectWithUnreadableCharacters(boolean value)
```


Metin filigranı karakterlerinin okunamayan karakterlerle karıştırılıp karıştırılmadığını gösteren bir değeri alır veya ayarlar.

Bu koruma yalnızca `#isLocked().isLocked()` `true` döndürdüğünde uygulanır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | Metin filigran karakterlerinin okunamayan karakterlerle karıştırılıp karıştırılmadığını belirten bir değer. |
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
public final IPresentationWatermarkEffects getEffects()
```


Filigrana uygulanması gereken etkiler için `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` veya `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` değerini alır.


**Returns:**
[IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) - The value of `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` or `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` for effects that should be applied to the watermark.

### setEffects(IPresentationWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.IPresentationWatermarkEffects-}
```
public final void setEffects(IPresentationWatermarkEffects value)
```


Filigrana uygulanması gereken etkiler için `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` veya `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` değerini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) | `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` veya `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` değerleri, filigrana uygulanması gereken efektler içindir. |
|

