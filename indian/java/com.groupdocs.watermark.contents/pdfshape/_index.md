---
title: "PdfShape"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "XObjects आर्टिफैक्ट्स और एनोटेशन्स के लिए बेस क्लास प्रदान करता है।"
type: docs
weight: 69
url: /hi/java/com.groupdocs.watermark.contents/pdfshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public abstract class PdfShape extends ShapeSearchAdapter implements IRotatableTwoDObject
```

XObjects, Artifacts और Annotations के लिए बेस क्लास प्रदान करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getText()](#getText--) | इस `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` का टेक्स्ट प्राप्त करता है। |
|
|  | [setText(String value)](#setText-java.lang.String-) | इस `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` का टेक्स्ट प्राप्त करता है या सेट करता है। |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | इस `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` के फॉर्मेटेड टेक्स्ट फ्रैगमेंट्स का संग्रह प्राप्त करता है। |
|
|  | [getImage()](#getImage--) | इस `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` की इमेज प्राप्त करता है। |
|
|  | [setImage(PdfWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.PdfWatermarkableImage-) | इस `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` की छवि सेट करता है। |
|
|  | [getX()](#getX--) | ऑब्जेक्ट का x-निर्देशांक प्राप्त करता है। |
|
|  | [getY()](#getY--) | ऑब्जेक्ट का y-निर्देशांक प्राप्त करता है। |
|
|  | [getWidth()](#getWidth--) | ऑब्जेक्ट की चौड़ाई प्राप्त करता है। |
|
|  | [getHeight()](#getHeight--) | ऑब्जेक्ट की ऊँचाई प्राप्त करता है। |
|
|  | [getRotateAngle()](#getRotateAngle--) | ऑब्जेक्ट का घूर्णन कोण डिग्री में प्राप्त करता है। |
|
|  | [getOuterForm()](#getOuterForm--) | <br /> |

|
|  | [extractImageAppearance()](#extractImageAppearance--) | <br /> |

|
|  | [getTextForSearch()](#getTextForSearch--) | <br /> |

|
|  | [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) | <br /> |

|
|  | [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) | <br /> |

|
|  | [getImageForSearch()](#getImageForSearch--) | <br /> |

|
|  | [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) | <br /> |

|
### getText() {#getText--}
```
public String getText()
```


इस `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` का टेक्स्ट प्राप्त करता है।


**Returns:**
java.lang.String - इस `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` का पाठ।

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


इस `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` का टेक्स्ट प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | java.lang.String | इस `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` का पाठ। |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


इस `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` के फॉर्मेटेड टेक्स्ट फ्रैगमेंट्स का संग्रह प्राप्त करता है।


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.

### getImage() {#getImage--}
```
public final PdfWatermarkableImage getImage()
```


इस `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` की इमेज प्राप्त करता है।


**Returns:**
[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage) - The image of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.

### setImage(PdfWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.PdfWatermarkableImage-}
```
public final void setImage(PdfWatermarkableImage value)
```


इस `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` की छवि सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage) | इस `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` की छवि। |
|

### getX() {#getX--}
```
public abstract double getX()
```


ऑब्जेक्ट का x-निर्देशांक प्राप्त करता है।


**Returns:**
double - ऑब्जेक्ट का x-निर्देशांक।

### getY() {#getY--}
```
public abstract double getY()
```


ऑब्जेक्ट का y-निर्देशांक प्राप्त करता है।


**Returns:**
double - ऑब्जेक्ट का y-निर्देशांक।

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


ऑब्जेक्ट की चौड़ाई प्राप्त करता है।


**Returns:**
double - ऑब्जेक्ट की चौड़ाई।

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


ऑब्जेक्ट की ऊँचाई प्राप्त करता है।


**Returns:**
double - ऑब्जेक्ट की ऊँचाई।

### getRotateAngle() {#getRotateAngle--}
```
public abstract double getRotateAngle()
```


ऑब्जेक्ट का घूर्णन कोण डिग्री में प्राप्त करता है।


**Returns:**
double - ऑब्जेक्ट का घूर्णन कोण डिग्री में।

### getOuterForm() {#getOuterForm--}
```
public abstract XForm getOuterForm()
```


<br />



**Returns:**
com.aspose.pdf.XForm
### extractImageAppearance() {#extractImageAppearance--}
```
public PdfXImageAppearance extractImageAppearance()
```


<br />



**Returns:**
[PdfXImageAppearance](../../com.groupdocs.watermark.internal/pdfximageappearance)
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

