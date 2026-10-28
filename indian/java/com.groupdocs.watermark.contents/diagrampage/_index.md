---
title: "DiagramPage"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "Visio दस्तावेज़ पृष्ठ को दर्शाता है।"
type: docs
weight: 22
url: /hi/java/com.groupdocs.watermark.contents/diagrampage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public class DiagramPage extends ContentPart
```

Visio दस्तावेज़ पृष्ठ को दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
|  | [getShapes()](#getShapes--) | पृष्ठ की सभी आकृतियों का संग्रह प्राप्त करता है। |
|
|  | [isBackground()](#isBackground--) | पृष्ठ एक पृष्ठभूमि पृष्ठ है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
|
|  | [getBackgroundPage()](#getBackgroundPage--) | इसका पृष्ठभूमि पृष्ठ प्राप्त करता है। |
|
|  | [getWidth()](#getWidth--) | इसकी चौड़ाई बिंदुओं में प्राप्त करता है। |
|
|  | [getHeight()](#getHeight--) | इसकी ऊँचाई बिंदुओं में प्राप्त करता है। |
|
|  | [getTopMargin()](#getTopMargin--) | ऊपर के मार्जिन का आकार पॉइंट्स में प्राप्त करता है। |
|
|  | [getRightMargin()](#getRightMargin--) | दाएँ मार्जिन का आकार पॉइंट्स में प्राप्त करता है। |
|
|  | [getBottomMargin()](#getBottomMargin--) | नीचे के मार्जिन का आकार पॉइंट्स में प्राप्त करता है। |
|
|  | [getLeftMargin()](#getLeftMargin--) | बाएँ मार्जिन का आकार पॉइंट्स में प्राप्त करता है। |
|
|  | [isVisible()](#isVisible--) | पृष्ठ UI में दृश्यमान है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
|
|  | [setVisible(boolean value)](#setVisible-boolean-) | पृष्ठ UI में दृश्यमान है या नहीं, यह दर्शाने वाला मान सेट करता है। |
|
|  | [getName()](#getName--) | इसका नाम प्राप्त करता है |
DiagramPage
.
|
|  | [getAsposeDiagramPage()](#getAsposeDiagramPage--) | <br /> |

|
|  | [getContent()](#getContent--) | <br /> |

|
|  | [getPageToDrawingScale()](#getPageToDrawingScale--) | <br /> |

|
|  | [addWatermark(Watermark watermark, DiagramShapeSettings shapeSettings)](#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.internal.DiagramShapeSettings-) | <br /> |

|
|  | [convertValueFromDrawingScaleToPageScale(DoubleValue value)](#convertValueFromDrawingScaleToPageScale-com.aspose.diagram.DoubleValue-) | <br /> |

|
### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```




**Returns:**
java.lang.Integer
### getShapes() {#getShapes--}
```
public final DiagramShapeCollection getShapes()
```


पृष्ठ की सभी आकृतियों का संग्रह प्राप्त करता है।


**Returns:**
[DiagramShapeCollection](../../com.groupdocs.watermark.contents/diagramshapecollection) - The collection of all shapes of the page.

### isBackground() {#isBackground--}
```
public final boolean isBackground()
```


पृष्ठ एक पृष्ठभूमि पृष्ठ है या नहीं, यह दर्शाने वाला मान प्राप्त करता है।


**Returns:**
बूलियन - यदि पृष्ठ पृष्ठभूमि पृष्ठ है तो सत्य; अन्यथा असत्य।

### getBackgroundPage() {#getBackgroundPage--}
```
public final DiagramPage getBackgroundPage()
```


इसका पृष्ठभूमि पृष्ठ प्राप्त करता है।


**Returns:**
[DiagramPage](../../com.groupdocs.watermark.contents/diagrampage) - The background page for this .

### getWidth() {#getWidth--}
```
public final double getWidth()
```


इसकी चौड़ाई बिंदुओं में प्राप्त करता है।


**Returns:**
डबल - इसकी चौड़ाई बिंदुओं में।

### getHeight() {#getHeight--}
```
public final double getHeight()
```


इसकी ऊँचाई बिंदुओं में प्राप्त करता है।


**Returns:**
डबल - इसकी ऊँचाई बिंदुओं में।

### getTopMargin() {#getTopMargin--}
```
public final double getTopMargin()
```


ऊपर के मार्जिन का आकार पॉइंट्स में प्राप्त करता है।


**Returns:**
double - ऊपर के मार्जिन का आकार पॉइंट्स में।

### getRightMargin() {#getRightMargin--}
```
public final double getRightMargin()
```


दाएँ मार्जिन का आकार पॉइंट्स में प्राप्त करता है।


**Returns:**
double - दाएँ मार्जिन का आकार पॉइंट्स में।

### getBottomMargin() {#getBottomMargin--}
```
public final double getBottomMargin()
```


नीचे के मार्जिन का आकार पॉइंट्स में प्राप्त करता है।


**Returns:**
double - नीचे के मार्जिन का आकार पॉइंट्स में।

### getLeftMargin() {#getLeftMargin--}
```
public final double getLeftMargin()
```


बाएँ मार्जिन का आकार पॉइंट्स में प्राप्त करता है।


**Returns:**
double - बाएँ मार्जिन का आकार पॉइंट्स में।

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


पृष्ठ UI में दृश्यमान है या नहीं, यह दर्शाने वाला मान प्राप्त करता है।


**Returns:**
बूलियन - पृष्ठ UI में दृश्यमान है या नहीं दर्शाने वाला मान। यदि पृष्ठ दृश्यमान है तो सत्य; अन्यथा असत्य।

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


पृष्ठ UI में दृश्यमान है या नहीं, यह दर्शाने वाला मान सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | पृष्ठ UI में दृश्यमान है या नहीं दर्शाने वाला मान। यदि पृष्ठ दृश्यमान है तो सत्य; अन्यथा असत्य। |
|

### getName() {#getName--}
```
public final String getName()
```


इसका नाम प्राप्त करता है
DiagramPage
.


**Returns:**
java.lang.String - इस  DiagramPage  का नाम।

### getAsposeDiagramPage() {#getAsposeDiagramPage--}
```
public final Page getAsposeDiagramPage()
```


<br />



**Returns:**
com.aspose.diagram.Page
### getContent() {#getContent--}
```
public final DiagramContent getContent()
```


<br />



**Returns:**
[DiagramContent](../../com.groupdocs.watermark.contents/diagramcontent)
### getPageToDrawingScale() {#getPageToDrawingScale--}
```
public final double getPageToDrawingScale()
```


<br />



**Returns:**
double
### addWatermark(Watermark watermark, DiagramShapeSettings shapeSettings) {#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.internal.DiagramShapeSettings-}
```
public final void addWatermark(Watermark watermark, DiagramShapeSettings shapeSettings)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [DiagramShapeSettings](../../com.groupdocs.watermark.internal/diagramshapesettings) |  |

### convertValueFromDrawingScaleToPageScale(DoubleValue value) {#convertValueFromDrawingScaleToPageScale-com.aspose.diagram.DoubleValue-}
```
public final double convertValueFromDrawingScaleToPageScale(DoubleValue value)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | com.aspose.diagram.DoubleValue |  |

**Returns:**
double
