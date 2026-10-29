---
title: "SpreadsheetBackgroundWatermarkOptions"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar alternativ när vattenstämpeln läggs till som bakgrund i ett Spreadsheet-ark."
type: docs
weight: 49
url: /sv/java/com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)
```
public final class SpreadsheetBackgroundWatermarkOptions extends SpreadsheetWatermarkOptions
```

Representerar alternativ när vattenstämpeln läggs till som bakgrund i ett Spreadsheet-ark.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

Följande exempel demonstrerar hur man lägger till ett textvattenstämpel på ett Excel-dokumentark som bakgrund.
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


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [SpreadsheetBackgroundWatermarkOptions()](#SpreadsheetBackgroundWatermarkOptions--) | Initierar en ny instans av klassen `[SpreadsheetBackgroundWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions)`. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Hämta indexet för arbetsbladet som vattenstämpeln ska läggas till. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Ställer in indexet för arbetsbladet som vattenmärket ska läggas till på. |
|
|  | [getBackgroundWidth()](#getBackgroundWidth--) | Hämta den önskade bredden på bakgrundsbilden i pixlar. |
|
|  | [setBackgroundWidth(int value)](#setBackgroundWidth-int-) | Ställer in den önskade bredden på bakgrundsbilden i pixlar. |
|
|  | [getBackgroundHeight()](#getBackgroundHeight--) | Hämtar eller anger den önskade höjden på bakgrundsbilden i pixlar. |
|
|  | [setBackgroundHeight(int value)](#setBackgroundHeight-int-) | Hämtar eller anger den önskade höjden på bakgrundsbilden i pixlar. |
|
### SpreadsheetBackgroundWatermarkOptions() {#SpreadsheetBackgroundWatermarkOptions--}
```
public SpreadsheetBackgroundWatermarkOptions()
```


Initierar en ny instans av klassen `[SpreadsheetBackgroundWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions)`.


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


Hämta indexet för arbetsbladet som vattenstämpeln ska läggas till.

-1 means every worksheet.


**Returns:**
int - Indexet för arbetsbladet som vattenmärket ska läggas till på.

### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Ställer in indexet för arbetsbladet som vattenmärket ska läggas till på.

-1 means every worksheet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int | Indexet för arbetsbladet som vattenmärket ska läggas till på. |
|

### getBackgroundWidth() {#getBackgroundWidth--}
```
public final int getBackgroundWidth()
```


Hämta den önskade bredden på bakgrundsbilden i pixlar.


**Returns:**
int - Den önskade bredden på bakgrundsbilden i pixlar.

### setBackgroundWidth(int value) {#setBackgroundWidth-int-}
```
public final void setBackgroundWidth(int value)
```


Ställer in den önskade bredden på bakgrundsbilden i pixlar.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int | Den önskade bredden på bakgrundsbilden i pixlar. |
|

### getBackgroundHeight() {#getBackgroundHeight--}
```
public final int getBackgroundHeight()
```


Hämtar eller anger den önskade höjden på bakgrundsbilden i pixlar.


**Returns:**
int - Den önskade höjden på bakgrundsbilden i pixlar.

### setBackgroundHeight(int value) {#setBackgroundHeight-int-}
```
public final void setBackgroundHeight(int value)
```


Hämtar eller anger den önskade höjden på bakgrundsbilden i pixlar.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int | Den önskade höjden på bakgrundsbilden i pixlar. |
|

