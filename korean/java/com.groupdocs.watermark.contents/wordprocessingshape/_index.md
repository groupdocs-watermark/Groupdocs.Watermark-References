---
title: "WordProcessingShape"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "Word 문서의 그리기 도형을 나타냅니다."
type: docs
weight: 141
url: /ko/java/com.groupdocs.watermark.contents/wordprocessingshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject), [com.groupdocs.watermark.search.IHyperlinkContainer](../../com.groupdocs.watermark.search/ihyperlinkcontainer)
```
public class WordProcessingShape extends ShapeSearchAdapter implements IRotatableTwoDObject, IHyperlinkContainer
```

Word 문서의 그리기 도형을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getSection()](#getSection--) | 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 상위 섹션을 가져옵니다. |
|
|  | [getHeaderFooter()](#getHeaderFooter--) | 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 상위 머리글/바닥글을 가져옵니다(존재하는 경우). |
|
|  | [getShapeType()](#getShapeType--) | 도형 유형을 가져옵니다. |
|
|  | [isWordArt()](#isWordArt--) | 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`가 WordArt 객체인지 여부를 나타내는 값을 가져옵니다. |
|
|  | [getAlternativeText()](#getAlternativeText--) | 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`와 연결된 설명(대체) 텍스트를 가져옵니다. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`와 연결된 설명(대체) 텍스트를 설정합니다. |
|
|  | [getName()](#getName--) | 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 이름을 가져옵니다. |
|
|  | [getBehindText()](#getBehindText--) | 도형이 텍스트 위에 있는지 뒤에 있는지 여부를 나타내는 값을 가져옵니다. |
|
|  | [setBehindText(boolean value)](#setBehindText-boolean-) | 도형이 �스트 위에 있는지 뒤에 있는지 여부를 나타내는 값을 설정합니다. |
|
|  | [getText()](#getText--) | 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 텍스트를 가져옵니다. |
|
|  | [setText(String value)](#setText-java.lang.String-) | 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 텍스트를 설정합니다. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 서식이 지정된 텍스트 조각 컬렉션을 가져옵니다. |
|
|  | [getImage()](#getImage--) | 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 이미지를 가져옵니다. |
|
|  | [setImage(WordProcessingWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.WordProcessingWatermarkableImage-) | 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 이미지를 설정합니다. |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | 도형이 수평으로 배치되는 방식을 지정하는 값을 가져옵니다. |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | 도형이 수직으로 배치되는 방식을 지정하는 값을 가져옵니다. |
|
|  | [getRelativeHorizontalPosition()](#getRelativeHorizontalPosition--) | 도형이 수평으로 배치되는 대상을 지정하는 값을 가져옵니다. |
|
|  | [getRelativeVerticalPosition()](#getRelativeVerticalPosition--) | 형상이 수직으로 배치되는 방식을 지정하는 값을 가져옵니다. |
|
| [getImageFillFormat()](#getImageFillFormat--) |  |
| [getAsposeWordsShape()](#getAsposeWordsShape--) |  |
|  | [getHyperlink()](#getHyperlink--) | 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`와 연결된 하이퍼링크를 가져옵니다. |
|
|  | [setHyperlink(String value)](#setHyperlink-java.lang.String-) | 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`와 연결된 하이퍼링크를 설정합니다. |
|
|  | [getWidth()](#getWidth--) | 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 너비를 포인트 단위로 가져옵니다. |
|
|  | [setWidth(double value)](#setWidth-double-) | 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 너비를 포인트 단위로 설정합니다. |
|
|  | [getHeight()](#getHeight--) | 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 높이를 포인트 단위로 가져옵니다. |
|
|  | [setHeight(double value)](#setHeight-double-) | 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 높이를 포인트 단위로 설정합니다. |
|
|  | [getRotateAngle()](#getRotateAngle--) | 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 회전 각도를 도 단위로 가져옵니다. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 회전 각도를 도 단위로 설정합니다. |
|
|  | [getX()](#getX--) | 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 페이지 왼쪽 경계로부터의 수평 오프셋을 포인트 단위로 가져오거나 설정합니다. |
|
|  | [setX(double value)](#setX-double-) | 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 페이지 왼쪽 경계로부터의 수평 오프셋을 포인트 단위로 가져오거나 설정합니다. |
|
|  | [getY()](#getY--) | 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 페이지 상단 경계로부터의 수직 오프셋을 포인트 단위로 가져옵니다. |
|
|  | [setY(double value)](#setY-double-) | 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 페이지 상단 경계로부터의 수직 오프셋을 포인트 단위로 설정합니다. |
|
| [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) |  |
| [getTextForSearch()](#getTextForSearch--) |  |
| [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) |  |
| [getImageForSearch()](#getImageForSearch--) |  |
| [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) |  |
### getSection() {#getSection--}
```
public final WordProcessingSection getSection()
```


이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 상위 섹션을 가져옵니다.


**Returns:**
[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection) - The parent section of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getHeaderFooter() {#getHeaderFooter--}
```
public final WordProcessingHeaderFooter getHeaderFooter()
```


이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 상위 머리글/바닥글을 가져옵니다(존재하는 경우).


**Returns:**
[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter) - The parent header/footer of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


도형 유형을 가져옵니다.


**Returns:**
int - 도형 유형.

### isWordArt() {#isWordArt--}
```
public final boolean isWordArt()
```


이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`가 WordArt 객체인지 여부를 나타내는 값을 가져옵니다.


**Returns:**
boolean - 도형이 WordArt 객체이면 true; 그렇지 않으면 false.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`와 연결된 설명(대체) 텍스트를 가져옵니다.


**Returns:**
java.lang.String - 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`와 연결된 설명(대체) 텍스트.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`와 연결된 설명(대체) 텍스트를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | java.lang.String | 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`와 연결된 설명(대체) 텍스트. |
|

### getName() {#getName--}
```
public final String getName()
```


이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 이름을 가져옵니다.


**Returns:**
java.lang.String - 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 이름.

### getBehindText() {#getBehindText--}
```
public final boolean getBehindText()
```


도형이 텍스트 위에 있는지 뒤에 있는지 여부를 나타내는 값을 가져옵니다.


**Returns:**
boolean - 도형이 텍스트 위에 있는지 뒤에 있는지를 나타내는 값. 도형이 텍스트 뒤에 있으면 True; 그렇지 않으면 false.

### setBehindText(boolean value) {#setBehindText-boolean-}
```
public final void setBehindText(boolean value)
```


도형이 �스트 위에 있는지 뒤에 있는지 여부를 나타내는 값을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 도형이 텍스트 위에 있는지 뒤에 있는지를 나타내는 값. 도형이 텍스트 뒤에 있으면 True; 그렇지 않으면 false. |
|

### getText() {#getText--}
```
public final String getText()
```


이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 텍스트를 가져옵니다.


**Returns:**
java.lang.String - 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 텍스트.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 텍스트를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | java.lang.String | 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 텍스트. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 서식이 지정된 텍스트 조각 컬렉션을 가져옵니다.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getImage() {#getImage--}
```
public final WordProcessingWatermarkableImage getImage()
```


이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 이미지를 가져옵니다.


**Returns:**
[WordProcessingWatermarkableImage](../../com.groupdocs.watermark.contents/wordprocessingwatermarkableimage) - The image of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` or `null` if the shape has no image.

### setImage(WordProcessingWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.WordProcessingWatermarkableImage-}
```
public final void setImage(WordProcessingWatermarkableImage value)
```


이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 이미지를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [WordProcessingWatermarkableImage](../../com.groupdocs.watermark.contents/wordprocessingwatermarkableimage) | 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 이미지 또는 이미지를 제거해야 하는 경우 `null`. |
|

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


도형이 수평으로 배치되는 방식을 지정하는 값을 가져옵니다.


**Returns:**
int - 수평 정렬 값.

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


도형이 수직으로 배치되는 방식을 지정하는 값을 가져옵니다.


**Returns:**
int - 수직 정렬 값.

### getRelativeHorizontalPosition() {#getRelativeHorizontalPosition--}
```
public final int getRelativeHorizontalPosition()
```


도형이 수평으로 배치되는 대상을 지정하는 값을 가져옵니다.


**Returns:**
int - 상대 수평 위치 값.

### getRelativeVerticalPosition() {#getRelativeVerticalPosition--}
```
public final int getRelativeVerticalPosition()
```


형상이 수직으로 배치되는 방식을 지정하는 값을 가져옵니다.


**Returns:**
int - 상대 수직 위치 값.

### getImageFillFormat() {#getImageFillFormat--}
```
public final WordProcessingImageFillFormat getImageFillFormat()
```




**Returns:**
[WordProcessingImageFillFormat](../../com.groupdocs.watermark.internal/wordprocessingimagefillformat)
### getAsposeWordsShape() {#getAsposeWordsShape--}
```
public final Shape getAsposeWordsShape()
```




**Returns:**
com.aspose.words.Shape
### getHyperlink() {#getHyperlink--}
```
public final String getHyperlink()
```


이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`와 연결된 하이퍼링크를 가져옵니다.


**Returns:**
java.lang.String - 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`와 연결된 하이퍼링크.

### setHyperlink(String value) {#setHyperlink-java.lang.String-}
```
public final void setHyperlink(String value)
```


이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`와 연결된 하이퍼링크를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | java.lang.String | 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`와 연결된 하이퍼링크. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 너비를 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 너비(포인트).

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 너비를 포인트 단위로 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | double | 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 너비(포인트). |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 높이를 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 높이(포인트).

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 높이를 포인트 단위로 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | double | 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 높이(포인트). |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 회전 각도를 도 단위로 가져옵니다.


**Returns:**
double - 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 회전 각도(도).

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 회전 각도를 도 단위로 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | double | 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 회전 각도(도). |
|

### getX() {#getX--}
```
public final double getX()
```


이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 페이지 왼쪽 경계로부터의 수평 오프셋을 포인트 단위로 가져오거나 설정합니다.


**Returns:**
double - 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 x좌표.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 페이지 왼쪽 경계로부터의 수평 오프셋을 포인트 단위로 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | double | 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 x좌표. |
|

### getY() {#getY--}
```
public final double getY()
```


이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 페이지 상단 경계로부터의 수직 오프셋을 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 y좌표.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 페이지 상단 경계로부터의 수직 오프셋을 포인트 단위로 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | double | 이 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`의 y좌표. |
|

### getFormattedTextFragmentsForSearch() {#getFormattedTextFragmentsForSearch--}
```
public FormattedTextFragmentCollection getFormattedTextFragmentsForSearch()
```




**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
### getTextForSearch() {#getTextForSearch--}
```
public String getTextForSearch()
```




**Returns:**
java.lang.String
### setFoundWatermarkText(String value) {#setFoundWatermarkText-java.lang.String-}
```
public void setFoundWatermarkText(String value)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getImageForSearch() {#getImageForSearch--}
```
public WatermarkableImage getImageForSearch()
```




**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### setFoundWatermarkImage(byte[] imageData) {#setFoundWatermarkImage-byte---}
```
public void setFoundWatermarkImage(byte[] imageData)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageData | byte[] |  |

