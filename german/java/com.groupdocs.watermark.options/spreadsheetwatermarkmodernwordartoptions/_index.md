---
title: "SpreadsheetWatermarkModernWordArtOptions"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt Optionen dar, wenn ein modernes WordArt-Wasserzeichen zu einem Arbeitsblatt einer Kalkulationstabelle hinzugefügt wird."
type: docs
weight: 58
url: /de/java/com.groupdocs.watermark.options/spreadsheetwatermarkmodernwordartoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkBaseOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions)
```
public final class SpreadsheetWatermarkModernWordArtOptions extends SpreadsheetWatermarkBaseOptions
```

Stellt Optionen dar, wenn ein modernes WordArt-Wasserzeichen zu einem Arbeitsblatt einer Kalkulationstabelle hinzugefügt wird.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

Das folgende Beispiel zeigt, wie man ein modernes WordArt-Wasserzeichen zu einem Excel-Dokument hinzufügt.
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


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [SpreadsheetWatermarkModernWordArtOptions()](#SpreadsheetWatermarkModernWordArtOptions--) | Initialisiert eine neue Instanz der `[SpreadsheetWatermarkModernWordArtOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkmodernwordartoptions)` Klasse. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Liest den Index des Arbeitsblatts, dem das Wasserzeichen hinzugefügt wird. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Setzt den Index des Arbeitsblatts, dem das Wasserzeichen hinzugefügt wird. |
|
### SpreadsheetWatermarkModernWordArtOptions() {#SpreadsheetWatermarkModernWordArtOptions--}
```
public SpreadsheetWatermarkModernWordArtOptions()
```


Initialisiert eine neue Instanz der `[SpreadsheetWatermarkModernWordArtOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkmodernwordartoptions)` Klasse.


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

