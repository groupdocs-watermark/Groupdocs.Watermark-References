---
title: "ImageThumbnailSearchCriteria"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "कंटेंट में छवियों को खोजने के लिए खोज मानदंड का प्रतिनिधित्व करता है।"
type: docs
weight: 33
url: /hi/java/com.groupdocs.watermark.search/imagethumbnailsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria), [com.groupdocs.watermark.search.ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria)
```
public class ImageThumbnailSearchCriteria extends ImageSearchCriteria
```

कंटेंट में छवियों को खोजने के लिए खोज मानदंड का प्रतिनिधित्व करता है।

<br />

*** ** * ** ***

यह सर्च क्राइटेरिया इमेज बाइनराइज़्ड थंबनेल का उपयोग इमेज सिमिलैरिटी की गणना के लिए करता है।

<br />


## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [ImageThumbnailSearchCriteria(String filePath)](#ImageThumbnailSearchCriteria-java.lang.String-) | `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` क्लास का नया इंस्टेंस निर्दिष्ट फ़ाइल पाथ के साथ इनिशियलाइज़ करता है। |
|
|  | [ImageThumbnailSearchCriteria(InputStream stream)](#ImageThumbnailSearchCriteria-java.io.InputStream-) | `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` क्लास का नया इंस्टेंस निर्दिष्ट स्ट्रीम के साथ इनिशियलाइज़ करता है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getThumbnailSize()](#getThumbnailSize--) | थंबनेल आकार प्राप्त करता है। |
|
|  | [setThumbnailSize(byte value)](#setThumbnailSize-byte-) | थंबनेल आकार सेट करता है। |
|
### ImageThumbnailSearchCriteria(String filePath) {#ImageThumbnailSearchCriteria-java.lang.String-}
```
public ImageThumbnailSearchCriteria(String filePath)
```


`[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` क्लास का नया इंस्टेंस निर्दिष्ट फ़ाइल पाथ के साथ इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | छवि लोड करने के लिए फ़ाइल पथ। |
|

### ImageThumbnailSearchCriteria(InputStream stream) {#ImageThumbnailSearchCriteria-java.io.InputStream-}
```
public ImageThumbnailSearchCriteria(InputStream stream)
```


`[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` क्लास का नया इंस्टेंस निर्दिष्ट स्ट्रीम के साथ इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | stream | java.io.InputStream | छवि लोड करने के लिए स्ट्रीम। |
|

### getThumbnailSize() {#getThumbnailSize--}
```
public final byte getThumbnailSize()
```


थंबनेल आकार प्राप्त करता है।


**Returns:**
byte - डिफ़ॉल्ट रूप से 32X32 थंबनेल उपयोग किया जाएगा।

### setThumbnailSize(byte value) {#setThumbnailSize-byte-}
```
public final void setThumbnailSize(byte value)
```


थंबनेल आकार सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | byte | डिफ़ॉल्ट रूप से 32X32 थंबनेल उपयोग किया जाएगा। |
|

