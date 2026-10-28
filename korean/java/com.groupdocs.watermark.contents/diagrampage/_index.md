---
title: "DiagramPage"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "Visio 문서 페이지를 나타냅니다."
type: docs
weight: 22
url: /ko/java/com.groupdocs.watermark.contents/diagrampage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class DiagramPage extends ContentPart
```

Visio 문서 페이지를 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
|  | [getShapes()](#getShapes--) | 페이지의 모든 도형 컬렉션을 가져옵니다. |
|
|  | [isBackground()](#isBackground--) | 페이지가 배경 페이지인지 여부를 나타내는 값을 가져옵니다. |
|
|  | [getBackgroundPage()](#getBackgroundPage--) | 이것에 대한 배경 페이지를 가져옵니다. |
|
|  | [getWidth()](#getWidth--) | 이것의 너비를 포인트 단위로 가져옵니다. |
|
|  | [getHeight()](#getHeight--) | 이것의 높이를 포인트 단위로 가져옵니다. |
|
|  | [getTopMargin()](#getTopMargin--) | 위쪽 여백의 크기를 포인트 단위로 가져옵니다. |
|
|  | [getRightMargin()](#getRightMargin--) | 오른쪽 여백의 크기를 포인트 단위로 가져옵니다. |
|
|  | [getBottomMargin()](#getBottomMargin--) | 아래쪽 여백의 크기를 포인트 단위로 가져옵니다. |
|
|  | [getLeftMargin()](#getLeftMargin--) | 왼쪽 여백의 크기를 포인트 단위로 가져옵니다. |
|
|  | [isVisible()](#isVisible--) | 페이지가 UI에 표시되는지 여부를 나타내는 값을 가져옵니다. |
|
|  | [setVisible(boolean value)](#setVisible-boolean-) | 페이지가 UI에 표시되는지 여부를 나타내는 값을 설정합니다. |
|
|  | [getName()](#getName--) | 이것의 이름을 가져옵니다 |
DiagramPage
.
|
|  | [getAsposeDiagramPage()](#getAsposeDiagramPage--) | <br /> |

|
|  | [getContent()](#getContent--) | <br /> |

|
|  | [getPageToDrawingScale()](#getPageToDrawingScale--) | <br /> |

|
|  | [addWatermark(Watermark watermark, DiagramShapeSettings shapeSettings)](#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.internal.DiagramShapeSettings-) | <br /> |

|
|  | [convertValueFromDrawingScaleToPageScale(DoubleValue value)](#convertValueFromDrawingScaleToPageScale-com.aspose.diagram.DoubleValue-) | <br /> |

|
### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```




**Returns:**
java.lang.Integer
### getShapes() {#getShapes--}
```
public final DiagramShapeCollection getShapes()
```


페이지의 모든 도형 컬렉션을 가져옵니다.


**Returns:**
[DiagramShapeCollection](../../com.groupdocs.watermark.contents/diagramshapecollection) - The collection of all shapes of the page.

### isBackground() {#isBackground--}
```
public final boolean isBackground()
```


페이지가 배경 페이지인지 여부를 나타내는 값을 가져옵니다.


**Returns:**
boolean - 페이지가 배경 페이지이면 true; 그렇지 않으면 false.

### getBackgroundPage() {#getBackgroundPage--}
```
public final DiagramPage getBackgroundPage()
```


이것에 대한 배경 페이지를 가져옵니다.


**Returns:**
[DiagramPage](../../com.groupdocs.watermark.contents/diagrampage) - The background page for this .

### getWidth() {#getWidth--}
```
public final double getWidth()
```


이것의 너비를 포인트 단위로 가져옵니다.


**Returns:**
double - 이것의 너비를 포인트 단위로 나타냅니다.

### getHeight() {#getHeight--}
```
public final double getHeight()
```


이것의 높이를 포인트 단위로 가져옵니다.


**Returns:**
double - 이것의 높이를 포인트 단위로 나타냅니다.

### getTopMargin() {#getTopMargin--}
```
public final double getTopMargin()
```


위쪽 여백의 크기를 포인트 단위로 가져옵니다.


**Returns:**
double - 상단 여백의 크기(포인트).

### getRightMargin() {#getRightMargin--}
```
public final double getRightMargin()
```


오른쪽 여백의 크기를 포인트 단위로 가져옵니다.


**Returns:**
double - 오른쪽 여백의 크기 (포인트).

### getBottomMargin() {#getBottomMargin--}
```
public final double getBottomMargin()
```


아래쪽 여백의 크기를 포인트 단위로 가져옵니다.


**Returns:**
double - 하단 여백의 크기(포인트).

### getLeftMargin() {#getLeftMargin--}
```
public final double getLeftMargin()
```


왼쪽 여백의 크기를 포인트 단위로 가져옵니다.


**Returns:**
double - 왼쪽 여백의 크기 (포인트).

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


페이지가 UI에 표시되는지 여부를 나타내는 값을 가져옵니다.


**Returns:**
boolean - 페이지가 UI에 표시되는지 여부를 나타내는 값. 페이지가 표시되면 true; 그렇지 않으면 false.

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


페이지가 UI에 표시되는지 여부를 나타내는 값을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | UI에서 페이지가 표시되는지 여부를 나타내는 값입니다. 페이지가 표시되면 true; 그렇지 않으면 false. |
|

### getName() {#getName--}
```
public final String getName()
```


이것의 이름을 가져옵니다
DiagramPage
.


**Returns:**
java.lang.String - 이 DiagramPage의 이름입니다.

### getAsposeDiagramPage() {#getAsposeDiagramPage--}
```
public final Page getAsposeDiagramPage()
```


<br />



**Returns:**
com.aspose.diagram.Page
### getContent() {#getContent--}
```
public final DiagramContent getContent()
```


<br />



**Returns:**
[DiagramContent](../../com.groupdocs.watermark.contents/diagramcontent)
### getPageToDrawingScale() {#getPageToDrawingScale--}
```
public final double getPageToDrawingScale()
```


<br />



**Returns:**
double
### addWatermark(Watermark watermark, DiagramShapeSettings shapeSettings) {#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.internal.DiagramShapeSettings-}
```
public final void addWatermark(Watermark watermark, DiagramShapeSettings shapeSettings)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [DiagramShapeSettings](../../com.groupdocs.watermark.internal/diagramshapesettings) |  |

### convertValueFromDrawingScaleToPageScale(DoubleValue value) {#convertValueFromDrawingScaleToPageScale-com.aspose.diagram.DoubleValue-}
```
public final double convertValueFromDrawingScaleToPageScale(DoubleValue value)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | com.aspose.diagram.DoubleValue |  |

**Returns:**
double
