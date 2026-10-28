---
title: "PresentationBaseShape"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "PowerPoint 문서에서 모든 유형의 도형에 대한 추상 기본 클래스를 제공합니다."
type: docs
weight: 77
url: /ko/java/com.groupdocs.watermark.contents/presentationbaseshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.ITwoDObject](../../com.groupdocs.watermark.search/itwodobject), [com.groupdocs.watermark.contents.IPresentationHyperlinkContainer](../../com.groupdocs.watermark.contents/ipresentationhyperlinkcontainer)
```
public abstract class PresentationBaseShape extends ShapeSearchAdapter implements ITwoDObject, IPresentationHyperlinkContainer
```

PowerPoint 문서에서 모든 유형의 도형에 대한 추상 기본 클래스를 제공합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPresentation()](#getPresentation--) | 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 상위 프레젠테이션을 가져옵니다. |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 이미지 채우기 형식 설정을 가져옵니다. |
|
|  | [getName()](#getName--) | 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 이름을 가져옵니다. |
|
|  | [getAlternativeText()](#getAlternativeText--) | 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`와 연결된 설명(대체) 텍스트를 가져옵니다. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`와 연결된 설명(대체) 텍스트를 설정합니다. |
|
|  | [getId()](#getId--) | 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 식별자를 가져옵니다. |
|
|  | [getZOrderPosition()](#getZOrderPosition--) | z-순서에서 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 위치를 가져옵니다. |
|
|  | [getHyperlink(int actionType)](#getHyperlink-int-) | 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`와 연결된 하이퍼링크를 가져옵니다. |
|
|  | [setHyperlink(int actionType, String url)](#setHyperlink-int-java.lang.String-) | 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`와 연결된 하이퍼링크를 설정합니다. |
|
|  | [getX()](#getX--) | 프레젠테이션 왼쪽 경계에서 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 수평 오프셋을 포인트 단위로 가져옵니다. |
|
|  | [setX(double value)](#setX-double-) | 프레젠테이션 왼쪽 경계에서 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 수평 오프셋을 포인트 단위로 설정합니다. |
|
|  | [getY()](#getY--) | 프레젠테이션 상단 경계에서 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 수직 오프셋을 포인트 단위로 가져오거나 설정합니다. |
|
|  | [setY(double value)](#setY-double-) | 프레젠테이션 상단 경계에서 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 수직 오프셋을 포인트 단위로 가져오거나 설정합니다. |
|
|  | [getWidth()](#getWidth--) | 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 너비를 포인트 단위로 가져옵니다. |
|
|  | [setWidth(double value)](#setWidth-double-) | 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 너비를 포인트 단위로 설정합니다. |
|
|  | [getHeight()](#getHeight--) | 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 높이를 포인트 단위로 가져옵니다. |
|
|  | [setHeight(double value)](#setHeight-double-) | 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 높이를 포인트 단위로 설정합니다. |
|
### getPresentation() {#getPresentation--}
```
public final PresentationBaseSlide getPresentation()
```


이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 상위 프레젠테이션을 가져옵니다.


**Returns:**
[PresentationBaseSlide](../../com.groupdocs.watermark.contents/presentationbaseslide) - The parent presentation of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getImageFillFormat() {#getImageFillFormat--}
```
public final PresentationImageFillFormat getImageFillFormat()
```


이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 이미지 채우기 형식 설정을 가져옵니다.


**Returns:**
[PresentationImageFillFormat](../../com.groupdocs.watermark.contents/presentationimagefillformat) - The image fill format settings of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getName() {#getName--}
```
public final String getName()
```


이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 이름을 가져옵니다.


**Returns:**
java.lang.String - 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 이름입니다.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`와 연결된 설명(대체) 텍스트를 가져옵니다.


**Returns:**
java.lang.String - 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`와 연결된 설명(대체) 텍스트입니다.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`와 연결된 설명(대체) 텍스트를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | java.lang.String | 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`와 연결된 설명(대체) 텍스트입니다. |
|

### getId() {#getId--}
```
public final long getId()
```


이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 식별자를 가져옵니다.


**Returns:**
long - 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 식별자입니다.

### getZOrderPosition() {#getZOrderPosition--}
```
public final int getZOrderPosition()
```


z-순서에서 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 위치를 가져옵니다.

z-순서가 높은 도형은 항상 z-순서가 낮은 도형보다 앞에 있습니다.


**Returns:**
int - 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 z-순서 위치.

### getHyperlink(int actionType) {#getHyperlink-int-}
```
public final String getHyperlink(int actionType)
```


이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`와 연결된 하이퍼링크를 가져옵니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | actionType | int | 하이퍼링크를 활성화하는 동작. |
|

**Returns:**
java.lang.String - 지정된 동작에서 활성화되는 하이퍼링크의 URL.

### setHyperlink(int actionType, String url) {#setHyperlink-int-java.lang.String-}
```
public final void setHyperlink(int actionType, String url)
```


이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`와 연결된 하이퍼링크를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | actionType | int | 하이퍼링크를 활성화하는 동작. |
|
|  | url | java.lang.String | 하이퍼링크 URL. |
|

### getX() {#getX--}
```
public final double getX()
```


프레젠테이션 왼쪽 경계에서 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 수평 오프셋을 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 x 좌표.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


프레젠테이션 왼쪽 경계에서 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 수평 오프셋을 포인트 단위로 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | double | 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 x 좌표. |
|

### getY() {#getY--}
```
public final double getY()
```


프레젠테이션 상단 경계에서 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 수직 오프셋을 포인트 단위로 가져오거나 설정합니다.


**Returns:**
double - 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 y 좌표.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


프레젠테이션 상단 경계에서 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 수직 오프셋을 포인트 단위로 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | double | 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 y 좌표. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 너비를 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 너비(포인트).

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 너비를 포인트 단위로 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | double | 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 너비(포인트). |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 높이를 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 높이(포인트).

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 높이를 포인트 단위로 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | double | 이 `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`의 높이(포인트). |
|

