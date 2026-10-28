---
title: "PdfAnnotation"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "PDF दस्तावेज़ में एक एनोटेशन का प्रतिनिधित्व करता है।"
type: docs
weight: 51
url: /hi/java/com.groupdocs.watermark.contents/pdfannotation/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public class PdfAnnotation extends PdfShape
```

PDF दस्तावेज़ में एक एनोटेशन का प्रतिनिधित्व करता है।

**Learn more:**

* [Working with annotations](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-Workingwithannotations)

## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
|  | [NormalAppearanceKey](#NormalAppearanceKey) | <br /> |

|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getPage()](#getPage--) | इस `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` की पैरेंट पेज प्राप्त करता है। |
|
|  | [getAnnotationType()](#getAnnotationType--) | इस `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` का प्रकार प्राप्त करता है। |
|
|  | [getX()](#getX--) | इस `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` का क्षैतिज ऑफ़सेट पेज के बाएँ किनारे से पॉइंट्स में प्राप्त करता है। |
|
|  | [getY()](#getY--) | इस `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` का लंबवत ऑफ़सेट कार्यपत्र के नीचे किनारे से पॉइंट्स में प्राप्त करता है। |
|
|  | [getRotateAngle()](#getRotateAngle--) | इस `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` का घुमाव कोण डिग्री में प्राप्त करता है। |
|
|  | [getWidth()](#getWidth--) | इस `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` की चौड़ाई पॉइंट्स में प्राप्त करता है। |
|
|  | [getHeight()](#getHeight--) | इस `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` की ऊँचाई पॉइंट्स में प्राप्त करता है। |
|
|  | [getAsposePdfAnnotation()](#getAsposePdfAnnotation--) | <br /> |

|
|  | [getOuterForm()](#getOuterForm--) | <br /> |

|
### NormalAppearanceKey {#NormalAppearanceKey}
```
public static final String NormalAppearanceKey
```


<br />



### getPage() {#getPage--}
```
public final PdfPage getPage()
```


इस `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` की पैरेंट पेज प्राप्त करता है।


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)`.

### getAnnotationType() {#getAnnotationType--}
```
public final int getAnnotationType()
```


इस `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` का प्रकार प्राप्त करता है।


**Returns:**
int - इस `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` का प्रकार।

### getX() {#getX--}
```
public double getX()
```


इस `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` का क्षैतिज ऑफ़सेट पेज के बाएँ किनारे से पॉइंट्स में प्राप्त करता है।


**Returns:**
double - इस `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` का पेज के बाएँ किनारे से पॉइंट्स में क्षैतिज ऑफ़सेट।

### getY() {#getY--}
```
public double getY()
```


इस `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` का लंबवत ऑफ़सेट कार्यपत्र के नीचे किनारे से पॉइंट्स में प्राप्त करता है।


**Returns:**
double - इस `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` का कार्यपत्र के नीचे किनारे से पॉइंट्स में लंबवत ऑफ़सेट।

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


इस `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` का घुमाव कोण डिग्री में प्राप्त करता है।


**Returns:**
double - इस `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` का डिग्री में घुमाव कोण।

### getWidth() {#getWidth--}
```
public double getWidth()
```


इस `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` की चौड़ाई पॉइंट्स में प्राप्त करता है।


**Returns:**
double - इस `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` की पॉइंट्स में चौड़ाई।

### getHeight() {#getHeight--}
```
public double getHeight()
```


इस `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` की ऊँचाई पॉइंट्स में प्राप्त करता है।


**Returns:**
double - इस `[PdfAnnotation](../../com.groupdocs.watermark.contents/pdfannotation)` की पॉइंट्स में ऊँचाई।

### getAsposePdfAnnotation() {#getAsposePdfAnnotation--}
```
public final Annotation getAsposePdfAnnotation()
```


<br />



**Returns:**
com.aspose.pdf.Annotation
### getOuterForm() {#getOuterForm--}
```
public XForm getOuterForm()
```


<br />



**Returns:**
com.aspose.pdf.XForm
