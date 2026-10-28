---
title: "PresentationShape"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "PowerPoint दस्तावेज़ में एक ड्राइंग आकार का प्रतिनिधित्व करता है।"
type: docs
weight: 93
url: /hi/java/com.groupdocs.watermark.contents/presentationshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public class PresentationShape extends PresentationBaseShape implements IRotatableTwoDObject
```

PowerPoint दस्तावेज़ में एक ड्राइंग आकार का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getRotateAngle()](#getRotateAngle--) | इस `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` का घुमाव कोण डिग्री में प्राप्त करता है। |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | इस `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` का घुमाव कोण डिग्री में सेट करता है। |
|
|  | [getText()](#getText--) | इस `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` का पाठ प्राप्त करता है। |
|
|  | [setText(String value)](#setText-java.lang.String-) | इस `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` का पाठ सेट करता है। |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | इस `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` के स्वरूपित पाठ अंशों का संग्रह प्राप्त करता है। |
|
|  | [getShapeType()](#getShapeType--) | आकार ज्यामिति प्रीसेट प्रकार प्राप्त करता है। |
|
|  | [getImage()](#getImage--) | इस `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` की छवि प्राप्त करता है। |
|
|  | [setImage(PresentationWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-) | इस `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` की छवि सेट करता है। |
|
|  | [getImageForSearch()](#getImageForSearch--) | <br /> |

|
|  | [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) | <br /> |

|
|  | [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) | <br /> |

|
|  | [getTextForSearch()](#getTextForSearch--) | <br /> |

|
|  | [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) | <br /> |

|
### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


इस `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` का घुमाव कोण डिग्री में प्राप्त करता है।


**Returns:**
double - इस `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` का घुमाव कोण डिग्री में।

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


इस `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` का घुमाव कोण डिग्री में सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | double | इस `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` का घुमाव कोण डिग्री में। |
|

### getText() {#getText--}
```
public final String getText()
```


इस `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` का पाठ प्राप्त करता है।


**Returns:**
java.lang.String - इस `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` का पाठ।

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


इस `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` का पाठ सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | java.lang.String | इस `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` का पाठ। |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


इस `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` के स्वरूपित पाठ अंशों का संग्रह प्राप्त करता है।


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


आकार ज्यामिति प्रीसेट प्रकार प्राप्त करता है।


**Returns:**
int - ज्यामिति प्रीसेट प्रकार।

### getImage() {#getImage--}
```
public final PresentationWatermarkableImage getImage()
```


इस `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` की छवि प्राप्त करता है।


**Returns:**
[PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) - The image of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` or null if the shape has no image.

### setImage(PresentationWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-}
```
public final void setImage(PresentationWatermarkableImage value)
```


इस `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` की छवि सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) | इस `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` की छवि या null यदि छवि को हटाना चाहिए। |
|

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

### getFormattedTextFragmentsForSearch() {#getFormattedTextFragmentsForSearch--}
```
public FormattedTextFragmentCollection getFormattedTextFragmentsForSearch()
```


<br />



**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
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

