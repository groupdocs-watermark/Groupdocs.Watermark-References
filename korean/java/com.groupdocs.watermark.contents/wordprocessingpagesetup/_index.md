---
title: "WordProcessingPageSetup"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "Word 문서 섹션의 인쇄 페이지 속성을 나타냅니다."
type: docs
weight: 134
url: /ko/java/com.groupdocs.watermark.contents/wordprocessingpagesetup/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingPageSetup
```

Word 문서 섹션의 인쇄 페이지 속성을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getWidth()](#getWidth--) | 인쇄 페이지의 너비를 포인트 단위로 가져옵니다. |
|
|  | [getHeight()](#getHeight--) | 인쇄 페이지의 높이를 포인트 단위로 가져옵니다. |
|
|  | [getLeftMargin()](#getLeftMargin--) | 왼쪽 여백의 크기를 포인트 단위로 가져옵니다. |
|
|  | [getTopMargin()](#getTopMargin--) | 위쪽 여백의 크기를 포인트 단위로 가져옵니다. |
|
|  | [getRightMargin()](#getRightMargin--) | 오른쪽 여백의 크기를 포인트 단위로 가져옵니다. |
|
|  | [getBottomMargin()](#getBottomMargin--) | 아래쪽 여백의 크기를 포인트 단위로 가져옵니다. |
|
|  | [getDifferentFirstPageHeaderFooter()](#getDifferentFirstPageHeaderFooter--) | 첫 페이지에 다른 머리글/바닥글이 사용되는지 여부를 나타내는 값을 가져옵니다. |
|
|  | [setDifferentFirstPageHeaderFooter(boolean value)](#setDifferentFirstPageHeaderFooter-boolean-) | 첫 페이지에 다른 머리글/바닥글이 사용되는지 여부를 나타내는 값을 설정합니다. |
|
|  | [getOddAndEvenPagesHeaderFooter()](#getOddAndEvenPagesHeaderFooter--) | 홀수 페이지와 짝수 페이지에 서로 다른 머리글/바닥글이 사용되는지 여부를 나타내는 값을 가져옵니다 |
페이지.
|
|  | [setOddAndEvenPagesHeaderFooter(boolean value)](#setOddAndEvenPagesHeaderFooter-boolean-) | 홀수 페이지와 짝수 페이지에 서로 다른 머리글/바닥글이 사용되는지 여부를 나타내는 값을 설정합니다 |
페이지.
|
### getWidth() {#getWidth--}
```
public final double getWidth()
```


인쇄 페이지의 너비를 포인트 단위로 가져옵니다.


**Returns:**
double - 인쇄 페이지의 너비 (포인트).

### getHeight() {#getHeight--}
```
public final double getHeight()
```


인쇄 페이지의 높이를 포인트 단위로 가져옵니다.


**Returns:**
double - 인쇄 페이지의 높이 (포인트).

### getLeftMargin() {#getLeftMargin--}
```
public final double getLeftMargin()
```


왼쪽 여백의 크기를 포인트 단위로 가져옵니다.


**Returns:**
double - 왼쪽 여백의 크기 (포인트).

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

### getDifferentFirstPageHeaderFooter() {#getDifferentFirstPageHeaderFooter--}
```
public final boolean getDifferentFirstPageHeaderFooter()
```


첫 페이지에 다른 머리글/바닥글이 사용되는지 여부를 나타내는 값을 가져옵니다.


**Returns:**
boolean - 첫 페이지에 다른 머리글/바닥글이 사용되는 경우 true; 그렇지 않으면 false.

### setDifferentFirstPageHeaderFooter(boolean value) {#setDifferentFirstPageHeaderFooter-boolean-}
```
public final void setDifferentFirstPageHeaderFooter(boolean value)
```


첫 페이지에 다른 머리글/바닥글이 사용되는지 여부를 나타내는 값을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 첫 페이지에 다른 머리글/바닥글이 사용되는 경우 true; 그렇지 않으면 false. |
|

### getOddAndEvenPagesHeaderFooter() {#getOddAndEvenPagesHeaderFooter--}
```
public final boolean getOddAndEvenPagesHeaderFooter()
```


홀수 페이지와 짝수 페이지에 서로 다른 머리글/바닥글이 사용되는지 여부를 나타내는 값을 가져옵니다
페이지.
참고: 이 속성을 변경하면 콘텐츠의 모든 섹션에 영향을 줍니다.


**Returns:**
boolean - 홀수 페이지와 짝수 페이지에 서로 다른 머리글/바닥글이 사용되는 경우 true; 그렇지 않으면 false.

### setOddAndEvenPagesHeaderFooter(boolean value) {#setOddAndEvenPagesHeaderFooter-boolean-}
```
public final void setOddAndEvenPagesHeaderFooter(boolean value)
```


홀수 페이지와 짝수 페이지에 서로 다른 머리글/바닥글이 사용되는지 여부를 나타내는 값을 설정합니다
페이지.
참고: 이 속성을 변경하면 콘텐츠의 모든 섹션에 영향을 줍니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 홀수 페이지와 짝수 페이지에 서로 다른 머리글/바닥글이 사용되는 경우 true; 그렇지 않으면 false. |
|

