---
title: "PdfTextPossibleWatermark"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "PDF 문서 텍스트에서 가능한 워터마크를 나타냅니다."
type: docs
weight: 43
url: /ko/java/com.groupdocs.watermark.search/pdftextpossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)
```
public class PdfTextPossibleWatermark extends PossibleWatermark
```

PDF 문서 텍스트에서 가능한 워터마크를 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PdfTextPossibleWatermark(PdfPage parent, TextFragment fragment)](#PdfTextPossibleWatermark-com.groupdocs.watermark.contents.PdfPage-com.aspose.pdf.TextFragment-) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getParent()](#getParent--) | 이 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`의 부모를 가져옵니다. |
|
|  | [getWidth()](#getWidth--) | 이 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`의 너비를 포인트 단위로 가져옵니다. |
|
|  | [getHeight()](#getHeight--) | 이 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`의 높이를 포인트 단위로 가져옵니다. |
|
|  | [getX()](#getX--) | 이 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`의 페이지 왼쪽 경계로부터의 수평 오프셋을 포인트 단위로 가져옵니다. |
|
|  | [getY()](#getY--) | 이 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`의 페이지 하단 경계로부터의 수직 오프셋을 포인트 단위로 가져옵니다. |
|
|  | [getRotateAngle()](#getRotateAngle--) | 이 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`의 회전 각도를 도 단위로 가져옵니다. |
|
|  | [getText()](#getText--) | 이 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`의 텍스트를 가져옵니다. |
|
|  | [setText(String value)](#setText-java.lang.String-) | 이 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`의 텍스트를 설정합니다. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | 이 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`의 서식이 지정된 텍스트 조각 컬렉션을 가져옵니다. |
|
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | 이 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`의 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`를 가져옵니다. |
|
| [remove()](#remove--) |  |
### PdfTextPossibleWatermark(PdfPage parent, TextFragment fragment) {#PdfTextPossibleWatermark-com.groupdocs.watermark.contents.PdfPage-com.aspose.pdf.TextFragment-}
```
public PdfTextPossibleWatermark(PdfPage parent, TextFragment fragment)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| parent | [PdfPage](../../com.groupdocs.watermark.contents/pdfpage) |  |
| 조각 | com.aspose.pdf.TextFragment |  |

### getParent() {#getParent--}
```
public ContentPart getParent()
```


이 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`의 부모를 가져옵니다.


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


이 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`의 너비를 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`의 너비를 포인트 단위로 가져옵니다.

### getHeight() {#getHeight--}
```
public double getHeight()
```


이 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`의 높이를 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`의 높이를 포인트 단위로 가져옵니다.

### getX() {#getX--}
```
public double getX()
```


이 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`의 페이지 왼쪽 경계로부터의 수평 오프셋을 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`의 x좌표.

### getY() {#getY--}
```
public double getY()
```


이 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`의 페이지 하단 경계로부터의 수직 오프셋을 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`의 y좌표.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


이 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`의 회전 각도를 도 단위로 가져옵니다.


**Returns:**
double - 이 가능한 워터마크 유형에 대해 값은 항상 0입니다.

### getText() {#getText--}
```
public String getText()
```


이 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`의 텍스트를 가져옵니다.


**Returns:**
java.lang.String - 이 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`의 텍스트.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


이 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`의 텍스트를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | java.lang.String | 이 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`의 텍스트. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


이 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`의 서식이 지정된 텍스트 조각 컬렉션을 가져옵니다.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


이 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`의 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`를 가져옵니다.


**Returns:**
int - 이 `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`의 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`.

### remove() {#remove--}
```
public void remove()
```




