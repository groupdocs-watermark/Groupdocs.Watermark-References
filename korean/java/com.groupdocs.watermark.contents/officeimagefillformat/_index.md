---
title: "OfficeImageFillFormat"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "지원되는 모든 오피스 콘텐츠의 이미지 채우기 형식 설정을 나타냅니다."
type: docs
weight: 46
url: /ko/java/com.groupdocs.watermark.contents/officeimagefillformat/
---
**Inheritance:**
java.lang.Object
```
public abstract class OfficeImageFillFormat<TWatermarkableImage>
```

지원되는 모든 오피스 콘텐츠의 이미지 채우기 형식 설정을 나타냅니다.


TWatermarkableImage
: 배경으로 사용되는 워터마크 가능한 이미지의 정확한 유형입니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [OfficeImageFillFormat()](#OfficeImageFillFormat--) | <br /> |

|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | 이미지가 배경에 타일링되는지 여부를 나타내는 값을 가져옵니다. |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | 이미지가 배경에 타일링되는지 여부를 나타내는 값을 설정합니다. |
|
|  | [getTransparency()](#getTransparency--) | 배경 이미지의 투명도를 0.0(불투명)에서 1.0(완전 투명)까지의 값으로 가져옵니다. |
|
|  | [setTransparency(double value)](#setTransparency-double-) | 배경 이미지의 투명도를 0.0(불투명)에서 1.0(완전 투명)까지의 값으로 설정합니다. |
|
|  | [getBackgroundImage()](#getBackgroundImage--) | 배경 이미지를 가져옵니다. |
|
|  | [setBackgroundImage(TWatermarkableImage value)](#setBackgroundImage-TWatermarkableImage-) | 배경 이미지를 설정합니다. |
|
|  | [checkIfBackgroundImageIsSet()](#checkIfBackgroundImageIsSet--) | <br /> |

|
### OfficeImageFillFormat() {#OfficeImageFillFormat--}
```
public OfficeImageFillFormat()
```


<br />



### getTileAsTexture() {#getTileAsTexture--}
```
public abstract boolean getTileAsTexture()
```


이미지가 배경에 타일링되는지 여부를 나타내는 값을 가져옵니다.


**Returns:**
boolean - 이미지가 배경에 타일링되는 경우 true; 그렇지 않으면 false(이미지가 늘어납니다).

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public abstract void setTileAsTexture(boolean value)
```


이미지가 배경에 타일링되는지 여부를 나타내는 값을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 이미지가 배경에 타일링되는 경우 true; 그렇지 않으면 false(이미지가 늘어납니다). |
|

### getTransparency() {#getTransparency--}
```
public abstract double getTransparency()
```


배경 이미지의 투명도를 0.0(불투명)에서 1.0(완전 투명)까지의 값으로 가져옵니다.


**Returns:**
double - 배경 이미지의 투명도를 0.0(불투명)부터 1.0(완전 투명)까지 값으로 나타냅니다.

### setTransparency(double value) {#setTransparency-double-}
```
public abstract void setTransparency(double value)
```


배경 이미지의 투명도를 0.0(불투명)에서 1.0(완전 투명)까지의 값으로 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | double | 배경 이미지의 투명도를 0.0(불투명)부터 1.0(완전 투명)까지 값으로 나타냅니다. |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public abstract TWatermarkableImage getBackgroundImage()
```


배경 이미지를 가져옵니다.


**Returns:**
TWatermarkableImage - 배경 이미지입니다. 이미지가 설정되지 않은 경우 null을 반환합니다.

### setBackgroundImage(TWatermarkableImage value) {#setBackgroundImage-TWatermarkableImage-}
```
public abstract void setBackgroundImage(TWatermarkableImage value)
```


배경 이미지를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | TWatermarkableImage | 배경 이미지. 이미지가 설정되지 않은 경우 null을 반환합니다. |
|

### checkIfBackgroundImageIsSet() {#checkIfBackgroundImageIsSet--}
```
public final void checkIfBackgroundImageIsSet()
```


<br />



