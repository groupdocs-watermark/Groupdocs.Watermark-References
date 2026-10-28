---
title: "PdfArtifactWatermarkOptions"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "PDF दस्तावेज़ में आर्टिफैक्ट वॉटरमार्क जोड़ते समय वॉटरमार्क जोड़ने के विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 29
url: /hi/java/com.groupdocs.watermark.options/pdfartifactwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfArtifactWatermarkOptions extends PdfWatermarkOptions
```

PDF दस्तावेज़ में आर्टिफैक्ट वॉटरमार्क जोड़ते समय वॉटरमार्क जोड़ने के विकल्पों का प्रतिनिधित्व करता है।

**Leran more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

निम्न उदाहरण दर्शाता है कि कैसे एक PDF दस्तावेज़ में इमेज आर्टिफैक्ट वॉटरमार्क जोड़ा जाए।
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.pdf", loadOptions);
>
>    ImageWatermark watermark = new ImageWatermark("D:\\icon.png");
>
>    PdfArtifactWatermarkOptions options = new PdfArtifactWatermarkOptions();
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
|  | [PdfArtifactWatermarkOptions()](#PdfArtifactWatermarkOptions--) | नया इंस्टेंस `[PdfArtifactWatermarkOptions](../../com.groupdocs.watermark.options/pdfartifactwatermarkoptions)` क्लास का इनिशियलाइज़ करता है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | वॉटरमार्क जोड़ने के लिए पृष्ठ सूचकांक प्राप्त करता है। |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | वॉटरमार्क जोड़ने के लिए पृष्ठ सूचकांक सेट करता है। |
|
### PdfArtifactWatermarkOptions() {#PdfArtifactWatermarkOptions--}
```
public PdfArtifactWatermarkOptions()
```


नया इंस्टेंस `[PdfArtifactWatermarkOptions](../../com.groupdocs.watermark.options/pdfartifactwatermarkoptions)` क्लास का इनिशियलाइज़ करता है।


### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


वॉटरमार्क जोड़ने के लिए पृष्ठ सूचकांक प्राप्त करता है।


**Returns:**
int - वॉटरमार्क जोड़ने के लिए पृष्ठ सूचकांक।

### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


वॉटरमार्क जोड़ने के लिए पृष्ठ सूचकांक सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | वॉटरमार्क जोड़ने के लिए पृष्ठ सूचकांक। |
|

