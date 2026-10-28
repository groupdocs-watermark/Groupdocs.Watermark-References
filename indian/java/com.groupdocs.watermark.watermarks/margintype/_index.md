---
title: "MarginType"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "मार्जिन मानों की व्याख्या कैसे की जानी चाहिए, यह निर्दिष्ट करता है।"
type: docs
weight: 14
url: /hi/java/com.groupdocs.watermark.watermarks/margintype/
---
**Inheritance:**
java.lang.Object
```
public final class MarginType
```

मार्जिन मानों की व्याख्या कैसे की जानी चाहिए, यह निर्दिष्ट करता है।

## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
|  | [Absolute](#Absolute) | मार्जिन मान को कंटेंट यूनिट्स में मापा जाता है। |
|
|  | [RelativeToParentDimensions](#RelativeToParentDimensions) | मार्जिन मान को उपयुक्त पैरेंट आयाम के हिस्से के रूप में व्याख्यायित किया जाना चाहिए। |
|
|  | [RelativeToParentMinDimension](#RelativeToParentMinDimension) | मार्जिन मान को पैरेंट न्यूनतम आयाम के हिस्से के रूप में व्याख्यायित किया जाना चाहिए। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [toString(int value)](#toString-int-) | `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` मान का स्ट्रिंग प्रतिनिधित्व लौटाता है। |
|
|  | [parse(String value)](#parse-java.lang.String-) | एक स्ट्रिंग को `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` एनेमरेशन मान में पार्स करता है। |
|
### Absolute {#Absolute}
```
public static final int Absolute
```


मार्जिन मान को कंटेंट यूनिट्स में मापा जाता है।


### RelativeToParentDimensions {#RelativeToParentDimensions}
```
public static final int RelativeToParentDimensions
```


मार्जिन मान को उपयुक्त पैरेंट आयाम के हिस्से के रूप में व्याख्यायित किया जाना चाहिए।


बाएँ और दाएँ मार्जिन पैरेंट की चौड़ाई के सापेक्ष होते हैं,
ऊपर और नीचे के मार्जिन पैरेंट की ऊँचाई के सापेक्ष होते हैं।
यदि यह प्रकार चुना जाता है, तो मार्जिन मान 0.0 और 1.0 के बीच होना चाहिए।


### RelativeToParentMinDimension {#RelativeToParentMinDimension}
```
public static final int RelativeToParentMinDimension
```


मार्जिन मान को पैरेंट न्यूनतम आयाम के हिस्से के रूप में व्याख्यायित किया जाना चाहिए।


यदि यह प्रकार चुना जाता है, तो मार्जिन मान 0.0 और 1.0 के बीच होना चाहिए।


### toString(int value) {#toString-int-}
```
public static final String toString(int value)
```


`[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` मान का स्ट्रिंग प्रतिनिधित्व लौटाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | परिवर्तित करने के लिए मान। |
|

**Returns:**
java.lang.String - `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` मान का स्ट्रिंग प्रतिनिधित्व।

### parse(String value) {#parse-java.lang.String-}
```
public static final int parse(String value)
```


एक स्ट्रिंग को `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` एनेमरेशन मान में पार्स करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | पार्स करने के लिए स्ट्रिंग। |
|

**Returns:**
int - `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` एनेमरेशन मान।

