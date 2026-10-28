---
title: "WatermarkerSettings"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Définit les paramètres pour personnaliser le comportement du Watermarker."
type: docs
weight: 15
url: /fr/java/com.groupdocs.watermark/watermarkersettings/
---
**Inheritance:**
java.lang.Object
```
public final class WatermarkerSettings
```

Définit les paramètres pour personnaliser le comportement du Watermarker.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [WatermarkerSettings()](#WatermarkerSettings--) | Initialise une nouvelle instance de |
WatermarkerSettings
classe.
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getSearchableObjects()](#getSearchableObjects--) | Obtient |
SearchableObjects
qui doivent être inclus dans une recherche de filigrane.
|
|  | [setSearchableObjects(SearchableObjects value)](#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-) | Définit |
SearchableObjects
qui doivent être inclus dans une recherche de filigrane.
|
|  | [getLogger()](#getLogger--) | Obtient le journaliseur qui est utilisé pour consigner les événements et les erreurs lors du filigrane. |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.watermark.options.ILogger-) | Définit le journaliseur qui est utilisé pour consigner les événements et les erreurs lors du filigrane. |
|
| [logError(WatermarkException exception, String format, Object[] args)](#logError-com.groupdocs.watermark.exceptions.WatermarkException-java.lang.String-java.lang.Object...-) |  |
| [logError(WatermarkException exception)](#logError-com.groupdocs.watermark.exceptions.WatermarkException-) |  |
| [logWarning(String format, Object[] args)](#logWarning-java.lang.String-java.lang.Object...-) |  |
| [logTrace(String format, Object[] args)](#logTrace-java.lang.String-java.lang.Object...-) |  |
### WatermarkerSettings() {#WatermarkerSettings--}
```
public WatermarkerSettings()
```


Initialise une nouvelle instance de
WatermarkerSettings
classe.


### getSearchableObjects() {#getSearchableObjects--}
```
public final SearchableObjects getSearchableObjects()
```


Obtient
SearchableObjects
qui doivent être inclus dans une recherche de filigrane.


**Returns:**
[SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) - The  SearchableObjects  that are to be included in a watermark search.

### setSearchableObjects(SearchableObjects value) {#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-}
```
public final void setSearchableObjects(SearchableObjects value)
```


Définit
SearchableObjects
qui doivent être inclus dans une recherche de filigrane.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) | Les  SearchableObjects  qui doivent être inclus dans une recherche de filigrane. |
|

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Obtient le journaliseur qui est utilisé pour consigner les événements et les erreurs lors du filigrane.


**Returns:**
[ILogger](../../com.groupdocs.watermark.options/ilogger) - An instance of class that implements `[ILogger](../../com.groupdocs.watermark.options/ilogger)` interface.

### setLogger(ILogger value) {#setLogger-com.groupdocs.watermark.options.ILogger-}
```
public final void setLogger(ILogger value)
```


Définit le journaliseur qui est utilisé pour consigner les événements et les erreurs lors du filigrane.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [ILogger](../../com.groupdocs.watermark.options/ilogger) | Une instance de classe qui implémente l'interface `[ILogger](../../com.groupdocs.watermark.options/ilogger)`. |
|

### logError(WatermarkException exception, String format, Object[] args) {#logError-com.groupdocs.watermark.exceptions.WatermarkException-java.lang.String-java.lang.Object...-}
```
public final void logError(WatermarkException exception, String format, Object[] args)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| exception | [WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception) |  |
| format | java.lang.String |  |
| args | java.lang.Object[] |  |

### logError(WatermarkException exception) {#logError-com.groupdocs.watermark.exceptions.WatermarkException-}
```
public final void logError(WatermarkException exception)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| exception | [WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception) |  |

### logWarning(String format, Object[] args) {#logWarning-java.lang.String-java.lang.Object...-}
```
public final void logWarning(String format, Object[] args)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| format | java.lang.String |  |
| args | java.lang.Object[] |  |

### logTrace(String format, Object[] args) {#logTrace-java.lang.String-java.lang.Object...-}
```
public final void logTrace(String format, Object[] args)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| format | java.lang.String |  |
| args | java.lang.Object[] |  |

