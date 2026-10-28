---
title: "SpreadsheetShape"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "Excel 문서의 그리기 도형을 나타냅니다."
type: docs
weight: 117
url: /ko/java/com.groupdocs.watermark.contents/spreadsheetshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject), [com.groupdocs.watermark.search.IHyperlinkContainer](../../com.groupdocs.watermark.search/ihyperlinkcontainer)
```
public class SpreadsheetShape extends ShapeSearchAdapter implements IRotatableTwoDObject, IHyperlinkContainer
```

Excel 문서의 그리기 도형을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getWorksheet()](#getWorksheet--) | 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 상위 워크시트를 가져옵니다. |
|
|  | [getAutoShapeType()](#getAutoShapeType--) | 자동 도형 유형을 가져옵니다. |
|
|  | [getMsoDrawingType()](#getMsoDrawingType--) | MSO 그리기 유형을 가져옵니다. |
|
|  | [getText()](#getText--) | 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 텍스트를 가져옵니다. |
|
|  | [setText(String value)](#setText-java.lang.String-) | 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 텍스트를 설정합니다. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 서식이 지정된 텍스트 조각 컬렉션을 가져옵니다. |
|
|  | [getImage()](#getImage--) | 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 이미지를 가져옵니다. |
|
|  | [setImage(SpreadsheetWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 이미지를 설정합니다. |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 이미지 채우기 형식 설정을 가져옵니다. |
|
|  | [getId()](#getId--) | 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 식별자를 가져옵니다. |
|
|  | [getAlternativeText()](#getAlternativeText--) | 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`와 연결된 설명(대체) 텍스트를 가져옵니다. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`와 연결된 설명(대체) 텍스트를 설정합니다. |
|
|  | [isWordArt()](#isWordArt--) | 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`가 WordArt 객체인지 여부를 나타내는 값을 가져옵니다. |
|
|  | [getName()](#getName--) | 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 이름을 가져옵니다. |
|
|  | [getAsposeCellsShape()](#getAsposeCellsShape--) | <br /> |

|
|  | [getHyperlink()](#getHyperlink--) | 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`와 연결된 하이퍼링크를 가져옵니다. |
|
|  | [setHyperlink(String value)](#setHyperlink-java.lang.String-) | 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`와 연결된 하이퍼링크를 설정합니다. |
|
|  | [getX()](#getX--) | 워크시트 왼쪽 경계에서 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 수평 오프셋을 포인트 단위로 가져옵니다. |
|
|  | [setX(double value)](#setX-double-) | 워크시트 왼쪽 경계에서 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 수평 오프셋을 포인트 단위로 설정합니다. |
|
|  | [getY()](#getY--) | 워크시트 상단 경계에서 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 수직 오프셋을 포인트 단위로 가져옵니다. |
|
|  | [setY(double value)](#setY-double-) | 워크시트 상단 경계에서 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 수직 오프셋을 포인트 단위로 설정합니다. |
|
|  | [getWidth()](#getWidth--) | 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 너비를 포인트 단위로 가져옵니다. |
|
|  | [setWidth(double value)](#setWidth-double-) | 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 너비를 포인트 단위로 설정합니다. |
|
|  | [getHeight()](#getHeight--) | 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 높이를 포인트 단위로 가져옵니다. |
|
|  | [setHeight(double value)](#setHeight-double-) | 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 높이를 포인트 단위로 설정합니다. |
|
|  | [getRotateAngle()](#getRotateAngle--) | 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 회전 각도를 도 단위로 가져오거나 설정합니다. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 회전 각도를 도 단위로 가져오거나 설정합니다. |
|
|  | [getImageForSearch()](#getImageForSearch--) | <br /> |

|
|  | [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) | <br /> |

|
|  | [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) | <br /> |

|
|  | [getTextForSearch()](#getTextForSearch--) | <br /> |

|
|  | [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) | <br /> |

|
### getWorksheet() {#getWorksheet--}
```
public final SpreadsheetWorksheet getWorksheet()
```


이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 상위 워크시트를 가져옵니다.


**Returns:**
[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) - The parent worksheet of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getAutoShapeType() {#getAutoShapeType--}
```
public final int getAutoShapeType()
```


자동 도형 유형을 가져옵니다.


**Returns:**
int - 자동 도형 유형입니다.

### getMsoDrawingType() {#getMsoDrawingType--}
```
public final int getMsoDrawingType()
```


MSO 그리기 유형을 가져옵니다.


**Returns:**
int - mso 그리기 유형입니다.

### getText() {#getText--}
```
public final String getText()
```


이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 텍스트를 가져옵니다.


**Returns:**
java.lang.String - 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 텍스트입니다.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 텍스트를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | java.lang.String | 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 텍스트입니다. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 서식이 지정된 텍스트 조각 컬렉션을 가져옵니다.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getImage() {#getImage--}
```
public final SpreadsheetWatermarkableImage getImage()
```


이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 이미지를 가져옵니다.


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The image of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` or null if the shape has no image.

### setImage(SpreadsheetWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public final void setImage(SpreadsheetWatermarkableImage value)
```


이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 이미지를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 이미지이며, 이미지를 제거해야 하는 경우 null입니다. |
|

### getImageFillFormat() {#getImageFillFormat--}
```
public final SpreadsheetImageFillFormat getImageFillFormat()
```


이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 이미지 채우기 형식 설정을 가져옵니다.


**Returns:**
[SpreadsheetImageFillFormat](../../com.groupdocs.watermark.contents/spreadsheetimagefillformat) - The image fill format settings of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getId() {#getId--}
```
public final int getId()
```


이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 식별자를 가져옵니다.


**Returns:**
int - 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 식별자입니다.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`와 연결된 설명(대체) 텍스트를 가져옵니다.


**Returns:**
java.lang.String - 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`와 연결된 설명(대체) 텍스트입니다.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`와 연결된 설명(대체) 텍스트를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | java.lang.String | 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`와 연결된 설명(대체) 텍스트입니다. |
|

### isWordArt() {#isWordArt--}
```
public final boolean isWordArt()
```


이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`가 WordArt 객체인지 여부를 나타내는 값을 가져옵니다.


**Returns:**
boolean - 도형이 WordArt 객체이면 true; 그렇지 않으면 false.

### getName() {#getName--}
```
public final String getName()
```


이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 이름을 가져옵니다.


**Returns:**
java.lang.String - 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 이름입니다.

### getAsposeCellsShape() {#getAsposeCellsShape--}
```
public final Shape getAsposeCellsShape()
```


<br />



**Returns:**
com.aspose.cells.Shape
### getHyperlink() {#getHyperlink--}
```
public final String getHyperlink()
```


이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`와 연결된 하이퍼링크를 가져옵니다.


**Returns:**
java.lang.String - 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`와 연결된 하이퍼링크입니다.

### setHyperlink(String value) {#setHyperlink-java.lang.String-}
```
public final void setHyperlink(String value)
```


이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`와 연결된 하이퍼링크를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | java.lang.String | 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`와 연결된 하이퍼링크입니다. |
|

### getX() {#getX--}
```
public final double getX()
```


워크시트 왼쪽 경계에서 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 수평 오프셋을 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 x좌표입니다.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


워크시트 왼쪽 경계에서 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 수평 오프셋을 포인트 단위로 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | double | 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 x좌표입니다. |
|

### getY() {#getY--}
```
public final double getY()
```


워크시트 상단 경계에서 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 수직 오프셋을 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 y 좌표.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


워크시트 상단 경계에서 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 수직 오프셋을 포인트 단위로 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | double | 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 y 좌표. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 너비를 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 너비(포인트 단위).

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 너비를 포인트 단위로 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | double | 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 너비(포인트 단위). |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 높이를 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 높이(포인트 단위).

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 높이를 포인트 단위로 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | double | 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 높이(포인트 단위). |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 회전 각도를 도 단위로 가져오거나 설정합니다.


**Returns:**
double - 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 회전 각도(도 단위).

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 회전 각도를 도 단위로 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | double | 이 `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`의 회전 각도(도 단위). |
|

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

### getFormattedTextFragmentsForSearch() {#getFormattedTextFragmentsForSearch--}
```
public FormattedTextFragmentCollection getFormattedTextFragmentsForSearch()
```


<br />



**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
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

