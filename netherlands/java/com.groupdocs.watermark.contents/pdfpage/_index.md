---
title: "PdfPage"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt een pdf-documentpagina voor."
type: docs
weight: 65
url: /nl/java/com.groupdocs.watermark.contents/pdfpage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class PdfPage extends ContentPart
```

Stelt een pdf-documentpagina voor.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [PdfPage(PdfContent parent, StrategyManager<Integer> strategyManager, Page asposePdfPage)](#PdfPage-com.groupdocs.watermark.contents.PdfContent-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.pdf.Page-) | <br /> |

|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getWidth()](#getWidth--) | Haalt de breedte van deze `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` op in punten. |
|
|  | [getHeight()](#getHeight--) | Haalt de hoogte van deze `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` op in punten. |
|
|  | [getArtifacts()](#getArtifacts--) | Haalt de collectie van alle artefacten van deze `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` op. |
|
|  | [getXObjects()](#getXObjects--) | Haalt de collectie van alle XObjecten van deze `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` op. |
|
|  | [getAnnotations()](#getAnnotations--) | Haalt de collectie van alle annotaties van deze `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` op. |
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
|  | [rasterize(int horizontalResolution, int verticalResolution, int imageFormat)](#rasterize-int-int-int-) | Converteert paginainhoud naar een afbeelding. |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parent | [PdfContent](../../com.groupdocs.watermark.contents/pdfcontent) |  |
| strategyManager | com.groupdocs.watermark.internal.StrategyManager<java.lang.Integer> |  |
| asposePdfPage | com.aspose.pdf.Page |  |

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Haalt de breedte van deze `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` op in punten.


**Returns:**
double - De breedte van deze `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` in punten.

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Haalt de hoogte van deze `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` op in punten.


**Returns:**
double - De hoogte van deze `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` in punten.

### getArtifacts() {#getArtifacts--}
```
public final PdfArtifactCollection getArtifacts()
```


Haalt de collectie van alle artefacten van deze `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` op.


**Returns:**
[PdfArtifactCollection](../../com.groupdocs.watermark.contents/pdfartifactcollection) - The collection of all artifacts of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.

### getXObjects() {#getXObjects--}
```
public final PdfXObjectCollection getXObjects()
```


Haalt de collectie van alle XObjecten van deze `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` op.


**Returns:**
[PdfXObjectCollection](../../com.groupdocs.watermark.contents/pdfxobjectcollection) - The collection of all XObjects of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.

### getAnnotations() {#getAnnotations--}
```
public final PdfAnnotationCollection getAnnotations()
```


Haalt de collectie van alle annotaties van deze `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` op.


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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### addAnnotationWatermark(Watermark watermark, boolean isPrintOnly) {#addAnnotationWatermark-com.groupdocs.watermark.Watermark-boolean-}
```
public final void addAnnotationWatermark(Watermark watermark, boolean isPrintOnly)
```


<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| isPrintOnly | boolean |  |

### rasterize(int horizontalResolution, int verticalResolution, int imageFormat) {#rasterize-int-int-int-}
```
public void rasterize(int horizontalResolution, int verticalResolution, int imageFormat)
```


Converteert paginainhoud naar een afbeelding.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | horizontalResolution | int | Horizontale beeldresolutie. |
|
|  | verticalResolution | int | Verticale beeldresolutie. |
|
|  | imageFormat | int | Beeldformaat. |
|

### addArtifactToCollection(Artifact artifact) {#addArtifactToCollection-com.aspose.pdf.Artifact-}
```
public final void addArtifactToCollection(Artifact artifact)
```


<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| artefact | com.aspose.pdf.Artifact |  |

### addAnnotationToCollection(Annotation annotation) {#addAnnotationToCollection-com.aspose.pdf.Annotation-}
```
public final void addAnnotationToCollection(Annotation annotation)
```


<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| annotatie | com.aspose.pdf.Annotation |  |

