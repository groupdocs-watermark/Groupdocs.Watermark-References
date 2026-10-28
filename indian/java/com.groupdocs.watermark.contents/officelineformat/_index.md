---
title: "OfficeLineFormat"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "शेप लाइन फ़ॉर्मेट का प्रतिनिधित्व करता है।"
type: docs
weight: 47
url: /hi/java/com.groupdocs.watermark.contents/officelineformat/
---
**Inheritance:**
java.lang.Object
```
public final class OfficeLineFormat
```

शेप लाइन फ़ॉर्मेट का प्रतिनिधित्व करता है।

## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [OfficeLineFormat()](#OfficeLineFormat--) | एक नया उदाहरण प्रारंभ करता है `[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat)` क्लास का। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getWeight()](#getWeight--) | एक आकार के पथ को स्ट्रोक करने वाले ब्रश की मोटाई प्राप्त करता है। |
|
|  | [setWeight(double value)](#setWeight-double-) | एक आकार के पथ को स्ट्रोक करने वाले ब्रश की मोटाई सेट करता है। |
|
|  | [getColor()](#getColor--) | रेखा का रंग प्राप्त करता है। |
|
|  | [setColor(Color value)](#setColor-com.groupdocs.watermark.watermarks.Color-) | रेखा का रंग सेट करता है। |
|
|  | [getOpacity()](#getOpacity--) | रेखा की अपारदर्शिता प्राप्त करता है। |
|
|  | [setOpacity(double value)](#setOpacity-double-) | रेखा की अपारदर्शिता सेट करता है। |
|
|  | [getEnabled()](#getEnabled--) | एक मान प्राप्त करता है जो दर्शाता है कि आकार स्ट्रोक किया जाएगा या नहीं। |
|
|  | [setEnabled(boolean value)](#setEnabled-boolean-) | एक मान सेट करता है जो दर्शाता है कि आकार स्ट्रोक किया जाएगा या नहीं। |
|
|  | [getDashStyle()](#getDashStyle--) | रेखा के लिए बिंदु और डैश पैटर्न प्राप्त करता है। |
|
|  | [setDashStyle(int value)](#setDashStyle-int-) | रेखा के लिए बिंदु और डैश पैटर्न सेट करता है। |
|
|  | [getLineStyle()](#getLineStyle--) | रेखा की शैली प्राप्त करता है। |
|
|  | [setLineStyle(int value)](#setLineStyle-int-) | रेखा की शैली सेट करता है। |
|
|  | [getTransparency()](#getTransparency--) | <br /> |

|
|  | [getColorConsideringOpacity()](#getColorConsideringOpacity--) | <br /> |

|
### OfficeLineFormat() {#OfficeLineFormat--}
```
public OfficeLineFormat()
```


एक नया उदाहरण प्रारंभ करता है `[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat)` क्लास का।


### getWeight() {#getWeight--}
```
public final double getWeight()
```


एक आकार के पथ को स्ट्रोक करने वाले ब्रश की मोटाई प्राप्त करता है।


**Returns:**
double - बिंदुओं में रेखा की मोटाई। डिफ़ॉल्ट मान 0.75 है।

### setWeight(double value) {#setWeight-double-}
```
public final void setWeight(double value)
```


एक आकार के पथ को स्ट्रोक करने वाले ब्रश की मोटाई सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | double | बिंदुओं में रेखा की मोटाई। डिफ़ॉल्ट मान 0.75 है। |
|

### getColor() {#getColor--}
```
public final Color getColor()
```


रेखा का रंग प्राप्त करता है।

डिफ़ॉल्ट मान `[Color.getBlack()](../../com.groupdocs.watermark.watermarks/color#getBlack--)` है।


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The color of the line.

### setColor(Color value) {#setColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setColor(Color value)
```


रेखा का रंग सेट करता है।

डिफ़ॉल्ट मान `[Color.getBlack()](../../com.groupdocs.watermark.watermarks/color#getBlack--)` है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | रेखा का रंग। |
|

### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


रेखा की अपारदर्शिता प्राप्त करता है।


**Returns:**
double - मान 0 और 1 के बीच होना चाहिए। डिफ़ॉल्ट मान 1 है।

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


रेखा की अपारदर्शिता सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | double | मान 0 और 1 के बीच होना चाहिए। डिफ़ॉल्ट मान 1 है। |
|

### getEnabled() {#getEnabled--}
```
public final boolean getEnabled()
```


एक मान प्राप्त करता है जो दर्शाता है कि आकार स्ट्रोक किया जाएगा या नहीं।


**Returns:**
boolean - डिफ़ॉल्ट मान false है।

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


एक मान सेट करता है जो दर्शाता है कि आकार स्ट्रोक किया जाएगा या नहीं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | डिफ़ॉल्ट मान false है। |
|

### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


रेखा के लिए बिंदु और डैश पैटर्न प्राप्त करता है।

<br />



**Returns:**
int
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


रेखा के लिए बिंदु और डैश पैटर्न सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getLineStyle() {#getLineStyle--}
```
public final int getLineStyle()
```


रेखा की शैली प्राप्त करता है।

डिफ़ॉल्ट मान है `[OfficeLineStyle.Single](../../com.groupdocs.watermark.contents/officelinestyle#Single)`।


**Returns:**
int - लाइन शैली।

### setLineStyle(int value) {#setLineStyle-int-}
```
public final void setLineStyle(int value)
```


रेखा की शैली सेट करता है।

डिफ़ॉल्ट मान है `[OfficeLineStyle.Single](../../com.groupdocs.watermark.contents/officelinestyle#Single)`।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | लाइन शैली। |
|

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


<br />



**Returns:**
double
### getColorConsideringOpacity() {#getColorConsideringOpacity--}
```
public final Color getColorConsideringOpacity()
```


<br />



**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color)
