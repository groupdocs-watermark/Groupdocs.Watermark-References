---
title: "MarginType"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "여백 값이 어떻게 해석되어야 하는지를 지정합니다."
type: docs
weight: 14
url: /ko/java/com.groupdocs.watermark.watermarks/margintype/
---
**Inheritance:**
java.lang.Object
```
public final class MarginType
```

여백 값이 어떻게 해석되어야 하는지를 지정합니다.

## 필드

| 필드 | 설명 |
| --- | --- |
|  | [Absolute](#Absolute) | 여백 값은 콘텐츠 단위로 측정됩니다. |
|
|  | [RelativeToParentDimensions](#RelativeToParentDimensions) | 여백 값은 해당 부모 차원의 일부로 해석되어야 합니다. |
|
|  | [RelativeToParentMinDimension](#RelativeToParentMinDimension) | 여백 값은 부모 최소 차원의 일부로 해석되어야 합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [toString(int value)](#toString-int-) | `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` 값의 문자열 표현을 반환합니다. |
|
|  | [parse(String value)](#parse-java.lang.String-) | 문자열을 `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` 열거형 값으로 변환합니다. |
|
### Absolute {#Absolute}
```
public static final int Absolute
```


여백 값은 콘텐츠 단위로 측정됩니다.


### RelativeToParentDimensions {#RelativeToParentDimensions}
```
public static final int RelativeToParentDimensions
```


여백 값은 해당 부모 차원의 일부로 해석되어야 합니다.


왼쪽 및 오른쪽 여백은 부모 너비에 상대적이며,
위와 아래 여백은 부모 높이에 상대적입니다.
이 유형을 선택하면 여백 값은 0.0과 1.0 사이여야 합니다.


### RelativeToParentMinDimension {#RelativeToParentMinDimension}
```
public static final int RelativeToParentMinDimension
```


여백 값은 부모 최소 차원의 일부로 해석되어야 합니다.


이 유형을 선택하면 여백 값은 0.0과 1.0 사이여야 합니다.


### toString(int value) {#toString-int-}
```
public static final String toString(int value)
```


`[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` 값의 문자열 표현을 반환합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | int | 변환할 값. |
|

**Returns:**
java.lang.String - `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` 값의 문자열 표현입니다.

### parse(String value) {#parse-java.lang.String-}
```
public static final int parse(String value)
```


문자열을 `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` 열거형 값으로 변환합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 구문 분석할 문자열. |
|

**Returns:**
int - `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` 열거형 값입니다.

