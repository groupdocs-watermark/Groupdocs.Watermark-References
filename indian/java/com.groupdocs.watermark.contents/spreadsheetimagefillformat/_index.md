---
title: "SpreadsheetImageFillFormat"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "Excel दस्तावेज़ में इमेज फ़िल फ़ॉर्मेट सेटिंग्स का प्रतिनिधित्व करता है।"
type: docs
weight: 114
url: /hi/java/com.groupdocs.watermark.contents/spreadsheetimagefillformat/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.contents.OfficeImageFillFormat
```
public class SpreadsheetImageFillFormat extends OfficeImageFillFormat<SpreadsheetWatermarkableImage>
```

Excel दस्तावेज़ में इमेज फ़िल फ़ॉर्मेट सेटिंग्स का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | एक मान प्राप्त करता है जो दर्शाता है कि क्या छवि पृष्ठभूमि में टाइल की गई है। |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | एक मान सेट करता है जो दर्शाता है कि क्या छवि पृष्ठभूमि में टाइल की गई है। |
|
|  | [getTransparency()](#getTransparency--) | पृष्ठभूमि छवि की पारदर्शिता को 0.0 (अपारदर्शी) से मान के रूप में प्राप्त करता है |
1.0 (पूर्णतः पारदर्शी) तक।
|
|  | [setTransparency(double value)](#setTransparency-double-) | पृष्ठभूमि छवि की पारदर्शिता को 0.0 (अपारदर्शी) से मान के रूप में सेट करता है |
1.0 (पूर्णतः पारदर्शी) तक।
|
|  | [getBackgroundImage()](#getBackgroundImage--) | पृष्ठभूमि छवि को प्राप्त करता है। |
|
|  | [setBackgroundImage(SpreadsheetWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | पृष्ठभूमि छवि को सेट करता है। |
|
### getTileAsTexture() {#getTileAsTexture--}
```
public boolean getTileAsTexture()
```


एक मान प्राप्त करता है जो दर्शाता है कि क्या छवि पृष्ठभूमि में टाइल की गई है।


**Returns:**
boolean - यदि छवि पृष्ठभूमि में टाइल की गई है तो True; अन्यथा false (छवि खिंची हुई है)।

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public void setTileAsTexture(boolean value)
```


एक मान सेट करता है जो दर्शाता है कि क्या छवि पृष्ठभूमि में टाइल की गई है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | यदि छवि पृष्ठभूमि में टाइल की गई है तो True; अन्यथा false (छवि खिंची हुई है)। |
|

### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


पृष्ठभूमि छवि की पारदर्शिता को 0.0 (अपारदर्शी) से मान के रूप में प्राप्त करता है
1.0 (पूर्णतः पारदर्शी) तक।


**Returns:**
double - पृष्ठभूमि छवि की पारदर्शिता को 0.0 (अपारदर्शी) से 1.0 (पूर्णतः पारदर्शी) तक मान के रूप में।

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


पृष्ठभूमि छवि की पारदर्शिता को 0.0 (अपारदर्शी) से मान के रूप में सेट करता है
1.0 (पूर्णतः पारदर्शी) तक।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | double | पृष्ठभूमि छवि की पारदर्शिता को 0.0 (अपारदर्शी) से 1.0 (पूर्णतः पारदर्शी) तक मान के रूप में। |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public SpreadsheetWatermarkableImage getBackgroundImage()
```


पृष्ठभूमि छवि को प्राप्त करता है।


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The background image. Returns null if the image is not set.

### setBackgroundImage(SpreadsheetWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public void setBackgroundImage(SpreadsheetWatermarkableImage value)
```


पृष्ठभूमि छवि को सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | पृष्ठभूमि छवि। यदि छवि सेट नहीं है तो null लौटाता है। |
|

