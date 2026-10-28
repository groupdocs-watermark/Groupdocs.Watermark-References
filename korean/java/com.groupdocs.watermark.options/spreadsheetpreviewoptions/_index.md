---
title: "SpreadsheetPreviewOptions"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "스프레드시트 문서의 미리보기 생성을 위한 요구 사항 및 스트림 대리자를 설정하는 옵션을 제공합니다."
type: docs
weight: 52
url: /ko/java/com.groupdocs.watermark.options/spreadsheetpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class SpreadsheetPreviewOptions extends PreviewOptions
```

스프레드시트 문서의 미리보기 생성을 위한 요구 사항 및 스트림 대리자를 설정하는 옵션을 제공합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [SpreadsheetPreviewOptions(ICreatePageStream createPageStream)](#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` 클래스의 새 인스턴스를 초기화하여 출력 스트림을 닫습니다. |
|
|  | [SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` 클래스의 새 인스턴스를 초기화하여 출력 스트림을 클라이언트에 반환하고 이후에 사용할 수 있게 합니다. |
|
## 필드

| 필드 | 설명 |
| --- | --- |
|  | [DefaultResolution](#DefaultResolution) | 기본 해상도(인치당 도트 수). |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getResolution()](#getResolution--) | 생성된 이미지의 해상도를 인치당 도트 수로 가져옵니다. |
|
|  | [setResolution(int value)](#setResolution-int-) | 생성된 이미지의 해상도를 인치당 도트 수로 설정합니다. |
|
|  | [getOnlyDataArea()](#getOnlyDataArea--) | 헤더, 푸터, 여백 없이 데이터 영역만 렌더링하기 위한 플래그를 가져옵니다. |
|
|  | [setOnlyDataArea(boolean value)](#setOnlyDataArea-boolean-) | 헤더, 푸터, 여백 없이 데이터 영역만 렌더링하기 위한 플래그를 설정합니다. |
|
### SpreadsheetPreviewOptions(ICreatePageStream createPageStream) {#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public SpreadsheetPreviewOptions(ICreatePageStream createPageStream)
```


`[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` 클래스의 새 인스턴스를 초기화하여 출력 스트림을 닫습니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | 특정 페이지 미리보기를 위한 스트림을 생성합니다. |
|

### SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


`[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` 클래스의 새 인스턴스를 초기화하여 출력 스트림을 클라이언트에 반환하고 이후에 사용할 수 있게 합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | 특정 페이지 미리보기를 위한 스트림을 생성합니다. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | 페이지 미리보기 생성이 완료되었음을 알리고 출력 스트림을 가져옵니다. |
|

### DefaultResolution {#DefaultResolution}
```
public static final int DefaultResolution
```


기본 해상도(인치당 도트 수).


### getResolution() {#getResolution--}
```
public final int getResolution()
```


생성된 이미지의 해상도를 인치당 도트 수로 가져옵니다.


**Returns:**
int - 생성된 이미지의 해상도(인치당 도트 수)입니다.

<br />

*** ** * ** ***

기본값은 96입니다.

<br />


### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


생성된 이미지의 해상도를 인치당 도트 수로 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | int | 생성된 이미지의 해상도, 인치당 도트 수. |

<br />

*** ** * ** ***

기본값은 96입니다.

<br />

|

### getOnlyDataArea() {#getOnlyDataArea--}
```
public final boolean getOnlyDataArea()
```


헤더, 푸터, 여백 없이 데이터 영역만 렌더링하기 위한 플래그를 가져옵니다.


**Returns:**
boolean - 헤더, 푸터, 여백 없이 데이터 영역만 렌더링하기 위한 플래그입니다.

<br />

*** ** * ** ***

이 플래그는 전체 워크시트를 한 페이지에 렌더링하도록 합니다. 기본값은 false입니다.

<br />


### setOnlyDataArea(boolean value) {#setOnlyDataArea-boolean-}
```
public final void setOnlyDataArea(boolean value)
```


헤더, 푸터, 여백 없이 데이터 영역만 렌더링하기 위한 플래그를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 헤더, 푸터, 여백 없이 데이터 영역만 렌더링하기 위한 플래그. |

<br />

*** ** * ** ***

이 플래그는 전체 워크시트를 한 페이지에 렌더링하도록 합니다. 기본값은 false입니다.

<br />

|

