---
title: "SpreadsheetWatermarkModernWordArtOptions"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "스프레드시트 워크시트에 최신 워드 아트 워터마크를 추가할 때 옵션을 나타냅니다."
type: docs
weight: 58
url: /ko/java/com.groupdocs.watermark.options/spreadsheetwatermarkmodernwordartoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkBaseOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions)
```
public final class SpreadsheetWatermarkModernWordArtOptions extends SpreadsheetWatermarkBaseOptions
```

스프레드시트 워크시트에 최신 워드 아트 워터마크를 추가할 때 옵션을 나타냅니다.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

다음 예제는 Excel 문서에 최신 WordArt 워터마크를 추가하는 방법을 보여줍니다.
>
> ````
> ```
>
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.xls", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    SpreadsheetWatermarkModernWordArtOptions options = new SpreadsheetWatermarkModernWordArtOptions();
>    options.setWorksheetIndex(-1); // default
>    options.setLocked(false); // default
>    
>    watermarker.save("D:\\watermarked_test.xlsx");
>    watermarker.close();
>  
> ```
> ````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [SpreadsheetWatermarkModernWordArtOptions()](#SpreadsheetWatermarkModernWordArtOptions--) | `[SpreadsheetWatermarkModernWordArtOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkmodernwordartoptions)` 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | 워터마크를 추가할 워크시트의 인덱스를 가져옵니다. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | 워터마크를 추가할 워크시트의 인덱스를 설정합니다. |
|
### SpreadsheetWatermarkModernWordArtOptions() {#SpreadsheetWatermarkModernWordArtOptions--}
```
public SpreadsheetWatermarkModernWordArtOptions()
```


`[SpreadsheetWatermarkModernWordArtOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkmodernwordartoptions)` 클래스의 새 인스턴스를 초기화합니다.


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


워터마크를 추가할 워크시트의 인덱스를 가져옵니다.


**Returns:**
int - 워터마크를 추가할 워크시트의 인덱스.

<br />

*** ** * ** ***

-1 means every worksheet.

<br />


### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


워터마크를 추가할 워크시트의 인덱스를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | int | 워터마크를 추가할 워크시트의 인덱스. |

<br />

*** ** * ** ***

-1 means every worksheet.

<br />

|

