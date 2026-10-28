---
title: "DiagramShape"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "Visio दस्तावेज़ में एक ड्राइंग आकार का प्रतिनिधित्व करता है।"
type: docs
weight: 24
url: /hi/java/com.groupdocs.watermark.contents/diagramshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public class DiagramShape extends ShapeSearchAdapter implements IRotatableTwoDObject
```

Visio दस्तावेज़ में एक ड्राइंग आकार का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
|  | [getPage()](#getPage--) | इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` का पैरेंट पेज प्राप्त करता है। |
|
|  | [getWidth()](#getWidth--) | इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` की चौड़ाई पॉइंट्स में प्राप्त करता है। |
|
|  | [setWidth(double value)](#setWidth-double-) | इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` की चौड़ाई पॉइंट्स में सेट करता है। |
|
|  | [getHeight()](#getHeight--) | इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` की ऊँचाई पॉइंट्स में प्राप्त करता है। |
|
|  | [setHeight(double value)](#setHeight-double-) | इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` की ऊँचाई पॉइंट्स में सेट करता है। |
|
|  | [getX()](#getX--) | इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` का पेज के बाएँ किनारे से क्षैतिज ऑफ़सेट पॉइंट्स में प्राप्त करता है। |
|
|  | [setX(double value)](#setX-double-) | इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` का पेज के बाएँ किनारे से क्षैतिज ऑफ़सेट पॉइंट्स में सेट करता है। |
|
|  | [getY()](#getY--) | इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` का पेज के नीचे किनारे से लंबवत ऑफ़सेट पॉइंट्स में प्राप्त करता है। |
|
|  | [setY(double value)](#setY-double-) | इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` का पेज के नीचे किनारे से लंबवत ऑफ़सेट पॉइंट्स में सेट करता है। |
|
|  | [getRotateAngle()](#getRotateAngle--) | इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` का घूर्णन कोण डिग्री में प्राप्त या सेट करता है। |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` का घूर्णन कोण डिग्री में प्राप्त या सेट करता है। |
|
|  | [getText()](#getText--) | इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` का टेक्स्ट प्राप्त या सेट करता है। |
|
|  | [setText(String value)](#setText-java.lang.String-) | इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` का टेक्स्ट प्राप्त या सेट करता है। |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` के स्वरूपित टेक्स्ट फ्रैगमेंट्स का संग्रह प्राप्त करता है। |
|
|  | [getImage()](#getImage--) | इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` की इमेज प्राप्त करता है। |
|
|  | [setImage(DiagramWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.DiagramWatermarkableImage-) | इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` की इमेज सेट करता है। |
|
|  | [getId()](#getId--) | इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` की पहचानकर्ता प्राप्त करता है। |
|
|  | [getName()](#getName--) | इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` का नाम प्राप्त करता है। |
|
|  | [getHyperlinks()](#getHyperlinks--) | इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` से जुड़े हाइपरलिंक का संग्रह प्राप्त करता है। |
|
|  | [getAsposeShape()](#getAsposeShape--) | <br /> |

|
|  | [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) | <br /> |

|
|  | [getImageForSearch()](#getImageForSearch--) | <br /> |

|
|  | [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) | <br /> |

|
|  | [getTextForSearch()](#getTextForSearch--) | <br /> |

|
|  | [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) | <br /> |

|
### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```




**Returns:**
java.lang.Integer
### getPage() {#getPage--}
```
public final DiagramPage getPage()
```


इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` का पैरेंट पेज प्राप्त करता है।


**Returns:**
[DiagramPage](../../com.groupdocs.watermark.contents/diagrampage) - The parent page of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getWidth() {#getWidth--}
```
public final double getWidth()
```


इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` की चौड़ाई पॉइंट्स में प्राप्त करता है।


**Returns:**
double - इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` की चौड़ाई पॉइंट्स में।

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` की चौड़ाई पॉइंट्स में सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | double | इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` की चौड़ाई पॉइंट्स में। |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` की ऊँचाई पॉइंट्स में प्राप्त करता है।


**Returns:**
double - इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` की ऊँचाई पॉइंट्स में।

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` की ऊँचाई पॉइंट्स में सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | double | इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` की ऊँचाई पॉइंट्स में। |
|

### getX() {#getX--}
```
public final double getX()
```


इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` का पेज के बाएँ किनारे से क्षैतिज ऑफ़सेट पॉइंट्स में प्राप्त करता है।


**Returns:**
double - इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` का पेज के बाएँ किनारे से क्षैतिज ऑफ़सेट पॉइंट्स में।

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` का पेज के बाएँ किनारे से क्षैतिज ऑफ़सेट पॉइंट्स में सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | double | इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` का पेज के बाएँ किनारे से क्षैतिज ऑफ़सेट पॉइंट्स में। |
|

### getY() {#getY--}
```
public final double getY()
```


इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` का पेज के नीचे किनारे से लंबवत ऑफ़सेट पॉइंट्स में प्राप्त करता है।


**Returns:**
double - इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` का पेज के नीचे किनारे से लंबवत ऑफ़सेट पॉइंट्स में।

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` का पेज के नीचे किनारे से लंबवत ऑफ़सेट पॉइंट्स में सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | double | इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` का पेज के नीचे किनारे से लंबवत ऑफ़सेट पॉइंट्स में। |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` का घूर्णन कोण डिग्री में प्राप्त या सेट करता है।


**Returns:**
double - इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` का घुमाव कोण डिग्री में।

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` का घूर्णन कोण डिग्री में प्राप्त या सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | double | इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` का घुमाव कोण डिग्री में। |
|

### getText() {#getText--}
```
public final String getText()
```


इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` का टेक्स्ट प्राप्त या सेट करता है।


**Returns:**
java.lang.String - इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` का पाठ।

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` का टेक्स्ट प्राप्त या सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | java.lang.String | इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` का पाठ। |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` के स्वरूपित टेक्स्ट फ्रैगमेंट्स का संग्रह प्राप्त करता है।


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getImage() {#getImage--}
```
public final DiagramWatermarkableImage getImage()
```


इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` की इमेज प्राप्त करता है।


**Returns:**
[DiagramWatermarkableImage](../../com.groupdocs.watermark.contents/diagramwatermarkableimage) - The image of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### setImage(DiagramWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.DiagramWatermarkableImage-}
```
public final void setImage(DiagramWatermarkableImage value)
```


इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` की इमेज सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [DiagramWatermarkableImage](../../com.groupdocs.watermark.contents/diagramwatermarkableimage) | इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` की छवि। |
|

### getId() {#getId--}
```
public final long getId()
```


इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` की पहचानकर्ता प्राप्त करता है।


**Returns:**
long - इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` की पहचानकर्ता।

### getName() {#getName--}
```
public final String getName()
```


इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` का नाम प्राप्त करता है।


**Returns:**
java.lang.String - इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` का नाम।

### getHyperlinks() {#getHyperlinks--}
```
public final DiagramHyperlinkCollection getHyperlinks()
```


इस `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` से जुड़े हाइपरलिंक का संग्रह प्राप्त करता है।


**Returns:**
[DiagramHyperlinkCollection](../../com.groupdocs.watermark.contents/diagramhyperlinkcollection) - The collection of hyperlinks attached to this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getAsposeShape() {#getAsposeShape--}
```
public final Shape getAsposeShape()
```


<br />



**Returns:**
com.aspose.diagram.Shape
### getFormattedTextFragmentsForSearch() {#getFormattedTextFragmentsForSearch--}
```
public FormattedTextFragmentCollection getFormattedTextFragmentsForSearch()
```


<br />



**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
### getImageForSearch() {#getImageForSearch--}
```
public WatermarkableImage getImageForSearch()
```


<br />



**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### setFoundWatermarkImage(byte[] imageData) {#setFoundWatermarkImage-byte---}
```
public void setFoundWatermarkImage(byte[] imageData)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| imageData | byte[] |  |

### getTextForSearch() {#getTextForSearch--}
```
public String getTextForSearch()
```


<br />



**Returns:**
java.lang.String
### setFoundWatermarkText(String value) {#setFoundWatermarkText-java.lang.String-}
```
public void setFoundWatermarkText(String value)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

