---
title: "SpreadsheetShapeSettings"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar inställningar som kan tillämpas på en formvattenstämpel för ett Excel-dokument."
type: docs
weight: 54
url: /sv/java/com.groupdocs.watermark.options/spreadsheetshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class SpreadsheetShapeSettings extends OfficeShapeSettings
```

Representerar inställningar som kan tillämpas på en formvattenstämpel för ett Excel-dokument.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [SpreadsheetShapeSettings()](#SpreadsheetShapeSettings--) | Initierar en ny instans av klassen `[SpreadsheetShapeSettings](../../com.groupdocs.watermark.options/spreadsheetshapesettings)`. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isLocked()](#isLocked--) | Hämtar ett värde som indikerar om redigering av formen i Excel är förbjuden. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Anger ett värde som indikerar om redigering av formen i Excel är förbjuden. |
|
### SpreadsheetShapeSettings() {#SpreadsheetShapeSettings--}
```
public SpreadsheetShapeSettings()
```


Initierar en ny instans av klassen `[SpreadsheetShapeSettings](../../com.groupdocs.watermark.options/spreadsheetshapesettings)`.


### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Hämtar ett värde som indikerar om redigering av formen i Excel är förbjuden.


**Returns:**
boolean - Om värdet är true, kommer redigering av formen att vara förbjuden. Som standard är värdet false, så formen kan redigeras i Excel.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Anger ett värde som indikerar om redigering av formen i Excel är förbjuden.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | Om värdet är true, kommer redigering av formen att vara förbjuden. Som standard är värdet false, så formen kan redigeras i Excel. |
|

