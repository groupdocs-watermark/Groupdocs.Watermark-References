---
title: "WatermarkerSettings"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "Watermarker व्यवहार को अनुकूलित करने के लिए सेटिंग्स को परिभाषित करता है।"
type: docs
weight: 15
url: /hi/java/com.groupdocs.watermark/watermarkersettings/
---
**Inheritance:**
java.lang.Object
```
public final class WatermarkerSettings
```

Watermarker व्यवहार को अनुकूलित करने के लिए सेटिंग्स को परिभाषित करता है।

## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [WatermarkerSettings()](#WatermarkerSettings--) | का नया उदाहरण प्रारंभ करता है |
WatermarkerSettings
क्लास।
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getSearchableObjects()](#getSearchableObjects--) | प्राप्त करता है |
SearchableObjects
जो वॉटरमार्क खोज में शामिल किए जाने हैं।
|
|  | [setSearchableObjects(SearchableObjects value)](#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-) | सेट करता है |
SearchableObjects
जो वॉटरमार्क खोज में शामिल किए जाने हैं।
|
|  | [getLogger()](#getLogger--) | वॉटरमार्किंग के दौरान घटनाओं और त्रुटियों को लॉग करने के लिए उपयोग किए जाने वाले लॉगर को प्राप्त करता है। |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.watermark.options.ILogger-) | वॉटरमार्किंग के दौरान घटनाओं और त्रुटियों को लॉग करने के लिए उपयोग किए जाने वाले लॉगर को सेट करता है। |
|
| [logError(WatermarkException exception, String format, Object[] args)](#logError-com.groupdocs.watermark.exceptions.WatermarkException-java.lang.String-java.lang.Object...-) |  |
| [logError(WatermarkException exception)](#logError-com.groupdocs.watermark.exceptions.WatermarkException-) |  |
| [logWarning(String format, Object[] args)](#logWarning-java.lang.String-java.lang.Object...-) |  |
| [logTrace(String format, Object[] args)](#logTrace-java.lang.String-java.lang.Object...-) |  |
### WatermarkerSettings() {#WatermarkerSettings--}
```
public WatermarkerSettings()
```


का नया उदाहरण प्रारंभ करता है
WatermarkerSettings
क्लास।


### getSearchableObjects() {#getSearchableObjects--}
```
public final SearchableObjects getSearchableObjects()
```


प्राप्त करता है
SearchableObjects
जो वॉटरमार्क खोज में शामिल किए जाने हैं।


**Returns:**
[SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) - The  SearchableObjects  that are to be included in a watermark search.

### setSearchableObjects(SearchableObjects value) {#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-}
```
public final void setSearchableObjects(SearchableObjects value)
```


सेट करता है
SearchableObjects
जो वॉटरमार्क खोज में शामिल किए जाने हैं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) | वॉटरमार्क खोज में शामिल किए जाने वाले  SearchableObjects  । |
|

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


वॉटरमार्किंग के दौरान घटनाओं और त्रुटियों को लॉग करने के लिए उपयोग किए जाने वाले लॉगर को प्राप्त करता है।


**Returns:**
[ILogger](../../com.groupdocs.watermark.options/ilogger) - An instance of class that implements `[ILogger](../../com.groupdocs.watermark.options/ilogger)` interface.

### setLogger(ILogger value) {#setLogger-com.groupdocs.watermark.options.ILogger-}
```
public final void setLogger(ILogger value)
```


वॉटरमार्किंग के दौरान घटनाओं और त्रुटियों को लॉग करने के लिए उपयोग किए जाने वाले लॉगर को सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [ILogger](../../com.groupdocs.watermark.options/ilogger) | एक क्लास का उदाहरण जो `[ILogger](../../com.groupdocs.watermark.options/ilogger)` इंटरफ़ेस को लागू करता है। |
|

### logError(WatermarkException exception, String format, Object[] args) {#logError-com.groupdocs.watermark.exceptions.WatermarkException-java.lang.String-java.lang.Object...-}
```
public final void logError(WatermarkException exception, String format, Object[] args)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| exception | [WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception) |  |
| फ़ॉर्मेट | java.lang.String |  |
| आर्ग्स | java.lang.Object[] |  |

### logError(WatermarkException exception) {#logError-com.groupdocs.watermark.exceptions.WatermarkException-}
```
public final void logError(WatermarkException exception)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| exception | [WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception) |  |

### logWarning(String format, Object[] args) {#logWarning-java.lang.String-java.lang.Object...-}
```
public final void logWarning(String format, Object[] args)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ॉर्मेट | java.lang.String |  |
| आर्ग्स | java.lang.Object[] |  |

### logTrace(String format, Object[] args) {#logTrace-java.lang.String-java.lang.Object...-}
```
public final void logTrace(String format, Object[] args)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ॉर्मेट | java.lang.String |  |
| आर्ग्स | java.lang.Object[] |  |

