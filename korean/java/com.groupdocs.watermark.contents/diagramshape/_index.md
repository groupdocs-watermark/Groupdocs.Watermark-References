---
title: "DiagramShape"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "Visio 문서에서 그리기 도형을 나타냅니다."
type: docs
weight: 24
url: /ko/java/com.groupdocs.watermark.contents/diagramshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public class DiagramShape extends ShapeSearchAdapter implements IRotatableTwoDObject
```

Visio 문서에서 그리기 도형을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
|  | [getPage()](#getPage--) | 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 상위 페이지를 가져옵니다. |
|
|  | [getWidth()](#getWidth--) | 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 너비를 포인트 단위로 가져옵니다. |
|
|  | [setWidth(double value)](#setWidth-double-) | 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 너비를 포인트 단위로 설정합니다. |
|
|  | [getHeight()](#getHeight--) | 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 높이를 포인트 단위로 가져옵니다. |
|
|  | [setHeight(double value)](#setHeight-double-) | 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 높이를 포인트 단위로 설정합니다. |
|
|  | [getX()](#getX--) | 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 페이지 왼쪽 경계로부터 수평 오프셋을 포인트 단위로 가져옵니다. |
|
|  | [setX(double value)](#setX-double-) | 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 페이지 왼쪽 경계로부터 수평 오프셋을 포인트 단위로 설정합니다. |
|
|  | [getY()](#getY--) | 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 페이지 하단 경계로부터 수직 오프셋을 포인트 단위로 가져옵니다. |
|
|  | [setY(double value)](#setY-double-) | 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 페이지 하단 경계로부터 수직 오프셋을 포인트 단위로 설정합니다. |
|
|  | [getRotateAngle()](#getRotateAngle--) | 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 회전 각도를 도 단위로 가져오거나 설정합니다. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 회전 각도를 도 단위로 가져오거나 설정합니다. |
|
|  | [getText()](#getText--) | 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 텍스트를 가져오거나 설정합니다. |
|
|  | [setText(String value)](#setText-java.lang.String-) | 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 텍스트를 가져오거나 설정합니다. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 서식이 지정된 텍스트 조각 컬렉션을 가져옵니다. |
|
|  | [getImage()](#getImage--) | 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 이미지를 가져옵니다. |
|
|  | [setImage(DiagramWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.DiagramWatermarkableImage-) | 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 이미지를 설정합니다. |
|
|  | [getId()](#getId--) | 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 식별자를 가져옵니다. |
|
|  | [getName()](#getName--) | 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 이름을 가져옵니다. |
|
|  | [getHyperlinks()](#getHyperlinks--) | 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`에 첨부된 하이퍼링크 컬렉션을 가져옵니다. |
|
|  | [getAsposeShape()](#getAsposeShape--) | <br /> |

|
|  | [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) | <br /> |

|
|  | [getImageForSearch()](#getImageForSearch--) | <br /> |

|
|  | [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) | <br /> |

|
|  | [getTextForSearch()](#getTextForSearch--) | <br /> |

|
|  | [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) | <br /> |

|
### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```




**Returns:**
java.lang.Integer
### getPage() {#getPage--}
```
public final DiagramPage getPage()
```


이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 상위 페이지를 가져옵니다.


**Returns:**
[DiagramPage](../../com.groupdocs.watermark.contents/diagrampage) - The parent page of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getWidth() {#getWidth--}
```
public final double getWidth()
```


이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 너비를 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 너비(포인트).

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 너비를 포인트 단위로 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | double | 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 너비(포인트). |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 높이를 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 높이(포인트).

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 높이를 포인트 단위로 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | double | 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 높이(포인트). |
|

### getX() {#getX--}
```
public final double getX()
```


이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 페이지 왼쪽 경계로부터 수평 오프셋을 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 페이지 왼쪽 경계로부터 수평 오프셋(포인트).

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 페이지 왼쪽 경계로부터 수평 오프셋을 포인트 단위로 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | double | 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 페이지 왼쪽 경계로부터 수평 오프셋(포인트). |
|

### getY() {#getY--}
```
public final double getY()
```


이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 페이지 하단 경계로부터 수직 오프셋을 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 페이지 하단 경계로부터 수직 오프셋(포인트).

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 페이지 하단 경계로부터 수직 오프셋을 포인트 단위로 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | double | 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 페이지 하단 경계로부터 수직 오프셋(포인트). |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 회전 각도를 도 단위로 가져오거나 설정합니다.


**Returns:**
double - 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 회전 각도(도).

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 회전 각도를 도 단위로 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | double | 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 회전 각도(도). |
|

### getText() {#getText--}
```
public final String getText()
```


이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 텍스트를 가져오거나 설정합니다.


**Returns:**
java.lang.String - 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 텍스트.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 텍스트를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | java.lang.String | 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 텍스트. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 서식이 지정된 텍스트 조각 컬렉션을 가져옵니다.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getImage() {#getImage--}
```
public final DiagramWatermarkableImage getImage()
```


이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 이미지를 가져옵니다.


**Returns:**
[DiagramWatermarkableImage](../../com.groupdocs.watermark.contents/diagramwatermarkableimage) - The image of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### setImage(DiagramWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.DiagramWatermarkableImage-}
```
public final void setImage(DiagramWatermarkableImage value)
```


이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 이미지를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [DiagramWatermarkableImage](../../com.groupdocs.watermark.contents/diagramwatermarkableimage) | 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 이미지. |
|

### getId() {#getId--}
```
public final long getId()
```


이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 식별자를 가져옵니다.


**Returns:**
long - 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 식별자.

### getName() {#getName--}
```
public final String getName()
```


이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 이름을 가져옵니다.


**Returns:**
java.lang.String - 이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`의 이름.

### getHyperlinks() {#getHyperlinks--}
```
public final DiagramHyperlinkCollection getHyperlinks()
```


이 `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`에 첨부된 하이퍼링크 컬렉션을 가져옵니다.


**Returns:**
[DiagramHyperlinkCollection](../../com.groupdocs.watermark.contents/diagramhyperlinkcollection) - The collection of hyperlinks attached to this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getAsposeShape() {#getAsposeShape--}
```
public final Shape getAsposeShape()
```


<br />



**Returns:**
com.aspose.diagram.Shape
### getFormattedTextFragmentsForSearch() {#getFormattedTextFragmentsForSearch--}
```
public FormattedTextFragmentCollection getFormattedTextFragmentsForSearch()
```


<br />



**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
### getImageForSearch() {#getImageForSearch--}
```
public WatermarkableImage getImageForSearch()
```


<br />



**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### setFoundWatermarkImage(byte[] imageData) {#setFoundWatermarkImage-byte---}
```
public void setFoundWatermarkImage(byte[] imageData)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageData | byte[] |  |

### getTextForSearch() {#getTextForSearch--}
```
public String getTextForSearch()
```


<br />



**Returns:**
java.lang.String
### setFoundWatermarkText(String value) {#setFoundWatermarkText-java.lang.String-}
```
public void setFoundWatermarkText(String value)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

