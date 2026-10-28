---
title: "OfficeImageEffects"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "오피스 콘텐츠의 이미지 워터마크에 적용할 수 있는 효과를 나타냅니다."
type: docs
weight: 45
url: /ko/java/com.groupdocs.watermark.contents/officeimageeffects/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IDocumentSpecificSettings](../../com.groupdocs.watermark.internal/idocumentspecificsettings)
```
public abstract class OfficeImageEffects implements IDocumentSpecificSettings
```

오피스 콘텐츠의 이미지 워터마크에 적용할 수 있는 효과를 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getBorderLineFormat()](#getBorderLineFormat--) | 이미지 테두리의 선 형식 설정을 가져옵니다. |
|
|  | [setBorderLineFormat(OfficeLineFormat value)](#setBorderLineFormat-com.groupdocs.watermark.contents.OfficeLineFormat-) | 이미지 테두리의 선 형식 설정을 설정합니다. |
|
|  | [getGrayScale()](#getGrayScale--) | 그림이 그레이스케일 모드로 표시되는지 여부를 나타내는 값을 가져옵니다. |
|
|  | [setGrayScale(boolean value)](#setGrayScale-boolean-) | 그림이 그레이스케일 모드로 표시되는지 여부를 나타내는 값을 설정합니다. |
|
|  | [getChromaKey()](#getChromaKey--) | 투명하게 처리될 이미지의 색상 값을 가져옵니다. |
|
|  | [setChromaKey(Color value)](#setChromaKey-com.groupdocs.watermark.watermarks.Color-) | 투명하게 처리될 이미지의 색상 값을 설정합니다. |
|
|  | [getBrightness()](#getBrightness--) | 그림의 밝기를 가져옵니다. |
|
|  | [setBrightness(double value)](#setBrightness-double-) | 그림의 밝기를 설정합니다. |
|
|  | [getContrast()](#getContrast--) | 지정된 그림의 대비를 가져옵니다. |
|
|  | [setContrast(double value)](#setContrast-double-) | 지정된 그림의 대비를 설정합니다. |
|
### getBorderLineFormat() {#getBorderLineFormat--}
```
public final OfficeLineFormat getBorderLineFormat()
```


이미지 테두리의 선 형식 설정을 가져옵니다.


**Returns:**
[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat) - Instance of  OfficeLineFormat  class, representing shape line format.

### setBorderLineFormat(OfficeLineFormat value) {#setBorderLineFormat-com.groupdocs.watermark.contents.OfficeLineFormat-}
```
public final void setBorderLineFormat(OfficeLineFormat value)
```


이미지 테두리의 선 형식 설정을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat) | OfficeLineFormat 클래스의 인스턴스로, 도형 선 형식을 나타냅니다. |
|

### getGrayScale() {#getGrayScale--}
```
public final boolean getGrayScale()
```


그림이 그레이스케일 모드로 표시되는지 여부를 나타내는 값을 가져옵니다.


**Returns:**
boolean - 기본값은 false입니다.

### setGrayScale(boolean value) {#setGrayScale-boolean-}
```
public final void setGrayScale(boolean value)
```


그림이 그레이스케일 모드로 표시되는지 여부를 나타내는 값을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 기본값은 false입니다. |
|

### getChromaKey() {#getChromaKey--}
```
public final Color getChromaKey()
```


투명하게 처리될 이미지의 색상 값을 가져옵니다.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The default value is fully transparent color.

### setChromaKey(Color value) {#setChromaKey-com.groupdocs.watermark.watermarks.Color-}
```
public final void setChromaKey(Color value)
```


투명하게 처리될 이미지의 색상 값을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | 기본값은 완전 투명 색상입니다. |
|

### getBrightness() {#getBrightness--}
```
public final double getBrightness()
```


그림의 밝기를 가져옵니다. 이 속성의 값은 반드시
0.0 (가장 어두운)에서 1.0 (가장 밝은) 사이의 숫자여야 합니다.


**Returns:**
double - 기본값은 0.5입니다.

### setBrightness(double value) {#setBrightness-double-}
```
public final void setBrightness(double value)
```


그림의 밝기를 설정합니다. 이 속성의 값은 반드시
0.0 (가장 어두운)에서 1.0 (가장 밝은) 사이의 숫자여야 합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | double | 기본값은 0.5입니다. |
|

### getContrast() {#getContrast--}
```
public final double getContrast()
```


지정된 그림의 대비를 가져옵니다. 이 속성의 값은
0.0 (가장 낮은 대비)에서 1.0 (가장 높은 대비) 사이의 숫자여야 합니다.


**Returns:**
double - 기본값은 0.5입니다.

### setContrast(double value) {#setContrast-double-}
```
public final void setContrast(double value)
```


지정된 그림의 대비를 설정합니다. 이 속성의 값은
0.0 (가장 낮은 대비)에서 1.0 (가장 높은 대비) 사이의 숫자여야 합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | double | 기본값은 0.5입니다. |
|

