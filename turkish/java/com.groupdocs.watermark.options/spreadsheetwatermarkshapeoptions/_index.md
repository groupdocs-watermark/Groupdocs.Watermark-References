---
title: "SpreadsheetWatermarkShapeOptions"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Bir elektronik tablo çalışma sayfasına şekil filigranı eklerken seçenekleri temsil eder."
type: docs
weight: 60
url: /tr/java/com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkBaseOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions)
```
public final class SpreadsheetWatermarkShapeOptions extends SpreadsheetWatermarkBaseOptions
```

Bir elektronik tablo çalışma sayfasına şekil filigranı eklerken seçenekleri temsil eder.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

Aşağıdaki örnek, bir Excel belgesinin belirli bir çalışma sayfasına filigran eklemeyi gösterir.
>
> ````
> ```
>
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.xls", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    SpreadsheetWatermarkShapeOptions options = new SpreadsheetWatermarkShapeOptions();
>    options.setWorksheetIndex(0);
>    
>    watermarker.save("D:\\watermarked_test.xlsx");
>    watermarker.close();
>  
> ```
> ````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [SpreadsheetWatermarkShapeOptions()](#SpreadsheetWatermarkShapeOptions--) | `[SpreadsheetWatermarkShapeOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions)` sınıfının yeni bir örneğini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Filigranı eklemek için çalışma sayfasının indeksini alır. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Filigranı eklemek için çalışma sayfasının indeksini ayarlar. |
|
|  | [getEffects()](#getEffects--) | `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` veya `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` için filigrana uygulanacak etkilerin değerini alır. |
|
|  | [setEffects(ISpreadsheetWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-) | `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` veya `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` için filigrana uygulanacak etkilerin değerini alır veya ayarlar. |
|
### SpreadsheetWatermarkShapeOptions() {#SpreadsheetWatermarkShapeOptions--}
```
public SpreadsheetWatermarkShapeOptions()
```


`[SpreadsheetWatermarkShapeOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions)` sınıfının yeni bir örneğini başlatır.


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


Filigranı eklemek için çalışma sayfasının indeksini alır.


**Returns:**
int - Filigranı eklemek için çalışma sayfasının indeksi.

<br />

*** ** * ** ***

-1 means every worksheet.

<br />


### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Filigranı eklemek için çalışma sayfasının indeksini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Filigranı eklemek için çalışma sayfasının dizini. |

<br />

*** ** * ** ***

-1 means every worksheet.

<br />

|

### getEffects() {#getEffects--}
```
public final ISpreadsheetWatermarkEffects getEffects()
```


`[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` veya `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` için filigrana uygulanacak etkilerin değerini alır.


**Returns:**
[ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) - The `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` or `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` for effects that should be applied to the watermark.

### setEffects(ISpreadsheetWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-}
```
public final void setEffects(ISpreadsheetWatermarkEffects value)
```


`[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` veya `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` için filigrana uygulanacak etkilerin değerini alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) | Filigrana uygulanması gereken etkiler için `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` veya `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)`. |
|

