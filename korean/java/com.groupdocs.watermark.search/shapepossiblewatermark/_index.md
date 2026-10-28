---
title: "ShapePossibleWatermark"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "지원되는 모든 형식의 콘텐츠에서 모양 워터마크를 나타냅니다."
type: docs
weight: 55
url: /ko/java/com.groupdocs.watermark.search/shapepossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark), [com.groupdocs.watermark.search.TwoDObjectPossibleWatermark](../../com.groupdocs.watermark.search/twodobjectpossiblewatermark)
```
public abstract class ShapePossibleWatermark<T> extends TwoDObjectPossibleWatermark
```

지원되는 모든 형식의 콘텐츠에서 모양 워터마크를 나타냅니다.


T
: 도형의 유형.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getRotateAngle()](#getRotateAngle--) | 도형의 회전 각도를(도) 가져옵니다. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | 도형의 서식이 지정된 텍스트 조각 컬렉션을 가져옵니다. |
|
|  | [getText()](#getText--) | 도형의 텍스트를 가져옵니다. |
|
|  | [setText(String value)](#setText-java.lang.String-) | 도형의 텍스트를 설정합니다. |
|
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


도형의 회전 각도를(도) 가져옵니다.


**Returns:**
double - 도형의 회전 각도(도).

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


도형의 서식이 지정된 텍스트 조각 컬렉션을 가져옵니다.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of shape.

### getText() {#getText--}
```
public String getText()
```


도형의 텍스트를 가져옵니다.


**Returns:**
java.lang.String - 도형의 �스트.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


도형의 텍스트를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 도형의 텍스트. |
|

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




