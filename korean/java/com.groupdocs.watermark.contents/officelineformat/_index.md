---
title: "OfficeLineFormat"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "도형 선 형식을 나타냅니다."
type: docs
weight: 47
url: /ko/java/com.groupdocs.watermark.contents/officelineformat/
---
**Inheritance:**
java.lang.Object
```
public final class OfficeLineFormat
```

도형 선 형식을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [OfficeLineFormat()](#OfficeLineFormat--) | 새 인스턴스인 `[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat)` 클래스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getWeight()](#getWeight--) | 도형 경로를 스트로크하는 브러시 두께를 가져옵니다. |
|
|  | [setWeight(double value)](#setWeight-double-) | 도형 경로를 스트로크하는 브러시 두께를 설정합니다. |
|
|  | [getColor()](#getColor--) | 선의 색상을 가져옵니다. |
|
|  | [setColor(Color value)](#setColor-com.groupdocs.watermark.watermarks.Color-) | 선의 색상을 설정합니다. |
|
|  | [getOpacity()](#getOpacity--) | 선의 불투명도를 가져옵니다. |
|
|  | [setOpacity(double value)](#setOpacity-double-) | 선의 불투명도를 설정합니다. |
|
|  | [getEnabled()](#getEnabled--) | 도형이 스트로크될지 여부를 나타내는 값을 가져옵니다. |
|
|  | [setEnabled(boolean value)](#setEnabled-boolean-) | 도형이 스트로크될지 여부를 나타내는 값을 설정합니다. |
|
|  | [getDashStyle()](#getDashStyle--) | 선의 점·대시 패턴을 가져옵니다. |
|
|  | [setDashStyle(int value)](#setDashStyle-int-) | 선의 점·대시 패턴을 설정합니다. |
|
|  | [getLineStyle()](#getLineStyle--) | 선 스타일을 가져옵니다. |
|
|  | [setLineStyle(int value)](#setLineStyle-int-) | 선 스타일을 설정합니다. |
|
|  | [getTransparency()](#getTransparency--) | <br /> |

|
|  | [getColorConsideringOpacity()](#getColorConsideringOpacity--) | <br /> |

|
### OfficeLineFormat() {#OfficeLineFormat--}
```
public OfficeLineFormat()
```


새 인스턴스인 `[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat)` 클래스를 초기화합니다.


### getWeight() {#getWeight--}
```
public final double getWeight()
```


도형 경로를 스트로크하는 브러시 두께를 가져옵니다.


**Returns:**
double - 포인트 단위의 선 두께입니다. 기본값은 0.75입니다.

### setWeight(double value) {#setWeight-double-}
```
public final void setWeight(double value)
```


도형 경로를 스트로크하는 브러시 두께를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | double | 포인트 단위의 선 두께입니다. 기본값은 0.75입니다. |
|

### getColor() {#getColor--}
```
public final Color getColor()
```


선의 색상을 가져옵니다.

기본값은 `[Color.getBlack()](../../com.groupdocs.watermark.watermarks/color#getBlack--)`입니다.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The color of the line.

### setColor(Color value) {#setColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setColor(Color value)
```


선의 색상을 설정합니다.

기본값은 `[Color.getBlack()](../../com.groupdocs.watermark.watermarks/color#getBlack--)`입니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | 선의 색상입니다. |
|

### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


선의 불투명도를 가져옵니다.


**Returns:**
double - 값은 0과 1 사이여야 합니다. 기본값은 1입니다.

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


선의 불투명도를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | double | 값은 0과 1 사이여야 합니다. 기본값은 1입니다. |
|

### getEnabled() {#getEnabled--}
```
public final boolean getEnabled()
```


도형이 스트로크될지 여부를 나타내는 값을 가져옵니다.


**Returns:**
boolean - 기본값은 false입니다.

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


도형이 스트로크될지 여부를 나타내는 값을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 기본값은 false입니다. |
|

### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


선의 점·대시 패턴을 가져옵니다.

<br />



**Returns:**
int
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


선의 점·대시 패턴을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getLineStyle() {#getLineStyle--}
```
public final int getLineStyle()
```


선 스타일을 가져옵니다.

기본값은 `[OfficeLineStyle.Single](../../com.groupdocs.watermark.contents/officelinestyle#Single)`입니다.


**Returns:**
int - 선 스타일입니다.

### setLineStyle(int value) {#setLineStyle-int-}
```
public final void setLineStyle(int value)
```


선 스타일을 설정합니다.

기본값은 `[OfficeLineStyle.Single](../../com.groupdocs.watermark.contents/officelinestyle#Single)`입니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | int | 선 스타일입니다. |
|

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


<br />



**Returns:**
double
### getColorConsideringOpacity() {#getColorConsideringOpacity--}
```
public final Color getColorConsideringOpacity()
```


<br />



**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color)
