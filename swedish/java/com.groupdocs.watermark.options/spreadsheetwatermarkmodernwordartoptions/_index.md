---
title: "SpreadsheetWatermarkModernWordArtOptions"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar alternativ när modern ordkonst‑vattenstämpel läggs till i ett Spreadsheet-ark."
type: docs
weight: 58
url: /sv/java/com.groupdocs.watermark.options/spreadsheetwatermarkmodernwordartoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkBaseOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions)
```
public final class SpreadsheetWatermarkModernWordArtOptions extends SpreadsheetWatermarkBaseOptions
```

Representerar alternativ när modern ordkonst‑vattenstämpel läggs till i ett Spreadsheet-ark.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

Följande exempel visar hur man lägger till en modern WordArt-vattenstämpel i ett Excel-dokument.
>
> ````
> ```
>
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.xls", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    SpreadsheetWatermarkModernWordArtOptions options = new SpreadsheetWatermarkModernWordArtOptions();
>    options.setWorksheetIndex(-1); // default
>    options.setLocked(false); // default
>    
>    watermarker.save("D:\\watermarked_test.xlsx");
>    watermarker.close();
>  
> ```
> ````


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [SpreadsheetWatermarkModernWordArtOptions()](#SpreadsheetWatermarkModernWordArtOptions--) | Initierar en ny instans av klassen `[SpreadsheetWatermarkModernWordArtOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkmodernwordartoptions)`. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Hämtar indexet för arbetsbladet som vattenmärket ska läggas till på. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Ställer in indexet för arbetsbladet som vattenmärket ska läggas till på. |
|
### SpreadsheetWatermarkModernWordArtOptions() {#SpreadsheetWatermarkModernWordArtOptions--}
```
public SpreadsheetWatermarkModernWordArtOptions()
```


Initierar en ny instans av klassen `[SpreadsheetWatermarkModernWordArtOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkmodernwordartoptions)`.


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

