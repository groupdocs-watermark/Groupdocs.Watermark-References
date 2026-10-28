---
title: "ImageColorHistogramSearchCriteria"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "कंटेंट में छवियों को खोजने के लिए खोज मानदंड का प्रतिनिधित्व करता है।"
type: docs
weight: 30
url: /hi/java/com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria), [com.groupdocs.watermark.search.ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria)
```
public class ImageColorHistogramSearchCriteria extends ImageSearchCriteria
```

कंटेंट में छवियों को खोजने के लिए खोज मानदंड का प्रतिनिधित्व करता है।

<br />

*** ** * ** ***

यह खोज मानदंड छवि समानता की गणना के लिए इमेज रंग हिस्टोग्राम का उपयोग करता है।

<br />


## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [ImageColorHistogramSearchCriteria(String filePath)](#ImageColorHistogramSearchCriteria-java.lang.String-) | निर्दिष्ट फ़ाइल पथ के साथ `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` क्लास का एक नया उदाहरण प्रारंभ करता है। |
|
|  | [ImageColorHistogramSearchCriteria(InputStream stream)](#ImageColorHistogramSearchCriteria-java.io.InputStream-) | निर्दिष्ट स्ट्रीम के साथ `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` क्लास का एक नया उदाहरण प्रारंभ करता है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getBinsCount()](#getBinsCount--) | रंग हिस्टोग्राम बनाने के लिए उपयोग किए जाने वाले बिन्स की गिनती प्राप्त करता है। |
|
|  | [setBinsCount(byte value)](#setBinsCount-byte-) | रंग हिस्टोग्राम बनाने के लिए उपयोग किए जाने वाले बिन्स की गिनती सेट करता है। |
|
### ImageColorHistogramSearchCriteria(String filePath) {#ImageColorHistogramSearchCriteria-java.lang.String-}
```
public ImageColorHistogramSearchCriteria(String filePath)
```


निर्दिष्ट फ़ाइल पथ के साथ `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` क्लास का एक नया उदाहरण प्रारंभ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | छवि लोड करने के लिए फ़ाइल पथ। |
|

### ImageColorHistogramSearchCriteria(InputStream stream) {#ImageColorHistogramSearchCriteria-java.io.InputStream-}
```
public ImageColorHistogramSearchCriteria(InputStream stream)
```


निर्दिष्ट स्ट्रीम के साथ `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` क्लास का एक नया उदाहरण प्रारंभ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | stream | java.io.InputStream | छवि लोड करने के लिए स्ट्रीम। |
|

### getBinsCount() {#getBinsCount--}
```
public final byte getBinsCount()
```


रंग हिस्टोग्राम बनाने के लिए उपयोग किए जाने वाले बिन्स की गिनती प्राप्त करता है।


**Returns:**
byte - डिफ़ॉल्ट मान 10 है।

### setBinsCount(byte value) {#setBinsCount-byte-}
```
public final void setBinsCount(byte value)
```


रंग हिस्टोग्राम बनाने के लिए उपयोग किए जाने वाले बिन्स की गिनती सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | byte | डिफ़ॉल्ट मान 10 है। |
|

