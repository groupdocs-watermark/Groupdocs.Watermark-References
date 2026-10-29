---
title: "WatermarkerSettings"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Watermarker davranışını özelleştirmek için ayarları tanımlar."
type: docs
weight: 15
url: /tr/java/com.groupdocs.watermark/watermarkersettings/
---
**Inheritance:**
java.lang.Object
```
public final class WatermarkerSettings
```

Watermarker davranışını özelleştirmek için ayarları tanımlar.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [WatermarkerSettings()](#WatermarkerSettings--) | Yeni bir örnek başlatır |
WatermarkerSettings
sınıf.
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getSearchableObjects()](#getSearchableObjects--) | Alır |
SearchableObjects
filigran aramasına dahil edilecek olanlar.
|
|  | [setSearchableObjects(SearchableObjects value)](#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-) | Ayarlar |
SearchableObjects
filigran aramasına dahil edilecek olanlar.
|
|  | [getLogger()](#getLogger--) | Filigranlama sırasında olayları ve hataları kaydetmek için kullanılan kaydediciyi alır. |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.watermark.options.ILogger-) | Filigranlama sırasında olayları ve hataları kaydetmek için kullanılan kaydediciyi ayarlar. |
|
| [logError(WatermarkException exception, String format, Object[] args)](#logError-com.groupdocs.watermark.exceptions.WatermarkException-java.lang.String-java.lang.Object...-) |  |
| [logError(WatermarkException exception)](#logError-com.groupdocs.watermark.exceptions.WatermarkException-) |  |
| [logWarning(String format, Object[] args)](#logWarning-java.lang.String-java.lang.Object...-) |  |
| [logTrace(String format, Object[] args)](#logTrace-java.lang.String-java.lang.Object...-) |  |
### WatermarkerSettings() {#WatermarkerSettings--}
```
public WatermarkerSettings()
```


Yeni bir örnek başlatır
WatermarkerSettings
sınıf.


### getSearchableObjects() {#getSearchableObjects--}
```
public final SearchableObjects getSearchableObjects()
```


Alır
SearchableObjects
filigran aramasına dahil edilecek olanlar.


**Returns:**
[SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) - The  SearchableObjects  that are to be included in a watermark search.

### setSearchableObjects(SearchableObjects value) {#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-}
```
public final void setSearchableObjects(SearchableObjects value)
```


Ayarlar
SearchableObjects
filigran aramasına dahil edilecek olanlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) | Filigran aramasına dahil edilecek olan  SearchableObjects  nesneleri. |
|

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Filigranlama sırasında olayları ve hataları kaydetmek için kullanılan kaydediciyi alır.


**Returns:**
[ILogger](../../com.groupdocs.watermark.options/ilogger) - An instance of class that implements `[ILogger](../../com.groupdocs.watermark.options/ilogger)` interface.

### setLogger(ILogger value) {#setLogger-com.groupdocs.watermark.options.ILogger-}
```
public final void setLogger(ILogger value)
```


Filigranlama sırasında olayları ve hataları kaydetmek için kullanılan kaydediciyi ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [ILogger](../../com.groupdocs.watermark.options/ilogger) | `[ILogger](../../com.groupdocs.watermark.options/ilogger)` arayüzünü uygulayan sınıfın bir örneği. |
|

### logError(WatermarkException exception, String format, Object[] args) {#logError-com.groupdocs.watermark.exceptions.WatermarkException-java.lang.String-java.lang.Object...-}
```
public final void logError(WatermarkException exception, String format, Object[] args)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| exception | [WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception) |  |
| biçim | java.lang.String |  |
| argümanlar | java.lang.Object[] |  |

### logError(WatermarkException exception) {#logError-com.groupdocs.watermark.exceptions.WatermarkException-}
```
public final void logError(WatermarkException exception)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| exception | [WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception) |  |

### logWarning(String format, Object[] args) {#logWarning-java.lang.String-java.lang.Object...-}
```
public final void logWarning(String format, Object[] args)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| biçim | java.lang.String |  |
| argümanlar | java.lang.Object[] |  |

### logTrace(String format, Object[] args) {#logTrace-java.lang.String-java.lang.Object...-}
```
public final void logTrace(String format, Object[] args)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| biçim | java.lang.String |  |
| argümanlar | java.lang.Object[] |  |

