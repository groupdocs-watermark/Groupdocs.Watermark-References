---
title: "SpreadsheetBackgroundWatermarkOptions"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Bir elektronik tablo çalışma sayfasına filigranı arka plan olarak eklerken seçenekleri temsil eder."
type: docs
weight: 49
url: /tr/java/com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)
```
public final class SpreadsheetBackgroundWatermarkOptions extends SpreadsheetWatermarkOptions
```

Bir elektronik tablo çalışma sayfasına filigranı arka plan olarak eklerken seçenekleri temsil eder.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

Aşağıdaki örnek, bir Excel belge sayfasına metin filigranı ekleyerek arka plan olarak nasıl kullanılacağını gösterir.
>
> ````
> ```
>
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\Documents\\test.xlsx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36));
>
>    SpreadsheetBackgroundWatermarkOptions options = new SpreadsheetBackgroundWatermarkOptions();
>    options.setWorksheetIndex(-1); // default
>    options.setBackgroundWidth(800);
>    options.setBackgroundHeight(600);
>    
>    watermarker.save("C:\\Documents\\watermarked_test.xlsx");
>    watermarker.close();
>  
> ```
> ````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [SpreadsheetBackgroundWatermarkOptions()](#SpreadsheetBackgroundWatermarkOptions--) | Yeni bir `[SpreadsheetBackgroundWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions)` sınıfı örneği başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Filigranı ekleyeceğiniz çalışma sayfasının dizinini alın. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Filigranı eklemek için çalışma sayfasının indeksini ayarlar. |
|
|  | [getBackgroundWidth()](#getBackgroundWidth--) | Arka plan görüntüsünün istenen genişliğini piksel cinsinden alın. |
|
|  | [setBackgroundWidth(int value)](#setBackgroundWidth-int-) | Arka plan görüntüsünün istenen genişliğini piksel cinsinden ayarlar. |
|
|  | [getBackgroundHeight()](#getBackgroundHeight--) | Arka plan görüntüsünün istenen yüksekliğini piksel cinsinden alır veya ayarlar. |
|
|  | [setBackgroundHeight(int value)](#setBackgroundHeight-int-) | Arka plan görüntüsünün istenen yüksekliğini piksel cinsinden alır veya ayarlar. |
|
### SpreadsheetBackgroundWatermarkOptions() {#SpreadsheetBackgroundWatermarkOptions--}
```
public SpreadsheetBackgroundWatermarkOptions()
```


Yeni bir `[SpreadsheetBackgroundWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions)` sınıfı örneği başlatır.


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


Filigranı ekleyeceğiniz çalışma sayfasının dizinini alın.

-1 means every worksheet.


**Returns:**
int - Filigranı eklemek için çalışma sayfasının indeksi.

### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Filigranı eklemek için çalışma sayfasının indeksini ayarlar.

-1 means every worksheet.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Filigranı eklemek için çalışma sayfasının dizini. |
|

### getBackgroundWidth() {#getBackgroundWidth--}
```
public final int getBackgroundWidth()
```


Arka plan görüntüsünün istenen genişliğini piksel cinsinden alın.


**Returns:**
int - Arka plan görüntüsünün istenen genişliği piksel cinsinden.

### setBackgroundWidth(int value) {#setBackgroundWidth-int-}
```
public final void setBackgroundWidth(int value)
```


Arka plan görüntüsünün istenen genişliğini piksel cinsinden ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Arka plan görüntüsünün istenen genişliği piksel cinsinden. |
|

### getBackgroundHeight() {#getBackgroundHeight--}
```
public final int getBackgroundHeight()
```


Arka plan görüntüsünün istenen yüksekliğini piksel cinsinden alır veya ayarlar.


**Returns:**
int - Arka plan görüntüsünün istenen yüksekliği piksel cinsinden.

### setBackgroundHeight(int value) {#setBackgroundHeight-int-}
```
public final void setBackgroundHeight(int value)
```


Arka plan görüntüsünün istenen yüksekliğini piksel cinsinden alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Arka plan görüntüsünün istenen yüksekliği piksel cinsinden. |
|

