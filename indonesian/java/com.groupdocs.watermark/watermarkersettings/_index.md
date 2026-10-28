---
title: "WatermarkerSettings"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mendefinisikan pengaturan untuk menyesuaikan perilaku Watermarker."
type: docs
weight: 15
url: /id/java/com.groupdocs.watermark/watermarkersettings/
---
**Inheritance:**
java.lang.Object
```
public final class WatermarkerSettings
```

Mendefinisikan pengaturan untuk menyesuaikan perilaku Watermarker.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [WatermarkerSettings()](#WatermarkerSettings--) | Menginisialisasi instance baru dari |
WatermarkerSettings
kelas.
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getSearchableObjects()](#getSearchableObjects--) | Mendapatkan |
SearchableObjects
yang akan disertakan dalam pencarian watermark.
|
|  | [setSearchableObjects(SearchableObjects value)](#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-) | Mengatur |
SearchableObjects
yang akan disertakan dalam pencarian watermark.
|
|  | [getLogger()](#getLogger--) | Mendapatkan logger yang digunakan untuk mencatat peristiwa dan kesalahan selama watermarking. |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.watermark.options.ILogger-) | Mengatur logger yang digunakan untuk mencatat peristiwa dan kesalahan selama watermarking. |
|
| [logError(WatermarkException exception, String format, Object[] args)](#logError-com.groupdocs.watermark.exceptions.WatermarkException-java.lang.String-java.lang.Object...-) |  |
| [logError(WatermarkException exception)](#logError-com.groupdocs.watermark.exceptions.WatermarkException-) |  |
| [logWarning(String format, Object[] args)](#logWarning-java.lang.String-java.lang.Object...-) |  |
| [logTrace(String format, Object[] args)](#logTrace-java.lang.String-java.lang.Object...-) |  |
### WatermarkerSettings() {#WatermarkerSettings--}
```
public WatermarkerSettings()
```


Menginisialisasi instance baru dari
WatermarkerSettings
kelas.


### getSearchableObjects() {#getSearchableObjects--}
```
public final SearchableObjects getSearchableObjects()
```


Mendapatkan
SearchableObjects
yang akan disertakan dalam pencarian watermark.


**Returns:**
[SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) - The  SearchableObjects  that are to be included in a watermark search.

### setSearchableObjects(SearchableObjects value) {#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-}
```
public final void setSearchableObjects(SearchableObjects value)
```


Mengatur
SearchableObjects
yang akan disertakan dalam pencarian watermark.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) | Objek SearchableObjects yang akan dimasukkan dalam pencarian watermark. |
|

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Mendapatkan logger yang digunakan untuk mencatat peristiwa dan kesalahan selama watermarking.


**Returns:**
[ILogger](../../com.groupdocs.watermark.options/ilogger) - An instance of class that implements `[ILogger](../../com.groupdocs.watermark.options/ilogger)` interface.

### setLogger(ILogger value) {#setLogger-com.groupdocs.watermark.options.ILogger-}
```
public final void setLogger(ILogger value)
```


Mengatur logger yang digunakan untuk mencatat peristiwa dan kesalahan selama watermarking.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [ILogger](../../com.groupdocs.watermark.options/ilogger) | Sebuah instance kelas yang mengimplementasikan antarmuka `[ILogger](../../com.groupdocs.watermark.options/ilogger)` interface. |
|

### logError(WatermarkException exception, String format, Object[] args) {#logError-com.groupdocs.watermark.exceptions.WatermarkException-java.lang.String-java.lang.Object...-}
```
public final void logError(WatermarkException exception, String format, Object[] args)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| exception | [WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception) |  |
| format | java.lang.String |  |
| args | java.lang.Object[] |  |

### logError(WatermarkException exception) {#logError-com.groupdocs.watermark.exceptions.WatermarkException-}
```
public final void logError(WatermarkException exception)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| exception | [WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception) |  |

### logWarning(String format, Object[] args) {#logWarning-java.lang.String-java.lang.Object...-}
```
public final void logWarning(String format, Object[] args)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| format | java.lang.String |  |
| args | java.lang.Object[] |  |

### logTrace(String format, Object[] args) {#logTrace-java.lang.String-java.lang.Object...-}
```
public final void logTrace(String format, Object[] args)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| format | java.lang.String |  |
| args | java.lang.Object[] |  |

