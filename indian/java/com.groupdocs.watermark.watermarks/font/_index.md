---
title: "Font"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "फ़ॉन्ट का प्रतिनिधित्व करने वाली क्लास।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.watermark.watermarks/font/
---
**Inheritance:**
java.lang.Object
```
public final class Font
```

फ़ॉन्ट का प्रतिनिधित्व करने वाली क्लास।

## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | `[Font](../../com.groupdocs.watermark.watermarks/font)` क्लास का नया इंस्टेंस प्रारंभ करता है, जिसमें निर्दिष्ट फ़ॉन्ट परिवार नाम और आकार होता है। |
|
|  | [Font(String fontFamilyName, float size, int style)](#Font-java.lang.String-float-int-) | `[Font](../../com.groupdocs.watermark.watermarks/font)` क्लास का नया इंस्टेंस प्रारंभ करता है, जिसमें निर्दिष्ट फ़ॉन्ट परिवार नाम, आकार और शैली होती है। |
|
| [Font(String fontFamilyName, String folderPath, float size)](#Font-java.lang.String-java.lang.String-float-) |  |
| [Font(String fontFamilyName, String folderPath, float size, FontStyle style)](#Font-java.lang.String-java.lang.String-float-com.groupdocs.watermark.watermarks.FontStyle-) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getFolderPath()](#getFolderPath--) |  |
| [setFolderPath(String folderPath)](#setFolderPath-java.lang.String-) |  |
|  | [getFamilyName()](#getFamilyName--) | इस `[Font](../../com.groupdocs.watermark.watermarks/font)` का परिवार नाम प्राप्त करता है। |
|
|  | [getSize()](#getSize--) | इस `[Font](../../com.groupdocs.watermark.watermarks/font)` का आकार प्राप्त करता है। |
|
|  | [getStyle()](#getStyle--) | इस `[Font](../../com.groupdocs.watermark.watermarks/font)` के लिए `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` प्राप्त करता है। |
|
|  | [getBold()](#getBold--) | फ़ॉन्ट बोल्ड है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
|
|  | [getItalic()](#getItalic--) | फ़ॉन्ट इटैलिक है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
|
|  | [getStrikeout()](#getStrikeout--) | फ़ॉन्ट में क्षैतिज रेखा निर्दिष्ट है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
|
|  | [getUnderline()](#getUnderline--) | फ़ॉन्ट अंडरलाइन है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
|
### Font(String fontFamilyName, float size) {#Font-java.lang.String-float-}
```
public Font(String fontFamilyName, float size)
```


`[Font](../../com.groupdocs.watermark.watermarks/font)` क्लास का नया इंस्टेंस प्रारंभ करता है, जिसमें निर्दिष्ट फ़ॉन्ट परिवार नाम और आकार होता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | फ़ॉन्ट परिवार का नाम। |
|
|  | size | float | नए फ़ॉन्ट का आकार। |
|

### Font(String fontFamilyName, float size, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontFamilyName, float size, int style)
```


`[Font](../../com.groupdocs.watermark.watermarks/font)` क्लास का नया इंस्टेंस प्रारंभ करता है, जिसमें निर्दिष्ट फ़ॉन्ट परिवार नाम, आकार और शैली होती है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | फ़ॉन्ट परिवार का नाम। |
|
|  | size | float | नए फ़ॉन्ट का आकार। |
|
|  | style | int | नए फ़ॉन्ट का `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)`। |
|

### Font(String fontFamilyName, String folderPath, float size) {#Font-java.lang.String-java.lang.String-float-}
```
public Font(String fontFamilyName, String folderPath, float size)
```


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontFamilyName | java.lang.String |  |
| folderPath | java.lang.String |  |
| size | float |  |

### Font(String fontFamilyName, String folderPath, float size, FontStyle style) {#Font-java.lang.String-java.lang.String-float-com.groupdocs.watermark.watermarks.FontStyle-}
```
public Font(String fontFamilyName, String folderPath, float size, FontStyle style)
```


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontFamilyName | java.lang.String |  |
| folderPath | java.lang.String |  |
| size | float |  |
| style | [FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle) |  |

### getFolderPath() {#getFolderPath--}
```
public String getFolderPath()
```




**Returns:**
java.lang.String
### setFolderPath(String folderPath) {#setFolderPath-java.lang.String-}
```
public void setFolderPath(String folderPath)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| folderPath | java.lang.String |  |

### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


इस `[Font](../../com.groupdocs.watermark.watermarks/font)` का परिवार नाम प्राप्त करता है।


**Returns:**
java.lang.String - इस `[Font](../../com.groupdocs.watermark.watermarks/font)` का परिवार नाम।

### getSize() {#getSize--}
```
public final float getSize()
```


इस `[Font](../../com.groupdocs.watermark.watermarks/font)` का आकार प्राप्त करता है।


**Returns:**
float - इस `[Font](../../com.groupdocs.watermark.watermarks/font)` का आकार।

### getStyle() {#getStyle--}
```
public final int getStyle()
```


इस `[Font](../../com.groupdocs.watermark.watermarks/font)` के लिए `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` प्राप्त करता है।

डिफ़ॉल्ट मान है `[FontStyle.Regular](../../com.groupdocs.watermark.watermarks/fontstyle#Regular)` (सामान्य पाठ)।


**Returns:**
int - इस `[Font](../../com.groupdocs.watermark.watermarks/font)` का `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)`।

### getBold() {#getBold--}
```
public final boolean getBold()
```


फ़ॉन्ट बोल्ड है या नहीं, यह दर्शाने वाला मान प्राप्त करता है।


**Returns:**
boolean - यदि यह फ़ॉन्ट बोल्ड है तो true; अन्यथा false।

### getItalic() {#getItalic--}
```
public final boolean getItalic()
```


फ़ॉन्ट इटैलिक है या नहीं, यह दर्शाने वाला मान प्राप्त करता है।


**Returns:**
boolean - यदि यह फ़ॉन्ट इटैलिक है तो true; अन्यथा false।

### getStrikeout() {#getStrikeout--}
```
public final boolean getStrikeout()
```


फ़ॉन्ट में क्षैतिज रेखा निर्दिष्ट है या नहीं, यह दर्शाने वाला मान प्राप्त करता है।


**Returns:**
boolean - यदि यह फ़ॉन्ट क्षैतिज रेखा निर्दिष्ट करता है तो true; अन्यथा false।

### getUnderline() {#getUnderline--}
```
public final boolean getUnderline()
```


फ़ॉन्ट अंडरलाइन है या नहीं, यह दर्शाने वाला मान प्राप्त करता है।


**Returns:**
boolean - यदि यह फ़ॉन्ट अंडरलाइन है तो true; अन्यथा false।

