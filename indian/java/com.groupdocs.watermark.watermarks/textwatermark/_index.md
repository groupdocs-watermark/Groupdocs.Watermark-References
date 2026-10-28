---
title: "TextWatermark"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "टेक्स्ट वॉटरमार्क का प्रतिनिधित्व करता है।"
type: docs
weight: 18
url: /hi/java/com.groupdocs.watermark.watermarks/textwatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.Watermark](../../com.groupdocs.watermark/watermark)
```
public class TextWatermark extends Watermark
```

टेक्स्ट वॉटरमार्क का प्रतिनिधित्व करता है।

**Learn more:**

* [Adding text watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+text+watermarks)

निम्नलिखित उदाहरण दिखाता है कि पैरेंट आकार के आधार पर टेक्स्ट वॉटरमार्क को कैसे स्केल किया जाए।
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("C:\\test.some_ext");
>    TextWatermark watermark = new TextWatermark("test watermark", new Font("Arial", 36));
>
>    watermark.setHorizontalAlignment(HorizontalAlignment.Center);
>    watermark.setVerticalAlignment(VerticalAlignment.Center);
>    watermark.setSizingType(SizingType.ScaleToParentDimensions);
>    watermark.setRotateAngle(45);
>    watermark.setScaleFactor(0.4);
>
>    watermarker.add(watermark);
>
>    watermarker.save("C:\\modified_test.some_ext");
>    watermarker.close();
>  
> ```
> ````


## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [TextWatermark(String text, Font font)](#TextWatermark-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` क्लास का नया उदाहरण निर्दिष्ट टेक्स्ट और फ़ॉन्ट के साथ प्रारंभ करता है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getText()](#getText--) | वॉटरमार्क के रूप में उपयोग किए जाने वाले पाठ को प्राप्त करता है। |
|
|  | [setText(String value)](#setText-java.lang.String-) | वॉटरमार्क के रूप में उपयोग किए जाने वाले पाठ को सेट करता है। |
|
|  | [getFont()](#getFont--) | पाठ का फ़ॉन्ट प्राप्त करता है। |
|
|  | [setFont(Font value)](#setFont-com.groupdocs.watermark.watermarks.Font-) | पाठ का फ़ॉन्ट सेट करता है। |
|
|  | [getForegroundColor()](#getForegroundColor--) | पाठ का अग्रभूमि रंग प्राप्त करता है। |
|
|  | [setForegroundColor(Color value)](#setForegroundColor-com.groupdocs.watermark.watermarks.Color-) | पाठ का अग्रभूमि रंग सेट करता है। |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | पाठ का पृष्ठभूमि रंग प्राप्त करता है। |
|
|  | [setBackgroundColor(Color value)](#setBackgroundColor-com.groupdocs.watermark.watermarks.Color-) | पाठ का पृष्ठभूमि रंग सेट करता है। |
|
|  | [getTextAlignment()](#getTextAlignment--) | वॉटरमार्क `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)` प्राप्त करता है। |
|
|  | [setTextAlignment(int value)](#setTextAlignment-int-) | वॉटरमार्क `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)` सेट करता है। |
|
| [isImageWatermark()](#isImageWatermark--) |  |
| [isTextWatermark()](#isTextWatermark--) |  |
| [getForegroundColorConsideringOpacity()](#getForegroundColorConsideringOpacity--) |  |
| [getBackgroundColorConsideringOpacity()](#getBackgroundColorConsideringOpacity--) |  |
| [getSize()](#getSize--) |  |
|  | [getPadding()](#getPadding--) | इस `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` की पैडिंग सेटिंग्स प्राप्त करता है। |
|
|  | [setPadding(Thickness value)](#setPadding-com.groupdocs.watermark.Thickness-) | इस `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` की पैडिंग सेटिंग्स सेट करता है। |
|
| [deepClone()](#deepClone--) |  |
| [hasSameValues(Watermark watermark)](#hasSameValues-com.groupdocs.watermark.Watermark-) |  |
| [createGeometry(ContentPartGeometry parent)](#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-) |  |
### TextWatermark(String text, Font font) {#TextWatermark-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public TextWatermark(String text, Font font)
```


`[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` क्लास का नया उदाहरण निर्दिष्ट टेक्स्ट और फ़ॉन्ट के साथ प्रारंभ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | पाठ | java.lang.String | वॉटरमार्क के रूप में उपयोग किया जाने वाला पाठ। |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | पाठ का फ़ॉन्ट। |
|

### getText() {#getText--}
```
public final String getText()
```


वॉटरमार्क के रूप में उपयोग किए जाने वाले पाठ को प्राप्त करता है।


**Returns:**
java.lang.String - वॉटरमार्क पाठ का प्रतिनिधित्व करने वाली स्ट्रिंग।

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


वॉटरमार्क के रूप में उपयोग किए जाने वाले पाठ को सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | वॉटरमार्क पाठ का प्रतिनिधित्व करने वाली स्ट्रिंग। |
|

### getFont() {#getFont--}
```
public final Font getFont()
```


पाठ का फ़ॉन्ट प्राप्त करता है।


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### setFont(Font value) {#setFont-com.groupdocs.watermark.watermarks.Font-}
```
public final void setFont(Font value)
```


पाठ का फ़ॉन्ट सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [Font](../../com.groupdocs.watermark.watermarks/font) | पाठ का फ़ॉन्ट। |
|

### getForegroundColor() {#getForegroundColor--}
```
public final Color getForegroundColor()
```


पाठ का अग्रभूमि रंग प्राप्त करता है।


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### setForegroundColor(Color value) {#setForegroundColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setForegroundColor(Color value)
```


पाठ का अग्रभूमि रंग सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | पाठ का अग्रभूमि रंग। |
|

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


पाठ का पृष्ठभूमि रंग प्राप्त करता है।


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

### setBackgroundColor(Color value) {#setBackgroundColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setBackgroundColor(Color value)
```


पाठ का पृष्ठभूमि रंग सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | पाठ का पृष्ठभूमि रंग। |
|

### getTextAlignment() {#getTextAlignment--}
```
public final int getTextAlignment()
```


वॉटरमार्क `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)` प्राप्त करता है।

डिफ़ॉल्ट मान है `[TextAlignment.Left](../../com.groupdocs.watermark.watermarks/textalignment#Left)`।


**Returns:**
int - वॉटरमार्क `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`।

### setTextAlignment(int value) {#setTextAlignment-int-}
```
public final void setTextAlignment(int value)
```


वॉटरमार्क `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)` सेट करता है।

डिफ़ॉल्ट मान है `[TextAlignment.Left](../../com.groupdocs.watermark.watermarks/textalignment#Left)`।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | int | वॉटरमार्क `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`। |
|

### isImageWatermark() {#isImageWatermark--}
```
public boolean isImageWatermark()
```




**Returns:**
boolean
### isTextWatermark() {#isTextWatermark--}
```
public boolean isTextWatermark()
```




**Returns:**
boolean
### getForegroundColorConsideringOpacity() {#getForegroundColorConsideringOpacity--}
```
public final Color getForegroundColorConsideringOpacity()
```




**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color)
### getBackgroundColorConsideringOpacity() {#getBackgroundColorConsideringOpacity--}
```
public final Color getBackgroundColorConsideringOpacity()
```




**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color)
### getSize() {#getSize--}
```
public SizeD getSize()
```




**Returns:**
[SizeD](../../com.groupdocs.watermark.internal/sized)
### getPadding() {#getPadding--}
```
public final Thickness getPadding()
```


इस `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` की पैडिंग सेटिंग्स प्राप्त करता है। यह प्रॉपर्टी केवल इमेज फ़ाइलों पर लागू होती है।


**Returns:**
[Thickness](../../com.groupdocs.watermark/thickness) - The padding settings of this `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`.

### setPadding(Thickness value) {#setPadding-com.groupdocs.watermark.Thickness-}
```
public final void setPadding(Thickness value)
```


इस `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` की पैडिंग सेटिंग्स सेट करता है। यह प्रॉपर्टी केवल इमेज फ़ाइलों पर लागू होती है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [Thickness](../../com.groupdocs.watermark/thickness) | इस `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` की पैडिंग सेटिंग्स। |
|

### deepClone() {#deepClone--}
```
public Watermark deepClone()
```




**Returns:**
[Watermark](../../com.groupdocs.watermark/watermark)
### hasSameValues(Watermark watermark) {#hasSameValues-com.groupdocs.watermark.Watermark-}
```
public boolean hasSameValues(Watermark watermark)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

**Returns:**
boolean
### createGeometry(ContentPartGeometry parent) {#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-}
```
public WatermarkGeometry createGeometry(ContentPartGeometry parent)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| parent | [ContentPartGeometry](../../com.groupdocs.watermark.internal/contentpartgeometry) |  |

**Returns:**
[WatermarkGeometry](../../com.groupdocs.watermark.internal/watermarkgeometry)
