---
title: "PdfArtifactWatermarkOptions"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "PDF belgesine artefakt filigranı eklenirken filigran ekleme seçeneklerini temsil eder."
type: docs
weight: 29
url: /tr/java/com.groupdocs.watermark.options/pdfartifactwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfArtifactWatermarkOptions extends PdfWatermarkOptions
```

PDF belgesine artefakt filigranı eklenirken filigran ekleme seçeneklerini temsil eder.

**Leran more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

Aşağıdaki örnek, bir PDF belgesine görüntü artefakt damgası eklemenin nasıl yapılacağını gösterir.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.pdf", loadOptions);
>
>    ImageWatermark watermark = new ImageWatermark("D:\\icon.png");
>
>    PdfArtifactWatermarkOptions options = new PdfArtifactWatermarkOptions();
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
|  | [PdfArtifactWatermarkOptions()](#PdfArtifactWatermarkOptions--) | `[PdfArtifactWatermarkOptions](../../com.groupdocs.watermark.options/pdfartifactwatermarkoptions)` sınıfının yeni bir örneğini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | Filigranı eklemek için sayfa dizinini alır. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | Filigranı eklemek için sayfa dizinini ayarlar. |
|
### PdfArtifactWatermarkOptions() {#PdfArtifactWatermarkOptions--}
```
public PdfArtifactWatermarkOptions()
```


`[PdfArtifactWatermarkOptions](../../com.groupdocs.watermark.options/pdfartifactwatermarkoptions)` sınıfının yeni bir örneğini başlatır.


### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


Filigranı eklemek için sayfa dizinini alır.


**Returns:**
int - Filigranı eklemek için sayfa dizini.

### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


Filigranı eklemek için sayfa dizinini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Filigranı eklemek için sayfa dizini. |
|

