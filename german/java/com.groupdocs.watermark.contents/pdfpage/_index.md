---
title: "PdfPage"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt eine PDF-Dokumentseite dar."
type: docs
weight: 65
url: /de/java/com.groupdocs.watermark.contents/pdfpage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class PdfPage extends ContentPart
```

Stellt eine PDF-Dokumentseite dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PdfPage(PdfContent parent, StrategyManager<Integer> strategyManager, Page asposePdfPage)](#PdfPage-com.groupdocs.watermark.contents.PdfContent-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.pdf.Page-) | <br /> |

|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getWidth()](#getWidth--) | Liefert die Breite dieser `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` in Punkten. |
|
|  | [getHeight()](#getHeight--) | Liefert die Höhe dieser `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` in Punkten. |
|
|  | [getArtifacts()](#getArtifacts--) | Liefert die Sammlung aller Artefakte dieser `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`. |
|
|  | [getXObjects()](#getXObjects--) | Liefert die Sammlung aller XObjects dieser `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`. |
|
|  | [getAnnotations()](#getAnnotations--) | Ruft die Sammlung aller Anmerkungen dieser `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` ab. |
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
|  | [rasterize(int horizontalResolution, int verticalResolution, int imageFormat)](#rasterize-int-int-int-) | Konvertiert den Seiteninhalt in ein Bild. |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parent | [PdfContent](../../com.groupdocs.watermark.contents/pdfcontent) |  |
| strategyManager | com.groupdocs.watermark.internal.StrategyManager<java.lang.Integer> |  |
| asposePdfPage | com.aspose.pdf.Page |  |

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Liefert die Breite dieser `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` in Punkten.


**Returns:**
double - Die Breite dieser `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` in Punkten.

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Liefert die Höhe dieser `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` in Punkten.


**Returns:**
double - Die Höhe dieser `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` in Punkten.

### getArtifacts() {#getArtifacts--}
```
public final PdfArtifactCollection getArtifacts()
```


Liefert die Sammlung aller Artefakte dieser `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.


**Returns:**
[PdfArtifactCollection](../../com.groupdocs.watermark.contents/pdfartifactcollection) - The collection of all artifacts of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.

### getXObjects() {#getXObjects--}
```
public final PdfXObjectCollection getXObjects()
```


Liefert die Sammlung aller XObjects dieser `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.


**Returns:**
[PdfXObjectCollection](../../com.groupdocs.watermark.contents/pdfxobjectcollection) - The collection of all XObjects of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.

### getAnnotations() {#getAnnotations--}
```
public final PdfAnnotationCollection getAnnotations()
```


Ruft die Sammlung aller Anmerkungen dieser `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` ab.


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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### addAnnotationWatermark(Watermark watermark, boolean isPrintOnly) {#addAnnotationWatermark-com.groupdocs.watermark.Watermark-boolean-}
```
public final void addAnnotationWatermark(Watermark watermark, boolean isPrintOnly)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| isPrintOnly | boolean |  |

### rasterize(int horizontalResolution, int verticalResolution, int imageFormat) {#rasterize-int-int-int-}
```
public void rasterize(int horizontalResolution, int verticalResolution, int imageFormat)
```


Konvertiert den Seiteninhalt in ein Bild.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | horizontalResolution | int | Horizontale Bildauflösung. |
|
|  | verticalResolution | int | Vertikale Bildauflösung. |
|
|  | imageFormat | int | Bildformat. |
|

### addArtifactToCollection(Artifact artifact) {#addArtifactToCollection-com.aspose.pdf.Artifact-}
```
public final void addArtifactToCollection(Artifact artifact)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Artefakt | com.aspose.pdf.Artifact |  |

### addAnnotationToCollection(Annotation annotation) {#addAnnotationToCollection-com.aspose.pdf.Annotation-}
```
public final void addAnnotationToCollection(Annotation annotation)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Annotation | com.aspose.pdf.Annotation |  |

