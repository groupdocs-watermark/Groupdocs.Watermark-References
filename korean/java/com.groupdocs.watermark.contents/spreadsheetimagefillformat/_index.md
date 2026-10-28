---
title: "SpreadsheetImageFillFormat"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "Excel 문서의 이미지 채우기 형식 설정을 나타냅니다."
type: docs
weight: 114
url: /ko/java/com.groupdocs.watermark.contents/spreadsheetimagefillformat/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.contents.OfficeImageFillFormat
```
public class SpreadsheetImageFillFormat extends OfficeImageFillFormat<SpreadsheetWatermarkableImage>
```

Excel 문서의 이미지 채우기 형식 설정을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | 이미지가 배경에 타일링되는지 여부를 나타내는 값을 가져옵니다. |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | 이미지가 배경에 타일링되는지 여부를 나타내는 값을 설정합니다. |
|
|  | [getTransparency()](#getTransparency--) | 배경 이미지의 투명도를 0.0(불투명)부터 값으로 가져옵니다 |
1.0(완전 투명)까지.
|
|  | [setTransparency(double value)](#setTransparency-double-) | 배경 이미지의 투명도를 0.0(불투명)부터 값으로 설정합니다 |
1.0(완전 투명)까지.
|
|  | [getBackgroundImage()](#getBackgroundImage--) | 배경 이미지를 가져옵니다. |
|
|  | [setBackgroundImage(SpreadsheetWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | 배경 이미지를 설정합니다. |
|
### getTileAsTexture() {#getTileAsTexture--}
```
public boolean getTileAsTexture()
```


이미지가 배경에 타일링되는지 여부를 나타내는 값을 가져옵니다.


**Returns:**
boolean - 이미지가 배경에 타일링되는 경우 true; 그렇지 않으면 false(이미지가 늘어납니다).

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public void setTileAsTexture(boolean value)
```


이미지가 배경에 타일링되는지 여부를 나타내는 값을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 이미지가 배경에 타일링되는 경우 true; 그렇지 않으면 false(이미지가 늘어납니다). |
|

### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


배경 이미지의 투명도를 0.0(불투명)부터 값으로 가져옵니다
1.0(완전 투명)까지.


**Returns:**
double - 배경 이미지의 투명도를 0.0(불투명)부터 1.0(완전 투명)까지 값으로 나타냅니다.

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


배경 이미지의 투명도를 0.0(불투명)부터 값으로 설정합니다
1.0(완전 투명)까지.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | double | 배경 이미지의 투명도를 0.0(불투명)부터 1.0(완전 투명)까지 값으로 나타냅니다. |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public SpreadsheetWatermarkableImage getBackgroundImage()
```


배경 이미지를 가져옵니다.


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The background image. Returns null if the image is not set.

### setBackgroundImage(SpreadsheetWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public void setBackgroundImage(SpreadsheetWatermarkableImage value)
```


배경 이미지를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | 배경 이미지. 이미지가 설정되지 않은 경우 null을 반환합니다. |
|

