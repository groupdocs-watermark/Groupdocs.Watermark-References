---
title: "PdfShape"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "XObjects 아티팩트 및 주석에 대한 기본 클래스를 제공합니다."
type: docs
weight: 69
url: /ko/java/com.groupdocs.watermark.contents/pdfshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public abstract class PdfShape extends ShapeSearchAdapter implements IRotatableTwoDObject
```

XObjects, Artifacts 및 Annotations에 대한 기본 클래스를 제공합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getText()](#getText--) | 이 `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`의 텍스트를 가져옵니다. |
|
|  | [setText(String value)](#setText-java.lang.String-) | 이 `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`의 텍스트를 가져오거나 설정합니다. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | 이 `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`의 서식이 지정된 텍스트 조각 컬렉션을 가져옵니다. |
|
|  | [getImage()](#getImage--) | 이 `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`의 이미지를 가져옵니다. |
|
|  | [setImage(PdfWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.PdfWatermarkableImage-) | 이 `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`의 이미지를 설정합니다. |
|
|  | [getX()](#getX--) | 객체의 x좌표를 가져옵니다. |
|
|  | [getY()](#getY--) | 객체의 y좌표를 가져옵니다. |
|
|  | [getWidth()](#getWidth--) | 객체의 너비를 가져옵니다. |
|
|  | [getHeight()](#getHeight--) | 객체의 높이를 가져옵니다. |
|
|  | [getRotateAngle()](#getRotateAngle--) | 객체의 회전 각도를 도 단위로 가져옵니다. |
|
|  | [getOuterForm()](#getOuterForm--) | <br /> |

|
|  | [extractImageAppearance()](#extractImageAppearance--) | <br /> |

|
|  | [getTextForSearch()](#getTextForSearch--) | <br /> |

|
|  | [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) | <br /> |

|
|  | [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) | <br /> |

|
|  | [getImageForSearch()](#getImageForSearch--) | <br /> |

|
|  | [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) | <br /> |

|
### getText() {#getText--}
```
public String getText()
```


이 `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`의 텍스트를 가져옵니다.


**Returns:**
java.lang.String - 이 `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`의 텍스트.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


이 `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`의 텍스트를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | java.lang.String | 이 `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`의 텍스트. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


이 `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`의 서식이 지정된 텍스트 조각 컬렉션을 가져옵니다.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.

### getImage() {#getImage--}
```
public final PdfWatermarkableImage getImage()
```


이 `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`의 이미지를 가져옵니다.


**Returns:**
[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage) - The image of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.

### setImage(PdfWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.PdfWatermarkableImage-}
```
public final void setImage(PdfWatermarkableImage value)
```


이 `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`의 이미지를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage) | 이 `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`의 이미지. |
|

### getX() {#getX--}
```
public abstract double getX()
```


객체의 x좌표를 가져옵니다.


**Returns:**
double - 객체의 x좌표.

### getY() {#getY--}
```
public abstract double getY()
```


객체의 y좌표를 가져옵니다.


**Returns:**
double - 객체의 y좌표.

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


객체의 너비를 가져옵니다.


**Returns:**
double - 객체의 너비.

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


객체의 높이를 가져옵니다.


**Returns:**
double - 객체의 높이.

### getRotateAngle() {#getRotateAngle--}
```
public abstract double getRotateAngle()
```


객체의 회전 각도를 도 단위로 가져옵니다.


**Returns:**
double - 객체의 회전 각도(도).

### getOuterForm() {#getOuterForm--}
```
public abstract XForm getOuterForm()
```


<br />



**Returns:**
com.aspose.pdf.XForm
### extractImageAppearance() {#extractImageAppearance--}
```
public PdfXImageAppearance extractImageAppearance()
```


<br />



**Returns:**
[PdfXImageAppearance](../../com.groupdocs.watermark.internal/pdfximageappearance)
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

### getFormattedTextFragmentsForSearch() {#getFormattedTextFragmentsForSearch--}
```
public FormattedTextFragmentCollection getFormattedTextFragmentsForSearch()
```


<br />



**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
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

