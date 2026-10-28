---
title: "SpreadsheetWatermarkShapeOptions"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "스프레드시트 워크시트에 도형 워터마크를 추가할 때 옵션을 나타냅니다."
type: docs
weight: 60
url: /ko/java/com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkBaseOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions)
```
public final class SpreadsheetWatermarkShapeOptions extends SpreadsheetWatermarkBaseOptions
```

스프레드시트 워크시트에 도형 워터마크를 추가할 때 옵션을 나타냅니다.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

다음 예제는 Excel 문서의 특정 워크시트에 워터마크를 추가하는 방법을 보여줍니다.
>
> ````
> ```
>
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.xls", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    SpreadsheetWatermarkShapeOptions options = new SpreadsheetWatermarkShapeOptions();
>    options.setWorksheetIndex(0);
>    
>    watermarker.save("D:\\watermarked_test.xlsx");
>    watermarker.close();
>  
> ```
> ````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [SpreadsheetWatermarkShapeOptions()](#SpreadsheetWatermarkShapeOptions--) | 새로운 `[SpreadsheetWatermarkShapeOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions)` 클래스의 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | 워터마크를 추가할 워크시트의 인덱스를 가져옵니다. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | 워터마크를 추가할 워크시트의 인덱스를 설정합니다. |
|
|  | [getEffects()](#getEffects--) | `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` 또는 `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` 값을 가져와 워터마크에 적용할 효과를 지정합니다. |
|
|  | [setEffects(ISpreadsheetWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-) | `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` 또는 `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` 값을 가져오거나 설정하여 워터마크에 적용할 효과를 지정합니다. |
|
### SpreadsheetWatermarkShapeOptions() {#SpreadsheetWatermarkShapeOptions--}
```
public SpreadsheetWatermarkShapeOptions()
```


새로운 `[SpreadsheetWatermarkShapeOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions)` 클래스의 인스턴스를 초기화합니다.


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

### getEffects() {#getEffects--}
```
public final ISpreadsheetWatermarkEffects getEffects()
```


`[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` 또는 `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` 값을 가져와 워터마크에 적용할 효과를 지정합니다.


**Returns:**
[ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) - The `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` or `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` for effects that should be applied to the watermark.

### setEffects(ISpreadsheetWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-}
```
public final void setEffects(ISpreadsheetWatermarkEffects value)
```


`[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` 또는 `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` 값을 가져오거나 설정하여 워터마크에 적용할 효과를 지정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) | `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` 또는 `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)`는 워터마크에 적용해야 하는 효과를 위한 것입니다. |
|

