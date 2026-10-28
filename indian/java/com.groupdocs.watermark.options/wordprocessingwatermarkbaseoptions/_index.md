---
title: "WordProcessingWatermarkBaseOptions"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "Word दस्तावेज़ में वॉटरमार्क जोड़ने के विकल्पों के लिए बेस क्लास।"
type: docs
weight: 73
url: /hi/java/com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions)
```
public abstract class WordProcessingWatermarkBaseOptions extends WordProcessingWatermarkOptions
```

Word दस्तावेज़ में वॉटरमार्क जोड़ने के विकल्पों के लिए बेस क्लास।

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
|  | [getName()](#getName--) | आकार का नाम प्राप्त करता है। |
|
|  | [setName(String value)](#setName-java.lang.String-) | आकार का नाम सेट करता है। |
|
|  | [getAlternativeText()](#getAlternativeText--) | आकार से जुड़ा वर्णनात्मक (वैकल्पिक) पाठ प्राप्त करता है। |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | आकार से जुड़ा वर्णनात्मक (वैकल्पिक) पाठ सेट करता है। |
|
| [getEffects()](#getEffects--) |  |
| [setEffects(IWordProcessingWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-) |  |
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
int - वॉटरमार्क `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)` लॉक प्रकार।

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
|  | value | int | वॉटरमार्क `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)` लॉक प्रकार। |
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

### getName() {#getName--}
```
public final String getName()
```


आकार का नाम प्राप्त करता है।


**Returns:**
java.lang.String - आकार का नाम।

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


आकार का नाम सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | आकार का नाम। |
|

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


आकार से जुड़ा वर्णनात्मक (वैकल्पिक) पाठ प्राप्त करता है।


**Returns:**
java.lang.String - वह वर्णनात्मक (वैकल्पिक) पाठ जो एक आकार के साथ जुड़ा होगा।

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


आकार से जुड़ा वर्णनात्मक (वैकल्पिक) पाठ सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | वर्णनात्मक (वैकल्पिक) पाठ जो एक आकार के साथ जुड़ा होगा। |
|

### getEffects() {#getEffects--}
```
public final IWordProcessingWatermarkEffects getEffects()
```




**Returns:**
[IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects)
### setEffects(IWordProcessingWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-}
```
public final void setEffects(IWordProcessingWatermarkEffects value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects) |  |

