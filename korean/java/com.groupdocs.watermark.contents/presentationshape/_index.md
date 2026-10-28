---
title: "PresentationShape"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "PowerPoint 문서에서 그리기 도형을 나타냅니다."
type: docs
weight: 93
url: /ko/java/com.groupdocs.watermark.contents/presentationshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public class PresentationShape extends PresentationBaseShape implements IRotatableTwoDObject
```

PowerPoint 문서에서 그리기 도형을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getRotateAngle()](#getRotateAngle--) | 이 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`의 회전 각도를 도 단위로 가져옵니다. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | 이 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`의 회전 각도를 도 단위로 설정합니다. |
|
|  | [getText()](#getText--) | 이 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`의 텍스트를 가져옵니다. |
|
|  | [setText(String value)](#setText-java.lang.String-) | 이 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`의 텍스트를 설정합니다. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | 이 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`의 서식이 지정된 텍스트 조각 컬렉션을 가져옵니다. |
|
|  | [getShapeType()](#getShapeType--) | 도형 기하학 사전 설정 유형을 가져옵니다. |
|
|  | [getImage()](#getImage--) | 이 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`의 이미지를 가져옵니다. |
|
|  | [setImage(PresentationWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-) | 이 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`의 이미지를 설정합니다. |
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
### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


이 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`의 회전 각도를 도 단위로 가져옵니다.


**Returns:**
double - 이 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`의 회전 각도(도).

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


이 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`의 회전 각도를 도 단위로 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | double | 이 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`의 회전 각도(도)입니다. |
|

### getText() {#getText--}
```
public final String getText()
```


이 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`의 텍스트를 가져옵니다.


**Returns:**
`java.lang.String` - 이 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`의 텍스트.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


이 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`의 텍스트를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | java.lang.String | 이 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`의 텍스트. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


이 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`의 서식이 지정된 텍스트 조각 컬렉션을 가져옵니다.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


도형 기하학 사전 설정 유형을 가져옵니다.


**Returns:**
int - 기하학 프리셋 유형.

### getImage() {#getImage--}
```
public final PresentationWatermarkableImage getImage()
```


이 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`의 이미지를 가져옵니다.


**Returns:**
[PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) - The image of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` or null if the shape has no image.

### setImage(PresentationWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-}
```
public final void setImage(PresentationWatermarkableImage value)
```


이 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`의 이미지를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) | 이 `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`의 이미지 또는 이미지를 제거해야 하는 경우 null. |
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

