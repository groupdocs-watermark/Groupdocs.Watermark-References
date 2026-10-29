---
title: "DiagramPageWatermarkOptions"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Visio belgesinin belirli bir sayfasına şekil filigranı eklerken filigran ekleme seçeneklerini temsil eder."
type: docs
weight: 11
url: /tr/java/com.groupdocs.watermark.options/diagrampagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.DiagramWatermarkOptions](../../com.groupdocs.watermark.options/diagramwatermarkoptions)
```
public final class DiagramPageWatermarkOptions extends DiagramWatermarkOptions
```

Visio belgesinin belirli bir sayfasına şekil filigranı eklerken filigran ekleme seçeneklerini temsil eder.

**Learn more:**

* [Add watermarks to diagram documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+diagram+documents)

Aşağıdaki örnek, bir Visio belgesinin ilk sayfasına korumalı bir filigran eklemenin nasıl yapılacağını gösterir.
>
> ````
> ```
>
>    DiagramLoadOptions loadOptions = new DiagramLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.vsdx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));
>
>    DiagramPageWatermarkOptions options = new DiagramPageWatermarkOptions();
>    options.setLocked(true);
>    options.setPageIndex(0);
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.vsdx");
>    watermarker.close();
>  
> ```
> ````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [DiagramPageWatermarkOptions()](#DiagramPageWatermarkOptions--) | Yeni bir `[DiagramPageWatermarkOptions](../../com.groupdocs.watermark.options/diagrampagewatermarkoptions)` sınıfı örneği başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | Filigranı eklemek için sayfa dizinini alır. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | Filigranı eklemek için sayfa dizinini ayarlar. |
|
### DiagramPageWatermarkOptions() {#DiagramPageWatermarkOptions--}
```
public DiagramPageWatermarkOptions()
```


Yeni bir `[DiagramPageWatermarkOptions](../../com.groupdocs.watermark.options/diagrampagewatermarkoptions)` sınıfı örneği başlatır.


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

