---
title: "PdfPage"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示 PDF 文档页面。"
type: docs
weight: 65
url: /zh/java/com.groupdocs.watermark.contents/pdfpage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class PdfPage extends ContentPart
```

表示 PDF 文档页面。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PdfPage(PdfContent parent, StrategyManager<Integer> strategyManager, Page asposePdfPage)](#PdfPage-com.groupdocs.watermark.contents.PdfContent-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.pdf.Page-) | <br /> |

|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getWidth()](#getWidth--) | 获取此 `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` 的宽度（单位：点）。 |
|
|  | [getHeight()](#getHeight--) | 获取此 `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` 的高度（单位：点）。 |
|
|  | [getArtifacts()](#getArtifacts--) | 获取此 `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` 的所有工件集合。 |
|
|  | [getXObjects()](#getXObjects--) | 获取此 `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` 的所有 XObjects 集合。 |
|
|  | [getAnnotations()](#getAnnotations--) | 获取此 `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` 的所有注释集合。 |
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
|  | [rasterize(int horizontalResolution, int verticalResolution, int imageFormat)](#rasterize-int-int-int-) | 将页面内容转换为图像。 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| parent | [PdfContent](../../com.groupdocs.watermark.contents/pdfcontent) |  |
| strategyManager | com.groupdocs.watermark.internal.StrategyManager<java.lang.Integer> |  |
| asposePdfPage | com.aspose.pdf.Page |  |

### getWidth() {#getWidth--}
```
public final double getWidth()
```


获取此 `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` 的宽度（单位：点）。


**Returns:**
double - 此 `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` 的宽度（单位：点）。

### getHeight() {#getHeight--}
```
public final double getHeight()
```


获取此 `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` 的高度（单位：点）。


**Returns:**
double - 此 `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` 的高度（单位：点）。

### getArtifacts() {#getArtifacts--}
```
public final PdfArtifactCollection getArtifacts()
```


获取此 `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` 的所有工件集合。


**Returns:**
[PdfArtifactCollection](../../com.groupdocs.watermark.contents/pdfartifactcollection) - The collection of all artifacts of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.

### getXObjects() {#getXObjects--}
```
public final PdfXObjectCollection getXObjects()
```


获取此 `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` 的所有 XObjects 集合。


**Returns:**
[PdfXObjectCollection](../../com.groupdocs.watermark.contents/pdfxobjectcollection) - The collection of all XObjects of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.

### getAnnotations() {#getAnnotations--}
```
public final PdfAnnotationCollection getAnnotations()
```


获取此 `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` 的所有注释集合。


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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### addAnnotationWatermark(Watermark watermark, boolean isPrintOnly) {#addAnnotationWatermark-com.groupdocs.watermark.Watermark-boolean-}
```
public final void addAnnotationWatermark(Watermark watermark, boolean isPrintOnly)
```


<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| isPrintOnly | boolean |  |

### rasterize(int horizontalResolution, int verticalResolution, int imageFormat) {#rasterize-int-int-int-}
```
public void rasterize(int horizontalResolution, int verticalResolution, int imageFormat)
```


将页面内容转换为图像。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | horizontalResolution | int | 水平图像分辨率. |
|
|  | verticalResolution | int | 垂直图像分辨率. |
|
|  | imageFormat | int | 图像格式. |
|

### addArtifactToCollection(Artifact artifact) {#addArtifactToCollection-com.aspose.pdf.Artifact-}
```
public final void addArtifactToCollection(Artifact artifact)
```


<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 工件 | com.aspose.pdf.Artifact |  |

### addAnnotationToCollection(Annotation annotation) {#addAnnotationToCollection-com.aspose.pdf.Annotation-}
```
public final void addAnnotationToCollection(Annotation annotation)
```


<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 注释 | com.aspose.pdf.Annotation |  |

