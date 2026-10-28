---
title: "PdfAnnotation"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "pdf 문서의 주석을 나타냅니다."
type: docs
weight: 51
url: /ko/java/com.groupdocs.watermark.contents/pdfannotation/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public class PdfAnnotation extends PdfShape
```

pdf 문서의 주석을 나타냅니다.

**Learn more:**

* [Working with annotations](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-Workingwithannotations)

## 필드

| 필드 | 설명 |
| --- | --- |
|  | [NormalAppearanceKey](#NormalAppearanceKey) | <br /> |

|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPage()](#getPage--) | 이 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`의 상위 페이지를 가져옵니다. |
|
|  | [getAnnotationType()](#getAnnotationType--) | 이 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`의 유형을 가져옵니다. |
|
|  | [getX()](#getX--) | 이 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`의 페이지 왼쪽 경계로부터 수평 오프셋을 포인트 단위로 가져옵니다. |
|
|  | [getY()](#getY--) | 이 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`의 워크시트 하단 경계로부터 수직 오프셋을 포인트 단위로 가져옵니다. |
|
|  | [getRotateAngle()](#getRotateAngle--) | 이 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`의 회전 각도를 도 단위로 가져옵니다. |
|
|  | [getWidth()](#getWidth--) | 이 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`의 너비를 포인트 단위로 가져옵니다. |
|
|  | [getHeight()](#getHeight--) | 이 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`의 높이를 포인트 단위로 가져옵니다. |
|
|  | [getAsposePdfAnnotation()](#getAsposePdfAnnotation--) | <br /> |

|
|  | [getOuterForm()](#getOuterForm--) | <br /> |

|
### NormalAppearanceKey {#NormalAppearanceKey}
```
public static final String NormalAppearanceKey
```


<br />



### getPage() {#getPage--}
```
public final PdfPage getPage()
```


이 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`의 상위 페이지를 가져옵니다.


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.

### getAnnotationType() {#getAnnotationType--}
```
public final int getAnnotationType()
```


이 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`의 유형을 가져옵니다.


**Returns:**
int - 이 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`의 유형입니다.

### getX() {#getX--}
```
public double getX()
```


이 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`의 페이지 왼쪽 경계로부터 수평 오프셋을 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`의 페이지 왼쪽 경계선으로부터의 수평 오프셋(포인트)입니다.

### getY() {#getY--}
```
public double getY()
```


이 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`의 워크시트 하단 경계로부터 수직 오프셋을 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`의 워크시트 하단 경계선으로부터의 수직 오프셋(포인트)입니다.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


이 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`의 회전 각도를 도 단위로 가져옵니다.


**Returns:**
double - 이 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`의 회전 각도(도)입니다.

### getWidth() {#getWidth--}
```
public double getWidth()
```


이 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`의 너비를 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`의 너비(포인트)입니다.

### getHeight() {#getHeight--}
```
public double getHeight()
```


이 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`의 높이를 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`의 높이(포인트)입니다.

### getAsposePdfAnnotation() {#getAsposePdfAnnotation--}
```
public final Annotation getAsposePdfAnnotation()
```


<br />



**Returns:**
com.aspose.pdf.Annotation
### getOuterForm() {#getOuterForm--}
```
public XForm getOuterForm()
```


<br />



**Returns:**
com.aspose.pdf.XForm
