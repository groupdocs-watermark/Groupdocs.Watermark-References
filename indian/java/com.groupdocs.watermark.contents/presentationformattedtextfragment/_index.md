---
title: "PresentationFormattedTextFragment"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "PowerPoint दस्तावेज़ में स्वरूपित पाठ का एक भाग दर्शाता है।"
type: docs
weight: 82
url: /hi/java/com.groupdocs.watermark.contents/presentationformattedtextfragment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)

**All Implemented Interfaces:**
[com.groupdocs.watermark.contents.IPresentationHyperlinkContainer](../../com.groupdocs.watermark.contents/ipresentationhyperlinkcontainer)
```
public class PresentationFormattedTextFragment extends FormattedTextFragment implements IPresentationHyperlinkContainer
```

PowerPoint दस्तावेज़ में स्वरूपित पाठ का एक भाग दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getText()](#getText--) | फ़्रैगमेंट टेक्स्ट प्राप्त करता है। |
|
|  | [getFont()](#getFont--) | पाठ का फ़ॉन्ट प्राप्त करता है। |
|
|  | [getForegroundColor()](#getForegroundColor--) | पाठ का अग्रभूमि रंग प्राप्त करता है। |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | पाठ का पृष्ठभूमि रंग प्राप्त करता है। |
|
|  | [getHyperlink(int actionType)](#getHyperlink-int-) | पाठ से जुड़ी हाइपरलिंक प्राप्त करता है। |
|
|  | [setHyperlink(int actionType, String url)](#setHyperlink-int-java.lang.String-) | पाठ से जुड़ी हाइपरलिंक सेट करता है। |
|
### getText() {#getText--}
```
public String getText()
```


फ़्रैगमेंट टेक्स्ट प्राप्त करता है।


**Returns:**
java.lang.String - फ़्रैगमेंट टेक्स्ट।

### getFont() {#getFont--}
```
public Font getFont()
```


पाठ का फ़ॉन्ट प्राप्त करता है।


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


पाठ का अग्रभूमि रंग प्राप्त करता है।


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


पाठ का पृष्ठभूमि रंग प्राप्त करता है।


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

### getHyperlink(int actionType) {#getHyperlink-int-}
```
public final String getHyperlink(int actionType)
```


पाठ से जुड़ी हाइपरलिंक प्राप्त करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | actionType | int | हाइपरलिंक को सक्रिय करने वाली क्रिया। |
|

**Returns:**
java.lang.String - निर्दिष्ट क्रिया पर सक्रिय होने वाली हाइपरलिंक का URL।

### setHyperlink(int actionType, String url) {#setHyperlink-int-java.lang.String-}
```
public final void setHyperlink(int actionType, String url)
```


पाठ से जुड़ी हाइपरलिंक सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | actionType | int | हाइपरलिंक को सक्रिय करने वाली क्रिया। |
|
|  | URL | java.lang.String | हाइपरलिंक URL। |
|

