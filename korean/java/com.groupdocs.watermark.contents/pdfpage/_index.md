---
title: "PdfPage"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "pdf 문서 페이지를 나타냅니다."
type: docs
weight: 65
url: /ko/java/com.groupdocs.watermark.contents/pdfpage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class PdfPage extends ContentPart
```

pdf 문서 페이지를 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [PdfPage(PdfContent parent, StrategyManager<Integer> strategyManager, Page asposePdfPage)](#PdfPage-com.groupdocs.watermark.contents.PdfContent-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.pdf.Page-) | <br /> |

|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getWidth()](#getWidth--) | 이 `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`의 너비를 포인트 단위로 가져옵니다. |
|
|  | [getHeight()](#getHeight--) | 이 `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`의 높이를 포인트 단위로 가져옵니다. |
|
|  | [getArtifacts()](#getArtifacts--) | 이 `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`의 모든 아티팩트 컬렉션을 가져옵니다. |
|
|  | [getXObjects()](#getXObjects--) | 이 `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`의 모든 XObjects 컬렉션을 가져옵니다. |
|
|  | [getAnnotations()](#getAnnotations--) | 이 `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`의 모든 주석 컬렉션을 가져옵니다. |
|
|  | [getAsposePdfPage()](#getAsposePdfPage--) | <br /> |

|
|  | [getContent()](#getContent--) | <br /> |

|
|  | [getPageRectangle()](#getPageRectangle--) | <br /> |

|
|  | [addArtifactWatermark(Watermark watermark)](#addArtifactWatermark-com.groupdocs.watermark.Watermark-) | <br /> |

|
|  | [addAnnotationWatermark(Watermark watermark, boolean isPrintOnly)](#addAnnotationWatermark-com.groupdocs.watermark.Watermark-boolean-) | <br /> |

|
|  | [rasterize(int horizontalResolution, int verticalResolution, int imageFormat)](#rasterize-int-int-int-) | 페이지 콘텐츠를 이미지로 변환합니다. |
|
|  | [addArtifactToCollection(Artifact artifact)](#addArtifactToCollection-com.aspose.pdf.Artifact-) | <br /> |

|
|  | [addAnnotationToCollection(Annotation annotation)](#addAnnotationToCollection-com.aspose.pdf.Annotation-) | <br /> |

|
### PdfPage(PdfContent parent, StrategyManager<Integer> strategyManager, Page asposePdfPage) {#PdfPage-com.groupdocs.watermark.contents.PdfContent-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.pdf.Page-}
```
public PdfPage(PdfContent parent, StrategyManager<Integer> strategyManager, Page asposePdfPage)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| parent | [PdfContent](../../com.groupdocs.watermark.contents/pdfcontent) |  |
| strategyManager | com.groupdocs.watermark.internal.StrategyManager<java.lang.Integer> |  |
| asposePdfPage | com.aspose.pdf.Page |  |

### getWidth() {#getWidth--}
```
public final double getWidth()
```


이 `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`의 너비를 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`의 너비(포인트 단위).

### getHeight() {#getHeight--}
```
public final double getHeight()
```


이 `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`의 높이를 포인트 단위로 가져옵니다.


**Returns:**
double - 이 `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`의 높이(포인트 단위).

### getArtifacts() {#getArtifacts--}
```
public final PdfArtifactCollection getArtifacts()
```


이 `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`의 모든 아티팩트 컬렉션을 가져옵니다.


**Returns:**
[PdfArtifactCollection](../../com.groupdocs.watermark.contents/pdfartifactcollection) - The collection of all artifacts of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.

### getXObjects() {#getXObjects--}
```
public final PdfXObjectCollection getXObjects()
```


이 `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`의 모든 XObjects 컬렉션을 가져옵니다.


**Returns:**
[PdfXObjectCollection](../../com.groupdocs.watermark.contents/pdfxobjectcollection) - The collection of all XObjects of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.

### getAnnotations() {#getAnnotations--}
```
public final PdfAnnotationCollection getAnnotations()
```


이 `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`의 모든 주석 컬렉션을 가져옵니다.


**Returns:**
[PdfAnnotationCollection](../../com.groupdocs.watermark.contents/pdfannotationcollection) - The collection of all annotations of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.

### getAsposePdfPage() {#getAsposePdfPage--}
```
public final Page getAsposePdfPage()
```


<br />



**Returns:**
com.aspose.pdf.Page
### getContent() {#getContent--}
```
public final PdfContent getContent()
```


<br />



**Returns:**
[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)
### getPageRectangle() {#getPageRectangle--}
```
public final Rectangle getPageRectangle()
```


<br />



**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle)
### addArtifactWatermark(Watermark watermark) {#addArtifactWatermark-com.groupdocs.watermark.Watermark-}
```
public final void addArtifactWatermark(Watermark watermark)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### addAnnotationWatermark(Watermark watermark, boolean isPrintOnly) {#addAnnotationWatermark-com.groupdocs.watermark.Watermark-boolean-}
```
public final void addAnnotationWatermark(Watermark watermark, boolean isPrintOnly)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| isPrintOnly | boolean |  |

### rasterize(int horizontalResolution, int verticalResolution, int imageFormat) {#rasterize-int-int-int-}
```
public void rasterize(int horizontalResolution, int verticalResolution, int imageFormat)
```


페이지 콘텐츠를 이미지로 변환합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | horizontalResolution | int | 수평 이미지 해상도. |
|
|  | verticalResolution | int | 수직 이미지 해상도. |
|
|  | imageFormat | int | 이미지 형식. |
|

### addArtifactToCollection(Artifact artifact) {#addArtifactToCollection-com.aspose.pdf.Artifact-}
```
public final void addArtifactToCollection(Artifact artifact)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 아티팩트 | com.aspose.pdf.Artifact |  |

### addAnnotationToCollection(Annotation annotation) {#addAnnotationToCollection-com.aspose.pdf.Annotation-}
```
public final void addAnnotationToCollection(Annotation annotation)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 주석 | com.aspose.pdf.Annotation |  |

