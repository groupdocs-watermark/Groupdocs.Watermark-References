---
title: "PdfAnnotationWatermarkOptions"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "PDF belgesine açıklama filigranı eklenirken filigran ekleme seçeneklerini temsil eder."
type: docs
weight: 28
url: /tr/java/com.groupdocs.watermark.options/pdfannotationwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfAnnotationWatermarkOptions extends PdfWatermarkOptions
```

PDF belgesine açıklama filigranı eklenirken filigran ekleme seçeneklerini temsil eder.

**Learn more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

Aşağıdaki örnek, bir PDF belgesine görüntü açıklama filigranı eklemenin nasıl yapılacağını gösterir.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.pdf", loadOptions);
>
>    ImageWatermark watermark = new ImageWatermark("D:\\icon.png");
>
>    PdfAnnotationWatermarkOptions options = new PdfAnnotationWatermarkOptions();
>    options.setPageIndex(-1); // default - all pages
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.pdf");
>    watermark.close();
>    watermarker.close();
>  
> ```
> ````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [PdfAnnotationWatermarkOptions()](#PdfAnnotationWatermarkOptions--) | Yeni bir `[PdfAnnotationWatermarkOptions](../../com.groupdocs.watermark.options/pdfannotationwatermarkoptions)` sınıfı örneği başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | Filigranı eklemek için sayfa dizinini alır. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | Filigranı eklemek için sayfa dizinini ayarlar. |
|
|  | [getPrintOnly()](#getPrintOnly--) | Açıklamanın yazdırılıp yazdırılmayacağını, ancak pdf görüntüleme uygulamasında gösterilmeyeceğini belirten değeri al. |
|
|  | [setPrintOnly(boolean value)](#setPrintOnly-boolean-) | Açıklamanın yazdırılıp yazdırılmayacağını, ancak pdf görüntüleme uygulamasında gösterilmeyeceğini belirten değeri ayarlar. |
|
### PdfAnnotationWatermarkOptions() {#PdfAnnotationWatermarkOptions--}
```
public PdfAnnotationWatermarkOptions()
```


Yeni bir `[PdfAnnotationWatermarkOptions](../../com.groupdocs.watermark.options/pdfannotationwatermarkoptions)` sınıfı örneği başlatır.


### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


Filigranı eklemek için sayfa dizinini alır.


**Returns:**
int - Filigranı eklemek için sayfa dizini.

<br />

*** ** * ** ***

-1 means all pages.

<br />


### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


Filigranı eklemek için sayfa dizinini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Filigranı eklemek için sayfa dizini. |

<br />

*** ** * ** ***

-1 means all pages.

<br />

|

### getPrintOnly() {#getPrintOnly--}
```
public final boolean getPrintOnly()
```


Açıklamanın yazdırılıp yazdırılmayacağını, ancak pdf görüntüleme uygulamasında gösterilmeyeceğini belirten değeri al.


**Returns:**
boolean - Açıklamanın yazdırılıp yazdırılmayacağını, ancak pdf görüntüleme uygulamasında gösterilmeyeceğini belirten değer.

### setPrintOnly(boolean value) {#setPrintOnly-boolean-}
```
public final void setPrintOnly(boolean value)
```


Açıklamanın yazdırılıp yazdırılmayacağını, ancak pdf görüntüleme uygulamasında gösterilmeyeceğini belirten değeri ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | Açıklamanın yazdırılıp yazdırılmayacağını, ancak pdf görüntüleme uygulamasında gösterilmeyeceğini belirten değer. |
|

