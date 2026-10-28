---
title: "SpreadsheetWatermarkHeaderFooterOptions"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt opties voor bij het toevoegen van het watermerk aan een Spreadsheet-kop-/voettekst."
type: docs
weight: 57
url: /nl/java/com.groupdocs.watermark.options/spreadsheetwatermarkheaderfooteroptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)
```
public final class SpreadsheetWatermarkHeaderFooterOptions extends SpreadsheetWatermarkOptions
```

Stelt opties voor bij het toevoegen van het watermerk aan een Spreadsheet-kop-/voettekst.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

Het volgende voorbeeld toont hoe een tekstwatermerk toe te voegen aan de header van een Excel-werkblad.
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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [SpreadsheetWatermarkHeaderFooterOptions()](#SpreadsheetWatermarkHeaderFooterOptions--) | Initialiseert een nieuw exemplaar van de `[SpreadsheetWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkheaderfooteroptions)` klasse. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Haalt de index van het werkblad op waaraan het watermerk moet worden toegevoegd. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Stelt de index van het werkblad in waaraan het watermerk moet worden toegevoegd. |
|
### SpreadsheetWatermarkHeaderFooterOptions() {#SpreadsheetWatermarkHeaderFooterOptions--}
```
public SpreadsheetWatermarkHeaderFooterOptions()
```


Initialiseert een nieuw exemplaar van de `[SpreadsheetWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkheaderfooteroptions)` klasse.


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


Haalt de index van het werkblad op waaraan het watermerk moet worden toegevoegd.


**Returns:**
int - De index van het werkblad waaraan het watermerk moet worden toegevoegd.

<br />

*** ** * ** ***

-1 means every worksheet.

<br />


### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Stelt de index van het werkblad in waaraan het watermerk moet worden toegevoegd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | De index van het werkblad waaraan het watermerk moet worden toegevoegd. |

<br />

*** ** * ** ***

-1 means every worksheet.

<br />

|

