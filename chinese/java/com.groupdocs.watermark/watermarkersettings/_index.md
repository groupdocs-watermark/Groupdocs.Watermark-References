---
title: "WatermarkerSettings"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "定义用于自定义 Watermarker 行为的设置。"
type: docs
weight: 15
url: /zh/java/com.groupdocs.watermark/watermarkersettings/
---
**Inheritance:**
java.lang.Object
```
public final class WatermarkerSettings
```

定义用于自定义 Watermarker 行为的设置。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [WatermarkerSettings()](#WatermarkerSettings--) | 初始化新的实例 |
WatermarkerSettings
类。
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getSearchableObjects()](#getSearchableObjects--) | 获取 |
SearchableObjects
这些对象将被包含在水印搜索中。
|
|  | [setSearchableObjects(SearchableObjects value)](#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-) | 设置 |
SearchableObjects
这些对象将被包含在水印搜索中。
|
|  | [getLogger()](#getLogger--) | 获取在水印过程中用于记录事件和错误的日志记录器。 |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.watermark.options.ILogger-) | 设置在水印过程中用于记录事件和错误的日志记录器。 |
|
| [logError(WatermarkException exception, String format, Object[] args)](#logError-com.groupdocs.watermark.exceptions.WatermarkException-java.lang.String-java.lang.Object...-) |  |
| [logError(WatermarkException exception)](#logError-com.groupdocs.watermark.exceptions.WatermarkException-) |  |
| [logWarning(String format, Object[] args)](#logWarning-java.lang.String-java.lang.Object...-) |  |
| [logTrace(String format, Object[] args)](#logTrace-java.lang.String-java.lang.Object...-) |  |
### WatermarkerSettings() {#WatermarkerSettings--}
```
public WatermarkerSettings()
```


初始化新的实例
WatermarkerSettings
类。


### getSearchableObjects() {#getSearchableObjects--}
```
public final SearchableObjects getSearchableObjects()
```


获取
SearchableObjects
这些对象将被包含在水印搜索中。


**Returns:**
[SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) - The  SearchableObjects  that are to be included in a watermark search.

### setSearchableObjects(SearchableObjects value) {#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-}
```
public final void setSearchableObjects(SearchableObjects value)
```


设置
SearchableObjects
这些对象将被包含在水印搜索中。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) | 要包含在水印搜索中的 SearchableObjects。 |
|

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


获取在水印过程中用于记录事件和错误的日志记录器。


**Returns:**
[ILogger](../../com.groupdocs.watermark.options/ilogger) - An instance of class that implements `[ILogger](../../com.groupdocs.watermark.options/ilogger)` interface.

### setLogger(ILogger value) {#setLogger-com.groupdocs.watermark.options.ILogger-}
```
public final void setLogger(ILogger value)
```


设置在水印过程中用于记录事件和错误的日志记录器。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [ILogger](../../com.groupdocs.watermark.options/ilogger) | 实现 `[ILogger](../../com.groupdocs.watermark.options/ilogger)` 接口的类的实例。 |
|

### logError(WatermarkException exception, String format, Object[] args) {#logError-com.groupdocs.watermark.exceptions.WatermarkException-java.lang.String-java.lang.Object...-}
```
public final void logError(WatermarkException exception, String format, Object[] args)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| exception | [WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception) |  |
| 格式 | java.lang.String |  |
| 参数 | java.lang.Object[] |  |

### logError(WatermarkException exception) {#logError-com.groupdocs.watermark.exceptions.WatermarkException-}
```
public final void logError(WatermarkException exception)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| exception | [WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception) |  |

### logWarning(String format, Object[] args) {#logWarning-java.lang.String-java.lang.Object...-}
```
public final void logWarning(String format, Object[] args)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 格式 | java.lang.String |  |
| 参数 | java.lang.Object[] |  |

### logTrace(String format, Object[] args) {#logTrace-java.lang.String-java.lang.Object...-}
```
public final void logTrace(String format, Object[] args)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 格式 | java.lang.String |  |
| 参数 | java.lang.Object[] |  |

