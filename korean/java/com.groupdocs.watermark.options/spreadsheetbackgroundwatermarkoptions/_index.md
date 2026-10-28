---
title: "SpreadsheetBackgroundWatermarkOptions"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "스프레드시트 워크시트에 배경으로 워터마크를 추가할 때 옵션을 나타냅니다."
type: docs
weight: 49
url: /ko/java/com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)
```
public final class SpreadsheetBackgroundWatermarkOptions extends SpreadsheetWatermarkOptions
```

스프레드시트 워크시트에 배경으로 워터마크를 추가할 때 옵션을 나타냅니다.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

다음 예제는 텍스트 워터마크를 Excel 문서 워크시트에 배경으로 추가하는 방법을 보여줍니다.
>
> ````
> ```
>
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\Documents\\test.xlsx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36));
>
>    SpreadsheetBackgroundWatermarkOptions options = new SpreadsheetBackgroundWatermarkOptions();
>    options.setWorksheetIndex(-1); // default
>    options.setBackgroundWidth(800);
>    options.setBackgroundHeight(600);
>    
>    watermarker.save("C:\\Documents\\watermarked_test.xlsx");
>    watermarker.close();
>  
> ```
> ````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [SpreadsheetBackgroundWatermarkOptions()](#SpreadsheetBackgroundWatermarkOptions--) | `[SpreadsheetBackgroundWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions)` 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | 워터마크를 추가할 워크시트의 인덱스를 가져옵니다. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | 워터마크를 추가할 워크시트의 인덱스를 설정합니다. |
|
|  | [getBackgroundWidth()](#getBackgroundWidth--) | 배경 이미지의 원하는 너비(픽셀)를 가져옵니다. |
|
|  | [setBackgroundWidth(int value)](#setBackgroundWidth-int-) | 배경 이미지의 원하는 너비(픽셀)를 설정합니다. |
|
|  | [getBackgroundHeight()](#getBackgroundHeight--) | 배경 이미지의 원하는 높이(픽셀)를 가져오거나 설정합니다. |
|
|  | [setBackgroundHeight(int value)](#setBackgroundHeight-int-) | 배경 이미지의 원하는 높이(픽셀)를 가져오거나 설정합니다. |
|
### SpreadsheetBackgroundWatermarkOptions() {#SpreadsheetBackgroundWatermarkOptions--}
```
public SpreadsheetBackgroundWatermarkOptions()
```


`[SpreadsheetBackgroundWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions)` 클래스의 새 인스턴스를 초기화합니다.


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


워터마크를 추가할 워크시트의 인덱스를 가져옵니다.

-1 means every worksheet.


**Returns:**
int - 워터마크를 추가할 워크시트의 인덱스.

### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


워터마크를 추가할 워크시트의 인덱스를 설정합니다.

-1 means every worksheet.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | int | 워터마크를 추가할 워크시트의 인덱스. |
|

### getBackgroundWidth() {#getBackgroundWidth--}
```
public final int getBackgroundWidth()
```


배경 이미지의 원하는 너비(픽셀)를 가져옵니다.


**Returns:**
int - 배경 이미지의 원하는 너비(픽셀).

### setBackgroundWidth(int value) {#setBackgroundWidth-int-}
```
public final void setBackgroundWidth(int value)
```


배경 이미지의 원하는 너비(픽셀)를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | int | 배경 이미지의 원하는 너비(픽셀). |
|

### getBackgroundHeight() {#getBackgroundHeight--}
```
public final int getBackgroundHeight()
```


배경 이미지의 원하는 높이(픽셀)를 가져오거나 설정합니다.


**Returns:**
int - 배경 이미지의 원하는 높이(픽셀).

### setBackgroundHeight(int value) {#setBackgroundHeight-int-}
```
public final void setBackgroundHeight(int value)
```


배경 이미지의 원하는 높이(픽셀)를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | int | 배경 이미지의 원하는 높이(픽셀). |
|

