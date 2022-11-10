---
title: WatermarkerSettings
second_title: GroupDocs.Watermark for Java API Reference
description: Defines settings for customizing Watermarker behaviour.
type: docs
weight: 13
url: /java/com.groupdocs.watermark/watermarkersettings/
---
**Inheritance:**
java.lang.Object
```
public final class WatermarkerSettings
```

Defines settings for customizing Watermarker behaviour.
## Constructors

| Constructor | Description |
| --- | --- |
| [WatermarkerSettings()](#WatermarkerSettings--) | Initializes new instance of  WatermarkerSettings  class. |
## Methods

| Method | Description |
| --- | --- |
| [getSearchableObjects()](#getSearchableObjects--) | Gets  SearchableObjects  that are to be included in a watermark search. |
| [setSearchableObjects(SearchableObjects value)](#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-) | Sets  SearchableObjects  that are to be included in a watermark search. |
| [getLogger()](#getLogger--) | Gets the logger which is used for logging events and errors during watermarking. |
| [setLogger(ILogger value)](#setLogger-com.groupdocs.watermark.options.ILogger-) | Sets the logger which is used for logging events and errors during watermarking. |
| [logError(WatermarkException exception, String format, Object[] args)](#logError-com.groupdocs.watermark.exceptions.WatermarkException-java.lang.String-java.lang.Object...-) |  |
| [logError(WatermarkException exception)](#logError-com.groupdocs.watermark.exceptions.WatermarkException-) |  |
| [logWarning(String format, Object[] args)](#logWarning-java.lang.String-java.lang.Object...-) |  |
| [logTrace(String format, Object[] args)](#logTrace-java.lang.String-java.lang.Object...-) |  |
### WatermarkerSettings() {#WatermarkerSettings--}
```
public WatermarkerSettings()
```


Initializes new instance of  WatermarkerSettings  class.

### getSearchableObjects() {#getSearchableObjects--}
```
public final SearchableObjects getSearchableObjects()
```


Gets  SearchableObjects  that are to be included in a watermark search.

**Returns:**
[SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) - The  SearchableObjects  that are to be included in a watermark search.
### setSearchableObjects(SearchableObjects value) {#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-}
```
public final void setSearchableObjects(SearchableObjects value)
```


Sets  SearchableObjects  that are to be included in a watermark search.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) | The  SearchableObjects  that are to be included in a watermark search. |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Gets the logger which is used for logging events and errors during watermarking.

**Returns:**
[ILogger](../../com.groupdocs.watermark.options/ilogger) - An instance of class that implements `[ILogger](../../com.groupdocs.watermark.options/ilogger)` interface.
### setLogger(ILogger value) {#setLogger-com.groupdocs.watermark.options.ILogger-}
```
public final void setLogger(ILogger value)
```


Sets the logger which is used for logging events and errors during watermarking.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ILogger](../../com.groupdocs.watermark.options/ilogger) | An instance of class that implements `[ILogger](../../com.groupdocs.watermark.options/ilogger)` interface. |

### logError(WatermarkException exception, String format, Object[] args) {#logError-com.groupdocs.watermark.exceptions.WatermarkException-java.lang.String-java.lang.Object...-}
```
public final void logError(WatermarkException exception, String format, Object[] args)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| exception | [WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception) |  |
| format | java.lang.String |  |
| args | java.lang.Object[] |  |

### logError(WatermarkException exception) {#logError-com.groupdocs.watermark.exceptions.WatermarkException-}
```
public final void logError(WatermarkException exception)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| exception | [WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception) |  |

### logWarning(String format, Object[] args) {#logWarning-java.lang.String-java.lang.Object...-}
```
public final void logWarning(String format, Object[] args)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | java.lang.String |  |
| args | java.lang.Object[] |  |

### logTrace(String format, Object[] args) {#logTrace-java.lang.String-java.lang.Object...-}
```
public final void logTrace(String format, Object[] args)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | java.lang.String |  |
| args | java.lang.Object[] |  |

