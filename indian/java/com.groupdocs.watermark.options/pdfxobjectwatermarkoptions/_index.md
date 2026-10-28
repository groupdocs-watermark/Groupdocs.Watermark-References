---
title: "PdfXObjectWatermarkOptions"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "PDF दस्तावेज़ में XObject वॉटरमार्क जोड़ते समय वॉटरमार्क जोड़ने के विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 34
url: /hi/java/com.groupdocs.watermark.options/pdfxobjectwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfXObjectWatermarkOptions extends PdfWatermarkOptions
```

PDF दस्तावेज़ में XObject वॉटरमार्क जोड़ते समय वॉटरमार्क जोड़ने के विकल्पों का प्रतिनिधित्व करता है।

**Learn more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

निम्न उदाहरण दर्शाता है कि कैसे एक PDF दस्तावेज़ के किसी विशेष पृष्ठ में वॉटरमार्क जोड़ा जाए।
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\doc.pdf", loadOptions);
>
>    ImageWatermark watermark = new ImageWatermark("C:\\watermark.png");
>
>    PdfXObjectWatermarkOptions options = new PdfXObjectWatermarkOptions();
>    options.setPageIndex(0);
>
>    watermarker.add(watermark, options);
>    watermarker.save("C:\\watermarked_doc.pdf");
>    watermark.close();
>    watermarker.close();
>  
> ```
> ````


## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [PdfXObjectWatermarkOptions()](#PdfXObjectWatermarkOptions--) | नया इंस्टेंस `[PdfXObjectWatermarkOptions](../../com.groupdocs.watermark.options/pdfxobjectwatermarkoptions)` क्लास का इनिशियलाइज़ करता है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | वॉटरमार्क जोड़ने के लिए पृष्ठ सूचकांक प्राप्त करता है। |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | वॉटरमार्क जोड़ने के लिए पृष्ठ सूचकांक सेट करता है। |
|
### PdfXObjectWatermarkOptions() {#PdfXObjectWatermarkOptions--}
```
public PdfXObjectWatermarkOptions()
```


नया इंस्टेंस `[PdfXObjectWatermarkOptions](../../com.groupdocs.watermark.options/pdfxobjectwatermarkoptions)` क्लास का इनिशियलाइज़ करता है।


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

