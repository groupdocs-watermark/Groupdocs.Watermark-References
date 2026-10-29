---
title: "SpreadsheetWatermarkShapeOptions"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar alternativ när en formvattenstämpel läggs till i ett Spreadsheet-ark."
type: docs
weight: 60
url: /sv/java/com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkBaseOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions)
```
public final class SpreadsheetWatermarkShapeOptions extends SpreadsheetWatermarkBaseOptions
```

Representerar alternativ när en formvattenstämpel läggs till i ett Spreadsheet-ark.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

Följande exempel visar hur man lägger till ett vattenmärke på ett specifikt arbetsblad i ett Excel-dokument.
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


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [SpreadsheetWatermarkShapeOptions()](#SpreadsheetWatermarkShapeOptions--) | Initierar en ny instans av `[SpreadsheetWatermarkShapeOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions)`-klassen. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Hämtar indexet för arbetsbladet som vattenmärket ska läggas till på. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Ställer in indexet för arbetsbladet som vattenmärket ska läggas till på. |
|
|  | [getEffects()](#getEffects--) | Hämtar ett värde av `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` eller `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` för effekter som ska tillämpas på vattenmärket. |
|
|  | [setEffects(ISpreadsheetWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-) | Hämtar eller anger ett värde av `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` eller `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` för effekter som ska tillämpas på vattenmärket. |
|
### SpreadsheetWatermarkShapeOptions() {#SpreadsheetWatermarkShapeOptions--}
```
public SpreadsheetWatermarkShapeOptions()
```


Initierar en ny instans av `[SpreadsheetWatermarkShapeOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions)`-klassen.


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


Hämtar indexet för arbetsbladet som vattenmärket ska läggas till på.


**Returns:**
int - Indexet för arbetsbladet som vattenmärket ska läggas till på.

<br />

*** ** * ** ***

-1 means every worksheet.

<br />


### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Ställer in indexet för arbetsbladet som vattenmärket ska läggas till på.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int | Indexet för arbetsbladet som vattenmärket ska läggas till på. |

<br />

*** ** * ** ***

-1 means every worksheet.

<br />

|

### getEffects() {#getEffects--}
```
public final ISpreadsheetWatermarkEffects getEffects()
```


Hämtar ett värde av `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` eller `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` för effekter som ska tillämpas på vattenmärket.


**Returns:**
[ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) - The `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` or `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` for effects that should be applied to the watermark.

### setEffects(ISpreadsheetWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-}
```
public final void setEffects(ISpreadsheetWatermarkEffects value)
```


Hämtar eller anger ett värde av `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` eller `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` för effekter som ska tillämpas på vattenmärket.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) | Den `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` eller `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` för effekter som ska tillämpas på vattenstämpeln. |
|

