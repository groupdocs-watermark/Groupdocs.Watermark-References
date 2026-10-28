---
title: "WordProcessingPreviewOptions"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "वर्डप्रोसेसिंग दस्तावेज़ के पूर्वावलोकन निर्माण के लिए आवश्यकताओं और स्ट्रीम डेलीगेट्स सेट करने के विकल्प प्रदान करता है।"
type: docs
weight: 69
url: /hi/java/com.groupdocs.watermark.options/wordprocessingpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class WordProcessingPreviewOptions extends PreviewOptions
```

वर्डप्रोसेसिंग दस्तावेज़ के पूर्वावलोकन निर्माण के लिए आवश्यकताओं और स्ट्रीम डेलीगेट्स सेट करने के विकल्प प्रदान करता है।

## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [WordProcessingPreviewOptions(ICreatePageStream createPageStream)](#WordProcessingPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | `[WordProcessingPreviewOptions](../../com.groupdocs.watermark.options/wordprocessingpreviewoptions)` क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है जिससे आउटपुट स्ट्रीम बंद हो जाता है। |
|
|  | [WordProcessingPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#WordProcessingPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | `[WordProcessingPreviewOptions](../../com.groupdocs.watermark.options/wordprocessingpreviewoptions)` क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है जिससे आउटपुट स्ट्रीम आगे के उपयोग के लिए क्लाइंट को वापस किया जाता है। |
|
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
|  | [DefaultResolution](#DefaultResolution) | डॉट्स प्रति इंच में डिफ़ॉल्ट रिज़ॉल्यूशन। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getResolution()](#getResolution--) | जनरेट की गई छवियों के लिए रिज़ॉल्यूशन प्राप्त करता है, डॉट्स प्रति इंच में। |
|
|  | [setResolution(float value)](#setResolution-float-) | जनरेट की गई छवियों के लिए रिज़ॉल्यूशन सेट करता है, डॉट्स प्रति इंच में। |
|
### WordProcessingPreviewOptions(ICreatePageStream createPageStream) {#WordProcessingPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public WordProcessingPreviewOptions(ICreatePageStream createPageStream)
```


`[WordProcessingPreviewOptions](../../com.groupdocs.watermark.options/wordprocessingpreviewoptions)` क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है जिससे आउटपुट स्ट्रीम बंद हो जाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | एक विशिष्ट पृष्ठ प्रीव्यू के लिए स्ट्रीम बनाता है। |
|

### WordProcessingPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#WordProcessingPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public WordProcessingPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


`[WordProcessingPreviewOptions](../../com.groupdocs.watermark.options/wordprocessingpreviewoptions)` क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है जिससे आउटपुट स्ट्रीम आगे के उपयोग के लिए क्लाइंट को वापस किया जाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | एक विशिष्ट पृष्ठ प्रीव्यू के लिए स्ट्रीम बनाता है। |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | सूचित करता है कि पृष्ठ प्रीव्यू जनरेशन समाप्त हो गया है और आउटपुट स्ट्रीम प्राप्त करता है। |
|

### DefaultResolution {#DefaultResolution}
```
public static final float DefaultResolution
```


डॉट्स प्रति इंच में डिफ़ॉल्ट रिज़ॉल्यूशन।


### getResolution() {#getResolution--}
```
public final float getResolution()
```


जनरेट की गई छवियों के लिए रिज़ॉल्यूशन प्राप्त करता है, डॉट्स प्रति इंच में।


**Returns:**
float - उत्पन्न छवियों के लिए रिज़ॉल्यूशन, डॉट्स प्रति इंच में।

<br />

*** ** * ** ***

डिफ़ॉल्ट मान 96 है।

<br />


### setResolution(float value) {#setResolution-float-}
```
public final void setResolution(float value)
```


जनरेट की गई छवियों के लिए रिज़ॉल्यूशन सेट करता है, डॉट्स प्रति इंच में।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | float | जनरेट की गई छवियों के लिए रिज़ॉल्यूशन, डॉट्स प्रति इंच में। |

<br />

*** ** * ** ***

डिफ़ॉल्ट मान 96 है।

<br />

|

