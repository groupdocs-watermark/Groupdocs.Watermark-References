---
title: "SpreadsheetBackgroundWatermarkOptions"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt Optionen dar, wenn das Wasserzeichen als Hintergrund zu einem Arbeitsblatt einer Kalkulationstabelle hinzugefügt wird."
type: docs
weight: 49
url: /de/java/com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)
```
public final class SpreadsheetBackgroundWatermarkOptions extends SpreadsheetWatermarkOptions
```

Stellt Optionen dar, wenn das Wasserzeichen als Hintergrund zu einem Arbeitsblatt einer Kalkulationstabelle hinzugefügt wird.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

Das folgende Beispiel zeigt, wie man ein Textwasserzeichen zu einem Excel-Dokument-Arbeitsblatt als Hintergrund hinzufügt.
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


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [SpreadsheetBackgroundWatermarkOptions()](#SpreadsheetBackgroundWatermarkOptions--) | Initialisiert eine neue Instanz der `[SpreadsheetBackgroundWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions)` Klasse. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Ermittelt den Index des Arbeitsblatts, zu dem das Wasserzeichen hinzugefügt werden soll. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Setzt den Index des Arbeitsblatts, dem das Wasserzeichen hinzugefügt wird. |
|
|  | [getBackgroundWidth()](#getBackgroundWidth--) | Ermittelt die gewünschte Breite des Hintergrundbildes in Pixeln. |
|
|  | [setBackgroundWidth(int value)](#setBackgroundWidth-int-) | Legt die gewünschte Breite des Hintergrundbildes in Pixeln fest. |
|
|  | [getBackgroundHeight()](#getBackgroundHeight--) | Liest oder legt die gewünschte Höhe des Hintergrundbildes in Pixeln fest. |
|
|  | [setBackgroundHeight(int value)](#setBackgroundHeight-int-) | Liest oder legt die gewünschte Höhe des Hintergrundbildes in Pixeln fest. |
|
### SpreadsheetBackgroundWatermarkOptions() {#SpreadsheetBackgroundWatermarkOptions--}
```
public SpreadsheetBackgroundWatermarkOptions()
```


Initialisiert eine neue Instanz der `[SpreadsheetBackgroundWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions)` Klasse.


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


Ermittelt den Index des Arbeitsblatts, zu dem das Wasserzeichen hinzugefügt werden soll.

-1 means every worksheet.


**Returns:**
int - Der Index des Arbeitsblatts, dem das Wasserzeichen hinzugefügt wird.

### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Setzt den Index des Arbeitsblatts, dem das Wasserzeichen hinzugefügt wird.

-1 means every worksheet.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Der Index des Arbeitsblatts, dem das Wasserzeichen hinzugefügt wird. |
|

### getBackgroundWidth() {#getBackgroundWidth--}
```
public final int getBackgroundWidth()
```


Ermittelt die gewünschte Breite des Hintergrundbildes in Pixeln.


**Returns:**
int – Die gewünschte Breite des Hintergrundbildes in Pixeln.

### setBackgroundWidth(int value) {#setBackgroundWidth-int-}
```
public final void setBackgroundWidth(int value)
```


Legt die gewünschte Breite des Hintergrundbildes in Pixeln fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Die gewünschte Breite des Hintergrundbildes in Pixeln. |
|

### getBackgroundHeight() {#getBackgroundHeight--}
```
public final int getBackgroundHeight()
```


Liest oder legt die gewünschte Höhe des Hintergrundbildes in Pixeln fest.


**Returns:**
int – Die gewünschte Höhe des Hintergrundbildes in Pixeln.

### setBackgroundHeight(int value) {#setBackgroundHeight-int-}
```
public final void setBackgroundHeight(int value)
```


Liest oder legt die gewünschte Höhe des Hintergrundbildes in Pixeln fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Die gewünschte Höhe des Hintergrundbildes in Pixeln. |
|

