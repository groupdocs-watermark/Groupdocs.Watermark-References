---
title: "PdfArtifact"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "pdf 콘텐츠의 아티팩트를 나타냅니다."
type: docs
weight: 54
url: /ko/java/com.groupdocs.watermark.contents/pdfartifact/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public class PdfArtifact extends PdfShape
```

pdf 콘텐츠의 아티팩트를 나타냅니다.

**Lean more**

* [Working with artifacts](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-Workingwithartifacts)

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPage()](#getPage--) | 이 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`의 상위 페이지를 가져옵니다. |
|
|  | [getText()](#getText--) | 이 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`의 텍스트를 가져옵니다. |
|
|  | [setText(String value)](#setText-java.lang.String-) | 이 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`의 텍스트를 설정합니다. |
|
|  | [getArtifactType()](#getArtifactType--) | 이 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`의 유형을 가져옵니다. |
|
|  | [getArtifactSubtype()](#getArtifactSubtype--) | 이 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`의 하위 유형을 가져옵니다. |
|
|  | [getOpacity()](#getOpacity--) | 이 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`의 불투명도를 가져옵니다. |
|
|  | [getX()](#getX--) | 이 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`의 페이지 왼쪽 경계로부터 수평 오프셋을 포인트 단위로 가져옵니다. |
|
|  | [getY()](#getY--) | 이 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`의 페이지 하단 경계로부터 수직 오프셋을 포인트 단위로 가져옵니다. |
|
|  | [getRotateAngle()](#getRotateAngle--) | 이 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`의 회전 각도를 도 단위로 가져옵니다. |
|
|  | [getWidth()](#getWidth--) | 이 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`의 너비를 포인트 단위로 가져옵니다. |
|
|  | [getHeight()](#getHeight--) | 이 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`의 높이를 포인트 단위로 가져옵니다. |
|
|  | [getAsposePdfArtifact()](#getAsposePdfArtifact--) | <br /> |

|
|  | [getOuterForm()](#getOuterForm--) | <br /> |

|
### getPage() {#getPage--}
```
public final PdfPage getPage()
```


이 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`의 상위 페이지를 가져옵니다.


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getText() {#getText--}
```
public String getText()
```


이 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`의 텍스트를 가져옵니다.


**Returns:**
java.lang.String - 이 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`의 텍스트.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


이 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`의 텍스트를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | java.lang.String | 이 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`의 텍스트. |
|

### getArtifactType() {#getArtifactType--}
```
public final int getArtifactType()
```


이 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`의 유형을 가져옵니다.


**Returns:**
int - 이 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`의 유형.

### getArtifactSubtype() {#getArtifactSubtype--}
```
public final int getArtifactSubtype()
```


이 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`의 하위 유형을 가져옵니다.


**Returns:**
int - 이 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`의 하위 유형.

### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


이 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`의 불투명도를 가져옵니다.

가능한 값은 [0, 1] 범위에 있습니다.


**Returns:**
double - 이 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`의 불투명도.

### getX() {#getX--}
```
public double getX()
```


이 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`의 페이지 왼쪽 경계로부터 수평 오프셋을 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`의 x좌표.

### getY() {#getY--}
```
public double getY()
```


이 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`의 페이지 하단 경계로부터 수직 오프셋을 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`의 y좌표.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


이 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`의 회전 각도를 도 단위로 가져옵니다.


**Returns:**
double - 이 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`의 회전 각도(도).

### getWidth() {#getWidth--}
```
public double getWidth()
```


이 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`의 너비를 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`의 너비(포인트).

### getHeight() {#getHeight--}
```
public double getHeight()
```


이 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`의 높이를 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`의 높이(포인트).

### getAsposePdfArtifact() {#getAsposePdfArtifact--}
```
public final Artifact getAsposePdfArtifact()
```


<br />



**Returns:**
com.aspose.pdf.Artifact
### getOuterForm() {#getOuterForm--}
```
public XForm getOuterForm()
```


<br />



**Returns:**
com.aspose.pdf.XForm
