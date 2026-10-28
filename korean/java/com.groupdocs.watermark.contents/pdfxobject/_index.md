---
title: "PdfXObject"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "pdf 문서에서 XObject를 나타냅니다."
type: docs
weight: 75
url: /ko/java/com.groupdocs.watermark.contents/pdfxobject/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public abstract class PdfXObject extends PdfShape
```

pdf 문서에서 XObject를 나타냅니다.

**Learn more:**

* [Working with XObjects](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-WorkingwithXObjects)

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPage()](#getPage--) | 이 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`의 상위 페이지를 가져옵니다. |
|
|  | [getX()](#getX--) | 이 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`의 페이지 왼쪽 경계로부터의 수평 오프셋을 포인트 단위로 가져옵니다. |
|
|  | [getY()](#getY--) | 이 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`의 페이지 하단 경계로부터의 수직 오프셋을 포인트 단위로 가져옵니다. |
|
|  | [getWidth()](#getWidth--) | 이 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`의 너비를 포인트 단위로 가져옵니다. |
|
|  | [getHeight()](#getHeight--) | 이 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`의 높이를 포인트 단위로 가져옵니다. |
|
|  | [getRotateAngle()](#getRotateAngle--) | 이 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`의 회전 각도를 도 단위로 가져옵니다. |
|
|  | [getMatrix()](#getMatrix--) | <br /> |

|
### getPage() {#getPage--}
```
public final PdfPage getPage()
```


이 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`의 상위 페이지를 가져옵니다.


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.

### getX() {#getX--}
```
public double getX()
```


이 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`의 페이지 왼쪽 경계로부터의 수평 오프셋을 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`의 x좌표.

### getY() {#getY--}
```
public double getY()
```


이 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`의 페이지 하단 경계로부터의 수직 오프셋을 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`의 y좌표.

### getWidth() {#getWidth--}
```
public double getWidth()
```


이 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`의 너비를 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`의 너비(포인트).

### getHeight() {#getHeight--}
```
public double getHeight()
```


이 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`의 높이를 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`의 높이(포인트).

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


이 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`의 회전 각도를 도 단위로 가져옵니다.


**Returns:**
double - 이 `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`의 회전 각도(도).

### getMatrix() {#getMatrix--}
```
public final Matrix getMatrix()
```


<br />



**Returns:**
com.aspose.pdf.Matrix
