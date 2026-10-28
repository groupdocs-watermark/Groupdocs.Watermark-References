---
title: "PresentationPreviewOptions"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "Presentation दस्तावेज़ के पूर्वावलोकन निर्माण के लिए आवश्यकताओं और स्ट्रीम प्रतिनिधियों को सेट करने के विकल्प प्रदान करता है।"
type: docs
weight: 12
url: /hi/java/com.groupdocs.watermark/presentationpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class PresentationPreviewOptions extends PreviewOptions
```

Presentation दस्तावेज़ के पूर्वावलोकन निर्माण के लिए आवश्यकताओं और स्ट्रीम प्रतिनिधियों को सेट करने के विकल्प प्रदान करता है।

## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [PresentationPreviewOptions(ICreatePageStream createPageStream)](#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | एक नया इंस्टेंस प्रारंभ करता है `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` क्लास का, जिससे आउटपुट स्ट्रीम बंद हो जाता है। |
|
|  | [PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | एक नया इंस्टेंस प्रारंभ करता है `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` क्लास का, जिससे आउटपुट स्ट्रीम क्लाइंट को आगे उपयोग के लिए वापस किया जाता है। |
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
|  | [setResolution(long value)](#setResolution-long-) | जनरेट की गई छवियों के लिए रिज़ॉल्यूशन सेट करता है, डॉट्स प्रति इंच में। |
|
### PresentationPreviewOptions(ICreatePageStream createPageStream) {#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PresentationPreviewOptions(ICreatePageStream createPageStream)
```


एक नया इंस्टेंस प्रारंभ करता है `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` क्लास का, जिससे आउटपुट स्ट्रीम बंद हो जाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | एक विशिष्ट पृष्ठ प्रीव्यू के लिए स्ट्रीम बनाता है। |
|

### PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


एक नया इंस्टेंस प्रारंभ करता है `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` क्लास का, जिससे आउटपुट स्ट्रीम क्लाइंट को आगे उपयोग के लिए वापस किया जाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | एक विशिष्ट पृष्ठ प्रीव्यू के लिए स्ट्रीम बनाता है। |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | सूचित करता है कि पृष्ठ प्रीव्यू जनरेशन समाप्त हो गया है और आउटपुट स्ट्रीम प्राप्त करता है। |
|

### DefaultResolution {#DefaultResolution}
```
public static final long DefaultResolution
```


डॉट्स प्रति इंच में डिफ़ॉल्ट रिज़ॉल्यूशन।


### getResolution() {#getResolution--}
```
public final long getResolution()
```


जनरेट की गई छवियों के लिए रिज़ॉल्यूशन प्राप्त करता है, डॉट्स प्रति इंच में।


**Returns:**
long - जनरेट की गई छवियों के लिए रिज़ॉल्यूशन, डॉट्स प्रति इंच में।

### setResolution(long value) {#setResolution-long-}
```
public final void setResolution(long value)
```


जनरेट की गई छवियों के लिए रिज़ॉल्यूशन सेट करता है, डॉट्स प्रति इंच में।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | long | जनरेट की गई छवियों के लिए रिज़ॉल्यूशन, डॉट्स प्रति इंच में। |
|

