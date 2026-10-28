---
title: "PossibleWatermark"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "문서에서 발견된 가능한 워터마크를 나타냅니다."
type: docs
weight: 45
url: /ko/java/com.groupdocs.watermark.search/possiblewatermark/
---
**Inheritance:**
java.lang.Object
```
public abstract class PossibleWatermark
```

문서에서 발견된 가능한 워터마크를 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PossibleWatermark()](#PossibleWatermark--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getParent()](#getParent--) | 이 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`의 부모를 가져옵니다. |
|
| [getPageNumber()](#getPageNumber--) |  |
|  | [getWidth()](#getWidth--) | 이 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`의 너비를 가져옵니다. |
|
|  | [getHeight()](#getHeight--) | 이 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`의 높이를 가져옵니다. |
|
|  | [getX()](#getX--) | 이 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`의 x좌표를 가져옵니다. |
|
|  | [getY()](#getY--) | 이 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`의 y좌표를 가져옵니다. |
|
|  | [getRotateAngle()](#getRotateAngle--) | 이 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`의 회전 각도를(도) 가져옵니다. |
|
|  | [getText()](#getText--) | 이 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`의 텍스트를 가져옵니다. |
|
|  | [setText(String value)](#setText-java.lang.String-) | 이 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`의 텍스트를 설정합니다. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | 이 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`의 서식이 지정된 텍스트 조각 컬렉션을 가져옵니다. |
|
|  | [getImageData()](#getImageData--) | 이 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`의 이미지를 가져오거나 설정합니다. |
|
| [setImageData(byte[] value)](#setImageData-byte---) |  |
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | 이 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`의 측정 단위 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`를 가져옵니다. |
|
| [getCollection()](#getCollection--) |  |
| [setCollection(PossibleWatermarkCollection value)](#setCollection-com.groupdocs.watermark.search.PossibleWatermarkCollection-) |  |
| [getImageSize()](#getImageSize--) |  |
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### PossibleWatermark() {#PossibleWatermark--}
```
public PossibleWatermark()
```




### getParent() {#getParent--}
```
public abstract ContentPart getParent()
```


이 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`의 부모를 가져옵니다.


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```




**Returns:**
java.lang.Integer
### getWidth() {#getWidth--}
```
public double getWidth()
```


이 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`의 너비를 가져옵니다.


**Returns:**
double - 이 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`의 너비.

### getHeight() {#getHeight--}
```
public double getHeight()
```


이 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`의 높이를 가져옵니다.


**Returns:**
double - 이 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`의 높이.

### getX() {#getX--}
```
public double getX()
```


이 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`의 x좌표를 가져옵니다.


**Returns:**
double - 이 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`의 x좌표.

### getY() {#getY--}
```
public double getY()
```


이 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`의 y좌표를 가져옵니다.


**Returns:**
double - 이 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`의 y좌표.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


이 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`의 회전 각도를(도) 가져옵니다.


**Returns:**
double - 이 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`의 회전 각도.

### getText() {#getText--}
```
public String getText()
```


이 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`의 텍스트를 가져옵니다.


**Returns:**
java.lang.String - 이 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`의 텍스트.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


이 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`의 텍스트를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | java.lang.String | 이 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`의 텍스트. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


이 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`의 서식이 지정된 텍스트 조각 컬렉션을 가져옵니다.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


이 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`의 이미지를 가져오거나 설정합니다.


**Returns:**
byte[] - 이 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`의 이미지 또는 워터마크에 이미지가 없을 경우 null.

### setImageData(byte[] value) {#setImageData-byte---}
```
public final void setImageData(byte[] value)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | byte[] |  |

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


이 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`의 측정 단위 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`를 가져옵니다.


**Returns:**
int - 이 `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`의 측정 단위 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`.

### getCollection() {#getCollection--}
```
public final PossibleWatermarkCollection getCollection()
```




**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection)
### setCollection(PossibleWatermarkCollection value) {#setCollection-com.groupdocs.watermark.search.PossibleWatermarkCollection-}
```
public final void setCollection(PossibleWatermarkCollection value)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection) |  |

### getImageSize() {#getImageSize--}
```
public final Size getImageSize()
```




**Returns:**
[Size](../../com.groupdocs.watermark.internal/size)
### getImageInternally() {#getImageInternally--}
```
public WatermarkableImage getImageInternally()
```




**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### remove() {#remove--}
```
public abstract void remove()
```




