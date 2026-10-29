---
title: "PdfPage"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa una página de documento pdf."
type: docs
weight: 65
url: /es/java/com.groupdocs.watermark.contents/pdfpage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class PdfPage extends ContentPart
```

Representa una página de documento pdf.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PdfPage(PdfContent parent, StrategyManager<Integer> strategyManager, Page asposePdfPage)](#PdfPage-com.groupdocs.watermark.contents.PdfContent-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.pdf.Page-) | <br /> |

|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getWidth()](#getWidth--) | Obtiene el ancho de este `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` en puntos. |
|
|  | [getHeight()](#getHeight--) | Obtiene la altura de este `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` en puntos. |
|
|  | [getArtifacts()](#getArtifacts--) | Obtiene la colección de todos los artefactos de este `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`. |
|
|  | [getXObjects()](#getXObjects--) | Obtiene la colección de todos los XObjects de este `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`. |
|
|  | [getAnnotations()](#getAnnotations--) | Obtiene la colección de todas las anotaciones de este `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`. |
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
|  | [rasterize(int horizontalResolution, int verticalResolution, int imageFormat)](#rasterize-int-int-int-) | Convierte el contenido de la página en una imagen. |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parent | [PdfContent](../../com.groupdocs.watermark.contents/pdfcontent) |  |
| strategyManager | com.groupdocs.watermark.internal.StrategyManager<java.lang.Integer> |  |
| asposePdfPage | com.aspose.pdf.Page |  |

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Obtiene el ancho de este `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` en puntos.


**Returns:**
double - El ancho de este `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` en puntos.

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Obtiene la altura de este `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` en puntos.


**Returns:**
double - La altura de este `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` en puntos.

### getArtifacts() {#getArtifacts--}
```
public final PdfArtifactCollection getArtifacts()
```


Obtiene la colección de todos los artefactos de este `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.


**Returns:**
[PdfArtifactCollection](../../com.groupdocs.watermark.contents/pdfartifactcollection) - The collection of all artifacts of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.

### getXObjects() {#getXObjects--}
```
public final PdfXObjectCollection getXObjects()
```


Obtiene la colección de todos los XObjects de este `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.


**Returns:**
[PdfXObjectCollection](../../com.groupdocs.watermark.contents/pdfxobjectcollection) - The collection of all XObjects of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.

### getAnnotations() {#getAnnotations--}
```
public final PdfAnnotationCollection getAnnotations()
```


Obtiene la colección de todas las anotaciones de este `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.


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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### addAnnotationWatermark(Watermark watermark, boolean isPrintOnly) {#addAnnotationWatermark-com.groupdocs.watermark.Watermark-boolean-}
```
public final void addAnnotationWatermark(Watermark watermark, boolean isPrintOnly)
```


<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| isPrintOnly | boolean |  |

### rasterize(int horizontalResolution, int verticalResolution, int imageFormat) {#rasterize-int-int-int-}
```
public void rasterize(int horizontalResolution, int verticalResolution, int imageFormat)
```


Convierte el contenido de la página en una imagen.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | horizontalResolution | int | Resolución horizontal de la imagen. |
|
|  | verticalResolution | int | Resolución vertical de la imagen. |
|
|  | imageFormat | int | Formato de imagen. |
|

### addArtifactToCollection(Artifact artifact) {#addArtifactToCollection-com.aspose.pdf.Artifact-}
```
public final void addArtifactToCollection(Artifact artifact)
```


<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| artefacto | com.aspose.pdf.Artifact |  |

### addAnnotationToCollection(Annotation annotation) {#addAnnotationToCollection-com.aspose.pdf.Annotation-}
```
public final void addAnnotationToCollection(Annotation annotation)
```


<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| anotación | com.aspose.pdf.Annotation |  |

