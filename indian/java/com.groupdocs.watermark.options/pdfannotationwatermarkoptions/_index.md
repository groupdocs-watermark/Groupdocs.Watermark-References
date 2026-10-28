---
title: "PdfAnnotationWatermarkOptions"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "PDF दस्तावेज़ में एनोटेशन वॉटरमार्क जोड़ते समय वॉटरमार्क जोड़ने के विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 28
url: /hi/java/com.groupdocs.watermark.options/pdfannotationwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfAnnotationWatermarkOptions extends PdfWatermarkOptions
```

PDF दस्तावेज़ में एनोटेशन वॉटरमार्क जोड़ते समय वॉटरमार्क जोड़ने के विकल्पों का प्रतिनिधित्व करता है।

**Learn more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

निम्न उदाहरण दर्शाता है कि PDF दस्तावेज़ में छवि एनोटेशन वॉटरमार्क कैसे जोड़ें।
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.pdf", loadOptions);
>
>    ImageWatermark watermark = new ImageWatermark("D:\\icon.png");
>
>    PdfAnnotationWatermarkOptions options = new PdfAnnotationWatermarkOptions();
>    options.setPageIndex(-1); // default - all pages
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.pdf");
>    watermark.close();
>    watermarker.close();
>  
> ```
> ````


## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [PdfAnnotationWatermarkOptions()](#PdfAnnotationWatermarkOptions--) | एक नया उदाहरण आरंभ करता है `[PdfAnnotationWatermarkOptions](../../com.groupdocs.watermark.options/pdfannotationwatermarkoptions)` वर्ग का। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | वॉटरमार्क जोड़ने के लिए पृष्ठ सूचकांक प्राप्त करता है। |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | वॉटरमार्क जोड़ने के लिए पृष्ठ सूचकांक सेट करता है। |
|
|  | [getPrintOnly()](#getPrintOnly--) | ऐसी मान प्राप्त करें जो दर्शाता है कि एनोटेशन प्रिंट किया जाएगा, लेकिन PDF व्यूइंग एप्लिकेशन में प्रदर्शित नहीं होगा। |
|
|  | [setPrintOnly(boolean value)](#setPrintOnly-boolean-) | ऐसी मान सेट करें जो दर्शाता है कि एनोटेशन प्रिंट किया जाएगा, लेकिन PDF व्यूइंग एप्लिकेशन में प्रदर्शित नहीं होगा। |
|
### PdfAnnotationWatermarkOptions() {#PdfAnnotationWatermarkOptions--}
```
public PdfAnnotationWatermarkOptions()
```


एक नया उदाहरण आरंभ करता है `[PdfAnnotationWatermarkOptions](../../com.groupdocs.watermark.options/pdfannotationwatermarkoptions)` वर्ग का।


### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


वॉटरमार्क जोड़ने के लिए पृष्ठ सूचकांक प्राप्त करता है।


**Returns:**
int - वॉटरमार्क जोड़ने के लिए पृष्ठ सूचकांक।

<br />

*** ** * ** ***

-1 means all pages.

<br />


### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


वॉटरमार्क जोड़ने के लिए पृष्ठ सूचकांक सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | वॉटरमार्क जोड़ने के लिए पृष्ठ सूचकांक। |

<br />

*** ** * ** ***

-1 means all pages.

<br />

|

### getPrintOnly() {#getPrintOnly--}
```
public final boolean getPrintOnly()
```


ऐसी मान प्राप्त करें जो दर्शाता है कि एनोटेशन प्रिंट किया जाएगा, लेकिन PDF व्यूइंग एप्लिकेशन में प्रदर्शित नहीं होगा।


**Returns:**
boolean - वह मान जो दर्शाता है कि एनोटेशन प्रिंट किया जाएगा, लेकिन PDF व्यूइंग एप्लिकेशन में प्रदर्शित नहीं होगा।

### setPrintOnly(boolean value) {#setPrintOnly-boolean-}
```
public final void setPrintOnly(boolean value)
```


ऐसी मान सेट करें जो दर्शाता है कि एनोटेशन प्रिंट किया जाएगा, लेकिन PDF व्यूइंग एप्लिकेशन में प्रदर्शित नहीं होगा।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | वह मान जो दर्शाता है कि एनोटेशन प्रिंट किया जाएगा, लेकिन PDF व्यूइंग एप्लिकेशन में प्रदर्शित नहीं होगा। |
|

