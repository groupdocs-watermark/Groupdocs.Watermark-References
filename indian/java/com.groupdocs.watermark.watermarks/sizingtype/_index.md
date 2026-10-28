---
title: "SizingType"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "वॉटरमार्क आकार की गणना कैसे की जानी चाहिए, यह निर्दिष्ट करता है।"
type: docs
weight: 16
url: /hi/java/com.groupdocs.watermark.watermarks/sizingtype/
---
**Inheritance:**
java.lang.Object
```
public final class SizingType
```

वॉटरमार्क आकार की गणना कैसे की जानी चाहिए, यह निर्दिष्ट करता है।

## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
|  | [Auto](#Auto) | वॉटरमार्क को उसकी सामग्री के अनुसार स्वचालित रूप से आकार देना चाहिए। |
|
|  | [Absolute](#Absolute) | वॉटरमार्क को एक सटीक `[Watermark.getWidth()](../../com.groupdocs.watermark/watermark#getWidth--)` पर आकार देना चाहिए। |
और `[Watermark.getHeight()](../../com.groupdocs.watermark/watermark#getHeight--)`।
|
|  | [ScaleToParentDimensions](#ScaleToParentDimensions) | वॉटरमार्क को पैरेंट आयामों के सापेक्ष स्केल किया जाना चाहिए, उपयोग करके |
निर्दिष्ट `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`।
|
|  | [ScaleToParentArea](#ScaleToParentArea) | वॉटरमार्क को पैरेंट क्षेत्र के सापेक्ष स्केल किया जाना चाहिए, निर्दिष्ट `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)` का उपयोग करके। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [toString(int value)](#toString-int-) | `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)` मान का स्ट्रिंग प्रतिनिधित्व लौटाता है। |
|
|  | [parse(String value)](#parse-java.lang.String-) | `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)` एनोमरेशन मान में स्ट्रिंग को पार्स करता है। |
|
### Auto {#Auto}
```
public static final int Auto
```


वॉटरमार्क को उसकी सामग्री के अनुसार स्वचालित रूप से आकार देना चाहिए।


### Absolute {#Absolute}
```
public static final int Absolute
```


वॉटरमार्क को एक सटीक `[Watermark.getWidth()](../../com.groupdocs.watermark/watermark#getWidth--)` पर आकार देना चाहिए।
और `[Watermark.getHeight()](../../com.groupdocs.watermark/watermark#getHeight--)`।


### ScaleToParentDimensions {#ScaleToParentDimensions}
```
public static final int ScaleToParentDimensions
```


वॉटरमार्क को पैरेंट आयामों के सापेक्ष स्केल किया जाना चाहिए, उपयोग करके
निर्दिष्ट `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`।


### ScaleToParentArea {#ScaleToParentArea}
```
public static final int ScaleToParentArea
```


वॉटरमार्क को पैरेंट क्षेत्र के सापेक्ष स्केल किया जाना चाहिए, निर्दिष्ट `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)` का उपयोग करके।


### toString(int value) {#toString-int-}
```
public static final String toString(int value)
```


`[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)` मान का स्ट्रिंग प्रतिनिधित्व लौटाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | परिवर्तित करने के लिए मान। |
|

**Returns:**
java.lang.String - `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)` मान का स्ट्रिंग प्रतिनिधित्व।

### parse(String value) {#parse-java.lang.String-}
```
public static final int parse(String value)
```


`[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)` एनोमरेशन मान में स्ट्रिंग को पार्स करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | पार्स करने के लिए स्ट्रिंग। |
|

**Returns:**
int - `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)` एनोमरेशन मान।

