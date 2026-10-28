---
title: "FormattedTextFragmentCollection"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "स्वरूपित टेक्स्ट टुकड़ों का एक परिवर्तनशील संग्रह दर्शाता है।"
type: docs
weight: 27
url: /hi/java/com.groupdocs.watermark.search/formattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class FormattedTextFragmentCollection extends RemoveOnlyListBase<FormattedTextFragment>
```

स्वरूपित टेक्स्ट टुकड़ों का एक परिवर्तनशील संग्रह दर्शाता है।

यह संग्रह `[FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)` बेस टाइप के आइटम्स रखता है।

## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
| [FormattedTextFragmentCollection(int collectionType)](#FormattedTextFragmentCollection-int-) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getCollectionType()](#getCollectionType--) | फ़ॉर्मेटेड फ्रैगमेंट संग्रह प्रकार प्राप्त करता है। |
|
| [getDefaultFont()](#getDefaultFont--) |  |
| [getDefaultForegroundColor()](#getDefaultForegroundColor--) |  |
| [getDefaultBackgroundColor()](#getDefaultBackgroundColor--) |  |
| [getText()](#getText--) |  |
|  | [add(String text)](#add-java.lang.String-) | संग्रह में एक फ़ॉर्मेटेड टेक्स्ट फ्रैगमेंट जोड़ता है। |
|
|  | [add(String text, Font font)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | संग्रह में एक फ़ॉर्मेटेड टेक्स्ट फ्रैगमेंट जोड़ता है। |
|
|  | [add(String text, Font font, Color foregroundColor)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-) | संग्रह में एक फ़ॉर्मेटेड टेक्स्ट फ्रैगमेंट जोड़ता है। |
|
|  | [add(String text, Font font, Color foregroundColor, Color backgroundColor)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) | संग्रह में एक फ़ॉर्मेटेड टेक्स्ट फ्रैगमेंट जोड़ता है। |
|
|  | [insert(int index, String text)](#insert-int-java.lang.String-) | निर्दिष्ट इंडेक्स पर संग्रह में एक फ़ॉर्मेटेड टेक्स्ट फ्रैगमेंट डालता है। |
|
|  | [insert(int index, String text, Font font)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | निर्दिष्ट इंडेक्स पर संग्रह में एक फ़ॉर्मेटेड टेक्स्ट फ्रैगमेंट डालता है। |
|
|  | [insert(int index, String text, Font font, Color foregroundColor)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-) | निर्दिष्ट इंडेक्स पर संग्रह में एक फ़ॉर्मेटेड टेक्स्ट फ्रैगमेंट डालता है। |
|
|  | [insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) | निर्दिष्ट इंडेक्स पर संग्रह में एक फ़ॉर्मेटेड टेक्स्ट फ्रैगमेंट डालता है। |
|
| [createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) |  |
| [setText(String text)](#setText-java.lang.String-) |  |
### FormattedTextFragmentCollection(int collectionType) {#FormattedTextFragmentCollection-int-}
```
public FormattedTextFragmentCollection(int collectionType)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| collectionType | int |  |

### getCollectionType() {#getCollectionType--}
```
public final int getCollectionType()
```


फ़ॉर्मेटेड फ्रैगमेंट संग्रह प्रकार प्राप्त करता है।


**Returns:**
int - फ़ॉर्मेटेड फ्रैगमेंट संग्रह प्रकार।

### getDefaultFont() {#getDefaultFont--}
```
public final Font getDefaultFont()
```




**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font)
### getDefaultForegroundColor() {#getDefaultForegroundColor--}
```
public final Color getDefaultForegroundColor()
```




**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color)
### getDefaultBackgroundColor() {#getDefaultBackgroundColor--}
```
public final Color getDefaultBackgroundColor()
```




**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color)
### getText() {#getText--}
```
public String getText()
```




**Returns:**
java.lang.String
### add(String text) {#add-java.lang.String-}
```
public final void add(String text)
```


संग्रह में एक फ़ॉर्मेटेड टेक्स्ट फ्रैगमेंट जोड़ता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | पाठ | java.lang.String | फ्रैगमेंट टेक्स्ट। |
|

### add(String text, Font font) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public final void add(String text, Font font)
```


संग्रह में एक फ़ॉर्मेटेड टेक्स्ट फ्रैगमेंट जोड़ता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | पाठ | java.lang.String | फ्रैगमेंट टेक्स्ट। |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | पाठ का फ़ॉन्ट। |
|

### add(String text, Font font, Color foregroundColor) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-}
```
public final void add(String text, Font font, Color foregroundColor)
```


संग्रह में एक फ़ॉर्मेटेड टेक्स्ट फ्रैगमेंट जोड़ता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | पाठ | java.lang.String | फ्रैगमेंट टेक्स्ट। |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | पाठ का फ़ॉन्ट। |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | पाठ का अग्रभूमि रंग। |
|

### add(String text, Font font, Color foregroundColor, Color backgroundColor) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public final void add(String text, Font font, Color foregroundColor, Color backgroundColor)
```


संग्रह में एक फ़ॉर्मेटेड टेक्स्ट फ्रैगमेंट जोड़ता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | पाठ | java.lang.String | फ्रैगमेंट टेक्स्ट। |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | पाठ का फ़ॉन्ट। |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | पाठ का अग्रभूमि रंग। |
|
|  | backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | पाठ का पृष्ठभूमि रंग। |
|

### insert(int index, String text) {#insert-int-java.lang.String-}
```
public final void insert(int index, String text)
```


निर्दिष्ट इंडेक्स पर संग्रह में एक फ़ॉर्मेटेड टेक्स्ट फ्रैगमेंट डालता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | सूचकांक | int | शून्य-आधारित इंडेक्स जहाँ फ़ॉर्मेटेड टेक्स्ट फ्रैगमेंट डालना चाहिए। |
|
|  | पाठ | java.lang.String | फ्रैगमेंट टेक्स्ट। |
|

### insert(int index, String text, Font font) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public final void insert(int index, String text, Font font)
```


निर्दिष्ट इंडेक्स पर संग्रह में एक फ़ॉर्मेटेड टेक्स्ट फ्रैगमेंट डालता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | सूचकांक | int | शून्य-आधारित इंडेक्स जहाँ फ़ॉर्मेटेड टेक्स्ट फ्रैगमेंट डालना चाहिए। |
|
|  | पाठ | java.lang.String | फ्रैगमेंट टेक्स्ट। |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | पाठ का फ़ॉन्ट। |
|

### insert(int index, String text, Font font, Color foregroundColor) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-}
```
public final void insert(int index, String text, Font font, Color foregroundColor)
```


निर्दिष्ट इंडेक्स पर संग्रह में एक फ़ॉर्मेटेड टेक्स्ट फ्रैगमेंट डालता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | सूचकांक | int | शून्य-आधारित इंडेक्स जहाँ फ़ॉर्मेटेड टेक्स्ट फ्रैगमेंट डालना चाहिए। |
|
|  | पाठ | java.lang.String | फ्रैगमेंट टेक्स्ट। |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | पाठ का फ़ॉन्ट। |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | पाठ का अग्रभूमि रंग। |
|

### insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public final void insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```


निर्दिष्ट इंडेक्स पर संग्रह में एक फ़ॉर्मेटेड टेक्स्ट फ्रैगमेंट डालता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | सूचकांक | int | शून्य-आधारित इंडेक्स जहाँ फ़ॉर्मेटेड टेक्स्ट फ्रैगमेंट डालना चाहिए। |
|
|  | पाठ | java.lang.String | फ्रैगमेंट टेक्स्ट। |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | पाठ का फ़ॉन्ट। |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | पाठ का अग्रभूमि रंग। |
|
|  | backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | पाठ का पृष्ठभूमि रंग। |
|

### createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public FormattedTextFragment createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| सूचकांक | int |  |
| पाठ | java.lang.String |  |
| font | [Font](../../com.groupdocs.watermark.watermarks/font) |  |
| foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |
| backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |

**Returns:**
[FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)
### setText(String text) {#setText-java.lang.String-}
```
public void setText(String text)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पाठ | java.lang.String |  |

