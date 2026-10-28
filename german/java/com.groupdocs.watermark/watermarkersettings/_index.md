---
title: "WatermarkerSettings"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Definiert Einstellungen zum Anpassen des Verhaltens von Watermarker."
type: docs
weight: 15
url: /de/java/com.groupdocs.watermark/watermarkersettings/
---
**Inheritance:**
java.lang.Object
```
public final class WatermarkerSettings
```

Definiert Einstellungen zum Anpassen des Verhaltens von Watermarker.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [WatermarkerSettings()](#WatermarkerSettings--) | Initialisiert eine neue Instanz von |
WatermarkerSettings
Klasse.
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getSearchableObjects()](#getSearchableObjects--) | Ruft ab |
SearchableObjects
die in einer Wasserzeichen-Suche einbezogen werden sollen.
|
|  | [setSearchableObjects(SearchableObjects value)](#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-) | Setzt |
SearchableObjects
die in einer Wasserzeichen-Suche einbezogen werden sollen.
|
|  | [getLogger()](#getLogger--) | Ruft den logger ab, der zum Protokollieren von Ereignissen und Fehlern während der Wasserzeichen-Erstellung verwendet wird. |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.watermark.options.ILogger-) | Setzt den logger, der zum Protokollieren von Ereignissen und Fehlern während der Wasserzeichen-Erstellung verwendet wird. |
|
| [logError(WatermarkException exception, String format, Object[] args)](#logError-com.groupdocs.watermark.exceptions.WatermarkException-java.lang.String-java.lang.Object...-) |  |
| [logError(WatermarkException exception)](#logError-com.groupdocs.watermark.exceptions.WatermarkException-) |  |
| [logWarning(String format, Object[] args)](#logWarning-java.lang.String-java.lang.Object...-) |  |
| [logTrace(String format, Object[] args)](#logTrace-java.lang.String-java.lang.Object...-) |  |
### WatermarkerSettings() {#WatermarkerSettings--}
```
public WatermarkerSettings()
```


Initialisiert eine neue Instanz von
WatermarkerSettings
Klasse.


### getSearchableObjects() {#getSearchableObjects--}
```
public final SearchableObjects getSearchableObjects()
```


Ruft ab
SearchableObjects
die in einer Wasserzeichen-Suche einbezogen werden sollen.


**Returns:**
[SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) - The  SearchableObjects  that are to be included in a watermark search.

### setSearchableObjects(SearchableObjects value) {#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-}
```
public final void setSearchableObjects(SearchableObjects value)
```


Setzt
SearchableObjects
die in einer Wasserzeichen-Suche einbezogen werden sollen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) | Die  SearchableObjects  die in einer Wasserzeichen-Suche enthalten sein sollen. |
|

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Ruft den logger ab, der zum Protokollieren von Ereignissen und Fehlern während der Wasserzeichen-Erstellung verwendet wird.


**Returns:**
[ILogger](../../com.groupdocs.watermark.options/ilogger) - An instance of class that implements `[ILogger](../../com.groupdocs.watermark.options/ilogger)` interface.

### setLogger(ILogger value) {#setLogger-com.groupdocs.watermark.options.ILogger-}
```
public final void setLogger(ILogger value)
```


Setzt den logger, der zum Protokollieren von Ereignissen und Fehlern während der Wasserzeichen-Erstellung verwendet wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [ILogger](../../com.groupdocs.watermark.options/ilogger) | Eine Instanz einer Klasse, die das `[ILogger](../../com.groupdocs.watermark.options/ilogger)`-Interface implementiert. |
|

### logError(WatermarkException exception, String format, Object[] args) {#logError-com.groupdocs.watermark.exceptions.WatermarkException-java.lang.String-java.lang.Object...-}
```
public final void logError(WatermarkException exception, String format, Object[] args)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| exception | [WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception) |  |
| Format | java.lang.String |  |
| args | java.lang.Object[] |  |

### logError(WatermarkException exception) {#logError-com.groupdocs.watermark.exceptions.WatermarkException-}
```
public final void logError(WatermarkException exception)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| exception | [WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception) |  |

### logWarning(String format, Object[] args) {#logWarning-java.lang.String-java.lang.Object...-}
```
public final void logWarning(String format, Object[] args)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Format | java.lang.String |  |
| args | java.lang.Object[] |  |

### logTrace(String format, Object[] args) {#logTrace-java.lang.String-java.lang.Object...-}
```
public final void logTrace(String format, Object[] args)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Format | java.lang.String |  |
| args | java.lang.Object[] |  |

