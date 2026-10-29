---
title: "SpreadsheetWatermarkHeaderFooterOptions"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar alternativ när vattenstämpeln läggs till i ett Spreadsheet sidhuvud/sidfot."
type: docs
weight: 57
url: /sv/java/com.groupdocs.watermark.options/spreadsheetwatermarkheaderfooteroptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)
```
public final class SpreadsheetWatermarkHeaderFooterOptions extends SpreadsheetWatermarkOptions
```

Representerar alternativ när vattenstämpeln läggs till i ett Spreadsheet sidhuvud/sidfot.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

Följande exempel visar hur man lägger till en textvattenstämpel i rubriken för ett Excel-ark.
>
> ````
> ```
>
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.xls", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    SpreadsheetWatermarkHeaderFooterOptions options = new SpreadsheetWatermarkHeaderFooterOptions();
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
|  | [SpreadsheetWatermarkHeaderFooterOptions()](#SpreadsheetWatermarkHeaderFooterOptions--) | Initierar en ny instans av klassen `[SpreadsheetWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkheaderfooteroptions)`. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Hämtar indexet för arbetsbladet som vattenmärket ska läggas till på. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Ställer in indexet för arbetsbladet som vattenmärket ska läggas till på. |
|
### SpreadsheetWatermarkHeaderFooterOptions() {#SpreadsheetWatermarkHeaderFooterOptions--}
```
public SpreadsheetWatermarkHeaderFooterOptions()
```


Initierar en ny instans av klassen `[SpreadsheetWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkheaderfooteroptions)`.


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

