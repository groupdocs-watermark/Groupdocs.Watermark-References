---
title: "WatermarkerSettings"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يحدد الإعدادات لتخصيص سلوك Watermarker."
type: docs
weight: 15
url: /ar/java/com.groupdocs.watermark/watermarkersettings/
---
**Inheritance:**
java.lang.Object
```
public final class WatermarkerSettings
```

يحدد الإعدادات لتخصيص سلوك Watermarker.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [WatermarkerSettings()](#WatermarkerSettings--) | يُنشئ مثيلًا جديدًا من |
WatermarkerSettings
الفئة.
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getSearchableObjects()](#getSearchableObjects--) | يحصل على |
SearchableObjects
التي يجب تضمينها في بحث العلامة المائية.
|
|  | [setSearchableObjects(SearchableObjects value)](#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-) | يضبط |
SearchableObjects
التي يجب تضمينها في بحث العلامة المائية.
|
|  | [getLogger()](#getLogger--) | يحصل على المُسجل الذي يُستخدم لتسجيل الأحداث والأخطاء أثناء وضع العلامة المائية. |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.watermark.options.ILogger-) | يضبط المُسجل الذي يُستخدم لتسجيل الأحداث والأخطاء أثناء وضع العلامة المائية. |
|
| [logError(WatermarkException exception, String format, Object[] args)](#logError-com.groupdocs.watermark.exceptions.WatermarkException-java.lang.String-java.lang.Object...-) |  |
| [logError(WatermarkException exception)](#logError-com.groupdocs.watermark.exceptions.WatermarkException-) |  |
| [logWarning(String format, Object[] args)](#logWarning-java.lang.String-java.lang.Object...-) |  |
| [logTrace(String format, Object[] args)](#logTrace-java.lang.String-java.lang.Object...-) |  |
### WatermarkerSettings() {#WatermarkerSettings--}
```
public WatermarkerSettings()
```


يُنشئ مثيلًا جديدًا من
WatermarkerSettings
الفئة.


### getSearchableObjects() {#getSearchableObjects--}
```
public final SearchableObjects getSearchableObjects()
```


يحصل على
SearchableObjects
التي يجب تضمينها في بحث العلامة المائية.


**Returns:**
[SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) - The  SearchableObjects  that are to be included in a watermark search.

### setSearchableObjects(SearchableObjects value) {#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-}
```
public final void setSearchableObjects(SearchableObjects value)
```


يضبط
SearchableObjects
التي يجب تضمينها في بحث العلامة المائية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) | الـ  SearchableObjects  التي يجب تضمينها في بحث العلامة المائية. |
|

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


يحصل على المُسجل الذي يُستخدم لتسجيل الأحداث والأخطاء أثناء وضع العلامة المائية.


**Returns:**
[ILogger](../../com.groupdocs.watermark.options/ilogger) - An instance of class that implements `[ILogger](../../com.groupdocs.watermark.options/ilogger)` interface.

### setLogger(ILogger value) {#setLogger-com.groupdocs.watermark.options.ILogger-}
```
public final void setLogger(ILogger value)
```


يضبط المُسجل الذي يُستخدم لتسجيل الأحداث والأخطاء أثناء وضع العلامة المائية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [ILogger](../../com.groupdocs.watermark.options/ilogger) | مثال على فئة تُنفّذ واجهة `[ILogger](../../com.groupdocs.watermark.options/ilogger)`. |
|

### logError(WatermarkException exception, String format, Object[] args) {#logError-com.groupdocs.watermark.exceptions.WatermarkException-java.lang.String-java.lang.Object...-}
```
public final void logError(WatermarkException exception, String format, Object[] args)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| exception | [WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception) |  |
| تنسيق | java.lang.String |  |
| وسائط | java.lang.Object[] |  |

### logError(WatermarkException exception) {#logError-com.groupdocs.watermark.exceptions.WatermarkException-}
```
public final void logError(WatermarkException exception)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| exception | [WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception) |  |

### logWarning(String format, Object[] args) {#logWarning-java.lang.String-java.lang.Object...-}
```
public final void logWarning(String format, Object[] args)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تنسيق | java.lang.String |  |
| وسائط | java.lang.Object[] |  |

### logTrace(String format, Object[] args) {#logTrace-java.lang.String-java.lang.Object...-}
```
public final void logTrace(String format, Object[] args)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تنسيق | java.lang.String |  |
| وسائط | java.lang.Object[] |  |

