---
title: "PdfArtifact"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "PDF सामग्री में एक आर्टिफैक्ट का प्रतिनिधित्व करता है।"
type: docs
weight: 54
url: /hi/java/com.groupdocs.watermark.contents/pdfartifact/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PdfShape](../../com.groupdocs.watermark.contents/pdfshape)
```
public class PdfArtifact extends PdfShape
```

PDF सामग्री में एक आर्टिफैक्ट का प्रतिनिधित्व करता है।

**Lean more**

* [Working with artifacts](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document#ExistingobjectsinPDFdocument-Workingwithartifacts)

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getPage()](#getPage--) | इस `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` की पैरेंट पेज प्राप्त करता है। |
|
|  | [getText()](#getText--) | इस `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` का टेक्स्ट प्राप्त करता है। |
|
|  | [setText(String value)](#setText-java.lang.String-) | इस `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` का टेक्स्ट सेट करता है। |
|
|  | [getArtifactType()](#getArtifactType--) | इस `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` का टाइप प्राप्त करता है। |
|
|  | [getArtifactSubtype()](#getArtifactSubtype--) | इस `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` का सबटाइप प्राप्त करता है। |
|
|  | [getOpacity()](#getOpacity--) | इस `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` की अपारदर्शिता प्राप्त करता है। |
|
|  | [getX()](#getX--) | इस `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` का पेज बाएँ किनारे से क्षैतिज ऑफसेट पॉइंट्स में प्राप्त करता है। |
|
|  | [getY()](#getY--) | इस `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` का पेज नीचे किनारे से ऊर्ध्वाधर ऑफसेट पॉइंट्स में प्राप्त करता है। |
|
|  | [getRotateAngle()](#getRotateAngle--) | इस `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` का घूर्णन कोण डिग्री में प्राप्त करता है। |
|
|  | [getWidth()](#getWidth--) | इस `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` की चौड़ाई पॉइंट्स में प्राप्त करता है। |
|
|  | [getHeight()](#getHeight--) | इस `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` की ऊँचाई पॉइंट्स में प्राप्त करता है। |
|
|  | [getAsposePdfArtifact()](#getAsposePdfArtifact--) | <br /> |

|
|  | [getOuterForm()](#getOuterForm--) | <br /> |

|
### getPage() {#getPage--}
```
public final PdfPage getPage()
```


इस `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` की पैरेंट पेज प्राप्त करता है।


**Returns:**
[PdfPage](../../com.groupdocs.watermark.contents/pdfpage) - The parent page of this `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)`.

### getText() {#getText--}
```
public String getText()
```


इस `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` का टेक्स्ट प्राप्त करता है।


**Returns:**
java.lang.String - इस `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` का टेक्स्ट।

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


इस `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` का टेक्स्ट सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | java.lang.String | इस `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` का टेक्स्ट। |
|

### getArtifactType() {#getArtifactType--}
```
public final int getArtifactType()
```


इस `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` का टाइप प्राप्त करता है।


**Returns:**
int - इस `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` का टाइप।

### getArtifactSubtype() {#getArtifactSubtype--}
```
public final int getArtifactSubtype()
```


इस `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` का सबटाइप प्राप्त करता है।


**Returns:**
int - इस `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` का सबटाइप।

### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


इस `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` की अपारदर्शिता प्राप्त करता है।

संभव मान रेंज [0, 1] में हैं।


**Returns:**
double - इस `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` की अपारदर्शिता।

### getX() {#getX--}
```
public double getX()
```


इस `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` का पेज बाएँ किनारे से क्षैतिज ऑफसेट पॉइंट्स में प्राप्त करता है।


**Returns:**
double - इस `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` का x-कोऑर्डिनेट।

### getY() {#getY--}
```
public double getY()
```


इस `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` का पेज नीचे किनारे से ऊर्ध्वाधर ऑफसेट पॉइंट्स में प्राप्त करता है।


**Returns:**
double - इस `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` का y-कोऑर्डिनेट।

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


इस `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` का घूर्णन कोण डिग्री में प्राप्त करता है।


**Returns:**
double - इस `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` का घूर्णन कोण डिग्री में।

### getWidth() {#getWidth--}
```
public double getWidth()
```


इस `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` की चौड़ाई पॉइंट्स में प्राप्त करता है।


**Returns:**
double - इस `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` की चौड़ाई पॉइंट्स में।

### getHeight() {#getHeight--}
```
public double getHeight()
```


इस `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` की ऊँचाई पॉइंट्स में प्राप्त करता है।


**Returns:**
double - इस `[PdfArtifact](../../com.groupdocs.watermark.contents/pdfartifact)` की ऊँचाई पॉइंट्स में।

### getAsposePdfArtifact() {#getAsposePdfArtifact--}
```
public final Artifact getAsposePdfArtifact()
```


<br />



**Returns:**
com.aspose.pdf.Artifact
### getOuterForm() {#getOuterForm--}
```
public XForm getOuterForm()
```


<br />



**Returns:**
com.aspose.pdf.XForm
