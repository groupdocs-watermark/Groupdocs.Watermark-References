---
title: "ColorRange"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "색상 범위를 나타냅니다."
type: docs
weight: 12
url: /ko/java/com.groupdocs.watermark.search/colorrange/
---
**Inheritance:**
java.lang.Object
```
public class ColorRange
```

색상의 범위를 나타냅니다. RGB 색상의 HSB 표현을 사용하여 범위를 지정합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [ColorRange()](#ColorRange--) | 새 `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` 클래스 인스턴스를 초기화합니다. |
|
|  | [ColorRange(Color exactColor)](#ColorRange-com.groupdocs.watermark.watermarks.Color-) | 지정된 정확한 색상을 사용하여 새 `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` 클래스 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getMinHue()](#getMinHue--) | 시작 색조 값을 도 단위로 가져옵니다. |
|
|  | [setMinHue(float value)](#setMinHue-float-) | 시작 색조 값을 도 단위로 설정합니다. |
|
|  | [getMaxHue()](#getMaxHue--) | 끝 색조 값을 도 단위로 가져옵니다. |
|
|  | [setMaxHue(float value)](#setMaxHue-float-) | 끝 색조 값을 도 단위로 설정합니다. |
|
|  | [getMinSaturation()](#getMinSaturation--) | 시작 채도 값을 가져옵니다. |
|
|  | [setMinSaturation(float value)](#setMinSaturation-float-) | 시작 채도 값을 설정합니다. |
|
|  | [getMaxSaturation()](#getMaxSaturation--) | 끝 채도 값을 가져옵니다. |
|
|  | [setMaxSaturation(float value)](#setMaxSaturation-float-) | 끝 채도 값을 설정합니다. |
|
|  | [getMinBrightness()](#getMinBrightness--) | 시작 밝기 값을 가져옵니다. |
|
|  | [setMinBrightness(float value)](#setMinBrightness-float-) | 시작 밝기 값을 설정합니다. |
|
|  | [getMaxBrightness()](#getMaxBrightness--) | 끝 밝기 값을 가져옵니다. |
|
|  | [setMaxBrightness(float value)](#setMaxBrightness-float-) | 끝 밝기 값을 설정합니다. |
|
|  | [isEmpty()](#isEmpty--) | 빈 색상만 범위에 있는지 여부를 나타내는 값을 가져옵니다. |
|
|  | [setEmpty(boolean value)](#setEmpty-boolean-) | 빈 색상만 범위에 있는지 여부를 나타내는 값을 설정합니다. |
|
### ColorRange() {#ColorRange--}
```
public ColorRange()
```


새 `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` 클래스 인스턴스를 초기화합니다.


### ColorRange(Color exactColor) {#ColorRange-com.groupdocs.watermark.watermarks.Color-}
```
public ColorRange(Color exactColor)
```


지정된 정확한 색상을 사용하여 새 `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` 클래스 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | exactColor | [Color](../../com.groupdocs.watermark.watermarks/color) | 범위가 생성되는 정확한 색상입니다. |
|

### getMinHue() {#getMinHue--}
```
public final float getMinHue()
```


시작 색조 값을 도 단위로 가져옵니다.


**Returns:**
float - 시작 색조 값(도 단위).

### setMinHue(float value) {#setMinHue-float-}
```
public final void setMinHue(float value)
```


시작 색조 값을 도 단위로 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | float | 시작 색조 값(도 단위). |
|

### getMaxHue() {#getMaxHue--}
```
public final float getMaxHue()
```


끝 색조 값을 도 단위로 가져옵니다.


**Returns:**
float - 끝 색조 값(도 단위).

### setMaxHue(float value) {#setMaxHue-float-}
```
public final void setMaxHue(float value)
```


끝 색조 값을 도 단위로 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | float | 끝 색조 값(도 단위). |
|

### getMinSaturation() {#getMinSaturation--}
```
public final float getMinSaturation()
```


시작 채도 값을 가져옵니다.


**Returns:**
float - 채도는 0.0부터 1.0까지이며, 0.0은 회색조, 1.0은 가장 포화된 상태를 의미합니다.

### setMinSaturation(float value) {#setMinSaturation-float-}
```
public final void setMinSaturation(float value)
```


시작 채도 값을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | float | 채도는 0.0부터 1.0까지이며, 0.0은 회색조, 1.0은 가장 포화된 상태를 의미합니다. |
|

### getMaxSaturation() {#getMaxSaturation--}
```
public final float getMaxSaturation()
```


끝 채도 값을 가져옵니다.


**Returns:**
float - 채도는 0.0부터 1.0까지이며, 0.0은 회색조, 1.0은 가장 포화된 상태를 의미합니다.

### setMaxSaturation(float value) {#setMaxSaturation-float-}
```
public final void setMaxSaturation(float value)
```


끝 채도 값을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | float | 채도는 0.0부터 1.0까지이며, 0.0은 회색조, 1.0은 가장 포화된 상태를 의미합니다. |
|

### getMinBrightness() {#getMinBrightness--}
```
public final float getMinBrightness()
```


시작 밝기 값을 가져옵니다.


**Returns:**
float - 밝기는 0.0부터 1.0까지이며, 0.0은 검은색, 1.0은 흰색을 나타냅니다.

### setMinBrightness(float value) {#setMinBrightness-float-}
```
public final void setMinBrightness(float value)
```


시작 밝기 값을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | float | 밝기는 0.0부터 1.0까지이며, 0.0은 검은색, 1.0은 흰색을 나타냅니다. |
|

### getMaxBrightness() {#getMaxBrightness--}
```
public final float getMaxBrightness()
```


끝 밝기 값을 가져옵니다.


**Returns:**
float - 밝기는 0.0부터 1.0까지이며, 0.0은 검은색, 1.0은 흰색을 나타냅니다.

### setMaxBrightness(float value) {#setMaxBrightness-float-}
```
public final void setMaxBrightness(float value)
```


끝 밝기 값을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | float | 밝기는 0.0부터 1.0까지이며, 0.0은 검은색, 1.0은 흰색을 나타냅니다. |
|

### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


빈 색상만 범위에 있는지 여부를 나타내는 값을 가져옵니다.


**Returns:**
boolean - 빈 색상만 범위에 있는 경우 true(HSB 범위는 무시됨); 그렇지 않으면 false.

### setEmpty(boolean value) {#setEmpty-boolean-}
```
public final void setEmpty(boolean value)
```


빈 색상만 범위에 있는지 여부를 나타내는 값을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 빈 색상만 범위에 있는 경우 true(HSB 범위는 무시됨); 그렇지 않으면 false. |
|

