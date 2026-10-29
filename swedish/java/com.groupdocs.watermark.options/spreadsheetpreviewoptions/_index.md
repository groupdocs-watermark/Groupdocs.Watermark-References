---
title: "SpreadsheetPreviewOptions"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Tillhandahåller alternativ för att sätta krav och strömbaserade delegater för förhandsgranskningsgenerering av ett Spreadsheet-dokument."
type: docs
weight: 52
url: /sv/java/com.groupdocs.watermark.options/spreadsheetpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class SpreadsheetPreviewOptions extends PreviewOptions
```

Tillhandahåller alternativ för att sätta krav och strömbaserade delegater för förhandsgranskningsgenerering av ett Spreadsheet-dokument.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [SpreadsheetPreviewOptions(ICreatePageStream createPageStream)](#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Initierar en ny instans av klassen `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` som får utdataflödet att stängas. |
|
|  | [SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Initierar en ny instans av klassen `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` som får utdataflödet att returneras till klienten för vidare användning. |
|
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [DefaultResolution](#DefaultResolution) | Standardupplösning i punkter per tum. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getResolution()](#getResolution--) | Hämtar upplösningen för de genererade bilderna, i punkter per tum. |
|
|  | [setResolution(int value)](#setResolution-int-) | Ställer in upplösningen för de genererade bilderna, i punkter per tum. |
|
|  | [getOnlyDataArea()](#getOnlyDataArea--) | Hämtar flaggan för att rendera endast dataområdet utan rubriker, sidfötter och marginaler. |
|
|  | [setOnlyDataArea(boolean value)](#setOnlyDataArea-boolean-) | Ställer in flaggan för att rendera endast dataområdet utan rubriker, sidfötter och marginaler. |
|
### SpreadsheetPreviewOptions(ICreatePageStream createPageStream) {#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public SpreadsheetPreviewOptions(ICreatePageStream createPageStream)
```


Initierar en ny instans av klassen `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` som får utdataflödet att stängas.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Skapar en ström för en specifik sidoförhandsgranskning. |
|

### SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Initierar en ny instans av klassen `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` som får utdataflödet att returneras till klienten för vidare användning.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Skapar en ström för en specifik sidoförhandsgranskning. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Meddelar att sidoförhandsgranskningens generering är klar och hämtar utdataströmmen. |
|

### DefaultResolution {#DefaultResolution}
```
public static final int DefaultResolution
```


Standardupplösning i punkter per tum.


### getResolution() {#getResolution--}
```
public final int getResolution()
```


Hämtar upplösningen för de genererade bilderna, i punkter per tum.


**Returns:**
int - Upplösningen för de genererade bilderna, i punkter per tum.

<br />

*** ** * ** ***

Standardvärdet är 96.

<br />


### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


Ställer in upplösningen för de genererade bilderna, i punkter per tum.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int | Upplösningen för de genererade bilderna, i punkter per tum. |

<br />

*** ** * ** ***

Standardvärdet är 96.

<br />

|

### getOnlyDataArea() {#getOnlyDataArea--}
```
public final boolean getOnlyDataArea()
```


Hämtar flaggan för att rendera endast dataområdet utan rubriker, sidfötter och marginaler.


**Returns:**
boolean - Flaggan för att rendera endast dataområdet utan rubriker, sidfötter och marginaler.

<br />

*** ** * ** ***

Denna flagga leder till att hela arbetsbladet renderas på en sida. Standardvärdet är false.

<br />


### setOnlyDataArea(boolean value) {#setOnlyDataArea-boolean-}
```
public final void setOnlyDataArea(boolean value)
```


Ställer in flaggan för att rendera endast dataområdet utan rubriker, sidfötter och marginaler.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | Flaggan för att rendera endast dataområdet utan rubriker, sidfötter och marginaler. |

<br />

*** ** * ** ***

Denna flagga leder till att hela arbetsbladet renderas på en sida. Standardvärdet är false.

<br />

|

