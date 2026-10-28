---
title: "SpreadsheetBackgroundWatermarkOptions"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt opties voor bij het toevoegen van het watermerk als achtergrond aan een Spreadsheet-werkblad."
type: docs
weight: 49
url: /nl/java/com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)
```
public final class SpreadsheetBackgroundWatermarkOptions extends SpreadsheetWatermarkOptions
```

Stelt opties voor bij het toevoegen van het watermerk als achtergrond aan een Spreadsheet-werkblad.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

Het volgende voorbeeld laat zien hoe u een tekstwatermerk toevoegt aan een werkblad van een Excel‑document als achtergrond.
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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [SpreadsheetBackgroundWatermarkOptions()](#SpreadsheetBackgroundWatermarkOptions--) | Initialiseert een nieuw exemplaar van de `[SpreadsheetBackgroundWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions)` klasse. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Haal de index van het werkblad op waaraan het watermerk moet worden toegevoegd. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Stelt de index van het werkblad in waaraan het watermerk moet worden toegevoegd. |
|
|  | [getBackgroundWidth()](#getBackgroundWidth--) | Haal de gewenste breedte van de achtergrondafbeelding op in pixels. |
|
|  | [setBackgroundWidth(int value)](#setBackgroundWidth-int-) | Stelt de gewenste breedte van de achtergrondafbeelding in pixels in. |
|
|  | [getBackgroundHeight()](#getBackgroundHeight--) | Haalt op of stelt de gewenste hoogte van de achtergrondafbeelding in pixels in. |
|
|  | [setBackgroundHeight(int value)](#setBackgroundHeight-int-) | Haalt op of stelt de gewenste hoogte van de achtergrondafbeelding in pixels in. |
|
### SpreadsheetBackgroundWatermarkOptions() {#SpreadsheetBackgroundWatermarkOptions--}
```
public SpreadsheetBackgroundWatermarkOptions()
```


Initialiseert een nieuw exemplaar van de `[SpreadsheetBackgroundWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions)` klasse.


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


Haal de index van het werkblad op waaraan het watermerk moet worden toegevoegd.

-1 means every worksheet.


**Returns:**
int - De index van het werkblad waaraan het watermerk moet worden toegevoegd.

### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Stelt de index van het werkblad in waaraan het watermerk moet worden toegevoegd.

-1 means every worksheet.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | De index van het werkblad waaraan het watermerk moet worden toegevoegd. |
|

### getBackgroundWidth() {#getBackgroundWidth--}
```
public final int getBackgroundWidth()
```


Haal de gewenste breedte van de achtergrondafbeelding op in pixels.


**Returns:**
int - De gewenste breedte van de achtergrondafbeelding in pixels.

### setBackgroundWidth(int value) {#setBackgroundWidth-int-}
```
public final void setBackgroundWidth(int value)
```


Stelt de gewenste breedte van de achtergrondafbeelding in pixels in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | De gewenste breedte van de achtergrondafbeelding in pixels. |
|

### getBackgroundHeight() {#getBackgroundHeight--}
```
public final int getBackgroundHeight()
```


Haalt op of stelt de gewenste hoogte van de achtergrondafbeelding in pixels in.


**Returns:**
int - De gewenste hoogte van de achtergrondafbeelding in pixels.

### setBackgroundHeight(int value) {#setBackgroundHeight-int-}
```
public final void setBackgroundHeight(int value)
```


Haalt op of stelt de gewenste hoogte van de achtergrondafbeelding in pixels in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | De gewenste hoogte van de achtergrondafbeelding in pixels. |
|

