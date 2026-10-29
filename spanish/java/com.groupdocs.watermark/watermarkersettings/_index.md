---
title: "WatermarkerSettings"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Define configuraciones para personalizar el comportamiento del Watermarker."
type: docs
weight: 15
url: /es/java/com.groupdocs.watermark/watermarkersettings/
---
**Inheritance:**
java.lang.Object
```
public final class WatermarkerSettings
```

Define configuraciones para personalizar el comportamiento del Watermarker.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [WatermarkerSettings()](#WatermarkerSettings--) | Inicializa una nueva instancia de |
WatermarkerSettings
clase.
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getSearchableObjects()](#getSearchableObjects--) | Obtiene |
SearchableObjects
que deben incluirse en una búsqueda de marca de agua.
|
|  | [setSearchableObjects(SearchableObjects value)](#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-) | Establece |
SearchableObjects
que deben incluirse en una búsqueda de marca de agua.
|
|  | [getLogger()](#getLogger--) | Obtiene el logger que se usa para registrar eventos y errores durante la marca de agua. |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.watermark.options.ILogger-) | Establece el logger que se usa para registrar eventos y errores durante la marca de agua. |
|
| [logError(WatermarkException exception, String format, Object[] args)](#logError-com.groupdocs.watermark.exceptions.WatermarkException-java.lang.String-java.lang.Object...-) |  |
| [logError(WatermarkException exception)](#logError-com.groupdocs.watermark.exceptions.WatermarkException-) |  |
| [logWarning(String format, Object[] args)](#logWarning-java.lang.String-java.lang.Object...-) |  |
| [logTrace(String format, Object[] args)](#logTrace-java.lang.String-java.lang.Object...-) |  |
### WatermarkerSettings() {#WatermarkerSettings--}
```
public WatermarkerSettings()
```


Inicializa una nueva instancia de
WatermarkerSettings
clase.


### getSearchableObjects() {#getSearchableObjects--}
```
public final SearchableObjects getSearchableObjects()
```


Obtiene
SearchableObjects
que deben incluirse en una búsqueda de marca de agua.


**Returns:**
[SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) - The  SearchableObjects  that are to be included in a watermark search.

### setSearchableObjects(SearchableObjects value) {#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-}
```
public final void setSearchableObjects(SearchableObjects value)
```


Establece
SearchableObjects
que deben incluirse en una búsqueda de marca de agua.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) | Los  SearchableObjects  que se incluirán en una búsqueda de marca de agua. |
|

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Obtiene el logger que se usa para registrar eventos y errores durante la marca de agua.


**Returns:**
[ILogger](../../com.groupdocs.watermark.options/ilogger) - An instance of class that implements `[ILogger](../../com.groupdocs.watermark.options/ilogger)` interface.

### setLogger(ILogger value) {#setLogger-com.groupdocs.watermark.options.ILogger-}
```
public final void setLogger(ILogger value)
```


Establece el logger que se usa para registrar eventos y errores durante la marca de agua.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [ILogger](../../com.groupdocs.watermark.options/ilogger) | Una instancia de la clase que implementa la interfaz `[ILogger](../../com.groupdocs.watermark.options/ilogger)`. |
|

### logError(WatermarkException exception, String format, Object[] args) {#logError-com.groupdocs.watermark.exceptions.WatermarkException-java.lang.String-java.lang.Object...-}
```
public final void logError(WatermarkException exception, String format, Object[] args)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| exception | [WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception) |  |
| formato | java.lang.String |  |
| args | java.lang.Object[] |  |

### logError(WatermarkException exception) {#logError-com.groupdocs.watermark.exceptions.WatermarkException-}
```
public final void logError(WatermarkException exception)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| exception | [WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception) |  |

### logWarning(String format, Object[] args) {#logWarning-java.lang.String-java.lang.Object...-}
```
public final void logWarning(String format, Object[] args)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formato | java.lang.String |  |
| args | java.lang.Object[] |  |

### logTrace(String format, Object[] args) {#logTrace-java.lang.String-java.lang.Object...-}
```
public final void logTrace(String format, Object[] args)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formato | java.lang.String |  |
| args | java.lang.Object[] |  |

