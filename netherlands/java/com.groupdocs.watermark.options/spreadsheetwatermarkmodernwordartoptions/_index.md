---
title: "SpreadsheetWatermarkModernWordArtOptions"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt opties voor bij het toevoegen van een modern woordkunst-watermerk aan een Spreadsheet-werkblad."
type: docs
weight: 58
url: /nl/java/com.groupdocs.watermark.options/spreadsheetwatermarkmodernwordartoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkBaseOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions)
```
public final class SpreadsheetWatermarkModernWordArtOptions extends SpreadsheetWatermarkBaseOptions
```

Stelt opties voor bij het toevoegen van een modern woordkunst-watermerk aan een Spreadsheet-werkblad.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

Het volgende voorbeeld laat zien hoe je een moderne WordArt-watermerk toevoegt aan een Excel-document.
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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [SpreadsheetWatermarkModernWordArtOptions()](#SpreadsheetWatermarkModernWordArtOptions--) | Initialiseert een nieuw exemplaar van de `[SpreadsheetWatermarkModernWordArtOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkmodernwordartoptions)` klasse. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Haalt de index van het werkblad op waaraan het watermerk moet worden toegevoegd. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Stelt de index van het werkblad in waaraan het watermerk moet worden toegevoegd. |
|
### SpreadsheetWatermarkModernWordArtOptions() {#SpreadsheetWatermarkModernWordArtOptions--}
```
public SpreadsheetWatermarkModernWordArtOptions()
```


Initialiseert een nieuw exemplaar van de `[SpreadsheetWatermarkModernWordArtOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkmodernwordartoptions)` klasse.


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

