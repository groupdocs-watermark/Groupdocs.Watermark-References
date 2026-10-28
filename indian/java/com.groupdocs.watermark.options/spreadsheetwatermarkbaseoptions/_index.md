---
title: "SpreadsheetWatermarkBaseOptions"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "स्प्रेडशीट दस्तावेज़ में वॉटरमार्क जोड़ने के विकल्पों के लिए बेस क्लास।"
type: docs
weight: 56
url: /hi/java/com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)
```
public abstract class SpreadsheetWatermarkBaseOptions extends SpreadsheetWatermarkOptions
```

स्प्रेडशीट दस्तावेज़ में वॉटरमार्क जोड़ने के विकल्पों के लिए बेस क्लास।

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [isLocked()](#isLocked--) | Excel में आकार (shape) के संपादन को प्रतिबंधित करने का संकेत देने वाला मान प्राप्त करता है। |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Excel में आकार के संपादन को प्रतिबंधित करने का संकेत देने वाला मान सेट करता है। |
|
|  | [getName()](#getName--) | आकार का नाम प्राप्त करता है। |
|
|  | [setName(String value)](#setName-java.lang.String-) | आकार का नाम सेट करता है। |
|
|  | [getAlternativeText()](#getAlternativeText--) | आकार से जुड़ा वर्णनात्मक (वैकल्पिक) पाठ प्राप्त करता है। |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | आकार से जुड़ा वर्णनात्मक (वैकल्पिक) पाठ सेट करता है। |
|
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Excel में आकार (shape) के संपादन को प्रतिबंधित करने का संकेत देने वाला मान प्राप्त करता है।


**Returns:**
boolean - यदि मान true है, तो आकार का संपादन प्रतिबंधित होगा। डिफ़ॉल्ट रूप से, मान false है, आकार को Excel में संपादित किया जा सकता है।

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Excel में आकार के संपादन को प्रतिबंधित करने का संकेत देने वाला मान सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | यदि मान true है, तो आकार का संपादन प्रतिबंधित होगा। डिफ़ॉल्ट रूप से, मान false है, आकार को Excel में संपादित किया जा सकता है। |
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

