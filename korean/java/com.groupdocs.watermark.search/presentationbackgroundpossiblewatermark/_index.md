---
title: "PresentationBackgroundPossibleWatermark"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "PowerPoint 문서에서 가능한 배경 워터마크를 나타냅니다."
type: docs
weight: 47
url: /ko/java/com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)
```
public class PresentationBackgroundPossibleWatermark extends PossibleWatermark
```

PowerPoint 문서에서 가능한 배경 워터마크를 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PresentationBackgroundPossibleWatermark(PresentationBaseSlide slide)](#PresentationBackgroundPossibleWatermark-com.groupdocs.watermark.contents.PresentationBaseSlide-) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getParent()](#getParent--) | 이 `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`의 부모를 가져옵니다. |
|
|  | [getWidth()](#getWidth--) | 이 `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`의 너비를 포인트 단위로 가져옵니다. |
|
|  | [getHeight()](#getHeight--) | 이 `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`의 높이를 포인트 단위로 가져옵니다. |
|
|  | [getX()](#getX--) | 이 `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`의 슬라이드 왼쪽 경계로부터의 수평 오프셋을 포인트 단위로 가져옵니다. |
|
|  | [getY()](#getY--) | 이 `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`의 슬라이드 상단 경계로부터의 수직 오프셋을 포인트 단위로 가져옵니다. |
|
|  | [getRotateAngle()](#getRotateAngle--) | 이 `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`의 회전 각도를 도 단위로 가져옵니다. |
|
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | 이 `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`의 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`를 가져옵니다. |
|
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### PresentationBackgroundPossibleWatermark(PresentationBaseSlide slide) {#PresentationBackgroundPossibleWatermark-com.groupdocs.watermark.contents.PresentationBaseSlide-}
```
public PresentationBackgroundPossibleWatermark(PresentationBaseSlide slide)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| slide | [PresentationBaseSlide](../../com.groupdocs.watermark.contents/presentationbaseslide) |  |

### getParent() {#getParent--}
```
public ContentPart getParent()
```


이 `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`의 부모를 가져옵니다.


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


이 `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`의 너비를 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`의 너비(포인트).

### getHeight() {#getHeight--}
```
public double getHeight()
```


이 `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`의 높이를 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`의 높이(포인트).

### getX() {#getX--}
```
public double getX()
```


이 `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`의 슬라이드 왼쪽 경계로부터의 수평 오프셋을 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`의 x좌표.

### getY() {#getY--}
```
public double getY()
```


이 `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`의 슬라이드 상단 경계로부터의 수직 오프셋을 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`의 y좌표.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


이 `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`의 회전 각도를 도 단위로 가져옵니다.


**Returns:**
double - 이 `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`의 회전 각도(도).

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


이 `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`의 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`를 가져옵니다.


**Returns:**
int - 이 `[PresentationBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/presentationbackgroundpossiblewatermark)`의 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`.

### getImageInternally() {#getImageInternally--}
```
public WatermarkableImage getImageInternally()
```




**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### remove() {#remove--}
```
public void remove()
```




