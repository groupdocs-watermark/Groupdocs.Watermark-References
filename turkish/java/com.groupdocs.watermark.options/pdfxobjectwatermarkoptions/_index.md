---
title: "PdfXObjectWatermarkOptions"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "PDF belgesine XObject filigranı eklenirken filigran ekleme seçeneklerini temsil eder."
type: docs
weight: 34
url: /tr/java/com.groupdocs.watermark.options/pdfxobjectwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfXObjectWatermarkOptions extends PdfWatermarkOptions
```

PDF belgesine XObject filigranı eklenirken filigran ekleme seçeneklerini temsil eder.

**Learn more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

Aşağıdaki örnek, bir PDF belgesinin belirli bir sayfasına damga eklemenin nasıl yapılacağını gösterir.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\doc.pdf", loadOptions);
>
>    ImageWatermark watermark = new ImageWatermark("C:\\watermark.png");
>
>    PdfXObjectWatermarkOptions options = new PdfXObjectWatermarkOptions();
>    options.setPageIndex(0);
>
>    watermarker.add(watermark, options);
>    watermarker.save("C:\\watermarked_doc.pdf");
>    watermark.close();
>    watermarker.close();
>  
> ```
> ````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [PdfXObjectWatermarkOptions()](#PdfXObjectWatermarkOptions--) | `[PdfXObjectWatermarkOptions](../../com.groupdocs.watermark.options/pdfxobjectwatermarkoptions)` sınıfının yeni bir örneğini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | Filigranı eklemek için sayfa dizinini alır. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | Filigranı eklemek için sayfa dizinini ayarlar. |
|
### PdfXObjectWatermarkOptions() {#PdfXObjectWatermarkOptions--}
```
public PdfXObjectWatermarkOptions()
```


`[PdfXObjectWatermarkOptions](../../com.groupdocs.watermark.options/pdfxobjectwatermarkoptions)` sınıfının yeni bir örneğini başlatır.


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

