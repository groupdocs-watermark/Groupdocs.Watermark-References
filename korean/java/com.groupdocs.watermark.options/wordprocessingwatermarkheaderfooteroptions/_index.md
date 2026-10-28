---
title: "WordProcessingWatermarkHeaderFooterOptions"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "Word 섹션 머리글/바닥글에 워터마크를 추가할 때 옵션을 나타냅니다."
type: docs
weight: 74
url: /ko/java/com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkHeaderFooterOptions extends WordProcessingWatermarkBaseOptions
```

Word 섹션 머리글/바닥글에 워터마크를 추가할 때 옵션을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [WordProcessingWatermarkHeaderFooterOptions()](#WordProcessingWatermarkHeaderFooterOptions--) | `[WordProcessingWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions)` 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getSectionIndex()](#getSectionIndex--) | 워터마크를 추가할 섹션의 인덱스를 가져옵니다. |
|
|  | [setSectionIndex(int value)](#setSectionIndex-int-) | 워터마크를 추가할 섹션의 인덱스를 설정합니다. |
|
|  | [getHeaderFooterType()](#getHeaderFooterType--) | 워터마크를 추가할 머리글 또는 바닥글 유형을 식별하는 값을 가져옵니다. |
|
|  | [setHeaderFooterType(int value)](#setHeaderFooterType-int-) | 워터마크를 추가할 머리글 또는 바닥글 유형을 식별하는 값을 설정합니다. |
|
### WordProcessingWatermarkHeaderFooterOptions() {#WordProcessingWatermarkHeaderFooterOptions--}
```
public WordProcessingWatermarkHeaderFooterOptions()
```


`[WordProcessingWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions)` 클래스의 새 인스턴스를 초기화합니다.


### getSectionIndex() {#getSectionIndex--}
```
public final int getSectionIndex()
```


워터마크를 추가할 섹션의 인덱스를 가져옵니다.


**Returns:**
int - 워터마크를 추가할 섹션의 인덱스.

<br />

*** ** * ** ***

-1 means all sections.

<br />


### setSectionIndex(int value) {#setSectionIndex-int-}
```
public final void setSectionIndex(int value)
```


워터마크를 추가할 섹션의 인덱스를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | int | 워터마크를 추가할 섹션의 인덱스. |

<br />

*** ** * ** ***

-1 means all sections.

<br />

|

### getHeaderFooterType() {#getHeaderFooterType--}
```
public final int getHeaderFooterType()
```


워터마크를 추가할 머리글 또는 바닥글 유형을 식별하는 값을 가져옵니다.


**Returns:**
int - 워터마크를 추가할 머리글 또는 바닥글 유형을 식별하는 `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` 타입의 값.

### setHeaderFooterType(int value) {#setHeaderFooterType-int-}
```
public final void setHeaderFooterType(int value)
```


워터마크를 추가할 머리글 또는 바닥글 유형을 식별하는 값을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | int | `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` 타입의 값으로, 워터마크를 추가할 머리글 또는 바닥글 유형을 식별합니다. |
|

