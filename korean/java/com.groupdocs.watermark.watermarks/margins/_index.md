---
title: "Margins"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "객체의 각 가장자리에 대한 여백 설정을 나타냅니다."
type: docs
weight: 15
url: /ko/java/com.groupdocs.watermark.watermarks/margins/
---
**Inheritance:**
java.lang.Object
```
public class Margins
```

객체의 각 가장자리에 대한 여백 설정을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [Margins()](#Margins--) | `[Margins](../../com.groupdocs.watermark.watermarks/margins)` 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Margins(int marginType, double left, double right, double top, double bottom)](#Margins-int-double-double-double-double-) | 지정된 유형, 위치 및 크기를 사용하여 `[Margins](../../com.groupdocs.watermark.watermarks/margins)` 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getMarginType()](#getMarginType--) | `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`을 가져옵니다. |
|
|  | [setMarginType(int value)](#setMarginType-int-) | `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`을 설정합니다. |
|
|  | [getLeft()](#getLeft--) | 왼쪽 여백을 가져옵니다. |
|
|  | [setLeft(double value)](#setLeft-double-) | 왼쪽 여백을 설정합니다. |
|
|  | [getRight()](#getRight--) | 오른쪽 여백을 가져옵니다. |
|
|  | [setRight(double value)](#setRight-double-) | 오른쪽 여백을 설정합니다. |
|
|  | [getTop()](#getTop--) | 위쪽 여백을 가져옵니다. |
|
|  | [setTop(double value)](#setTop-double-) | 위쪽 여백을 설정합니다. |
|
|  | [getBottom()](#getBottom--) | 아래쪽 여백을 가져옵니다. |
|
|  | [setBottom(double value)](#setBottom-double-) | 아래쪽 여백을 설정합니다. |
|
### Margins() {#Margins--}
```
public Margins()
```


`[Margins](../../com.groupdocs.watermark.watermarks/margins)` 클래스의 새 인스턴스를 초기화합니다.


### Margins(int marginType, double left, double right, double top, double bottom) {#Margins-int-double-double-double-double-}
```
public Margins(int marginType, double left, double right, double top, double bottom)
```


지정된 유형, 위치 및 크기를 사용하여 `[Margins](../../com.groupdocs.watermark.watermarks/margins)` 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | marginType | int | `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`입니다. 여백 값이 어떻게 해석되어야 하는지 지정합니다. |
|
|  | 왼쪽 | double | 왼쪽 여백 값입니다. |
|
|  | 오른쪽 | double | 오른쪽 여백 값입니다. |
|
|  | 위쪽 | double | 위쪽 여백 값입니다. |
|
|  | 아래쪽 | double | 아래쪽 여백 값입니다. |
|

### getMarginType() {#getMarginType--}
```
public final int getMarginType()
```


`[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`을 가져옵니다. 이 속성에 새 값을 설정하면 모든 여백이 자동으로 기본값(0)으로 반환됩니다.

기본값은 `[MarginType.Absolute](../../com.groupdocs.watermark.watermarks/margintype#Absolute)`입니다.


**Returns:**
int - 여백이 어떻게 해석되어야 하는지를 지정하는 값입니다.

### setMarginType(int value) {#setMarginType-int-}
```
public final void setMarginType(int value)
```


`[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`을 설정합니다. 이 속성에 새 값을 설정하면 모든 여백이 자동으로 기본값(0)으로 반환됩니다.

기본값은 `[MarginType.Absolute](../../com.groupdocs.watermark.watermarks/margintype#Absolute)`입니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | int | 여백이 어떻게 해석되어야 하는지를 지정하는 값입니다. |
|

### getLeft() {#getLeft--}
```
public final double getLeft()
```


왼쪽 여백을 가져옵니다.


**Returns:**
double - 부모 왼쪽 경계선으로부터의 수평 오프셋입니다.

### setLeft(double value) {#setLeft-double-}
```
public final void setLeft(double value)
```


왼쪽 여백을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | double | 부모 왼쪽 테두리로부터의 수평 오프셋. |
|

### getRight() {#getRight--}
```
public final double getRight()
```


오른쪽 여백을 가져옵니다.


**Returns:**
double - 부모 오른쪽 테두리로부터의 수평 오프셋.

### setRight(double value) {#setRight-double-}
```
public final void setRight(double value)
```


오른쪽 여백을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | double | 부모 오른쪽 테두리로부터의 수평 오프셋. |
|

### getTop() {#getTop--}
```
public final double getTop()
```


위쪽 여백을 가져옵니다.


**Returns:**
double - 부모 상단 테두리로부터의 수평 오프셋.

### setTop(double value) {#setTop-double-}
```
public final void setTop(double value)
```


위쪽 여백을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | double | 부모 상단 테두리로부터의 수평 오프셋. |
|

### getBottom() {#getBottom--}
```
public final double getBottom()
```


아래쪽 여백을 가져옵니다.


**Returns:**
double - 부모 하단 테두리로부터의 수평 오프셋.

### setBottom(double value) {#setBottom-double-}
```
public final void setBottom(double value)
```


아래쪽 여백을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | double | 부모 하단 테두리로부터의 수평 오프셋. |
|

