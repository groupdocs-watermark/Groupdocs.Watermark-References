---
title: "SpreadsheetWatermarkShapeOptions"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt Optionen dar, wenn ein Formwasserzeichen zu einem Arbeitsblatt einer Kalkulationstabelle hinzugefügt wird."
type: docs
weight: 60
url: /de/java/com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkBaseOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions)
```
public final class SpreadsheetWatermarkShapeOptions extends SpreadsheetWatermarkBaseOptions
```

Stellt Optionen dar, wenn ein Formwasserzeichen zu einem Arbeitsblatt einer Kalkulationstabelle hinzugefügt wird.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

Das folgende Beispiel demonstriert, wie man ein Wasserzeichen zu einem bestimmten Arbeitsblatt eines Excel-Dokuments hinzufügt.
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


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [SpreadsheetWatermarkShapeOptions()](#SpreadsheetWatermarkShapeOptions--) | Initialisiert eine neue Instanz der `[SpreadsheetWatermarkShapeOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions)` Klasse. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Liest den Index des Arbeitsblatts, dem das Wasserzeichen hinzugefügt wird. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Setzt den Index des Arbeitsblatts, dem das Wasserzeichen hinzugefügt wird. |
|
|  | [getEffects()](#getEffects--) | Liest einen Wert von `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` oder `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` für Effekte, die auf das Wasserzeichen angewendet werden sollen. |
|
|  | [setEffects(ISpreadsheetWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-) | Liest oder setzt einen Wert von `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` oder `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` für Effekte, die auf das Wasserzeichen angewendet werden sollen. |
|
### SpreadsheetWatermarkShapeOptions() {#SpreadsheetWatermarkShapeOptions--}
```
public SpreadsheetWatermarkShapeOptions()
```


Initialisiert eine neue Instanz der `[SpreadsheetWatermarkShapeOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions)` Klasse.


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


Liest den Index des Arbeitsblatts, dem das Wasserzeichen hinzugefügt wird.


**Returns:**
int - Der Index des Arbeitsblatts, dem das Wasserzeichen hinzugefügt wird.

<br />

*** ** * ** ***

-1 means every worksheet.

<br />


### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Setzt den Index des Arbeitsblatts, dem das Wasserzeichen hinzugefügt wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Der Index des Arbeitsblatts, dem das Wasserzeichen hinzugefügt wird. |

<br />

*** ** * ** ***

-1 means every worksheet.

<br />

|

### getEffects() {#getEffects--}
```
public final ISpreadsheetWatermarkEffects getEffects()
```


Liest einen Wert von `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` oder `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` für Effekte, die auf das Wasserzeichen angewendet werden sollen.


**Returns:**
[ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) - The `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` or `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` for effects that should be applied to the watermark.

### setEffects(ISpreadsheetWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-}
```
public final void setEffects(ISpreadsheetWatermarkEffects value)
```


Liest oder setzt einen Wert von `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` oder `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` für Effekte, die auf das Wasserzeichen angewendet werden sollen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) | Der `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` oder `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` für Effekte, die auf das Wasserzeichen angewendet werden sollen. |
|

