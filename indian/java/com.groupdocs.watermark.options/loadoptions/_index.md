---
title: "LoadOptions"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "दस्तावेज़ लोड करते समय दस्तावेज़ लोड करने के विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 24
url: /hi/java/com.groupdocs.watermark.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

दस्तावेज़ लोड करते समय दस्तावेज़ लोड करने के विकल्पों का प्रतिनिधित्व करता है।

**Learn more:**

* [Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents)
* [Load from local disk](../https://docs.groupdocs.com/display/watermarkjava/Load+from+local+disk)
* [Load from stream](../https://docs.groupdocs.com/display/watermarkjava/Load+from+stream)
* [Load document of specific format](../https://docs.groupdocs.com/display/watermarkjava/Load+document+of+specific+format)
* [Load password-protected document](../https://docs.groupdocs.com/display/watermarkjava/Load+password-protected+document)

## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` क्लास का नया उदाहरण आरंभ करता है। |
|
|  | [LoadOptions(String password)](#LoadOptions-java.lang.String-) | `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` क्लास का नया उदाहरण निर्दिष्ट पासवर्ड के साथ आरंभ करता है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getPassword()](#getPassword--) | एन्क्रिप्टेड दस्तावेज़ खोलने के लिए पासवर्ड प्राप्त करता है। |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | एन्क्रिप्टेड दस्तावेज़ खोलने के लिए पासवर्ड सेट करता है। |
|
|  | [getFormatFamily()](#getFormatFamily--) | दस्तावेज़ का फ़ॉर्मेट परिवार प्राप्त करें, जो उसके प्रकार को दर्शाता है (उदा., Image, Pdf, Spreadsheet आदि)। |
|
|  | [setFormatFamily(int formatFamily)](#setFormatFamily-int-) | दस्तावेज़ का फ़ॉर्मेट परिवार सेट करें, जो उसके प्रकार को दर्शाता है (उदा., Image, Pdf, Spreadsheet आदि)। |
|
|  | [getFileType()](#getFileType--) | फ़ाइल का प्रकार प्राप्त करें, जो उसके प्रकार को दर्शाता है (उदा., docx, pdf, xlsx आदि)। |
|
|  | [setFileType(FileType fileType)](#setFileType-com.groupdocs.watermark.common.FileType-) | फ़ाइल का प्रकार सेट करें, जो उसके प्रकार को दर्शाता है (उदा., docx, pdf, xlsx आदि)। |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


`[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` क्लास का नया उदाहरण आरंभ करता है।


### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


`[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` क्लास का नया उदाहरण निर्दिष्ट पासवर्ड के साथ आरंभ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | पासवर्ड | java.lang.String | एन्क्रिप्टेड कंटेंट खोलने के लिए पासवर्ड। |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


एन्क्रिप्टेड दस्तावेज़ खोलने के लिए पासवर्ड प्राप्त करता है।


**Returns:**
java.lang.String - एन्क्रिप्टेड दस्तावेज़ खोलने के लिए पासवर्ड।

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


एन्क्रिप्टेड दस्तावेज़ खोलने के लिए पासवर्ड सेट करता है।

पासवर्ड null या खाली स्ट्रिंग हो सकता है। डिफ़ॉल्ट मान null है।
यदि सामग्री एन्क्रिप्टेड नहीं है, तो इसे null या खाली स्ट्रिंग पर सेट करें।

निम्नलिखित उदाहरण दिखाता है कि पासवर्ड से संरक्षित दस्तावेज़ को कैसे लोड करें।
>
> ````
> ```
>
>    LoadOptions loadOptions = new LoadOptions();
>    loadOptions.setPassword("pwd123");
>  
>    Watermarker watermarker = new Watermarker("D:\\doc.vsdx", loadOptions);
>    // ...
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | एन्क्रिप्टेड दस्तावेज़ खोलने के लिए पासवर्ड। |
|

### getFormatFamily() {#getFormatFamily--}
```
public int getFormatFamily()
```


दस्तावेज़ का फ़ॉर्मेट परिवार प्राप्त करें, जो उसके प्रकार को दर्शाता है (उदा., Image, Pdf, Spreadsheet आदि)।


**Returns:**
int - formatFamily फ़ाइल प्रकार।

### setFormatFamily(int formatFamily) {#setFormatFamily-int-}
```
public void setFormatFamily(int formatFamily)
```


दस्तावेज़ का फ़ॉर्मेट परिवार सेट करें, जो उसके प्रकार को दर्शाता है (उदा., Image, Pdf, Spreadsheet आदि)।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | formatFamily | int | फ़ाइल प्रकार। |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


फ़ाइल का प्रकार प्राप्त करें, जो उसके प्रकार को दर्शाता है (उदा., docx, pdf, xlsx आदि)।


**Returns:**
[FileType](../../com.groupdocs.watermark.common/filetype) - fileType The file type.

### setFileType(FileType fileType) {#setFileType-com.groupdocs.watermark.common.FileType-}
```
public void setFileType(FileType fileType)
```


फ़ाइल का प्रकार सेट करें, जो उसके प्रकार को दर्शाता है (उदा., docx, pdf, xlsx आदि)।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.watermark.common/filetype) | फ़ाइल प्रकार। |
|

