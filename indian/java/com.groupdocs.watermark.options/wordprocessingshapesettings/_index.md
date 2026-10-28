---
title: "WordProcessingShapeSettings"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "वर्ड दस्तावेज़ के लिए आकार वॉटरमार्क पर लागू किए जा सकने वाले सेटिंग्स का प्रतिनिधित्व करता है।"
type: docs
weight: 71
url: /hi/java/com.groupdocs.watermark.options/wordprocessingshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class WordProcessingShapeSettings extends OfficeShapeSettings
```

वर्ड दस्तावेज़ के लिए आकार वॉटरमार्क पर लागू किए जा सकने वाले सेटिंग्स का प्रतिनिधित्व करता है।

## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [WordProcessingShapeSettings()](#WordProcessingShapeSettings--) | `[WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings)` क्लास का नया उदाहरण प्रारंभ करता है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [isLocked()](#isLocked--) | एक मान प्राप्त करता है जो दर्शाता है कि Word में आकार का संपादन प्रतिबंधित है या नहीं। |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | एक मान सेट करता है जो दर्शाता है कि Word में आकार का संपादन प्रतिबंधित है या नहीं। |
|
|  | [getLockType()](#getLockType--) | वॉटरमार्क लॉक प्रकार प्राप्त करता है। |
|
|  | [setLockType(int value)](#setLockType-int-) | वॉटरमार्क लॉक प्रकार सेट करता है। |
|
|  | [getPassword()](#getPassword--) | वॉटरमार्क को लॉक करने के लिए उपयोग किया गया पासवर्ड प्राप्त करता है। |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | वॉटरमार्क को लॉक करने के लिए उपयोग किया गया पासवर्ड सेट करता है। |
|
|  | [getPageNumbers()](#getPageNumbers--) | वॉटरमार्क जोड़ने के लिए पृष्ठ संख्याएँ प्राप्त करता है। |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | वॉटरमार्क जोड़ने के लिए पृष्ठ संख्याएँ सेट करता है। |
|
### WordProcessingShapeSettings() {#WordProcessingShapeSettings--}
```
public WordProcessingShapeSettings()
```


`[WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings)` क्लास का नया उदाहरण प्रारंभ करता है।


### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


एक मान प्राप्त करता है जो दर्शाता है कि Word में आकार का संपादन प्रतिबंधित है या नहीं।


**Returns:**
boolean - यदि मान true है, तो आकार का संपादन प्रतिबंधित होगा। डिफ़ॉल्ट रूप से, मान false है, और आकार को Word में संपादित किया जा सकता है।

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


एक मान सेट करता है जो दर्शाता है कि Word में आकार का संपादन प्रतिबंधित है या नहीं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | यदि मान true है, तो आकार संपादन प्रतिबंधित होगा। डिफ़ॉल्ट रूप से, मान false है, आकार को Word में संपादित किया जा सकता है। |
|

### getLockType() {#getLockType--}
```
public final int getLockType()
```


वॉटरमार्क लॉक प्रकार प्राप्त करता है।


**Returns:**
int - वॉटरमार्क लॉक प्रकार `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)` का।

### setLockType(int value) {#setLockType-int-}
```
public final void setLockType(int value)
```


वॉटरमार्क लॉक प्रकार सेट करता है।

मान `[WordProcessingLockType.AllowOnlyFormFields](../../com.groupdocs.watermark.options/wordprocessinglocktype#AllowOnlyFormFields)` के साथ उपयोग नहीं किया जा सकता है।
प्रकार `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` का एक ऑब्जेक्ट।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | int | वॉटरमार्क लॉक प्रकार `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)` का। |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


वॉटरमार्क को लॉक करने के लिए उपयोग किया गया पासवर्ड प्राप्त करता है।


**Returns:**
java.lang.String - वॉटरमार्क को लॉक करने के लिए उपयोग किया गया पासवर्ड।

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


वॉटरमार्क को लॉक करने के लिए उपयोग किया गया पासवर्ड सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | वॉटरमार्क को लॉक करने के लिए उपयोग किया गया पासवर्ड। |
|

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


वॉटरमार्क जोड़ने के लिए पृष्ठ संख्याएँ प्राप्त करता है।


**Returns:**
int[] - वॉटरमार्क जोड़ने के लिए पृष्ठ संख्याएँ।

<br />

*** ** * ** ***

सभी संख्याएँ 1 से बड़ी या बराबर होनी चाहिए। यह प्रॉपर्टी केवल तब उपयोग होती है जब दस्तावेज़ में वॉटरमार्क जोड़ा जाता है। यदि यह मान null है, तो वॉटरमार्क सभी पृष्ठों में जोड़ा जाता है।

<br />


### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


वॉटरमार्क जोड़ने के लिए पृष्ठ संख्याएँ सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int[] | वॉटरमार्क जोड़ने के लिए पृष्ठ संख्याएँ। |

<br />

*** ** * ** ***

सभी संख्याएँ 1 से बड़ी या बराबर होनी चाहिए। यह प्रॉपर्टी केवल तब उपयोग होती है जब दस्तावेज़ में वॉटरमार्क जोड़ा जाता है। यदि यह मान null है, तो वॉटरमार्क सभी पृष्ठों में जोड़ा जाता है।

<br />

|

