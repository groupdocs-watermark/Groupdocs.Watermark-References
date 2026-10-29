---
title: "WordProcessingWatermarkSectionOptions"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Şekil filigranını bir Word belge bölümüne eklerken seçenekleri temsil eder."
type: docs
weight: 77
url: /tr/java/com.groupdocs.watermark.options/wordprocessingwatermarksectionoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkSectionOptions extends WordProcessingWatermarkBaseOptions
```

Şekil filigranını bir Word belge bölümüne eklerken seçenekleri temsil eder.

**Learn more:**

* [Add watermarks to word processing documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+word+processing+documents)

Aşağıdaki örnek, bir Word belgesinin belirli bir bölümüne filigran eklemenin nasıl yapılacağını gösterir.
>
> ````
> ```
>
>    WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.doc", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    WordProcessingWatermarkSectionOptions options = new WordProcessingWatermarkSectionOptions();
>    options.setSectionIndex(0);
>    
>    watermarker.save("D:\\watermarked_test.doc");
>    watermarker.close();
>  
> ```
> ````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [WordProcessingWatermarkSectionOptions()](#WordProcessingWatermarkSectionOptions--) | Yeni bir `[WordProcessingWatermarkSectionOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarksectionoptions)` sınıf örneği oluşturur. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getSectionIndex()](#getSectionIndex--) | Filigranı eklemek için bölümün dizinini alır. |
|
|  | [setSectionIndex(int value)](#setSectionIndex-int-) | Filigranı eklemek için bölümün dizinini ayarlar. |
|
### WordProcessingWatermarkSectionOptions() {#WordProcessingWatermarkSectionOptions--}
```
public WordProcessingWatermarkSectionOptions()
```


Yeni bir `[WordProcessingWatermarkSectionOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarksectionoptions)` sınıf örneği oluşturur.


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

