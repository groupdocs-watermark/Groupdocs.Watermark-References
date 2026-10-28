---
title: "OfficeImageFillFormat"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "किसी भी समर्थित ऑफिस कंटेंट में इमेज फ़िल फ़ॉर्मेट सेटिंग्स का प्रतिनिधित्व करता है।"
type: docs
weight: 46
url: /hi/java/com.groupdocs.watermark.contents/officeimagefillformat/
---
**Inheritance:**
java.lang.Object
```
public abstract class OfficeImageFillFormat<TWatermarkableImage>
```

किसी भी समर्थित ऑफिस कंटेंट में इमेज फ़िल फ़ॉर्मेट सेटिंग्स का प्रतिनिधित्व करता है।


TWatermarkableImage
: बैकग्राउंड के रूप में उपयोग की जाने वाली वॉटरमार्क योग्य छवि का सटीक प्रकार।

## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [OfficeImageFillFormat()](#OfficeImageFillFormat--) | <br /> |

|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | एक मान प्राप्त करता है जो दर्शाता है कि क्या छवि पृष्ठभूमि में टाइल की गई है। |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | एक मान सेट करता है जो दर्शाता है कि क्या छवि पृष्ठभूमि में टाइल की गई है। |
|
|  | [getTransparency()](#getTransparency--) | बैकग्राउंड छवि की पारदर्शिता को 0.0 (अपारदर्शी) से 1.0 (पूरी तरह पारदर्शी) तक के मान के रूप में प्राप्त करता है। |
|
|  | [setTransparency(double value)](#setTransparency-double-) | बैकग्राउंड छवि की पारदर्शिता को 0.0 (अपारदर्शी) से 1.0 (पूरी तरह पारदर्शी) तक के मान के रूप में सेट करता है। |
|
|  | [getBackgroundImage()](#getBackgroundImage--) | पृष्ठभूमि छवि को प्राप्त करता है। |
|
|  | [setBackgroundImage(TWatermarkableImage value)](#setBackgroundImage-TWatermarkableImage-) | पृष्ठभूमि छवि को सेट करता है। |
|
|  | [checkIfBackgroundImageIsSet()](#checkIfBackgroundImageIsSet--) | <br /> |

|
### OfficeImageFillFormat() {#OfficeImageFillFormat--}
```
public OfficeImageFillFormat()
```


<br />



### getTileAsTexture() {#getTileAsTexture--}
```
public abstract boolean getTileAsTexture()
```


एक मान प्राप्त करता है जो दर्शाता है कि क्या छवि पृष्ठभूमि में टाइल की गई है।


**Returns:**
boolean - यदि छवि पृष्ठभूमि में टाइल की गई है तो True; अन्यथा false (छवि खिंची हुई है)।

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public abstract void setTileAsTexture(boolean value)
```


एक मान सेट करता है जो दर्शाता है कि क्या छवि पृष्ठभूमि में टाइल की गई है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | यदि छवि पृष्ठभूमि में टाइल की गई है तो True; अन्यथा false (छवि खिंची हुई है)। |
|

### getTransparency() {#getTransparency--}
```
public abstract double getTransparency()
```


बैकग्राउंड छवि की पारदर्शिता को 0.0 (अपारदर्शी) से 1.0 (पूरी तरह पारदर्शी) तक के मान के रूप में प्राप्त करता है।


**Returns:**
double - पृष्ठभूमि छवि की पारदर्शिता को 0.0 (अपारदर्शी) से 1.0 (पूर्णतः पारदर्शी) तक मान के रूप में।

### setTransparency(double value) {#setTransparency-double-}
```
public abstract void setTransparency(double value)
```


बैकग्राउंड छवि की पारदर्शिता को 0.0 (अपारदर्शी) से 1.0 (पूरी तरह पारदर्शी) तक के मान के रूप में सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | double | पृष्ठभूमि छवि की पारदर्शिता को 0.0 (अपारदर्शी) से 1.0 (पूर्णतः पारदर्शी) तक मान के रूप में। |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public abstract TWatermarkableImage getBackgroundImage()
```


पृष्ठभूमि छवि को प्राप्त करता है।


**Returns:**
TWatermarkableImage - बैकग्राउंड छवि। यदि छवि सेट नहीं है तो null लौटाता है।

### setBackgroundImage(TWatermarkableImage value) {#setBackgroundImage-TWatermarkableImage-}
```
public abstract void setBackgroundImage(TWatermarkableImage value)
```


पृष्ठभूमि छवि को सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | TWatermarkableImage | पृष्ठभूमि छवि। यदि छवि सेट नहीं है तो null लौटाता है। |
|

### checkIfBackgroundImageIsSet() {#checkIfBackgroundImageIsSet--}
```
public final void checkIfBackgroundImageIsSet()
```


<br />



