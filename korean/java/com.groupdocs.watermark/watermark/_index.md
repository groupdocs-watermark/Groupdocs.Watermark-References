---
title: "워터마크"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "문서에 추가될 워터마크를 나타냅니다."
type: docs
weight: 13
url: /ko/java/com.groupdocs.watermark/watermark/
---
**Inheritance:**
java.lang.Object
```
public abstract class Watermark
```

문서에 추가될 워터마크를 나타냅니다.

**Learn more**

* More details about watermark properties:
  [Adding text watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+text+watermarks).

* More advanced watermarking topics: [Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks)

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Watermark()](#Watermark--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getOpacity()](#getOpacity--) | 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 불투명도를 가져오거나 설정합니다. |
|
|  | [setOpacity(double value)](#setOpacity-double-) | 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 불투명도를 가져오거나 설정합니다. |
|
|  | [getY()](#getY--) | 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 y 좌표를 가져옵니다. |
|
|  | [setY(double value)](#setY-double-) | 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 y 좌표를 설정합니다. |
|
|  | [getX()](#getX--) | 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 x 좌표를 가져옵니다. |
|
|  | [setX(double value)](#setX-double-) | 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 x 좌표를 설정합니다. |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 수직 정렬을 가져옵니다. |
|
|  | [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 수직 정렬을 설정합니다. |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 수평 정렬을 가져옵니다. |
|
|  | [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 수평 정렬을 설정합니다. |
|
|  | [getRotateAngle()](#getRotateAngle--) | 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 회전 각도를(도 단위) 가져옵니다. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 회전 각도를(도 단위) 설정합니다. |
|
|  | [isBackground()](#isBackground--) | 워터마크를 배경에 배치할지 여부를 나타내는 값을 가져옵니다. |
|
|  | [setBackground(boolean value)](#setBackground-boolean-) | 워터마크를 배경에 배치할지 여부를 나타내는 값을 설정합니다. |
|
|  | [getMargins()](#getMargins--) | 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 여백 설정을 가져옵니다. |
|
|  | [setMargins(Margins value)](#setMargins-com.groupdocs.watermark.watermarks.Margins-) | 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 여백 설정을 설정합니다. |
|
|  | [getPagesSetup()](#getPagesSetup--) | 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 페이지 설정을 가져옵니다. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.watermark.PagesSetup-) | 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 페이지 설정을 설정합니다. |
|
|  | [getHeight()](#getHeight--) | 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 원하는 높이를 가져옵니다. |
|
|  | [setHeight(double value)](#setHeight-double-) | 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 원하는 높이를 설정합니다. |
|
|  | [getWidth()](#getWidth--) | 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 원하는 너비를 가져옵니다. |
|
|  | [setWidth(double value)](#setWidth-double-) | 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 원하는 너비를 설정합니다. |
|
|  | [getScaleFactor()](#getScaleFactor--) | 워터마크 크기가 부모 크기에 어떻게 의존하는지를 정의하는 값을 가져옵니다. |
|
|  | [setScaleFactor(double value)](#setScaleFactor-double-) | 워터마크 크기가 부모 크기에 어떻게 의존하는지를 정의하는 값을 설정합니다. |
|
|  | [getSizingType()](#getSizingType--) | 워터마크의 크기 지정 방식을 나타내는 값을 가져옵니다. |
|
|  | [setSizingType(int value)](#setSizingType-int-) | 워터마크의 크기 지정 방식을 나타내는 값을 설정합니다. |
|
|  | [getConsiderParentMargins()](#getConsiderParentMargins--) | 워터마크 크기와 좌표가 계산되는지 여부를 나타내는 값을 가져옵니다 |
부모 여백을 고려합니다.
|
|  | [setConsiderParentMargins(boolean value)](#setConsiderParentMargins-boolean-) | 워터마크 크기와 좌표가 계산되는지 여부를 나타내는 값을 설정합니다 |
부모 여백을 고려합니다.
|
| [isImageWatermark()](#isImageWatermark--) |  |
| [isTextWatermark()](#isTextWatermark--) |  |
| [getTransparency()](#getTransparency--) |  |
| [getSize()](#getSize--) |  |
| [getTileOptions()](#getTileOptions--) |  |
| [setTileOptions(TileOptions tileOptions)](#setTileOptions-com.groupdocs.watermark.watermarks.TileOptions-) |  |
| [copyPropertiesValues(Watermark source, Watermark destination)](#copyPropertiesValues-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.Watermark-) |  |
| [deepClone()](#deepClone--) |  |
| [hasSameValues(Watermark watermark)](#hasSameValues-com.groupdocs.watermark.Watermark-) |  |
| [createGeometry(ContentPartGeometry parent)](#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-) |  |
### Watermark() {#Watermark--}
```
public Watermark()
```




### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 불투명도를 가져오거나 설정합니다.

불투명도 값은 0과 1 사이여야 합니다. 기본값은 1입니다.


**Returns:**
double - 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 불투명도.

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 불투명도를 가져오거나 설정합니다.

불투명도 값은 0과 1 사이여야 합니다. 기본값은 1입니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | double | 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 불투명도. |
|

### getY() {#getY--}
```
public final double getY()
```


이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 y 좌표를 가져옵니다.


**Returns:**
double - 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 y좌표.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 y 좌표를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | double | 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 y좌표. |
|

### getX() {#getX--}
```
public final double getX()
```


이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 x 좌표를 가져옵니다.


**Returns:**
double - 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 x좌표.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 x 좌표를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | double | 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 x좌표. |
|

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 수직 정렬을 가져옵니다.

기본값은 `[VerticalAlignment.None](../../com.groupdocs.watermark.common/verticalalignment#None)`입니다.


**Returns:**
int - 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 `[VerticalAlignment](../../com.groupdocs.watermark.common/verticalalignment)`.

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 수직 정렬을 설정합니다.

기본값은 `[VerticalAlignment.None](../../com.groupdocs.watermark.common/verticalalignment#None)`입니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | int | 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 `[VerticalAlignment](../../com.groupdocs.watermark.common/verticalalignment)`. |
|

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 수평 정렬을 가져옵니다.

기본값은 `[HorizontalAlignment.None](../../com.groupdocs.watermark.common/horizontalalignment#None)`입니다.


**Returns:**
int - 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 `[HorizontalAlignment](../../com.groupdocs.watermark.common/horizontalalignment)`.

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public final void setHorizontalAlignment(int value)
```


이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 수평 정렬을 설정합니다.

기본값은 `[HorizontalAlignment.None](../../com.groupdocs.watermark.common/horizontalalignment#None)`입니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | int | 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 `[HorizontalAlignment](../../com.groupdocs.watermark.common/horizontalalignment)`. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 회전 각도를(도 단위) 가져옵니다.


**Returns:**
double - 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 회전 각도(도).

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 회전 각도를(도 단위) 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | double | 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 회전 각도(도). |
|

### isBackground() {#isBackground--}
```
public final boolean isBackground()
```


워터마크를 배경에 배치할지 여부를 나타내는 값을 가져옵니다.


**Returns:**
boolean - 값이 true이면 워터마크가 하단에 배치됩니다. 기본값은 false이며, 워터마크는 상단에 배치됩니다.

### setBackground(boolean value) {#setBackground-boolean-}
```
public final void setBackground(boolean value)
```


워터마크를 배경에 배치할지 여부를 나타내는 값을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 값이 true이면 워터마크가 하단에 배치됩니다. 기본값은 false이며, 워터마크는 상단에 배치됩니다. |
|

### getMargins() {#getMargins--}
```
public final Margins getMargins()
```


이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 여백 설정을 가져옵니다.


**Returns:**
[Margins](../../com.groupdocs.watermark.watermarks/margins) - The margin settings of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setMargins(Margins value) {#setMargins-com.groupdocs.watermark.watermarks.Margins-}
```
public final void setMargins(Margins value)
```


이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 여백 설정을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [Margins](../../com.groupdocs.watermark.watermarks/margins) | 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 여백 설정. |
|

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 페이지 설정을 가져옵니다.


**Returns:**
[PagesSetup](../../com.groupdocs.watermark/pagessetup) - The pages setup settings of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.watermark.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 페이지 설정을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 페이지 설정. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 원하는 높이를 가져옵니다.


**Returns:**
double - 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 원하는 높이.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 원하는 높이를 설정합니다.

이 속성을 설정하면 `#getSizingType().getSizingType()`의 값도 변경됩니다.
속성을 `[SizingType.Absolute](../../com.groupdocs.watermark.watermarks/sizingtype#Absolute)` 로 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | double | 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 원하는 높이. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 원하는 너비를 가져옵니다.


**Returns:**
double - 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 원하는 너비.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 원하는 너비를 설정합니다.

이 속성을 설정하면 `#getSizingType().getSizingType()`의 값도 변경됩니다.
속성을 `[SizingType.Absolute](../../com.groupdocs.watermark.watermarks/sizingtype#Absolute)` 로 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | double | 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 원하는 너비. |
|

### getScaleFactor() {#getScaleFactor--}
```
public final double getScaleFactor()
```


워터마크 크기가 부모 크기에 어떻게 의존하는지를 정의하는 값을 가져옵니다.

값은 0과 1 사이여야 합니다.


**Returns:**
double - 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 배율.

### setScaleFactor(double value) {#setScaleFactor-double-}
```
public final void setScaleFactor(double value)
```


워터마크 크기가 부모 크기에 어떻게 의존하는지를 정의하는 값을 설정합니다.

값은 0과 1 사이여야 합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | double | 이 `[Watermark](../../com.groupdocs.watermark/watermark)`의 배율. |
|

### getSizingType() {#getSizingType--}
```
public final int getSizingType()
```


워터마크의 크기 지정 방식을 나타내는 값을 가져옵니다.


**Returns:**
int - 크기 지정 유형.

### setSizingType(int value) {#setSizingType-int-}
```
public final void setSizingType(int value)
```


워터마크의 크기 지정 방식을 나타내는 값을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | int | 크기 지정 유형. |
|

### getConsiderParentMargins() {#getConsiderParentMargins--}
```
public final boolean getConsiderParentMargins()
```


워터마크 크기와 좌표가 계산되는지 여부를 나타내는 값을 가져옵니다
부모 여백을 고려합니다.


**Returns:**
boolean - 값이 true이면 워터마크 크기와 좌표가 상위 여백을 고려하여 계산됩니다. 기본값은 false이며, 상위 여백은 무시됩니다.

### setConsiderParentMargins(boolean value) {#setConsiderParentMargins-boolean-}
```
public final void setConsiderParentMargins(boolean value)
```


워터마크 크기와 좌표가 계산되는지 여부를 나타내는 값을 설정합니다
부모 여백을 고려합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 값이 true이면 워터마크 크기와 좌표가 상위 여백을 고려하여 계산됩니다. 기본값은 false이며, 상위 여백은 무시됩니다. |
|

### isImageWatermark() {#isImageWatermark--}
```
public abstract boolean isImageWatermark()
```




**Returns:**
boolean
### isTextWatermark() {#isTextWatermark--}
```
public abstract boolean isTextWatermark()
```




**Returns:**
boolean
### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```




**Returns:**
double
### getSize() {#getSize--}
```
public abstract SizeD getSize()
```




**Returns:**
[SizeD](../../com.groupdocs.watermark.internal/sized)
### getTileOptions() {#getTileOptions--}
```
public TileOptions getTileOptions()
```




**Returns:**
[TileOptions](../../com.groupdocs.watermark.watermarks/tileoptions)
### setTileOptions(TileOptions tileOptions) {#setTileOptions-com.groupdocs.watermark.watermarks.TileOptions-}
```
public void setTileOptions(TileOptions tileOptions)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| tileOptions | [TileOptions](../../com.groupdocs.watermark.watermarks/tileoptions) |  |

### copyPropertiesValues(Watermark source, Watermark destination) {#copyPropertiesValues-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.Watermark-}
```
public static void copyPropertiesValues(Watermark source, Watermark destination)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| source | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| destination | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### deepClone() {#deepClone--}
```
public abstract Watermark deepClone()
```




**Returns:**
[Watermark](../../com.groupdocs.watermark/watermark)
### hasSameValues(Watermark watermark) {#hasSameValues-com.groupdocs.watermark.Watermark-}
```
public boolean hasSameValues(Watermark watermark)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

**Returns:**
boolean
### createGeometry(ContentPartGeometry parent) {#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-}
```
public abstract WatermarkGeometry createGeometry(ContentPartGeometry parent)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| parent | [ContentPartGeometry](../../com.groupdocs.watermark.internal/contentpartgeometry) |  |

**Returns:**
[WatermarkGeometry](../../com.groupdocs.watermark.internal/watermarkgeometry)
