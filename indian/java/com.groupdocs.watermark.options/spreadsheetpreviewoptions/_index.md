---
title: "SpreadsheetPreviewOptions"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "स्प्रेडशीट दस्तावेज़ के पूर्वावलोकन निर्माण के लिए आवश्यकताओं और स्ट्रीम डेलीगेट्स सेट करने के विकल्प प्रदान करता है।"
type: docs
weight: 52
url: /hi/java/com.groupdocs.watermark.options/spreadsheetpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class SpreadsheetPreviewOptions extends PreviewOptions
```

स्प्रेडशीट दस्तावेज़ के पूर्वावलोकन निर्माण के लिए आवश्यकताओं और स्ट्रीम डेलीगेट्स सेट करने के विकल्प प्रदान करता है।

## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [SpreadsheetPreviewOptions(ICreatePageStream createPageStream)](#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | नया उदाहरण प्रारंभ करता है `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` क्लास का, जिससे आउटपुट स्ट्रीम बंद हो जाता है। |
|
|  | [SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | नया उदाहरण प्रारंभ करता है `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` क्लास का, जिससे आउटपुट स्ट्रीम क्लाइंट को आगे उपयोग के लिए वापस किया जाता है। |
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
|  | [getOnlyDataArea()](#getOnlyDataArea--) | हेडर, फुटर, मार्जिन के बिना केवल डेटा क्षेत्र को रेंडर करने के लिए फ़्लैग प्राप्त करता है। |
|
|  | [setOnlyDataArea(boolean value)](#setOnlyDataArea-boolean-) | हेडर, फुटर, मार्जिन के बिना केवल डेटा क्षेत्र को रेंडर करने के लिए फ़्लैग सेट करता है। |
|
### SpreadsheetPreviewOptions(ICreatePageStream createPageStream) {#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public SpreadsheetPreviewOptions(ICreatePageStream createPageStream)
```


नया उदाहरण प्रारंभ करता है `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` क्लास का, जिससे आउटपुट स्ट्रीम बंद हो जाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | एक विशिष्ट पृष्ठ प्रीव्यू के लिए स्ट्रीम बनाता है। |
|

### SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


नया उदाहरण प्रारंभ करता है `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` क्लास का, जिससे आउटपुट स्ट्रीम क्लाइंट को आगे उपयोग के लिए वापस किया जाता है।


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

डिफ़ॉल्ट मान 96 है।

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

डिफ़ॉल्ट मान 96 है।

<br />

|

### getOnlyDataArea() {#getOnlyDataArea--}
```
public final boolean getOnlyDataArea()
```


हेडर, फुटर, मार्जिन के बिना केवल डेटा क्षेत्र को रेंडर करने के लिए फ़्लैग प्राप्त करता है।


**Returns:**
boolean - हेडर, फुटर, मार्जिन के बिना केवल डेटा क्षेत्र को रेंडर करने के लिए फ़्लैग।

<br />

*** ** * ** ***

यह फ़्लैग पूरे वर्कशीट को एक पृष्ठ पर रेंडर करने का कारण बनता है। डिफ़ॉल्ट मान false है।

<br />


### setOnlyDataArea(boolean value) {#setOnlyDataArea-boolean-}
```
public final void setOnlyDataArea(boolean value)
```


हेडर, फुटर, मार्जिन के बिना केवल डेटा क्षेत्र को रेंडर करने के लिए फ़्लैग सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | हेडर, फुटर, मार्जिन के बिना केवल डेटा क्षेत्र को रेंडर करने के लिए फ़्लैग। |

<br />

*** ** * ** ***

यह फ़्लैग पूरे वर्कशीट को एक पृष्ठ पर रेंडर करने का कारण बनता है। डिफ़ॉल्ट मान false है।

<br />

|

