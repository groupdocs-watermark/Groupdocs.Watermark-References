---
title: "SpreadsheetChart"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "Excel 문서의 차트를 나타냅니다."
type: docs
weight: 106
url: /ko/java/com.groupdocs.watermark.contents/spreadsheetchart/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IHyperlinkContainer](../../com.groupdocs.watermark.search/ihyperlinkcontainer), [com.groupdocs.watermark.search.ITwoDObject](../../com.groupdocs.watermark.search/itwodobject)
```
public class SpreadsheetChart implements IHyperlinkContainer, ITwoDObject
```

Excel 문서의 차트를 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getWorksheet()](#getWorksheet--) | 이 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`의 상위 워크시트를 가져옵니다. |
|
|  | [getId()](#getId--) | 이 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`의 식별자를 가져옵니다. |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | 이 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`의 이미지 채우기 형식 설정을 가져옵니다. |
|
|  | [getName()](#getName--) | 이 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`의 이름을 가져옵니다. |
|
|  | [getAlternativeText()](#getAlternativeText--) | 이 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`와 연결된 설명(대체) 텍스트를 가져옵니다. |
|
|  | [getHyperlink()](#getHyperlink--) | 이 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`와 연결된 하이퍼링크를 가져옵니다. |
|
|  | [setHyperlink(String value)](#setHyperlink-java.lang.String-) | 이 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`와 연결된 하이퍼링크를 설정합니다. |
|
|  | [getX()](#getX--) | 이 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`의 워크시트 왼쪽 경계로부터의 수평 오프셋을 포인트 단위로 가져옵니다. |
|
|  | [getY()](#getY--) | 이 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`의 워크시트 상단 경계로부터의 수직 오프셋을 포인트 단위로 가져옵니다. |
|
|  | [getWidth()](#getWidth--) | 이 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`의 너비를 포인트 단위로 가져옵니다. |
|
|  | [getHeight()](#getHeight--) | 이 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`의 높이를 포인트 단위로 가져옵니다. |
|
### getWorksheet() {#getWorksheet--}
```
public final SpreadsheetWorksheet getWorksheet()
```


이 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`의 상위 워크시트를 가져옵니다.


**Returns:**
[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) - The parent worksheet of this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.

### getId() {#getId--}
```
public final int getId()
```


이 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`의 식별자를 가져옵니다.


**Returns:**
`int` - 이 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`의 식별자.

### getImageFillFormat() {#getImageFillFormat--}
```
public final SpreadsheetImageFillFormat getImageFillFormat()
```


이 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`의 이미지 채우기 형식 설정을 가져옵니다.


**Returns:**
[SpreadsheetImageFillFormat](../../com.groupdocs.watermark.contents/spreadsheetimagefillformat) - The image fill format settings of this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.

### getName() {#getName--}
```
public final String getName()
```


이 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`의 이름을 가져옵니다.


**Returns:**
`java.lang.String` - 이 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`의 이름.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


이 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`와 연결된 설명(대체) 텍스트를 가져옵니다.


**Returns:**
`java.lang.String` - 이 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`와 연결된 설명(대체) 텍스트.

### getHyperlink() {#getHyperlink--}
```
public final String getHyperlink()
```


이 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`와 연결된 하이퍼링크를 가져옵니다.


**Returns:**
`java.lang.String` - 이 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`와 연결된 하이퍼링크.

### setHyperlink(String value) {#setHyperlink-java.lang.String-}
```
public final void setHyperlink(String value)
```


이 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`와 연결된 하이퍼링크를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | java.lang.String | 이 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`와 연결된 하이퍼링크. |
|

### getX() {#getX--}
```
public final double getX()
```


이 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`의 워크시트 왼쪽 경계로부터의 수평 오프셋을 포인트 단위로 가져옵니다.


**Returns:**
`double` - 이 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`의 x좌표.

### getY() {#getY--}
```
public final double getY()
```


이 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`의 워크시트 상단 경계로부터의 수직 오프셋을 포인트 단위로 가져옵니다.


**Returns:**
`double` - 이 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`의 y좌표.

### getWidth() {#getWidth--}
```
public final double getWidth()
```


이 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`의 너비를 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`의 너비(포인트).

### getHeight() {#getHeight--}
```
public final double getHeight()
```


이 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`의 높이를 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`의 높이(포인트).

