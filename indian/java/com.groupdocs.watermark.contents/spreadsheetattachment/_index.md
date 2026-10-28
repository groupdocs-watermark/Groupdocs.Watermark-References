---
title: "SpreadsheetAttachment"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "Excel दस्तावेज़ से जुड़ी फ़ाइल का प्रतिनिधित्व करता है।"
type: docs
weight: 101
url: /hi/java/com.groupdocs.watermark.contents/spreadsheetattachment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.ITwoDObject](../../com.groupdocs.watermark.search/itwodobject)
```
public class SpreadsheetAttachment extends Attachment implements ITwoDObject
```

Excel दस्तावेज़ से जुड़ी फ़ाइल का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getContent()](#getContent--) | संलग्न फ़ाइल की सामग्री प्राप्त करता है। |
|
|  | [setContent(byte[] value)](#setContent-byte---) | संलग्न फ़ाइल की सामग्री सेट करता है। |
|
|  | [getPreviewImageContent()](#getPreviewImageContent--) | संलग्न फ़ाइल पूर्वावलोकन छवि को बाइट ऐरे के रूप में प्राप्त करता है। |
|
|  | [setPreviewImageContent(byte[] value)](#setPreviewImageContent-byte---) | संलग्न फ़ाइल पूर्वावलोकन छवि को बाइट ऐरे के रूप में सेट करता है। |
|
|  | [isLink()](#isLink--) | एक मान प्राप्त करता है जो दर्शाता है कि सामग्री में केवल फ़ाइल का लिंक ही है या नहीं। |
|
|  | [getSourceFullName()](#getSourceFullName--) | संलग्न फ़ाइल का पूर्ण नाम प्राप्त करता है। |
|
|  | [getAlternativeText()](#getAlternativeText--) | संलग्न फ़ाइल से संबंधित वर्णनात्मक (वैकल्पिक) पाठ प्राप्त करता है। |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | संलग्न फ़ाइल से संबंधित वर्णनात्मक (वैकल्पिक) पाठ सेट करता है। |
|
|  | [getAsposeOleObject()](#getAsposeOleObject--) | <br /> |

|
|  | [getX()](#getX--) | वर्कशीट के बाएँ किनारे से बिंदुओं में अटैचमेंट फ्रेम का क्षैतिज ऑफ़सेट प्राप्त करता है। |
|
|  | [setX(double value)](#setX-double-) | वर्कशीट के बाएँ किनारे से बिंदुओं में अटैचमेंट फ्रेम का क्षैतिज ऑफ़सेट सेट करता है। |
|
|  | [getY()](#getY--) | वर्कशीट के शीर्ष किनारे से बिंदुओं में अटैचमेंट फ्रेम का लंबवत ऑफ़सेट प्राप्त करता है। |
|
|  | [setY(double value)](#setY-double-) | वर्कशीट के शीर्ष किनारे से बिंदुओं में अटैचमेंट फ्रेम का लंबवत ऑफ़सेट सेट करता है। |
|
|  | [getWidth()](#getWidth--) | बिंदुओं में अटैचमेंट फ्रेम की चौड़ाई प्राप्त करता है। |
|
|  | [setWidth(double value)](#setWidth-double-) | बिंदुओं में अटैचमेंट फ्रेम की चौड़ाई सेट करता है। |
|
|  | [getHeight()](#getHeight--) | बिंदुओं में अटैचमेंट फ्रेम की ऊँचाई प्राप्त करता है। |
|
|  | [setHeight(double value)](#setHeight-double-) | बिंदुओं में अटैचमेंट फ्रेम की ऊँचाई सेट करता है। |
|
|  | [checkImageType()](#checkImageType--) | <br /> |

|
### getContent() {#getContent--}
```
public byte[] getContent()
```


संलग्न फ़ाइल की सामग्री प्राप्त करता है।


**Returns:**
byte[] - संलग्न फ़ाइल की सामग्री।

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


संलग्न फ़ाइल की सामग्री सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | byte[] | संलग्न फ़ाइल की सामग्री। |
|

### getPreviewImageContent() {#getPreviewImageContent--}
```
public final byte[] getPreviewImageContent()
```


संलग्न फ़ाइल पूर्वावलोकन छवि को बाइट ऐरे के रूप में प्राप्त करता है।


**Returns:**
byte[] - संलग्न फ़ाइल पूर्वावलोकन छवि को बाइट ऐरे के रूप में।

### setPreviewImageContent(byte[] value) {#setPreviewImageContent-byte---}
```
public final void setPreviewImageContent(byte[] value)
```


संलग्न फ़ाइल पूर्वावलोकन छवि को बाइट ऐरे के रूप में सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | byte[] | संलग्न फ़ाइल पूर्वावलोकन छवि को बाइट ऐरे के रूप में। |
|

### isLink() {#isLink--}
```
public final boolean isLink()
```


एक मान प्राप्त करता है जो दर्शाता है कि सामग्री में केवल फ़ाइल का लिंक ही है या नहीं।


**Returns:**
boolean - सत्य यदि संलग्न फ़ाइल लिंक द्वारा संदर्भित है (सामग्री में संलग्न फ़ाइल सामग्री नहीं है); अन्यथा, असत्य।

### getSourceFullName() {#getSourceFullName--}
```
public final String getSourceFullName()
```


संलग्न फ़ाइल का पूर्ण नाम प्राप्त करता है।


**Returns:**
java.lang.String - संलग्न फ़ाइल का पूर्ण नाम।

<br />

*** ** * ** ***

फ़ाइल खोलने के लिए उपयुक्त अनुप्रयोग निर्धारित करने हेतु एक्सटेंशन का उपयोग किया जाता है।

<br />


### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


संलग्न फ़ाइल से संबंधित वर्णनात्मक (वैकल्पिक) पाठ प्राप्त करता है।


**Returns:**
java.lang.String - संलग्न फ़ाइल से संबंधित वर्णनात्मक (वैकल्पिक) पाठ।

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


संलग्न फ़ाइल से संबंधित वर्णनात्मक (वैकल्पिक) पाठ सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | संलग्न फ़ाइल से संबंधित वर्णनात्मक (वैकल्पिक) पाठ। |
|

### getAsposeOleObject() {#getAsposeOleObject--}
```
public final OleObject getAsposeOleObject()
```


<br />



**Returns:**
com.aspose.cells.OleObject
### getX() {#getX--}
```
public final double getX()
```


वर्कशीट के बाएँ किनारे से बिंदुओं में अटैचमेंट फ्रेम का क्षैतिज ऑफ़सेट प्राप्त करता है।


**Returns:**
double - अटैचमेंट फ्रेम का x-निर्देशांक।

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


वर्कशीट के बाएँ किनारे से बिंदुओं में अटैचमेंट फ्रेम का क्षैतिज ऑफ़सेट सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | double | अटैचमेंट फ्रेम का x-निर्देशांक। |
|

### getY() {#getY--}
```
public final double getY()
```


वर्कशीट के शीर्ष किनारे से बिंदुओं में अटैचमेंट फ्रेम का लंबवत ऑफ़सेट प्राप्त करता है।


**Returns:**
double - अटैचमेंट फ्रेम का y-निर्देशांक।

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


वर्कशीट के शीर्ष किनारे से बिंदुओं में अटैचमेंट फ्रेम का लंबवत ऑफ़सेट सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | double | संलग्न फ्रेम का y-निर्देशांक। |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


बिंदुओं में अटैचमेंट फ्रेम की चौड़ाई प्राप्त करता है।


**Returns:**
double - संलग्न फ्रेम की चौड़ाई पॉइंट्स में।

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


बिंदुओं में अटैचमेंट फ्रेम की चौड़ाई सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | double | संलग्न फ्रेम की चौड़ाई पॉइंट्स में। |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


बिंदुओं में अटैचमेंट फ्रेम की ऊँचाई प्राप्त करता है।


**Returns:**
double - संलग्न फ्रेम की ऊँचाई पॉइंट्स में।

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


बिंदुओं में अटैचमेंट फ्रेम की ऊँचाई सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | double | संलग्न फ्रेम की ऊँचाई पॉइंट्स में। |
|

### checkImageType() {#checkImageType--}
```
public final void checkImageType()
```


<br />



