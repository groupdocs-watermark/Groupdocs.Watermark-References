---
title: "WordProcessingWatermarkHeaderFooterOptions"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "Word सेक्शन हेडर/फ़ूटर में वॉटरमार्क जोड़ते समय विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 74
url: /hi/java/com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkHeaderFooterOptions extends WordProcessingWatermarkBaseOptions
```

Word सेक्शन हेडर/फ़ूटर में वॉटरमार्क जोड़ते समय विकल्पों का प्रतिनिधित्व करता है।

## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [WordProcessingWatermarkHeaderFooterOptions()](#WordProcessingWatermarkHeaderFooterOptions--) | `[WordProcessingWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions)` क्लास का नया उदाहरण आरंभ करता है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getSectionIndex()](#getSectionIndex--) | वॉटरमार्क जोड़ने के लिए अनुभाग का सूचकांक प्राप्त करता है। |
|
|  | [setSectionIndex(int value)](#setSectionIndex-int-) | वॉटरमार्क जोड़ने के लिए अनुभाग का सूचकांक सेट करता है। |
|
|  | [getHeaderFooterType()](#getHeaderFooterType--) | वॉटरमार्क जोड़ने के लिए हेडर या फुटर के प्रकार की पहचान करने वाला मान प्राप्त करता है। |
|
|  | [setHeaderFooterType(int value)](#setHeaderFooterType-int-) | वॉटरमार्क जोड़ने के लिए हेडर या फुटर के प्रकार की पहचान करने वाले मान को सेट करता है। |
|
### WordProcessingWatermarkHeaderFooterOptions() {#WordProcessingWatermarkHeaderFooterOptions--}
```
public WordProcessingWatermarkHeaderFooterOptions()
```


`[WordProcessingWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions)` क्लास का नया उदाहरण आरंभ करता है।


### getSectionIndex() {#getSectionIndex--}
```
public final int getSectionIndex()
```


वॉटरमार्क जोड़ने के लिए अनुभाग का सूचकांक प्राप्त करता है।


**Returns:**
int - वॉटरमार्क जोड़ने के लिए सेक्शन का इंडेक्स।

<br />

*** ** * ** ***

-1 means all sections.

<br />


### setSectionIndex(int value) {#setSectionIndex-int-}
```
public final void setSectionIndex(int value)
```


वॉटरमार्क जोड़ने के लिए अनुभाग का सूचकांक सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | वॉटरमार्क जोड़ने के लिए सेक्शन का इंडेक्स। |

<br />

*** ** * ** ***

-1 means all sections.

<br />

|

### getHeaderFooterType() {#getHeaderFooterType--}
```
public final int getHeaderFooterType()
```


वॉटरमार्क जोड़ने के लिए हेडर या फुटर के प्रकार की पहचान करने वाला मान प्राप्त करता है।


**Returns:**
int - वह मान जिसका प्रकार `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` है, जो वॉटरमार्क जोड़ने के लिए हेडर या फुटर के प्रकार की पहचान करता है।

### setHeaderFooterType(int value) {#setHeaderFooterType-int-}
```
public final void setHeaderFooterType(int value)
```


वॉटरमार्क जोड़ने के लिए हेडर या फुटर के प्रकार की पहचान करने वाले मान को सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | int | वह मान जिसका प्रकार `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` है, जो वॉटरमार्क जोड़ने के लिए हेडर या फुटर के प्रकार की पहचान करता है। |
|

