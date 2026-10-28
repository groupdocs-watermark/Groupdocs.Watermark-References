---
title: "PdfPage"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل صفحة مستند PDF."
type: docs
weight: 65
url: /ar/java/com.groupdocs.watermark.contents/pdfpage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class PdfPage extends ContentPart
```

يمثل صفحة مستند PDF.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [PdfPage(PdfContent parent, StrategyManager<Integer> strategyManager, Page asposePdfPage)](#PdfPage-com.groupdocs.watermark.contents.PdfContent-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.pdf.Page-) | <br /> |

|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getWidth()](#getWidth--) | يحصل على عرض هذا `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` بالنقاط. |
|
|  | [getHeight()](#getHeight--) | يحصل على ارتفاع هذا `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` بالنقاط. |
|
|  | [getArtifacts()](#getArtifacts--) | يحصل على مجموعة جميع القطع الأثرية لهذا `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`. |
|
|  | [getXObjects()](#getXObjects--) | يحصل على مجموعة جميع كائنات X لهذا `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`. |
|
|  | [getAnnotations()](#getAnnotations--) | يحصل على مجموعة جميع التعليقات التوضيحية لهذه `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`. |
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
|  | [rasterize(int horizontalResolution, int verticalResolution, int imageFormat)](#rasterize-int-int-int-) | يقوم بتحويل محتوى الصفحة إلى صورة. |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| parent | [PdfContent](../../com.groupdocs.watermark.contents/pdfcontent) |  |
| strategyManager | com.groupdocs.watermark.internal.StrategyManager<java.lang.Integer> |  |
| asposePdfPage | com.aspose.pdf.Page |  |

### getWidth() {#getWidth--}
```
public final double getWidth()
```


يحصل على عرض هذا `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` بالنقاط.


**Returns:**
double - عرض هذه `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` بالنقاط.

### getHeight() {#getHeight--}
```
public final double getHeight()
```


يحصل على ارتفاع هذا `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` بالنقاط.


**Returns:**
double - ارتفاع هذه `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` بالنقاط.

### getArtifacts() {#getArtifacts--}
```
public final PdfArtifactCollection getArtifacts()
```


يحصل على مجموعة جميع القطع الأثرية لهذا `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.


**Returns:**
[PdfArtifactCollection](../../com.groupdocs.watermark.contents/pdfartifactcollection) - The collection of all artifacts of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.

### getXObjects() {#getXObjects--}
```
public final PdfXObjectCollection getXObjects()
```


يحصل على مجموعة جميع كائنات X لهذا `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.


**Returns:**
[PdfXObjectCollection](../../com.groupdocs.watermark.contents/pdfxobjectcollection) - The collection of all XObjects of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.

### getAnnotations() {#getAnnotations--}
```
public final PdfAnnotationCollection getAnnotations()
```


يحصل على مجموعة جميع التعليقات التوضيحية لهذه `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.


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
| معامل | نوع | الوصف |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### addAnnotationWatermark(Watermark watermark, boolean isPrintOnly) {#addAnnotationWatermark-com.groupdocs.watermark.Watermark-boolean-}
```
public final void addAnnotationWatermark(Watermark watermark, boolean isPrintOnly)
```


<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| isPrintOnly | boolean |  |

### rasterize(int horizontalResolution, int verticalResolution, int imageFormat) {#rasterize-int-int-int-}
```
public void rasterize(int horizontalResolution, int verticalResolution, int imageFormat)
```


يقوم بتحويل محتوى الصفحة إلى صورة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | horizontalResolution | int | دقة الصورة الأفقية. |
|
|  | verticalResolution | int | دقة الصورة العمودية. |
|
|  | imageFormat | int | تنسيق الصورة. |
|

### addArtifactToCollection(Artifact artifact) {#addArtifactToCollection-com.aspose.pdf.Artifact-}
```
public final void addArtifactToCollection(Artifact artifact)
```


<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| artifact | com.aspose.pdf.Artifact |  |

### addAnnotationToCollection(Annotation annotation) {#addAnnotationToCollection-com.aspose.pdf.Annotation-}
```
public final void addAnnotationToCollection(Annotation annotation)
```


<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| annotation | com.aspose.pdf.Annotation |  |

