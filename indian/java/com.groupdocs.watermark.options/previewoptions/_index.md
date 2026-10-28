---
title: "PreviewOptions"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "पूर्वावलोकन निर्माण के लिए आवश्यकताओं और स्ट्रीम डेलीगेट्स सेट करने के विकल्प प्रदान करता है।"
type: docs
weight: 47
url: /hi/java/com.groupdocs.watermark.options/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

पूर्वावलोकन निर्माण के लिए आवश्यकताओं और स्ट्रीम डेलीगेट्स सेट करने के विकल्प प्रदान करता है।

## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [PreviewOptions(ICreatePageStream createPageStream)](#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | एक नया उदाहरण प्रारंभ करता है `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` क्लास का जिससे आउटपुट स्ट्रीम बंद हो जाता है। |
|
|  | [PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | एक नया उदाहरण प्रारंभ करता है `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` क्लास का जिससे आउटपुट स्ट्रीम क्लाइंट को आगे उपयोग के लिए वापस किया जाता है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getWidth()](#getWidth--) | पृष्ठ पूर्वावलोकन की चौड़ाई प्राप्त करता है। |
|
|  | [setWidth(int value)](#setWidth-int-) | पृष्ठ पूर्वावलोकन की चौड़ाई सेट करता है। |
|
|  | [getHeight()](#getHeight--) | पृष्ठ पूर्वावलोकन की ऊँचाई प्राप्त करता है। |
|
|  | [setHeight(int value)](#setHeight-int-) | पृष्ठ पूर्वावलोकन की ऊँचाई सेट करता है। |
|
|  | [getPageNumbers()](#getPageNumbers--) | पूर्वावलोकन उत्पन्न करने के लिए पृष्ठ संख्याओं की एक सरणी प्राप्त करता है। |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | पूर्वावलोकन उत्पन्न करने के लिए पृष्ठ संख्याओं की एक सरणी सेट करता है। |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | पूर्वावलोकन छवि प्रारूप प्राप्त करता है। |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | पूर्वावलोकन छवि प्रारूप सेट करता है। |
|
|  | [getCreatePageStream()](#getCreatePageStream--) | पृष्ठ स्ट्रीम निर्माण क्लास का एक उदाहरण प्राप्त करता है। |
|
|  | [setCreatePageStream(ICreatePageStream value)](#setCreatePageStream-com.groupdocs.watermark.options.ICreatePageStream-) | पृष्ठ स्ट्रीम निर्माण क्लास का एक उदाहरण सेट करता है। |
|
|  | [getReleasePageStream()](#getReleasePageStream--) | पृष्ठ पूर्वावलोकन पूर्णता क्लास का एक उदाहरण प्राप्त करता है। |
|
|  | [setReleasePageStream(IReleasePageStream value)](#setReleasePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | पृष्ठ पूर्वावलोकन पूर्णता क्लास का एक उदाहरण सेट करता है। |
|
### PreviewOptions(ICreatePageStream createPageStream) {#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PreviewOptions(ICreatePageStream createPageStream)
```


एक नया उदाहरण प्रारंभ करता है `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` क्लास का जिससे आउटपुट स्ट्रीम बंद हो जाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | एक विशिष्ट पृष्ठ प्रीव्यू के लिए स्ट्रीम बनाता है। |
|

### PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


एक नया उदाहरण प्रारंभ करता है `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` क्लास का जिससे आउटपुट स्ट्रीम क्लाइंट को आगे उपयोग के लिए वापस किया जाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | एक विशिष्ट पृष्ठ प्रीव्यू के लिए स्ट्रीम बनाता है। |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | सूचित करता है कि पृष्ठ प्रीव्यू जनरेशन समाप्त हो गया है और आउटपुट स्ट्रीम प्राप्त करता है। |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


पृष्ठ पूर्वावलोकन की चौड़ाई प्राप्त करता है।


**Returns:**
int - पृष्ठ पूर्वावलोकन की चौड़ाई।

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


पृष्ठ पूर्वावलोकन की चौड़ाई सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | पृष्ठ पूर्वावलोकन की चौड़ाई। |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


पृष्ठ पूर्वावलोकन की ऊँचाई प्राप्त करता है।


**Returns:**
int - पृष्ठ पूर्वावलोकन की ऊँचाई।

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


पृष्ठ पूर्वावलोकन की ऊँचाई सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | पृष्ठ पूर्वावलोकन की ऊँचाई। |
|

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


पूर्वावलोकन उत्पन्न करने के लिए पृष्ठ संख्याओं की एक सरणी प्राप्त करता है।


**Returns:**
int[] - पूर्वावलोकन उत्पन्न करने के लिए पृष्ठ संख्याओं की सरणी।

### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


पूर्वावलोकन उत्पन्न करने के लिए पृष्ठ संख्याओं की एक सरणी सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int[] | पूर्वावलोकन उत्पन्न करने के लिए पृष्ठ संख्याओं की सरणी। |
|

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


पूर्वावलोकन छवि प्रारूप प्राप्त करता है।


**Returns:**
int - पूर्वावलोकन छवि प्रारूप।

### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


पूर्वावलोकन छवि प्रारूप सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | पूर्वावलोकन छवि प्रारूप। |
|

### getCreatePageStream() {#getCreatePageStream--}
```
public final ICreatePageStream getCreatePageStream()
```


पृष्ठ स्ट्रीम निर्माण क्लास का एक उदाहरण प्राप्त करता है।


**Returns:**
[ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) - The instance of the page stream creation class.

### setCreatePageStream(ICreatePageStream value) {#setCreatePageStream-com.groupdocs.watermark.options.ICreatePageStream-}
```
public final void setCreatePageStream(ICreatePageStream value)
```


पृष्ठ स्ट्रीम निर्माण क्लास का एक उदाहरण सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | पेज स्ट्रीम निर्माण क्लास का उदाहरण। |
|

### getReleasePageStream() {#getReleasePageStream--}
```
public final IReleasePageStream getReleasePageStream()
```


पृष्ठ पूर्वावलोकन पूर्णता क्लास का एक उदाहरण प्राप्त करता है।


**Returns:**
[IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) - The instance of the page preview completion delegate.

### setReleasePageStream(IReleasePageStream value) {#setReleasePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public final void setReleasePageStream(IReleasePageStream value)
```


पृष्ठ पूर्वावलोकन पूर्णता क्लास का एक उदाहरण सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | पेज प्रीव्यू पूर्णता डेलीगेट का उदाहरण। |
|

