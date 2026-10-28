---
title: "PresentationImageFillFormat"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "PowerPoint दस्तावेज़ में इमेज फ़िल फ़ॉर्मेट सेटिंग्स का प्रतिनिधित्व करता है।"
type: docs
weight: 85
url: /hi/java/com.groupdocs.watermark.contents/presentationimagefillformat/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.contents.OfficeImageFillFormat
```
public class PresentationImageFillFormat extends OfficeImageFillFormat<PresentationWatermarkableImage>
```

PowerPoint दस्तावेज़ में इमेज फ़िल फ़ॉर्मेट सेटिंग्स का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | एक मान प्राप्त करता है जो दर्शाता है कि क्या छवि पृष्ठभूमि में टाइल की गई है। |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | एक मान सेट करता है जो दर्शाता है कि क्या छवि पृष्ठभूमि में टाइल की गई है। |
|
|  | [getTransparency()](#getTransparency--) | पृष्ठभूमि छवि की पारदर्शिता को 0.0 (अपारदर्शी) से 1.0 तक के मान के रूप में प्राप्त करता है |
(पूरी तरह पारदर्शी)।
|
|  | [setTransparency(double value)](#setTransparency-double-) | पृष्ठभूमि छवि की पारदर्शिता को 0.0 (अपारदर्शी) से 1.0 तक के मान के रूप में सेट करता है |
(पूरी तरह पारदर्शी)।
|
|  | [getBackgroundImage()](#getBackgroundImage--) | पृष्ठभूमि छवि को प्राप्त करता है। |
|
|  | [setBackgroundImage(PresentationWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-) | पृष्ठभूमि छवि को सेट करता है। |
|
### getTileAsTexture() {#getTileAsTexture--}
```
public boolean getTileAsTexture()
```


एक मान प्राप्त करता है जो दर्शाता है कि क्या छवि पृष्ठभूमि में टाइल की गई है।


**Returns:**
बूलियन - यदि छवि पृष्ठभूमि में टाइल की गई है तो true; अन्यथा false (छवि खिंची हुई है)। डिफ़ॉल्ट मान false है।

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public void setTileAsTexture(boolean value)
```


एक मान सेट करता है जो दर्शाता है कि क्या छवि पृष्ठभूमि में टाइल की गई है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | यदि छवि पृष्ठभूमि में टाइल की गई है तो true; अन्यथा false (छवि खिंची हुई है)। डिफ़ॉल्ट मान false है। |
|

### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


पृष्ठभूमि छवि की पारदर्शिता को 0.0 (अपारदर्शी) से 1.0 तक के मान के रूप में प्राप्त करता है
(पूरी तरह पारदर्शी)।


**Returns:**
double - पृष्ठभूमि छवि की पारदर्शिता को 0.0 (अपारदर्शी) से 1.0 (पूर्णतः पारदर्शी) तक मान के रूप में।

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


पृष्ठभूमि छवि की पारदर्शिता को 0.0 (अपारदर्शी) से 1.0 तक के मान के रूप में सेट करता है
(पूरी तरह पारदर्शी)।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | double | पृष्ठभूमि छवि की पारदर्शिता को 0.0 (अपारदर्शी) से 1.0 (पूर्णतः पारदर्शी) तक मान के रूप में। |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public PresentationWatermarkableImage getBackgroundImage()
```


पृष्ठभूमि छवि को प्राप्त करता है।


**Returns:**
[PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) - The background image. Returns null if the image is not set.

### setBackgroundImage(PresentationWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-}
```
public void setBackgroundImage(PresentationWatermarkableImage value)
```


पृष्ठभूमि छवि को सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) | पृष्ठभूमि छवि। यदि छवि सेट नहीं है तो null लौटाता है। |
|

