---
title: "PresentationImageFillFormat"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "PowerPoint 문서에서 이미지 채우기 형식 설정을 나타냅니다."
type: docs
weight: 85
url: /ko/java/com.groupdocs.watermark.contents/presentationimagefillformat/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.contents.OfficeImageFillFormat
```
public class PresentationImageFillFormat extends OfficeImageFillFormat<PresentationWatermarkableImage>
```

PowerPoint 문서에서 이미지 채우기 형식 설정을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | 이미지가 배경에 타일링되는지 여부를 나타내는 값을 가져옵니다. |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | 이미지가 배경에 타일링되는지 여부를 나타내는 값을 설정합니다. |
|
|  | [getTransparency()](#getTransparency--) | 배경 이미지의 투명도를 0.0(불투명)에서 1.0(완전 투명)까지의 값으로 가져옵니다. |
(완전 투명).
|
|  | [setTransparency(double value)](#setTransparency-double-) | 배경 이미지의 투명도를 0.0(불투명)에서 1.0(완전 투명)까지의 값으로 설정합니다. |
(완전 투명).
|
|  | [getBackgroundImage()](#getBackgroundImage--) | 배경 이미지를 가져옵니다. |
|
|  | [setBackgroundImage(PresentationWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-) | 배경 이미지를 설정합니다. |
|
### getTileAsTexture() {#getTileAsTexture--}
```
public boolean getTileAsTexture()
```


이미지가 배경에 타일링되는지 여부를 나타내는 값을 가져옵니다.


**Returns:**
boolean - 이미지가 배경에 타일 형태로 배치된 경우 true, 그렇지 않으면 false(이미지가 늘어납니다). 기본값은 false입니다.

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public void setTileAsTexture(boolean value)
```


이미지가 배경에 타일링되는지 여부를 나타내는 값을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 이미지가 배경에 타일 형태로 배치된 경우 true, 그렇지 않으면 false(이미지가 늘어납니다). 기본값은 false입니다. |
|

### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


배경 이미지의 투명도를 0.0(불투명)에서 1.0(완전 투명)까지의 값으로 가져옵니다.
(완전 투명).


**Returns:**
double - 배경 이미지의 투명도를 0.0(불투명)부터 1.0(완전 투명)까지 값으로 나타냅니다.

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


배경 이미지의 투명도를 0.0(불투명)에서 1.0(완전 투명)까지의 값으로 설정합니다.
(완전 투명).


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | double | 배경 이미지의 투명도를 0.0(불투명)부터 1.0(완전 투명)까지 값으로 나타냅니다. |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public PresentationWatermarkableImage getBackgroundImage()
```


배경 이미지를 가져옵니다.


**Returns:**
[PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) - The background image. Returns null if the image is not set.

### setBackgroundImage(PresentationWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-}
```
public void setBackgroundImage(PresentationWatermarkableImage value)
```


배경 이미지를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) | 배경 이미지. 이미지가 설정되지 않은 경우 null을 반환합니다. |
|

