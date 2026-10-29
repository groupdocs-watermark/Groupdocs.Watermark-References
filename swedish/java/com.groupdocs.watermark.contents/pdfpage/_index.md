---
title: "PdfPage"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar pdf-dokumentsida."
type: docs
weight: 65
url: /sv/java/com.groupdocs.watermark.contents/pdfpage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class PdfPage extends ContentPart
```

Representerar pdf-dokumentsida.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [PdfPage(PdfContent parent, StrategyManager<Integer> strategyManager, Page asposePdfPage)](#PdfPage-com.groupdocs.watermark.contents.PdfContent-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.pdf.Page-) | <br /> |

|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getWidth()](#getWidth--) | Hämtar bredden på denna `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` i punkter. |
|
|  | [getHeight()](#getHeight--) | Hämtar höjden på denna `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` i punkter. |
|
|  | [getArtifacts()](#getArtifacts--) | Hämtar samlingen av alla artefakter för denna `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`. |
|
|  | [getXObjects()](#getXObjects--) | Hämtar samlingen av alla XObjects för denna `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`. |
|
|  | [getAnnotations()](#getAnnotations--) | Hämtar samlingen av alla annotationer för denna `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`. |
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
|  | [rasterize(int horizontalResolution, int verticalResolution, int imageFormat)](#rasterize-int-int-int-) | Konverterar sidinnehåll till en bild. |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parent | [PdfContent](../../com.groupdocs.watermark.contents/pdfcontent) |  |
| strategyManager | com.groupdocs.watermark.internal.StrategyManager<java.lang.Integer> |  |
| asposePdfPage | com.aspose.pdf.Page |  |

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Hämtar bredden på denna `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` i punkter.


**Returns:**
double - Bredden på denna `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` i punkter.

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Hämtar höjden på denna `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` i punkter.


**Returns:**
double - Höjden på denna `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` i punkter.

### getArtifacts() {#getArtifacts--}
```
public final PdfArtifactCollection getArtifacts()
```


Hämtar samlingen av alla artefakter för denna `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.


**Returns:**
[PdfArtifactCollection](../../com.groupdocs.watermark.contents/pdfartifactcollection) - The collection of all artifacts of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.

### getXObjects() {#getXObjects--}
```
public final PdfXObjectCollection getXObjects()
```


Hämtar samlingen av alla XObjects för denna `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.


**Returns:**
[PdfXObjectCollection](../../com.groupdocs.watermark.contents/pdfxobjectcollection) - The collection of all XObjects of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.

### getAnnotations() {#getAnnotations--}
```
public final PdfAnnotationCollection getAnnotations()
```


Hämtar samlingen av alla annotationer för denna `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.


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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### addAnnotationWatermark(Watermark watermark, boolean isPrintOnly) {#addAnnotationWatermark-com.groupdocs.watermark.Watermark-boolean-}
```
public final void addAnnotationWatermark(Watermark watermark, boolean isPrintOnly)
```


<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| isPrintOnly | boolean |  |

### rasterize(int horizontalResolution, int verticalResolution, int imageFormat) {#rasterize-int-int-int-}
```
public void rasterize(int horizontalResolution, int verticalResolution, int imageFormat)
```


Konverterar sidinnehåll till en bild.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | horizontalResolution | int | Horisontell bildupplösning. |
|
|  | verticalResolution | int | Vertikal bildupplösning. |
|
|  | imageFormat | int | Bildformat. |
|

### addArtifactToCollection(Artifact artifact) {#addArtifactToCollection-com.aspose.pdf.Artifact-}
```
public final void addArtifactToCollection(Artifact artifact)
```


<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| artifact | com.aspose.pdf.Artifact |  |

### addAnnotationToCollection(Annotation annotation) {#addAnnotationToCollection-com.aspose.pdf.Annotation-}
```
public final void addAnnotationToCollection(Annotation annotation)
```


<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| annotation | com.aspose.pdf.Annotation |  |

