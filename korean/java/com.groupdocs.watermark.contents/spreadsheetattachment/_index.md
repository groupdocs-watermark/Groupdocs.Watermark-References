---
title: "SpreadsheetAttachment"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "Excel 문서에 첨부된 파일을 나타냅니다."
type: docs
weight: 101
url: /ko/java/com.groupdocs.watermark.contents/spreadsheetattachment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.ITwoDObject](../../com.groupdocs.watermark.search/itwodobject)
```
public class SpreadsheetAttachment extends Attachment implements ITwoDObject
```

Excel 문서에 첨부된 파일을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getContent()](#getContent--) | 첨부된 파일 내용을 가져옵니다. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | 첨부된 파일 내용을 설정합니다. |
|
|  | [getPreviewImageContent()](#getPreviewImageContent--) | 첨부된 파일 미리보기 이미지를 바이트 배열로 가져옵니다. |
|
|  | [setPreviewImageContent(byte[] value)](#setPreviewImageContent-byte---) | 첨부된 파일 미리보기 이미지를 바이트 배열로 설정합니다. |
|
|  | [isLink()](#isLink--) | 콘텐츠에 파일에 대한 링크만 포함되는지 여부를 나타내는 값을 가져옵니다. |
|
|  | [getSourceFullName()](#getSourceFullName--) | 첨부된 파일의 전체 이름을 가져옵니다. |
|
|  | [getAlternativeText()](#getAlternativeText--) | 첨부된 파일과 연결된 설명(대체) 텍스트를 가져옵니다. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | 첨부된 파일과 연결된 설명(대체) 텍스트를 설정합니다. |
|
|  | [getAsposeOleObject()](#getAsposeOleObject--) | <br /> |

|
|  | [getX()](#getX--) | 워크시트 왼쪽 테두리에서 첨부 프레임의 수평 오프셋을 포인트 단위로 가져옵니다. |
|
|  | [setX(double value)](#setX-double-) | 워크시트 왼쪽 테두리에서 첨부 프레임의 수평 오프셋을 포인트 단위로 설정합니다. |
|
|  | [getY()](#getY--) | 워크시트 상단 테두리에서 첨부 프레임의 수직 오프셋을 포인트 단위로 가져옵니다. |
|
|  | [setY(double value)](#setY-double-) | 워크시트 상단 테두리에서 첨부 프레임의 수직 오프셋을 포인트 단위로 설정합니다. |
|
|  | [getWidth()](#getWidth--) | 첨부 프레임의 너비를 포인트 단위로 가져옵니다. |
|
|  | [setWidth(double value)](#setWidth-double-) | 첨부 프레임의 너비를 포인트 단위로 설정합니다. |
|
|  | [getHeight()](#getHeight--) | 첨부 프레임의 높이를 포인트 단위로 가져옵니다. |
|
|  | [setHeight(double value)](#setHeight-double-) | 첨부 프레임의 높이를 포인트 단위로 설정합니다. |
|
|  | [checkImageType()](#checkImageType--) | <br /> |

|
### getContent() {#getContent--}
```
public byte[] getContent()
```


첨부된 파일 내용을 가져옵니다.


**Returns:**
byte[] - 첨부된 파일 내용.

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


첨부된 파일 내용을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | byte[] | 첨부된 파일 내용. |
|

### getPreviewImageContent() {#getPreviewImageContent--}
```
public final byte[] getPreviewImageContent()
```


첨부된 파일 미리보기 이미지를 바이트 배열로 가져옵니다.


**Returns:**
byte[] - 첨부된 파일 미리보기 이미지를 바이트 배열로.

### setPreviewImageContent(byte[] value) {#setPreviewImageContent-byte---}
```
public final void setPreviewImageContent(byte[] value)
```


첨부된 파일 미리보기 이미지를 바이트 배열로 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | byte[] | 첨부된 파일 미리보기 이미지를 바이트 배열로. |
|

### isLink() {#isLink--}
```
public final boolean isLink()
```


콘텐츠에 파일에 대한 링크만 포함되는지 여부를 나타내는 값을 가져옵니다.


**Returns:**
boolean - 링크로 첨부 파일이 참조되는 경우 true (콘텐츠에 첨부 파일 내용이 포함되지 않음); 그렇지 않으면 false.

### getSourceFullName() {#getSourceFullName--}
```
public final String getSourceFullName()
```


첨부된 파일의 전체 이름을 가져옵니다.


**Returns:**
java.lang.String - 첨부된 파일의 전체 이름.

<br />

*** ** * ** ***

확장자는 파일을 열 적절한 응용 프로그램을 결정하는 데 사용됩니다.

<br />


### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


첨부된 파일과 연결된 설명(대체) 텍스트를 가져옵니다.


**Returns:**
java.lang.String - 첨부된 파일과 연결된 설명(대체) 텍스트.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


첨부된 파일과 연결된 설명(대체) 텍스트를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 첨부 파일과 연결된 설명(대체) 텍스트입니다. |
|

### getAsposeOleObject() {#getAsposeOleObject--}
```
public final OleObject getAsposeOleObject()
```


<br />



**Returns:**
com.aspose.cells.OleObject
### getX() {#getX--}
```
public final double getX()
```


워크시트 왼쪽 테두리에서 첨부 프레임의 수평 오프셋을 포인트 단위로 가져옵니다.


**Returns:**
double - 첨부 프레임의 x좌표.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


워크시트 왼쪽 테두리에서 첨부 프레임의 수평 오프셋을 포인트 단위로 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | double | 첨부 프레임의 x좌표. |
|

### getY() {#getY--}
```
public final double getY()
```


워크시트 상단 테두리에서 첨부 프레임의 수직 오프셋을 포인트 단위로 가져옵니다.


**Returns:**
double - 첨부 프레임의 y좌표.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


워크시트 상단 테두리에서 첨부 프레임의 수직 오프셋을 포인트 단위로 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | double | 첨부 프레임의 y좌표. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


첨부 프레임의 너비를 포인트 단위로 가져옵니다.


**Returns:**
double - 포인트 단위의 첨부 프레임 너비.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


첨부 프레임의 너비를 포인트 단위로 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | double | 포인트 단위의 첨부 프레임 너비. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


첨부 프레임의 높이를 포인트 단위로 가져옵니다.


**Returns:**
double - 포인트 단위의 첨부 프레임 높이.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


첨부 프레임의 높이를 포인트 단위로 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | double | 포인트 단위의 첨부 프레임 높이. |
|

### checkImageType() {#checkImageType--}
```
public final void checkImageType()
```


<br />



