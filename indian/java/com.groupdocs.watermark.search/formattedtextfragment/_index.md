---
title: "FormattedTextFragment"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "कंटेंट में स्वरूपित टेक्स्ट के एक टुकड़े के लिए एब्स्ट्रैक्ट बेस क्लास प्रदान करता है।"
type: docs
weight: 26
url: /hi/java/com.groupdocs.watermark.search/formattedtextfragment/
---
**Inheritance:**
java.lang.Object
```
public abstract class FormattedTextFragment
```

कंटेंट में स्वरूपित टेक्स्ट के एक टुकड़े के लिए एब्स्ट्रैक्ट बेस क्लास प्रदान करता है।

## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
| [FormattedTextFragment()](#FormattedTextFragment--) |  |
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
### FormattedTextFragment() {#FormattedTextFragment--}
```
public FormattedTextFragment()
```




### getText() {#getText--}
```
public abstract String getText()
```


फ़्रैगमेंट टेक्स्ट प्राप्त करता है।


**Returns:**
java.lang.String - फ़्रैगमेंट टेक्स्ट।

### getFont() {#getFont--}
```
public abstract Font getFont()
```


पाठ का फ़ॉन्ट प्राप्त करता है।


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### getForegroundColor() {#getForegroundColor--}
```
public abstract Color getForegroundColor()
```


पाठ का अग्रभूमि रंग प्राप्त करता है।


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### getBackgroundColor() {#getBackgroundColor--}
```
public abstract Color getBackgroundColor()
```


पाठ का पृष्ठभूमि रंग प्राप्त करता है।


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

