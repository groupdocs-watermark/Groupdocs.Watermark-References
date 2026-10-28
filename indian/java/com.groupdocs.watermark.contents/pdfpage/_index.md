---
title: "PdfPage"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "PDF दस्तावेज़ पृष्ठ का प्रतिनिधित्व करता है।"
type: docs
weight: 65
url: /hi/java/com.groupdocs.watermark.contents/pdfpage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class PdfPage extends ContentPart
```

PDF दस्तावेज़ पृष्ठ का प्रतिनिधित्व करता है।

## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [PdfPage(PdfContent parent, StrategyManager<Integer> strategyManager, Page asposePdfPage)](#PdfPage-com.groupdocs.watermark.contents.PdfContent-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.pdf.Page-) | <br /> |

|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getWidth()](#getWidth--) | इस `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` की चौड़ाई पॉइंट्स में प्राप्त करता है। |
|
|  | [getHeight()](#getHeight--) | इस `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` की ऊँचाई पॉइंट्स में प्राप्त करता है। |
|
|  | [getArtifacts()](#getArtifacts--) | इस `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` के सभी आर्टिफैक्ट्स का संग्रह प्राप्त करता है। |
|
|  | [getXObjects()](#getXObjects--) | इस `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` के सभी XObjects का संग्रह प्राप्त करता है। |
|
|  | [getAnnotations()](#getAnnotations--) | इस `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` के सभी एनोटेशन का संग्रह प्राप्त करता है। |
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
|  | [rasterize(int horizontalResolution, int verticalResolution, int imageFormat)](#rasterize-int-int-int-) | पृष्ठ सामग्री को एक छवि में परिवर्तित करता है। |
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| parent | [PdfContent](../../com.groupdocs.watermark.contents/pdfcontent) |  |
| strategyManager | com.groupdocs.watermark.internal.StrategyManager<java.lang.Integer> |  |
| asposePdfPage | com.aspose.pdf.Page |  |

### getWidth() {#getWidth--}
```
public final double getWidth()
```


इस `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` की चौड़ाई पॉइंट्स में प्राप्त करता है।


**Returns:**
double - इस `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` की चौड़ाई पॉइंट्स में।

### getHeight() {#getHeight--}
```
public final double getHeight()
```


इस `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` की ऊँचाई पॉइंट्स में प्राप्त करता है।


**Returns:**
double - इस `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` की ऊँचाई पॉइंट्स में।

### getArtifacts() {#getArtifacts--}
```
public final PdfArtifactCollection getArtifacts()
```


इस `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` के सभी आर्टिफैक्ट्स का संग्रह प्राप्त करता है।


**Returns:**
[PdfArtifactCollection](../../com.groupdocs.watermark.contents/pdfartifactcollection) - The collection of all artifacts of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.

### getXObjects() {#getXObjects--}
```
public final PdfXObjectCollection getXObjects()
```


इस `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` के सभी XObjects का संग्रह प्राप्त करता है।


**Returns:**
[PdfXObjectCollection](../../com.groupdocs.watermark.contents/pdfxobjectcollection) - The collection of all XObjects of this `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)`.

### getAnnotations() {#getAnnotations--}
```
public final PdfAnnotationCollection getAnnotations()
```


इस `[PdfPage](../../com.groupdocs.watermark.contents/pdfpage)` के सभी एनोटेशन का संग्रह प्राप्त करता है।


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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### addAnnotationWatermark(Watermark watermark, boolean isPrintOnly) {#addAnnotationWatermark-com.groupdocs.watermark.Watermark-boolean-}
```
public final void addAnnotationWatermark(Watermark watermark, boolean isPrintOnly)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| isPrintOnly | boolean |  |

### rasterize(int horizontalResolution, int verticalResolution, int imageFormat) {#rasterize-int-int-int-}
```
public void rasterize(int horizontalResolution, int verticalResolution, int imageFormat)
```


पृष्ठ सामग्री को एक छवि में परिवर्तित करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | horizontalResolution | int | क्षैतिज छवि रिज़ॉल्यूशन। |
|
|  | verticalResolution | int | ऊर्ध्वाधर छवि रिज़ॉल्यूशन। |
|
|  | imageFormat | int | छवि प्रारूप। |
|

### addArtifactToCollection(Artifact artifact) {#addArtifactToCollection-com.aspose.pdf.Artifact-}
```
public final void addArtifactToCollection(Artifact artifact)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| कलाकृति | com.aspose.pdf.Artifact |  |

### addAnnotationToCollection(Annotation annotation) {#addAnnotationToCollection-com.aspose.pdf.Annotation-}
```
public final void addAnnotationToCollection(Annotation annotation)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| एनोटेशन | com.aspose.pdf.Annotation |  |

