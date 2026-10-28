---
title: "OfficeImageEffects"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "ऑफ़िस कंटेंट के लिए इमेज वॉटरमार्क पर लागू किए जा सकने वाले इफ़ेक्ट्स का प्रतिनिधित्व करता है।"
type: docs
weight: 45
url: /hi/java/com.groupdocs.watermark.contents/officeimageeffects/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IDocumentSpecificSettings](../../com.groupdocs.watermark.internal/idocumentspecificsettings)
```
public abstract class OfficeImageEffects implements IDocumentSpecificSettings
```

ऑफ़िस कंटेंट के लिए इमेज वॉटरमार्क पर लागू किए जा सकने वाले इफ़ेक्ट्स का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getBorderLineFormat()](#getBorderLineFormat--) | छवि सीमा के लिए लाइन फ़ॉर्मेट सेटिंग प्राप्त करता है। |
|
|  | [setBorderLineFormat(OfficeLineFormat value)](#setBorderLineFormat-com.groupdocs.watermark.contents.OfficeLineFormat-) | छवि सीमा के लिए लाइन फ़ॉर्मेट सेटिंग सेट करता है। |
|
|  | [getGrayScale()](#getGrayScale--) | एक मान प्राप्त करता है जो दर्शाता है कि चित्र ग्रेस्केल मोड में प्रदर्शित होगा या नहीं। |
|
|  | [setGrayScale(boolean value)](#setGrayScale-boolean-) | एक मान सेट करता है जो दर्शाता है कि चित्र ग्रेस्केल मोड में प्रदर्शित होगा या नहीं। |
|
|  | [getChromaKey()](#getChromaKey--) | छवि का वह रंग मान प्राप्त करता है जिसे पारदर्शी माना जाएगा। |
|
|  | [setChromaKey(Color value)](#setChromaKey-com.groupdocs.watermark.watermarks.Color-) | छवि का वह रंग मान सेट करता है जिसे पारदर्शी माना जाएगा। |
|
|  | [getBrightness()](#getBrightness--) | चित्र की चमक प्राप्त करता है। |
|
|  | [setBrightness(double value)](#setBrightness-double-) | चित्र की चमक सेट करता है। |
|
|  | [getContrast()](#getContrast--) | निर्दिष्ट चित्र के लिए कंट्रास्ट प्राप्त करता है। |
|
|  | [setContrast(double value)](#setContrast-double-) | निर्दिष्ट चित्र के लिए कंट्रास्ट सेट करता है। |
|
### getBorderLineFormat() {#getBorderLineFormat--}
```
public final OfficeLineFormat getBorderLineFormat()
```


छवि सीमा के लिए लाइन फ़ॉर्मेट सेटिंग प्राप्त करता है।


**Returns:**
[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat) - Instance of  OfficeLineFormat  class, representing shape line format.

### setBorderLineFormat(OfficeLineFormat value) {#setBorderLineFormat-com.groupdocs.watermark.contents.OfficeLineFormat-}
```
public final void setBorderLineFormat(OfficeLineFormat value)
```


छवि सीमा के लिए लाइन फ़ॉर्मेट सेटिंग सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat) | OfficeLineFormat क्लास का एक उदाहरण, जो आकार की लाइन फ़ॉर्मेट का प्रतिनिधित्व करता है। |
|

### getGrayScale() {#getGrayScale--}
```
public final boolean getGrayScale()
```


एक मान प्राप्त करता है जो दर्शाता है कि चित्र ग्रेस्केल मोड में प्रदर्शित होगा या नहीं।


**Returns:**
boolean - डिफ़ॉल्ट मान false है।

### setGrayScale(boolean value) {#setGrayScale-boolean-}
```
public final void setGrayScale(boolean value)
```


एक मान सेट करता है जो दर्शाता है कि चित्र ग्रेस्केल मोड में प्रदर्शित होगा या नहीं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | डिफ़ॉल्ट मान false है। |
|

### getChromaKey() {#getChromaKey--}
```
public final Color getChromaKey()
```


छवि का वह रंग मान प्राप्त करता है जिसे पारदर्शी माना जाएगा।


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The default value is fully transparent color.

### setChromaKey(Color value) {#setChromaKey-com.groupdocs.watermark.watermarks.Color-}
```
public final void setChromaKey(Color value)
```


छवि का वह रंग मान सेट करता है जिसे पारदर्शी माना जाएगा।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | डिफ़ॉल्ट मान पूरी तरह पारदर्शी रंग है। |
|

### getBrightness() {#getBrightness--}
```
public final double getBrightness()
```


चित्र की चमक प्राप्त करता है। इस प्रॉपर्टी का मान होना चाहिए
0.0 (सबसे धुंधला) से 1.0 (सबसे उज्ज्वल) तक का संख्या होना चाहिए।


**Returns:**
double - डिफ़ॉल्ट मान 0.5 है।

### setBrightness(double value) {#setBrightness-double-}
```
public final void setBrightness(double value)
```


चित्र की चमक सेट करता है। इस प्रॉपर्टी का मान होना चाहिए
0.0 (सबसे धुंधला) से 1.0 (सबसे उज्ज्वल) तक का संख्या होना चाहिए।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | double | डिफ़ॉल्ट मान 0.5 है। |
|

### getContrast() {#getContrast--}
```
public final double getContrast()
```


निर्दिष्ट चित्र के लिए कंट्रास्ट प्राप्त करता है। इस प्रॉपर्टी का मान
0.0 (सबसे कम कंट्रास्ट) से 1.0 (सबसे अधिक कंट्रास्ट) के बीच एक संख्या होनी चाहिए।


**Returns:**
double - डिफ़ॉल्ट मान 0.5 है।

### setContrast(double value) {#setContrast-double-}
```
public final void setContrast(double value)
```


निर्दिष्ट चित्र के लिए कंट्रास्ट सेट करता है। इस प्रॉपर्टी का मान
0.0 (सबसे कम कंट्रास्ट) से 1.0 (सबसे अधिक कंट्रास्ट) के बीच एक संख्या होनी चाहिए।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | double | डिफ़ॉल्ट मान 0.5 है। |
|

