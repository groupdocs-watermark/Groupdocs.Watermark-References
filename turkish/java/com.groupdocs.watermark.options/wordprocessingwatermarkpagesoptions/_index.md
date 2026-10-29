---
title: "WordProcessingWatermarkPagesOptions"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Filigranı Word belge sayfalarına eklerken seçenekleri temsil eder."
type: docs
weight: 76
url: /tr/java/com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkPagesOptions extends WordProcessingWatermarkBaseOptions
```

Filigranı Word belge sayfalarına eklerken seçenekleri temsil eder.

**Learn more:**

* [Add watermarks to word processing documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+word+processing+documents)

Aşağıdaki örnek, bir Word belgesinin belirli bir sayfasına filigran eklemenin nasıl yapılacağını gösterir.
>
> ````
> ```
>
>    WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.doc", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    WordProcessingWatermarkPagesOptions options = new WordProcessingWatermarkPagesOptions();
>    options.setPageNumbers(new int[] { 1 });
>    
>    watermarker.save("D:\\watermarked_test.doc");
>    watermarker.close();
>  
> ```
> ````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [WordProcessingWatermarkPagesOptions()](#WordProcessingWatermarkPagesOptions--) | Yeni bir `[WordProcessingWatermarkPagesOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions)` sınıfı örneği başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPageNumbers()](#getPageNumbers--) | Filigranı eklemek için sayfa numaralarını alır. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Filigranı eklemek için sayfa numaralarını ayarlar. |
|
### WordProcessingWatermarkPagesOptions() {#WordProcessingWatermarkPagesOptions--}
```
public WordProcessingWatermarkPagesOptions()
```


Yeni bir `[WordProcessingWatermarkPagesOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions)` sınıfı örneği başlatır.


### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Filigranı eklemek için sayfa numaralarını alır.


**Returns:**
int[] - Filigranı eklemek için sayfa numaraları.

<br />

*** ** * ** ***

Tüm sayılar 1'e eşit veya daha büyük olmalıdır. Bu özellik yalnızca bir belgeye filigran eklenirken kullanılır. Bu değer null veya boş ise, filigran tüm sayfalara eklenir.

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

Tüm sayılar 1'e eşit veya daha büyük olmalıdır. Bu özellik yalnızca bir belgeye filigran eklenirken kullanılır. Bu değer null veya boş ise, filigran tüm sayfalara eklenir.

<br />

|

