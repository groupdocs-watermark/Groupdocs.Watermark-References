---
title: "WatermarkerSettings"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Definisce le impostazioni per personalizzare il comportamento del Watermarker."
type: docs
weight: 15
url: /it/java/com.groupdocs.watermark/watermarkersettings/
---
**Inheritance:**
java.lang.Object
```
public final class WatermarkerSettings
```

Definisce le impostazioni per personalizzare il comportamento del Watermarker.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [WatermarkerSettings()](#WatermarkerSettings--) | Inizializza una nuova istanza di |
WatermarkerSettings
classe.
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getSearchableObjects()](#getSearchableObjects--) | Ottiene |
SearchableObjects
che devono essere inclusi in una ricerca di filigrana.
|
|  | [setSearchableObjects(SearchableObjects value)](#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-) | Imposta |
SearchableObjects
che devono essere inclusi in una ricerca di filigrana.
|
|  | [getLogger()](#getLogger--) | Ottiene il logger che viene usato per registrare eventi ed errori durante il watermarking. |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.watermark.options.ILogger-) | Imposta il logger che viene usato per registrare eventi ed errori durante il watermarking. |
|
| [logError(WatermarkException exception, String format, Object[] args)](#logError-com.groupdocs.watermark.exceptions.WatermarkException-java.lang.String-java.lang.Object...-) |  |
| [logError(WatermarkException exception)](#logError-com.groupdocs.watermark.exceptions.WatermarkException-) |  |
| [logWarning(String format, Object[] args)](#logWarning-java.lang.String-java.lang.Object...-) |  |
| [logTrace(String format, Object[] args)](#logTrace-java.lang.String-java.lang.Object...-) |  |
### WatermarkerSettings() {#WatermarkerSettings--}
```
public WatermarkerSettings()
```


Inizializza una nuova istanza di
WatermarkerSettings
classe.


### getSearchableObjects() {#getSearchableObjects--}
```
public final SearchableObjects getSearchableObjects()
```


Ottiene
SearchableObjects
che devono essere inclusi in una ricerca di filigrana.


**Returns:**
[SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) - The  SearchableObjects  that are to be included in a watermark search.

### setSearchableObjects(SearchableObjects value) {#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-}
```
public final void setSearchableObjects(SearchableObjects value)
```


Imposta
SearchableObjects
che devono essere inclusi in una ricerca di filigrana.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) | Gli  SearchableObjects  che devono essere inclusi in una ricerca di watermark. |
|

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Ottiene il logger che viene usato per registrare eventi ed errori durante il watermarking.


**Returns:**
[ILogger](../../com.groupdocs.watermark.options/ilogger) - An instance of class that implements `[ILogger](../../com.groupdocs.watermark.options/ilogger)` interface.

### setLogger(ILogger value) {#setLogger-com.groupdocs.watermark.options.ILogger-}
```
public final void setLogger(ILogger value)
```


Imposta il logger che viene usato per registrare eventi ed errori durante il watermarking.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [ILogger](../../com.groupdocs.watermark.options/ilogger) | Un'istanza della classe che implementa l'interfaccia `[ILogger](../../com.groupdocs.watermark.options/ilogger)`. |
|

### logError(WatermarkException exception, String format, Object[] args) {#logError-com.groupdocs.watermark.exceptions.WatermarkException-java.lang.String-java.lang.Object...-}
```
public final void logError(WatermarkException exception, String format, Object[] args)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| exception | [WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception) |  |
| formato | java.lang.String |  |
| argomenti | java.lang.Object[] |  |

### logError(WatermarkException exception) {#logError-com.groupdocs.watermark.exceptions.WatermarkException-}
```
public final void logError(WatermarkException exception)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| exception | [WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception) |  |

### logWarning(String format, Object[] args) {#logWarning-java.lang.String-java.lang.Object...-}
```
public final void logWarning(String format, Object[] args)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formato | java.lang.String |  |
| argomenti | java.lang.Object[] |  |

### logTrace(String format, Object[] args) {#logTrace-java.lang.String-java.lang.Object...-}
```
public final void logTrace(String format, Object[] args)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formato | java.lang.String |  |
| argomenti | java.lang.Object[] |  |

