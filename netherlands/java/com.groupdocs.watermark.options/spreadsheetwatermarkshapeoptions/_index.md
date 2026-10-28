---
title: "SpreadsheetWatermarkShapeOptions"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt opties voor bij het toevoegen van een vormwatermerk aan een Spreadsheet-werkblad."
type: docs
weight: 60
url: /nl/java/com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkBaseOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions)
```
public final class SpreadsheetWatermarkShapeOptions extends SpreadsheetWatermarkBaseOptions
```

Stelt opties voor bij het toevoegen van een vormwatermerk aan een Spreadsheet-werkblad.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

Het volgende voorbeeld toont hoe u een watermerk toevoegt aan een specifiek werkblad van een Excel‑document.
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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [SpreadsheetWatermarkShapeOptions()](#SpreadsheetWatermarkShapeOptions--) | Initialiseert een nieuwe instantie van de `[SpreadsheetWatermarkShapeOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions)` klasse. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Haalt de index van het werkblad op waaraan het watermerk moet worden toegevoegd. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Stelt de index van het werkblad in waaraan het watermerk moet worden toegevoegd. |
|
|  | [getEffects()](#getEffects--) | Haalt een waarde van `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` of `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` op voor effecten die op het watermerk moeten worden toegepast. |
|
|  | [setEffects(ISpreadsheetWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-) | Haalt op of stelt een waarde van `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` of `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` in voor effecten die op het watermerk moeten worden toegepast. |
|
### SpreadsheetWatermarkShapeOptions() {#SpreadsheetWatermarkShapeOptions--}
```
public SpreadsheetWatermarkShapeOptions()
```


Initialiseert een nieuwe instantie van de `[SpreadsheetWatermarkShapeOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions)` klasse.


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

### getEffects() {#getEffects--}
```
public final ISpreadsheetWatermarkEffects getEffects()
```


Haalt een waarde van `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` of `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` op voor effecten die op het watermerk moeten worden toegepast.


**Returns:**
[ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) - The `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` or `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` for effects that should be applied to the watermark.

### setEffects(ISpreadsheetWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-}
```
public final void setEffects(ISpreadsheetWatermarkEffects value)
```


Haalt op of stelt een waarde van `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` of `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` in voor effecten die op het watermerk moeten worden toegepast.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) | De `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` of `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` voor effecten die op het watermerk moeten worden toegepast. |
|

