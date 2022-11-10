---
title: PdfPage
second_title: GroupDocs.Watermark for Java API Reference
description: Represents pdf document page.
type: docs
weight: 65
url: /java/com.groupdocs.watermark.contents/pdfpage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class PdfPage extends ContentPart
```

Represents pdf document page.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfPage(PdfContent parent, StrategyManager<Integer> strategyManager, Page asposePdfPage)](#PdfPage-com.groupdocs.watermark.contents.PdfContent-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.pdf.Page-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Gets the width of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` in points. |
| [getHeight()](#getHeight--) | Gets the height of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` in points. |
| [getArtifacts()](#getArtifacts--) | Gets the collection of all artifacts of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`. |
| [getXObjects()](#getXObjects--) | Gets the collection of all XObjects of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`. |
| [getAnnotations()](#getAnnotations--) | Gets the collection of all annotations of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`. |
| [getAsposePdfPage()](#getAsposePdfPage--) |  |
| [getContent()](#getContent--) |  |
| [getPageRectangle()](#getPageRectangle--) |  |
| [addArtifactWatermark(Watermark watermark)](#addArtifactWatermark-com.groupdocs.watermark.Watermark-) |  |
| [addAnnotationWatermark(Watermark watermark, boolean isPrintOnly)](#addAnnotationWatermark-com.groupdocs.watermark.Watermark-boolean-) |  |
| [rasterize(int horizontalResolution, int verticalResolution, int imageFormat)](#rasterize-int-int-int-) | Converts page content into an image. |
| [addArtifactToCollection(Artifact artifact)](#addArtifactToCollection-com.aspose.pdf.Artifact-) |  |
| [addAnnotationToCollection(Annotation annotation)](#addAnnotationToCollection-com.aspose.pdf.Annotation-) |  |
### PdfPage(PdfContent parent, StrategyManager<Integer> strategyManager, Page asposePdfPage) {#PdfPage-com.groupdocs.watermark.contents.PdfContent-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.pdf.Page-}
```
public PdfPage(PdfContent parent, StrategyManager<Integer> strategyManager, Page asposePdfPage)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parent | [PdfContent](../../com.groupdocs.watermark.contents/pdfcontent) |  |
| strategyManager | com.groupdocs.watermark.internal.StrategyManager<java.lang.Integer> |  |
| asposePdfPage | com.aspose.pdf.Page |  |

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Gets the width of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` in points.

**Returns:**
double - The width of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` in points.
### getHeight() {#getHeight--}
```
public final double getHeight()
```


Gets the height of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` in points.

**Returns:**
double - The height of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` in points.
### getArtifacts() {#getArtifacts--}
```
public final PdfArtifactCollection getArtifacts()
```


Gets the collection of all artifacts of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.

**Returns:**
[PdfArtifactCollection](../../com.groupdocs.watermark.contents/pdfartifactcollection) - The collection of all artifacts of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.
### getXObjects() {#getXObjects--}
```
public final PdfXObjectCollection getXObjects()
```


Gets the collection of all XObjects of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.

**Returns:**
[PdfXObjectCollection](../../com.groupdocs.watermark.contents/pdfxobjectcollection) - The collection of all XObjects of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.
### getAnnotations() {#getAnnotations--}
```
public final PdfAnnotationCollection getAnnotations()
```


Gets the collection of all annotations of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.

**Returns:**
[PdfAnnotationCollection](../../com.groupdocs.watermark.contents/pdfannotationcollection) - The collection of all annotations of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.
### getAsposePdfPage() {#getAsposePdfPage--}
```
public final Page getAsposePdfPage()
```




**Returns:**
com.aspose.pdf.Page
### getContent() {#getContent--}
```
public final PdfContent getContent()
```




**Returns:**
[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)
### getPageRectangle() {#getPageRectangle--}
```
public final Rectangle getPageRectangle()
```




**Returns:**
com.aspose.pdf.Rectangle
### addArtifactWatermark(Watermark watermark) {#addArtifactWatermark-com.groupdocs.watermark.Watermark-}
```
public final void addArtifactWatermark(Watermark watermark)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### addAnnotationWatermark(Watermark watermark, boolean isPrintOnly) {#addAnnotationWatermark-com.groupdocs.watermark.Watermark-boolean-}
```
public final void addAnnotationWatermark(Watermark watermark, boolean isPrintOnly)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| isPrintOnly | boolean |  |

### rasterize(int horizontalResolution, int verticalResolution, int imageFormat) {#rasterize-int-int-int-}
```
public void rasterize(int horizontalResolution, int verticalResolution, int imageFormat)
```


Converts page content into an image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| horizontalResolution | int | Horizontal image resolution. |
| verticalResolution | int | Vertical image resolution. |
| imageFormat | int | Image format. |

### addArtifactToCollection(Artifact artifact) {#addArtifactToCollection-com.aspose.pdf.Artifact-}
```
public final void addArtifactToCollection(Artifact artifact)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| artifact | com.aspose.pdf.Artifact |  |

### addAnnotationToCollection(Annotation annotation) {#addAnnotationToCollection-com.aspose.pdf.Annotation-}
```
public final void addAnnotationToCollection(Annotation annotation)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotation | com.aspose.pdf.Annotation |  |

