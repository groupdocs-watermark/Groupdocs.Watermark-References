---
title: "Margins"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "ऑब्जेक्ट के प्रत्येक किनारे के लिए मार्जिन सेटिंग्स का प्रतिनिधित्व करता है।"
type: docs
weight: 15
url: /hi/java/com.groupdocs.watermark.watermarks/margins/
---
**Inheritance:**
java.lang.Object
```
public class Margins
```

ऑब्जेक्ट के प्रत्येक किनारे के लिए मार्जिन सेटिंग्स का प्रतिनिधित्व करता है।

## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [Margins()](#Margins--) | `[Margins](../../com.groupdocs.watermark.watermarks/margins)` क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
|
|  | [Margins(int marginType, double left, double right, double top, double bottom)](#Margins-int-double-double-double-double-) | निर्दिष्ट प्रकार, स्थान और आकार के साथ `[Margins](../../com.groupdocs.watermark.watermarks/margins)` क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getMarginType()](#getMarginType--) | प्राप्त करता है `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`। |
|
|  | [setMarginType(int value)](#setMarginType-int-) | सेट करता है `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`। |
|
|  | [getLeft()](#getLeft--) | बाएँ मार्जिन को प्राप्त करता है। |
|
|  | [setLeft(double value)](#setLeft-double-) | बाएँ मार्जिन को सेट करता है। |
|
|  | [getRight()](#getRight--) | दाएँ मार्जिन को प्राप्त करता है। |
|
|  | [setRight(double value)](#setRight-double-) | दाएँ मार्जिन को सेट करता है। |
|
|  | [getTop()](#getTop--) | ऊपरी मार्जिन को प्राप्त करता है। |
|
|  | [setTop(double value)](#setTop-double-) | ऊपरी मार्जिन को सेट करता है। |
|
|  | [getBottom()](#getBottom--) | निचले मार्जिन को प्राप्त करता है। |
|
|  | [setBottom(double value)](#setBottom-double-) | निचले मार्जिन को सेट करता है। |
|
### Margins() {#Margins--}
```
public Margins()
```


`[Margins](../../com.groupdocs.watermark.watermarks/margins)` क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।


### Margins(int marginType, double left, double right, double top, double bottom) {#Margins-int-double-double-double-double-}
```
public Margins(int marginType, double left, double right, double top, double bottom)
```


निर्दिष्ट प्रकार, स्थान और आकार के साथ `[Margins](../../com.groupdocs.watermark.watermarks/margins)` क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | marginType | int | यह `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` है। निर्दिष्ट करता है कि मार्जिन मानों की व्याख्या कैसे की जानी चाहिए। |
|
|  | बाएँ | double | बाएँ मार्जिन का मान। |
|
|  | दाएँ | double | दाएँ मार्जिन का मान। |
|
|  | ऊपर | double | ऊपरी मार्जिन का मान। |
|
|  | नीचे | double | निचले मार्जिन का मान। |
|

### getMarginType() {#getMarginType--}
```
public final int getMarginType()
```


प्राप्त करता है `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`। इस प्रॉपर्टी को नया मान सेट करने से सभी मार्जिन स्वचालित रूप से उनके डिफ़ॉल्ट मान (शून्य) पर लौट आते हैं।

डिफ़ॉल्ट मान है `[MarginType.Absolute](../../com.groupdocs.watermark.watermarks/margintype#Absolute)`


**Returns:**
int - वह मान जो निर्दिष्ट करता है कि मार्जिन की व्याख्या कैसे की जानी चाहिए।

### setMarginType(int value) {#setMarginType-int-}
```
public final void setMarginType(int value)
```


सेट करता है `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`। इस प्रॉपर्टी को नया मान सेट करने से सभी मार्जिन स्वचालित रूप से उनके डिफ़ॉल्ट मान (शून्य) पर लौट आते हैं।

डिफ़ॉल्ट मान है `[MarginType.Absolute](../../com.groupdocs.watermark.watermarks/margintype#Absolute)`


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | मार्जिन की व्याख्या कैसे की जानी चाहिए, यह निर्दिष्ट करने वाला मान। |
|

### getLeft() {#getLeft--}
```
public final double getLeft()
```


बाएँ मार्जिन को प्राप्त करता है।


**Returns:**
double - पैरेंट के बाएँ बॉर्डर से क्षैतिज ऑफ़सेट।

### setLeft(double value) {#setLeft-double-}
```
public final void setLeft(double value)
```


बाएँ मार्जिन को सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | double | पैरेंट के बाएँ किनारे से क्षैतिज ऑफ़सेट। |
|

### getRight() {#getRight--}
```
public final double getRight()
```


दाएँ मार्जिन को प्राप्त करता है।


**Returns:**
डबल - पैरेंट के दाएँ किनारे से क्षैतिज ऑफ़सेट।

### setRight(double value) {#setRight-double-}
```
public final void setRight(double value)
```


दाएँ मार्जिन को सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | double | पैरेंट के दाएँ किनारे से क्षैतिज ऑफ़सेट। |
|

### getTop() {#getTop--}
```
public final double getTop()
```


ऊपरी मार्जिन को प्राप्त करता है।


**Returns:**
डबल - पैरेंट के शीर्ष किनारे से क्षैतिज ऑफ़सेट।

### setTop(double value) {#setTop-double-}
```
public final void setTop(double value)
```


ऊपरी मार्जिन को सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | double | पैरेंट के शीर्ष किनारे से क्षैतिज ऑफ़सेट। |
|

### getBottom() {#getBottom--}
```
public final double getBottom()
```


निचले मार्जिन को प्राप्त करता है।


**Returns:**
डबल - पैरेंट के नीचे किनारे से क्षैतिज ऑफ़सेट।

### setBottom(double value) {#setBottom-double-}
```
public final void setBottom(double value)
```


निचले मार्जिन को सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | double | पैरेंट के नीचे किनारे से क्षैतिज ऑफ़सेट। |
|

