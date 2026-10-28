---
title: "WatermarkerSettings"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Definieert instellingen voor het aanpassen van het gedrag van Watermarker."
type: docs
weight: 15
url: /nl/java/com.groupdocs.watermark/watermarkersettings/
---
**Inheritance:**
java.lang.Object
```
public final class WatermarkerSettings
```

Definieert instellingen voor het aanpassen van het gedrag van Watermarker.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [WatermarkerSettings()](#WatermarkerSettings--) | Initialiseert een nieuw exemplaar van |
WatermarkerSettings
klasse.
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getSearchableObjects()](#getSearchableObjects--) | Haalt op |
SearchableObjects
die moeten worden opgenomen in een watermerkzoekopdracht.
|
|  | [setSearchableObjects(SearchableObjects value)](#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-) | Stelt in |
SearchableObjects
die moeten worden opgenomen in een watermerkzoekopdracht.
|
|  | [getLogger()](#getLogger--) | Haalt de logger op die wordt gebruikt voor het loggen van gebeurtenissen en fouten tijdens het watermerken. |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.watermark.options.ILogger-) | Stelt de logger in die wordt gebruikt voor het loggen van gebeurtenissen en fouten tijdens het watermerken. |
|
| [logError(WatermarkException exception, String format, Object[] args)](#logError-com.groupdocs.watermark.exceptions.WatermarkException-java.lang.String-java.lang.Object...-) |  |
| [logError(WatermarkException exception)](#logError-com.groupdocs.watermark.exceptions.WatermarkException-) |  |
| [logWarning(String format, Object[] args)](#logWarning-java.lang.String-java.lang.Object...-) |  |
| [logTrace(String format, Object[] args)](#logTrace-java.lang.String-java.lang.Object...-) |  |
### WatermarkerSettings() {#WatermarkerSettings--}
```
public WatermarkerSettings()
```


Initialiseert een nieuw exemplaar van
WatermarkerSettings
klasse.


### getSearchableObjects() {#getSearchableObjects--}
```
public final SearchableObjects getSearchableObjects()
```


Haalt op
SearchableObjects
die moeten worden opgenomen in een watermerkzoekopdracht.


**Returns:**
[SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) - The  SearchableObjects  that are to be included in a watermark search.

### setSearchableObjects(SearchableObjects value) {#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-}
```
public final void setSearchableObjects(SearchableObjects value)
```


Stelt in
SearchableObjects
die moeten worden opgenomen in een watermerkzoekopdracht.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) | De  SearchableObjects  die moeten worden opgenomen in een watermerkzoekopdracht. |
|

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Haalt de logger op die wordt gebruikt voor het loggen van gebeurtenissen en fouten tijdens het watermerken.


**Returns:**
[ILogger](../../com.groupdocs.watermark.options/ilogger) - An instance of class that implements `[ILogger](../../com.groupdocs.watermark.options/ilogger)` interface.

### setLogger(ILogger value) {#setLogger-com.groupdocs.watermark.options.ILogger-}
```
public final void setLogger(ILogger value)
```


Stelt de logger in die wordt gebruikt voor het loggen van gebeurtenissen en fouten tijdens het watermerken.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [ILogger](../../com.groupdocs.watermark.options/ilogger) | Een instantie van een klasse die de `[ILogger](../../com.groupdocs.watermark.options/ilogger)` interface implementeert. |
|

### logError(WatermarkException exception, String format, Object[] args) {#logError-com.groupdocs.watermark.exceptions.WatermarkException-java.lang.String-java.lang.Object...-}
```
public final void logError(WatermarkException exception, String format, Object[] args)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| exception | [WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception) |  |
| indeling | java.lang.String |  |
| argumenten | java.lang.Object[] |  |

### logError(WatermarkException exception) {#logError-com.groupdocs.watermark.exceptions.WatermarkException-}
```
public final void logError(WatermarkException exception)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| exception | [WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception) |  |

### logWarning(String format, Object[] args) {#logWarning-java.lang.String-java.lang.Object...-}
```
public final void logWarning(String format, Object[] args)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| indeling | java.lang.String |  |
| argumenten | java.lang.Object[] |  |

### logTrace(String format, Object[] args) {#logTrace-java.lang.String-java.lang.Object...-}
```
public final void logTrace(String format, Object[] args)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| indeling | java.lang.String |  |
| argumenten | java.lang.Object[] |  |

