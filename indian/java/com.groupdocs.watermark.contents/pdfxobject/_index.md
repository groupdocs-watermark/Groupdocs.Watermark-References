---
title: "PdfXObject"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "pdf दस्तावेज़ में एक XObject का प्रतिनिधित्व करता है।"
type: docs
weight: 75
url: /hi/java/com.groupdocs.watermark.contents/pdfxobject/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public abstract class PdfXObject extends PdfShape
```

pdf दस्तावेज़ में एक XObject का प्रतिनिधित्व करता है।

**Learn more:**

* [Working with XObjects](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-WorkingwithXObjects)

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getPage()](#getPage--) | इस `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` की पैरेंट पेज प्राप्त करता है। |
|
|  | [getX()](#getX--) | इस `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` का पृष्ठ के बाएँ किनारे से क्षैतिज ऑफ़सेट पॉइंट्स में प्राप्त करता है। |
|
|  | [getY()](#getY--) | इस `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` का पृष्ठ के निचले किनारे से ऊर्ध्वाधर ऑफ़सेट पॉइंट्स में प्राप्त करता है। |
|
|  | [getWidth()](#getWidth--) | इस `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` की चौड़ाई पॉइंट्स में प्राप्त करता है। |
|
|  | [getHeight()](#getHeight--) | इस `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` की ऊँचाई पॉइंट्स में प्राप्त करता है। |
|
|  | [getRotateAngle()](#getRotateAngle--) | इस `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` का घूर्णन कोण डिग्री में प्राप्त करता है। |
|
|  | [getMatrix()](#getMatrix--) | <br /> |

|
### getPage() {#getPage--}
```
public final PdfPage getPage()
```


इस `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` की पैरेंट पेज प्राप्त करता है।


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)`.

### getX() {#getX--}
```
public double getX()
```


इस `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` का पृष्ठ के बाएँ किनारे से क्षैतिज ऑफ़सेट पॉइंट्स में प्राप्त करता है।


**Returns:**
double - इस `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` का x-निर्देशांक।

### getY() {#getY--}
```
public double getY()
```


इस `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` का पृष्ठ के निचले किनारे से ऊर्ध्वाधर ऑफ़सेट पॉइंट्स में प्राप्त करता है।


**Returns:**
double - इस `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` का y-निर्देशांक।

### getWidth() {#getWidth--}
```
public double getWidth()
```


इस `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` की चौड़ाई पॉइंट्स में प्राप्त करता है।


**Returns:**
double - इस `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` की चौड़ाई पॉइंट्स में।

### getHeight() {#getHeight--}
```
public double getHeight()
```


इस `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` की ऊँचाई पॉइंट्स में प्राप्त करता है।


**Returns:**
double - इस `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` की ऊँचाई पॉइंट्स में।

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


इस `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` का घूर्णन कोण डिग्री में प्राप्त करता है।


**Returns:**
double - इस `[PdfXObject](../../com.groupdocs.watermark.contents/pdfxobject)` का घूर्णन कोण डिग्री में।

### getMatrix() {#getMatrix--}
```
public final Matrix getMatrix()
```


<br />



**Returns:**
com.aspose.pdf.Matrix
