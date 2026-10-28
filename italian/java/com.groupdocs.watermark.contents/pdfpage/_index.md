---
title: "PdfPage"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta la pagina di un documento PDF."
type: docs
weight: 65
url: /it/java/com.groupdocs.watermark.contents/pdfpage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class PdfPage extends ContentPart
```

Rappresenta la pagina di un documento PDF.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [PdfPage(PdfContent parent, StrategyManager<Integer> strategyManager, Page asposePdfPage)](#PdfPage-com.groupdocs.watermark.contents.PdfContent-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.pdf.Page-) | <br /> |

|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getWidth()](#getWidth--) | Restituisce la larghezza di questo `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` in punti. |
|
|  | [getHeight()](#getHeight--) | Restituisce l'altezza di questo `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` in punti. |
|
|  | [getArtifacts()](#getArtifacts--) | Restituisce la collezione di tutti gli artefatti di questo `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`. |
|
|  | [getXObjects()](#getXObjects--) | Restituisce la collezione di tutti gli XObject di questo `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`. |
|
|  | [getAnnotations()](#getAnnotations--) | Restituisce la collezione di tutte le annotazioni di questo `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`. |
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
|  | [rasterize(int horizontalResolution, int verticalResolution, int imageFormat)](#rasterize-int-int-int-) | Converte il contenuto della pagina in un'immagine. |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| parent | [PdfContent](../../com.groupdocs.watermark.contents/pdfcontent) |  |
| strategyManager | com.groupdocs.watermark.internal.StrategyManager<java.lang.Integer> |  |
| asposePdfPage | com.aspose.pdf.Page |  |

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Restituisce la larghezza di questo `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` in punti.


**Returns:**
double - La larghezza di questo `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` in punti.

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Restituisce l'altezza di questo `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` in punti.


**Returns:**
double - L'altezza di questo `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` in punti.

### getArtifacts() {#getArtifacts--}
```
public final PdfArtifactCollection getArtifacts()
```


Restituisce la collezione di tutti gli artefatti di questo `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.


**Returns:**
[PdfArtifactCollection](../../com.groupdocs.watermark.contents/pdfartifactcollection) - The collection of all artifacts of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.

### getXObjects() {#getXObjects--}
```
public final PdfXObjectCollection getXObjects()
```


Restituisce la collezione di tutti gli XObject di questo `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.


**Returns:**
[PdfXObjectCollection](../../com.groupdocs.watermark.contents/pdfxobjectcollection) - The collection of all XObjects of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.

### getAnnotations() {#getAnnotations--}
```
public final PdfAnnotationCollection getAnnotations()
```


Restituisce la collezione di tutte le annotazioni di questo `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.


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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### addAnnotationWatermark(Watermark watermark, boolean isPrintOnly) {#addAnnotationWatermark-com.groupdocs.watermark.Watermark-boolean-}
```
public final void addAnnotationWatermark(Watermark watermark, boolean isPrintOnly)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| isPrintOnly | boolean |  |

### rasterize(int horizontalResolution, int verticalResolution, int imageFormat) {#rasterize-int-int-int-}
```
public void rasterize(int horizontalResolution, int verticalResolution, int imageFormat)
```


Converte il contenuto della pagina in un'immagine.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | horizontalResolution | int | Risoluzione orizzontale dell'immagine. |
|
|  | verticalResolution | int | Risoluzione verticale dell'immagine. |
|
|  | imageFormat | int | Formato immagine. |
|

### addArtifactToCollection(Artifact artifact) {#addArtifactToCollection-com.aspose.pdf.Artifact-}
```
public final void addArtifactToCollection(Artifact artifact)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| artefatto | com.aspose.pdf.Artifact |  |

### addAnnotationToCollection(Annotation annotation) {#addAnnotationToCollection-com.aspose.pdf.Annotation-}
```
public final void addAnnotationToCollection(Annotation annotation)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| annotazione | com.aspose.pdf.Annotation |  |

