---
title: "PdfPage"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "PDF belge sayfasını temsil eder."
type: docs
weight: 65
url: /tr/java/com.groupdocs.watermark.contents/pdfpage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class PdfPage extends ContentPart
```

PDF belge sayfasını temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [PdfPage(PdfContent parent, StrategyManager<Integer> strategyManager, Page asposePdfPage)](#PdfPage-com.groupdocs.watermark.contents.PdfContent-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.pdf.Page-) | <br /> |

|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getWidth()](#getWidth--) | Bu `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` nesnesinin genişliğini nokta cinsinden alır. |
|
|  | [getHeight()](#getHeight--) | Bu `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` nesnesinin yüksekliğini nokta cinsinden alır. |
|
|  | [getArtifacts()](#getArtifacts--) | Bu `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` nesnesinin tüm artefakt koleksiyonunu alır. |
|
|  | [getXObjects()](#getXObjects--) | Bu `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` nesnesinin tüm XObject'lerinin koleksiyonunu alır. |
|
|  | [getAnnotations()](#getAnnotations--) | Bu `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` öğesinin tüm açıklamalarının koleksiyonunu alır. |
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
|  | [rasterize(int horizontalResolution, int verticalResolution, int imageFormat)](#rasterize-int-int-int-) | Sayfa içeriğini bir görüntüye dönüştürür. |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parent | [PdfContent](../../com.groupdocs.watermark.contents/pdfcontent) |  |
| strategyManager | com.groupdocs.watermark.internal.StrategyManager<java.lang.Integer> |  |
| asposePdfPage | com.aspose.pdf.Page |  |

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Bu `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` nesnesinin genişliğini nokta cinsinden alır.


**Returns:**
double - Bu `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` öğesinin puan cinsinden genişliği.

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Bu `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` nesnesinin yüksekliğini nokta cinsinden alır.


**Returns:**
double - Bu `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` öğesinin puan cinsinden yüksekliği.

### getArtifacts() {#getArtifacts--}
```
public final PdfArtifactCollection getArtifacts()
```


Bu `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` nesnesinin tüm artefakt koleksiyonunu alır.


**Returns:**
[PdfArtifactCollection](../../com.groupdocs.watermark.contents/pdfartifactcollection) - The collection of all artifacts of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.

### getXObjects() {#getXObjects--}
```
public final PdfXObjectCollection getXObjects()
```


Bu `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` nesnesinin tüm XObject'lerinin koleksiyonunu alır.


**Returns:**
[PdfXObjectCollection](../../com.groupdocs.watermark.contents/pdfxobjectcollection) - The collection of all XObjects of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.

### getAnnotations() {#getAnnotations--}
```
public final PdfAnnotationCollection getAnnotations()
```


Bu `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` öğesinin tüm açıklamalarının koleksiyonunu alır.


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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### addAnnotationWatermark(Watermark watermark, boolean isPrintOnly) {#addAnnotationWatermark-com.groupdocs.watermark.Watermark-boolean-}
```
public final void addAnnotationWatermark(Watermark watermark, boolean isPrintOnly)
```


<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| isPrintOnly | boolean |  |

### rasterize(int horizontalResolution, int verticalResolution, int imageFormat) {#rasterize-int-int-int-}
```
public void rasterize(int horizontalResolution, int verticalResolution, int imageFormat)
```


Sayfa içeriğini bir görüntüye dönüştürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | horizontalResolution | int | Yatay görüntü çözünürlüğü. |
|
|  | verticalResolution | int | Dikey görüntü çözünürlüğü. |
|
|  | imageFormat | int | Görüntü formatı. |
|

### addArtifactToCollection(Artifact artifact) {#addArtifactToCollection-com.aspose.pdf.Artifact-}
```
public final void addArtifactToCollection(Artifact artifact)
```


<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| artefakt | com.aspose.pdf.Artifact |  |

### addAnnotationToCollection(Annotation annotation) {#addAnnotationToCollection-com.aspose.pdf.Annotation-}
```
public final void addAnnotationToCollection(Annotation annotation)
```


<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| annotation | com.aspose.pdf.Annotation |  |

