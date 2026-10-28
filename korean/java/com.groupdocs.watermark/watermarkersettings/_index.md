---
title: "WatermarkerSettings"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "Watermarker 동작을 사용자 지정하기 위한 설정을 정의합니다."
type: docs
weight: 15
url: /ko/java/com.groupdocs.watermark/watermarkersettings/
---
**Inheritance:**
java.lang.Object
```
public final class WatermarkerSettings
```

Watermarker 동작을 사용자 지정하기 위한 설정을 정의합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [WatermarkerSettings()](#WatermarkerSettings--) | 새 인스턴스를 초기화합니다. |
WatermarkerSettings
클래스.
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getSearchableObjects()](#getSearchableObjects--) | 가져옵니다 |
SearchableObjects
워터마크 검색에 포함될 객체입니다.
|
|  | [setSearchableObjects(SearchableObjects value)](#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-) | 설정 |
SearchableObjects
워터마크 검색에 포함될 객체입니다.
|
|  | [getLogger()](#getLogger--) | 워터마크 처리 중 이벤트와 오류를 기록하는 데 사용되는 로거를 가져옵니다. |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.watermark.options.ILogger-) | 워터마크 처리 중 이벤트와 오류를 기록하는 데 사용되는 로거를 설정합니다. |
|
| [logError(WatermarkException exception, String format, Object[] args)](#logError-com.groupdocs.watermark.exceptions.WatermarkException-java.lang.String-java.lang.Object...-) |  |
| [logError(WatermarkException exception)](#logError-com.groupdocs.watermark.exceptions.WatermarkException-) |  |
| [logWarning(String format, Object[] args)](#logWarning-java.lang.String-java.lang.Object...-) |  |
| [logTrace(String format, Object[] args)](#logTrace-java.lang.String-java.lang.Object...-) |  |
### WatermarkerSettings() {#WatermarkerSettings--}
```
public WatermarkerSettings()
```


새 인스턴스를 초기화합니다.
WatermarkerSettings
클래스.


### getSearchableObjects() {#getSearchableObjects--}
```
public final SearchableObjects getSearchableObjects()
```


가져옵니다
SearchableObjects
워터마크 검색에 포함될 객체입니다.


**Returns:**
[SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) - The  SearchableObjects  that are to be included in a watermark search.

### setSearchableObjects(SearchableObjects value) {#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-}
```
public final void setSearchableObjects(SearchableObjects value)
```


설정
SearchableObjects
워터마크 검색에 포함될 객체입니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) | 워터마크 검색에 포함될 SearchableObjects. |
|

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


워터마크 처리 중 이벤트와 오류를 기록하는 데 사용되는 로거를 가져옵니다.


**Returns:**
[ILogger](../../com.groupdocs.watermark.options/ilogger) - An instance of class that implements `[ILogger](../../com.groupdocs.watermark.options/ilogger)` interface.

### setLogger(ILogger value) {#setLogger-com.groupdocs.watermark.options.ILogger-}
```
public final void setLogger(ILogger value)
```


워터마크 처리 중 이벤트와 오류를 기록하는 데 사용되는 로거를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [ILogger](../../com.groupdocs.watermark.options/ilogger) | `[ILogger](../../com.groupdocs.watermark.options/ilogger)` 인터페이스를 구현하는 클래스의 인스턴스입니다. |
|

### logError(WatermarkException exception, String format, Object[] args) {#logError-com.groupdocs.watermark.exceptions.WatermarkException-java.lang.String-java.lang.Object...-}
```
public final void logError(WatermarkException exception, String format, Object[] args)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| exception | [WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception) |  |
| 형식 | java.lang.String |  |
| 인수 | java.lang.Object[] |  |

### logError(WatermarkException exception) {#logError-com.groupdocs.watermark.exceptions.WatermarkException-}
```
public final void logError(WatermarkException exception)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| exception | [WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception) |  |

### logWarning(String format, Object[] args) {#logWarning-java.lang.String-java.lang.Object...-}
```
public final void logWarning(String format, Object[] args)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 형식 | java.lang.String |  |
| 인수 | java.lang.Object[] |  |

### logTrace(String format, Object[] args) {#logTrace-java.lang.String-java.lang.Object...-}
```
public final void logTrace(String format, Object[] args)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 형식 | java.lang.String |  |
| 인수 | java.lang.Object[] |  |

