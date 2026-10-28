---
title: "TextAlignment"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "가능한 텍스트 정렬 값들의 열거형입니다."
type: docs
weight: 17
url: /ko/java/com.groupdocs.watermark.watermarks/textalignment/
---
**Inheritance:**
java.lang.Object
```
public final class TextAlignment
```

가능한 텍스트 정렬 값들의 열거형입니다.

## 필드

| 필드 | 설명 |
| --- | --- |
|  | [Left](#Left) | 왼쪽 정렬. |
|
|  | [Center](#Center) | 가운데 정렬. |
|
|  | [Right](#Right) | 오른쪽 정렬. |
|
|  | [Justify](#Justify) | 양쪽 정렬. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [toString(int value)](#toString-int-) | `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)` 값의 문자열 표현을 반환합니다. |
|
|  | [parse(String value)](#parse-java.lang.String-) | 문자열을 `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)` 열거형 값으로 변환합니다. |
|
### Left {#Left}
```
public static final int Left
```


왼쪽 정렬.


### Center {#Center}
```
public static final int Center
```


가운데 정렬.


### Right {#Right}
```
public static final int Right
```


오른쪽 정렬.


### Justify {#Justify}
```
public static final int Justify
```


양쪽 정렬. 텍스트가 왼쪽 및 오른쪽 여백에 맞춰 정렬됩니다.


### toString(int value) {#toString-int-}
```
public static final String toString(int value)
```


`[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)` 값의 문자열 표현을 반환합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | int | 변환할 값. |
|

**Returns:**
java.lang.String - `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)` 값의 문자열 표현입니다.

### parse(String value) {#parse-java.lang.String-}
```
public static final int parse(String value)
```


문자열을 `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)` 열거형 값으로 변환합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 구문 분석할 문자열. |
|

**Returns:**
int - `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)` 열거형 값입니다.

