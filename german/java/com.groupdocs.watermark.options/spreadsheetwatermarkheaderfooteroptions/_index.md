---
title: "SpreadsheetWatermarkHeaderFooterOptions"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt Optionen dar, wenn das Wasserzeichen zu einer Kopf- oder Fußzeile einer Kalkulationstabelle hinzugefügt wird."
type: docs
weight: 57
url: /de/java/com.groupdocs.watermark.options/spreadsheetwatermarkheaderfooteroptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)
```
public final class SpreadsheetWatermarkHeaderFooterOptions extends SpreadsheetWatermarkOptions
```

Stellt Optionen dar, wenn das Wasserzeichen zu einer Kopf- oder Fußzeile einer Kalkulationstabelle hinzugefügt wird.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

Das folgende Beispiel zeigt, wie man ein Text‑Wasserzeichen in die Kopfzeile eines Excel‑Arbeitsblatts einfügt.
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


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [SpreadsheetWatermarkHeaderFooterOptions()](#SpreadsheetWatermarkHeaderFooterOptions--) | Initialisiert eine neue Instanz der `[SpreadsheetWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkheaderfooteroptions)` Klasse. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Liest den Index des Arbeitsblatts, dem das Wasserzeichen hinzugefügt wird. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Setzt den Index des Arbeitsblatts, dem das Wasserzeichen hinzugefügt wird. |
|
### SpreadsheetWatermarkHeaderFooterOptions() {#SpreadsheetWatermarkHeaderFooterOptions--}
```
public SpreadsheetWatermarkHeaderFooterOptions()
```


Initialisiert eine neue Instanz der `[SpreadsheetWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkheaderfooteroptions)` Klasse.


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

