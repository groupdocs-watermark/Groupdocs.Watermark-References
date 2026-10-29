---
title: "WatermarkerSettings"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Definierar inställningar för att anpassa Watermarker-beteende."
type: docs
weight: 15
url: /sv/java/com.groupdocs.watermark/watermarkersettings/
---
**Inheritance:**
java.lang.Object
```
public final class WatermarkerSettings
```

Definierar inställningar för att anpassa Watermarker-beteende.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [WatermarkerSettings()](#WatermarkerSettings--) | Initierar en ny instans av |
WatermarkerSettings
klassen.
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getSearchableObjects()](#getSearchableObjects--) | Hämtar |
SearchableObjects
som ska inkluderas i en vattenstämpelsökning.
|
|  | [setSearchableObjects(SearchableObjects value)](#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-) | Ställer in |
SearchableObjects
som ska inkluderas i en vattenstämpelsökning.
|
|  | [getLogger()](#getLogger--) | Hämtar loggaren som används för att logga händelser och fel under vattenmärkning. |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.watermark.options.ILogger-) | Ställer in loggaren som används för att logga händelser och fel under vattenmärkning. |
|
| [logError(WatermarkException exception, String format, Object[] args)](#logError-com.groupdocs.watermark.exceptions.WatermarkException-java.lang.String-java.lang.Object...-) |  |
| [logError(WatermarkException exception)](#logError-com.groupdocs.watermark.exceptions.WatermarkException-) |  |
| [logWarning(String format, Object[] args)](#logWarning-java.lang.String-java.lang.Object...-) |  |
| [logTrace(String format, Object[] args)](#logTrace-java.lang.String-java.lang.Object...-) |  |
### WatermarkerSettings() {#WatermarkerSettings--}
```
public WatermarkerSettings()
```


Initierar en ny instans av
WatermarkerSettings
klassen.


### getSearchableObjects() {#getSearchableObjects--}
```
public final SearchableObjects getSearchableObjects()
```


Hämtar
SearchableObjects
som ska inkluderas i en vattenstämpelsökning.


**Returns:**
[SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) - The  SearchableObjects  that are to be included in a watermark search.

### setSearchableObjects(SearchableObjects value) {#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-}
```
public final void setSearchableObjects(SearchableObjects value)
```


Ställer in
SearchableObjects
som ska inkluderas i en vattenstämpelsökning.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) | De  SearchableObjects  som ska inkluderas i en vattenmärkesökning. |
|

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Hämtar loggaren som används för att logga händelser och fel under vattenmärkning.


**Returns:**
[ILogger](../../com.groupdocs.watermark.options/ilogger) - An instance of class that implements `[ILogger](../../com.groupdocs.watermark.options/ilogger)` interface.

### setLogger(ILogger value) {#setLogger-com.groupdocs.watermark.options.ILogger-}
```
public final void setLogger(ILogger value)
```


Ställer in loggaren som används för att logga händelser och fel under vattenmärkning.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [ILogger](../../com.groupdocs.watermark.options/ilogger) | En instans av en klass som implementerar `[ILogger](../../com.groupdocs.watermark.options/ilogger)`-gränssnittet. |
|

### logError(WatermarkException exception, String format, Object[] args) {#logError-com.groupdocs.watermark.exceptions.WatermarkException-java.lang.String-java.lang.Object...-}
```
public final void logError(WatermarkException exception, String format, Object[] args)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| exception | [WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception) |  |
| format | java.lang.String |  |
| args | java.lang.Object[] |  |

### logError(WatermarkException exception) {#logError-com.groupdocs.watermark.exceptions.WatermarkException-}
```
public final void logError(WatermarkException exception)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| exception | [WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception) |  |

### logWarning(String format, Object[] args) {#logWarning-java.lang.String-java.lang.Object...-}
```
public final void logWarning(String format, Object[] args)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| format | java.lang.String |  |
| args | java.lang.Object[] |  |

### logTrace(String format, Object[] args) {#logTrace-java.lang.String-java.lang.Object...-}
```
public final void logTrace(String format, Object[] args)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| format | java.lang.String |  |
| args | java.lang.Object[] |  |

