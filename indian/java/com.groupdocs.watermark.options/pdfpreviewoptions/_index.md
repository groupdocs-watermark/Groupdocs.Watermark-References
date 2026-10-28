---
title: "PdfPreviewOptions"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "PDF दस्तावेज़ के पूर्वावलोकन निर्माण के लिए आवश्यकताओं और स्ट्रीम प्रतिनिधियों को सेट करने के विकल्प प्रदान करता है।"
type: docs
weight: 31
url: /hi/java/com.groupdocs.watermark.options/pdfpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class PdfPreviewOptions extends PreviewOptions
```

PDF दस्तावेज़ के पूर्वावलोकन निर्माण के लिए आवश्यकताओं और स्ट्रीम प्रतिनिधियों को सेट करने के विकल्प प्रदान करता है।

## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [PdfPreviewOptions(ICreatePageStream createPageStream)](#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` क्लास का नया उदाहरण प्रारंभ करता है जिससे आउटपुट स्ट्रीम बंद हो जाती है। |
|
|  | [PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` क्लास का नया उदाहरण प्रारंभ करता है जिससे आउटपुट स्ट्रीम क्लाइंट को आगे उपयोग के लिए वापस किया जाता है। |
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
|  | [setResolution(int value)](#setResolution-int-) | जनरेट की गई छवियों के लिए रिज़ॉल्यूशन सेट करता है, डॉट्स प्रति इंच में। |
|
### PdfPreviewOptions(ICreatePageStream createPageStream) {#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PdfPreviewOptions(ICreatePageStream createPageStream)
```


`[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` क्लास का नया उदाहरण प्रारंभ करता है जिससे आउटपुट स्ट्रीम बंद हो जाती है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | एक विशिष्ट पृष्ठ प्रीव्यू के लिए स्ट्रीम बनाता है। |
|

### PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


`[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` क्लास का नया उदाहरण प्रारंभ करता है जिससे आउटपुट स्ट्रीम क्लाइंट को आगे उपयोग के लिए वापस किया जाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | एक विशिष्ट पृष्ठ प्रीव्यू के लिए स्ट्रीम बनाता है। |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | सूचित करता है कि पृष्ठ प्रीव्यू जनरेशन समाप्त हो गया है और आउटपुट स्ट्रीम प्राप्त करता है। |
|

### DefaultResolution {#DefaultResolution}
```
public static final int DefaultResolution
```


डॉट्स प्रति इंच में डिफ़ॉल्ट रिज़ॉल्यूशन।


### getResolution() {#getResolution--}
```
public final int getResolution()
```


जनरेट की गई छवियों के लिए रिज़ॉल्यूशन प्राप्त करता है, डॉट्स प्रति इंच में।


**Returns:**
int - उत्पन्न छवियों के लिए रिज़ॉल्यूशन, डॉट्स प्रति इंच में।

<br />

*** ** * ** ***

डिफ़ॉल्ट मान 150 है।

<br />


### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


जनरेट की गई छवियों के लिए रिज़ॉल्यूशन सेट करता है, डॉट्स प्रति इंच में।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | जनरेट की गई छवियों के लिए रिज़ॉल्यूशन, डॉट्स प्रति इंच में। |

<br />

*** ** * ** ***

डिफ़ॉल्ट मान 150 है।

<br />

|

