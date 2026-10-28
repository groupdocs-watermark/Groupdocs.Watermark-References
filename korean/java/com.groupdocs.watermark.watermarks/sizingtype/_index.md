---
title: "SizingType"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "워터마크 크기가 어떻게 계산되어야 하는지를 지정합니다."
type: docs
weight: 16
url: /ko/java/com.groupdocs.watermark.watermarks/sizingtype/
---
**Inheritance:**
java.lang.Object
```
public final class SizingType
```

워터마크 크기가 어떻게 계산되어야 하는지를 지정합니다.

## 필드

| 필드 | 설명 |
| --- | --- |
|  | [Auto](#Auto) | 워터마크는 내용에 따라 자동으로 크기가 조정되어야 합니다. |
|
|  | [Absolute](#Absolute) | 워터마크는 정확한 `[Watermark.getWidth()](../../com.groupdocs.watermark/watermark#getWidth--)` 로 크기가 지정되어야 합니다. |
그리고 `[Watermark.getHeight()](../../com.groupdocs.watermark/watermark#getHeight--)`.
|
|  | [ScaleToParentDimensions](#ScaleToParentDimensions) | 워터마크는 부모 차원을 기준으로 스케일링되어야 합니다, 사용하여 |
지정된 `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`.
|
|  | [ScaleToParentArea](#ScaleToParentArea) | 워터마크는 지정된 `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)` 를 사용하여 부모 영역을 기준으로 스케일링되어야 합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [toString(int value)](#toString-int-) | `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)` 값의 문자열 표현을 반환합니다. |
|
|  | [parse(String value)](#parse-java.lang.String-) | 문자열을 `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)` 열거형 값으로 구문 분석합니다. |
|
### Auto {#Auto}
```
public static final int Auto
```


워터마크는 내용에 따라 자동으로 크기가 조정되어야 합니다.


### Absolute {#Absolute}
```
public static final int Absolute
```


워터마크는 정확한 `[Watermark.getWidth()](../../com.groupdocs.watermark/watermark#getWidth--)` 로 크기가 지정되어야 합니다.
그리고 `[Watermark.getHeight()](../../com.groupdocs.watermark/watermark#getHeight--)`.


### ScaleToParentDimensions {#ScaleToParentDimensions}
```
public static final int ScaleToParentDimensions
```


워터마크는 부모 차원을 기준으로 스케일링되어야 합니다, 사용하여
지정된 `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`.


### ScaleToParentArea {#ScaleToParentArea}
```
public static final int ScaleToParentArea
```


워터마크는 지정된 `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)` 를 사용하여 부모 영역을 기준으로 스케일링되어야 합니다.


### toString(int value) {#toString-int-}
```
public static final String toString(int value)
```


`[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)` 값의 문자열 표현을 반환합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | int | 변환할 값. |
|

**Returns:**
java.lang.String - `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)` 값의 문자열 표현.

### parse(String value) {#parse-java.lang.String-}
```
public static final int parse(String value)
```


문자열을 `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)` 열거형 값으로 구문 분석합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 구문 분석할 문자열. |
|

**Returns:**
int - `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)` 열거형 값.

